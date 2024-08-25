# Journal-App

## Overview

The Journal App is an Android application that allows users to create, manage, and access their personal journal entries securely. The app integrates with Firebase for authentication and Firestore for data storage, providing a seamless and secure user experience.

## Features

- **User Authentication**: Secure sign-up and sign-in using Firebase Authentication.
- **Personal Journal Entries**: Create, edit, and delete personal journal entries.
- **Firestore Integration**: Store and retrieve journal entries using Firestore.
- **Offline Capabilities**: Access and manage your entries even when offline, with data synchronization when reconnected.
- **Responsive UI**: Designed for various screen sizes, from smartphones to tablets.

## Tech Stack

- **Language**: Java
- **IDE**: Android Studio
- **Backend**: Firebase Authentication, Firestore
- **UI**: XML layouts, Material Design Components

## Output Screenshots

### Home Page

![Home Page](https://github.com/user-attachments/assets/7f386abd-e1b8-4361-b142-e612cec8803c)

This is the home page of the Journal App, where users can create or login into their journal app.

### Login Create Account page

![image](https://github.com/user-attachments/assets/cfe8e476-9874-43c9-95a3-30908cb9fd39)
![image](https://github.com/user-attachments/assets/15395ee3-d2ba-4069-88f5-0a063c89836c)
![image](https://github.com/user-attachments/assets/24fba7a9-900f-4e16-8f80-cdffc70bab9c)

This is the home page of the Journal App, where users can create or login into their journal app.

### add journal 
![ADD JOURNAL](https://github.com/user-attachments/assets/5c45dcaa-3f14-43c3-8370-96822a0f7285)
![image](https://github.com/user-attachments/assets/b900ea88-7139-4a20-92f5-b556dddba25c)


### View Journal
![image](https://github.com/user-attachments/assets/4fb28384-8e1f-4ee7-943b-3705e542021d)



## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Android Studio](https://developer.android.com/studio) (Latest version)
- Android device or emulator with API level 21 or higher

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/journal-app.git
    cd journal-app
    ```

2. **Open in Android Studio**:
   - Open Android Studio.
   - Select `Open an existing project`.
   - Navigate to the `journal-app` directory and select it.

3. **Set up Firebase**:
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project.
   - Enable Firebase Authentication (Email/Password).
   - Set up Firestore Database.
   - Download the `google-services.json` file from Firebase Console and place it in the `app/` directory of your Android Studio project.

4. **Sync Project with Gradle Files**:
   - Open Android Studio.
   - Go to `File > Sync Project with Gradle Files` to ensure all dependencies are correctly loaded.

5. **Run the application**:
   - Connect your Android device via USB or start an emulator.
   - Click the `Run` button in Android Studio or use `Shift + F10`.

   The app should launch on your device/emulator.

## Usage

- **Sign Up / Sign In**: Create a new account or log in using your credentials.
- **Create Journal Entry**: Use the 'New Entry' button to create a journal entry.
- **Edit/Delete Entry**: Long-press an existing entry to edit or delete it.
- **View Entries**: View all your journal entries in the main list.

## Deployment

1. **Generate a Signed APK**:
   - In Android Studio, go to `Build > Generate Signed Bundle / APK`.
   - Follow the prompts to generate a signed APK.

2. **Distribute the APK**:
   - Share the APK directly or upload it to the Google Play Store.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Firebase team for their robust backend services.
- Inspiration from various journaling apps on the Android platform.
