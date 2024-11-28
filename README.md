📅 Attendance Management & Location Tracker App

Welcome to the Attendance Management & Location Tracker App, a comprehensive solution for managing attendance records with ease. This app is built using the Flutter framework, providing a seamless and interactive user experience for tracking and managing employee attendance as well as location.

📋 Table of Contents
Features
Screenshots
Installation
Usage
Technologies Used
Project Structure
Contributing
License
Contact

✨ Features
🔍 Search Functionality: Quickly find members by name using the search feature.
🗺️ Map Integration: View the geographical locations of all members on an interactive map.
📊 Detailed View: Access comprehensive details like in-time, out-time, and address for each member.
🌐 Cross-Platform: Built with Flutter, this app runs smoothly on both Android and iOS devices.
📸 Screenshots

View and manage attendance records & monitor location.


Detailed information about individual members.

🔧 Installation
Prerequisites
Flutter SDK: Installation Guide
IDE: Android Studio or Visual Studio Code for development
Steps
Clone the repository:


git clone (https://github.com/Anshi1102/LocationTrackerFlutter.git)
cd attendance-management-app
Install dependencies:


flutter pub get
Run the app:


flutter run
🚀 Usage
Home Screen:

View a list of all members and their attendance records.
Use the search bar to find specific members.
Attendance Recording:

Tap on a member to view and edit their attendance details.
Map View:

Use the "Show All Members" button to view the locations of all members on a map.
💻 Technologies Used
Frontend: Flutter, Dart
State Management: Stateful Widgets
Plugins:
google_maps_flutter: For integrating Google Maps.
geocoding: For converting addresses into geographical coordinates.

📂 Project Structure

lib/
│
├── main.dart                   # Entry point of the application
├── screens/
│   └── attendance_page.dart    # Main screen with attendance features
├── widgets/
│   ├── member_card.dart        # Widget for displaying member details
│   ├── date_selector.dart      # Widget for selecting dates
│   ├── custom_app_bar.dart     # Reusable custom app bar
│   └── show_map_button.dart    # Button for displaying map
└── models/
    └── member_model.dart       # Data model for member information

🤝 Contributing
We welcome contributions to make this project even better! To contribute:

Fork the repository.
Create a new branch:


git checkout -b feature-branch-name
Make your changes and commit:


git commit -m 'Add some feature'
Push to the branch:


git push origin feature-branch-name
Create a pull request.
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

📧 Contact
Anshika Singh

Email: anshikasingh1102@gmail.com
