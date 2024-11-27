# LocationTrackerFlutter
LocationTrackerFlutter is a Flutter-based application designed to track and display member locations and routes. It features Google Maps integration for real-time visualization of current locations, a timeline view of visited locations, and route details such as distance, duration, and stop times.

**Features**
**Member List:** View a list of members with quick access to their location and attendance details.
**Location Tracking:**
Displays the current location of members on an interactive map.
Shows a timeline of visited locations with date filters for historical data.
**Route Details:**
Generates routes between visited locations.
Provides details on start and stop locations, total distance traveled, total duration, and stop times.
**Date Filtering:** Enables users to filter data by specific dates.

**Screenshots**
(Add relevant screenshots of your app here after testing, or placeholders for now.)

**Getting Started**
**Prerequisites**
**Flutter SDK:** Install the latest version from Flutter's official website.
**Google Maps API Key:** Obtain a Google Maps API Key from the Google Cloud Console.

**Installation**
1. Clone the repository:
git clone https://github.com/<your-username>/LocationTrackerFlutter.git
cd LocationTrackerFlutter
2. Install dependencies:
flutter pub get
3. Add your **Google Maps API Key**:
Open android/app/src/main/AndroidManifest.xml and replace <YOUR_API_KEY> with your API key:
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY"/>
For iOS, add your API key to ios/Runner/AppDelegate.swift:
GMSServices.provideAPIKey("YOUR_API_KEY")
4. Run the app:
flutter run

**Folder Structure**
lib/
├── main.dart                   # Entry point of the app
├── screens/                    # Screens for different app pages
│   ├── member_list_screen.dart
│   ├── member_location_screen.dart
│   ├── route_screen.dart
├── models/                     # Data models for Member, Location, and Route
│   ├── member.dart
│   ├── location.dart
│   ├── route_data.dart
├── services/                   # Service for API calls
│   ├── api_service.dart
└── widgets/                    # Reusable widgets
    └── timeline_tile.dart

**Built With**
**Flutter-** Cross-platform mobile framework.
**Google Maps API-** Map rendering and route generation.
**Dart-** Programming language for Flutter.

**Future Enhancements**
Authentication for secure access.
Real-time location updates.
Push notifications for significant location changes.
Improved analytics for travel data.

**Contributing**
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch:
git checkout -b feature-name
3. Commit changes:
git commit -m "Add your message"
4. Push to the branch:
git push origin feature-name
5. Open a pull request.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Contact**
**Developer:** Anshika Singh
**Email:** anshikasingh1102@gmail.com
**GitHub:** 
