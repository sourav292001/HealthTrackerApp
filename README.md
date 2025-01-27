# Health Tracker App

## Description
The Health Tracker App is a Flutter-based mobile application designed to fetch and display health-related data from the Google Health Connect API. It provides users with insights into their health metrics such as steps, calories burned, and heart rate. The app is built to deliver a seamless user experience with a clean and responsive UI.

---

## Setup Instructions

### Prerequisites
- Flutter SDK (version 3.x or later)
- Dart (version 2.x or later)
- Android Studio / Visual Studio Code (recommended IDEs)
- Google Health Connect installed and configured on your Android device

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Connect an Android device or start an Android emulator.
4. Run the application:
   ```bash
   flutter run
   ```

---

## Dependencies
Below are the Flutter packages used in this project:

| Package         | Purpose                                              |
|-----------------|------------------------------------------------------|
| `http`          | For making API requests to the Google Health Connect API. |
| `provider`      | For state management across the app.                |
| `flutter_svg`   | To display SVG icons in the UI.                     |
| `google_fonts`  | For custom font styles to match the design.          |

---

## Features

1. **UI Design**:
   - Responsive and intuitive UI replicated from the Figma design.
   - Consistent color scheme, typography, and layouts.

2. **Backend Integration**:
   - Fetches health metrics (steps, calories burned, heart rate) from Google Health Connect API.
   - Proper permission handling and graceful error handling.

3. **Functional Screens**:
   - **Home Screen**:
     - Displays aggregated health metrics in an easy-to-understand layout.
   - **Details Screen**:
     - Shows detailed logs and trends for specific metrics, such as step count over time.

---

## Challenges
- **Permission Handling**: Ensuring smooth access to health data without interruptions.
- **Responsive Design**: Adapting the Figma UI design for various screen sizes.
- **Backend Errors**: Implementing retry mechanisms and error feedback for users.

---

## Future Enhancements
- Add support for iOS devices when Google Health Connect becomes available.
- Include more health metrics, such as sleep data and hydration levels.
- Add push notifications for daily health insights.
- Implement dark mode for better user accessibility.

---

## Screenshots
Include screenshots or GIFs of the app showcasing:
- **Home Screen**
- **Details Screen**
- **Permission Request Dialogs**

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
