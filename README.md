# Fetch Interview Project

This is an Android application developed for the Fetch Interview. The application retrieves data from a provided URL and displays it in an easy-to-read list.

## Features

- Retrieves data from `https://fetch-hiring.s3.amazonaws.com/hiring.json`.
- Displays the data in an expandable list view, grouped by "listId".
- Sorts the results first by "listId" then by "name".
- Filters out any items where "name" is blank or null.

## Prerequisites

- Android Studio
- Android SDK
  
## How to Run via APK on android device

1. **Copy the APK**: Copy the file `apk\fetchinterview.apk` from repository to Android device
2. **Install**: Select the file and install it on android device.
   
## How to Run Via Code

1. **Clone the repository**: Clone this repository to your local machine.

2. **Open the project**: Open Android Studio and select `File > Open...`. Navigate to the directory where you cloned the repository and click `OK`.

3. **Sync the project with Gradle files**: Android Studio should automatically sync the project with the Gradle files. If it doesn't, you can do this manually by selecting `File > Sync Project with Gradle Files`.

4. **Run the application**: Click on the green play button in the toolbar at the top of Android Studio. Choose either a connected device or a configured emulator to run the application.

## Notes

This is a simple example and doesn't follow best practices for production code (like error handling, loading states, etc.). For a production app, you might want to consider using architecture components like ViewModel and LiveData, and handle edge cases properly.
