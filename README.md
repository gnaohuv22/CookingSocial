# Recipe Sharing Social Network App

## Introduction

This is a mobile social network application built using Android Studio, where users can share and discover recipes. The app allows users to create posts with text, images, and videos, engage with other users' posts through likes and comments, and manage their own recipe collections.

## Status
Start developing...

## Features

- **User Authentication**: Sign up, log in, and manage user accounts using Firebase Authentication.
- **Recipe Feed**: View and interact with recipes posted by other users.
- **Create Posts**: Upload new recipes with descriptions, images, and videos.
- **Search Functionality**: Search for recipes by ingredients or dish names.
- **User Profiles**: View and edit personal information and posts.
- **Like & Comment**: Interact with others by liking and commenting on their recipes.
- **Notifications**: Stay updated with likes, comments, and other activities.
- **Settings**: Manage app preferences, notifications, and privacy settings.

## Tech Stack

- **Frontend**: XML with the support of Android.
- **Backend**: Firebase Authentication and Firestore for real-time data storage, Java for logic processing.
- **Database**: Firebase Firestore for storing user data, recipes, and media.
- **Storage**: Firebase Storage for storing images and videos.
- **Deployment**: The app will be available on the Amazon Appstore.

## Prerequisites

Before running the project, ensure you have the following software installed:

- **Android Studio**: Version [Koala Drop Feature](https://developer.android.com/studio) or above.
- **JDK (Java Development Kit)**: [Version 17](https://www.oracle.com/java/technologies/downloads/#jdk17-windows) or higher.
- **Firebase Project**: Set up Firebase for Authentication, Firestore, and Firebase Storage.
- **Google Play Services**: Ensure it's updated on your test device.

## Installation

To run the project locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/gnaohuv22/CookingSocial.git
    cd CookingSocial
    ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Select "Open an existing Android Studio project" and choose the cloned project directory.

3. **Install Dependencies**:
   - Android Studio will automatically sync and install dependencies when the project is opened.
   - If the sync doesn’t start, go to `File > Sync Project with Gradle Files`.

4. **Configure Firebase**:
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable **Firestore**, **Firebase Authentication**, and **Firebase Storage**.
   - Download the `google-services.json` file and place it in the `app/` directory of your Android project.

5. **Run the App**:
   - Connect an Android device or launch an emulator.
   - Click "Run" in Android Studio or use `Shift + F10`.

## Firebase Setup

1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Create a new Firebase project.
3. Enable **Firestore**, **Firebase Authentication**, and **Firebase Storage** in the Firebase dashboard.
4. Download the `google-services.json` file from Firebase and add it to the `app/` folder in your Android project.
5. Configure your app's Firebase integration by adding Firebase dependencies to your `build.gradle` files.

## Screenshots
This is the expected work flow of the project. It might be changed in the future.

![the expected working flow of the project](https://github.com/gnaohuv22/CookingSocial/blob/main/SketchInterface.png)

## Future Improvements

- Implement push notifications.
- Add support for multiple languages.
- Improve search functionality with advanced filters.
- Enhance user experience with personalized recipe recommendations.

## Contributing

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/my-feature`).
3. Commit your changes (`git commit -m 'Add my feature'`).
4. Push to the branch (`git push origin feature/my-feature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
