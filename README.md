# Mobile Desktop Stage 0
A React Native-based mobile application for HNG Internship's "Git-ting Started" Task.
Hosted on Appetize.io for easy testing.

## Project Overview
This project is part of HNG Internship’s Stage 0 Task, aimed at setting up a GitHub repository and developing a simple mobile app with React Native. The app provides direct links to:
. The GitHub repository.
. The HNG Hire page.

## Features
. GitHub Repository Link: Opens the project’s GitHub repo.
. HNG Hire Page Link: Directs users to HNG's hiring platform.
. Cross-Platform Compatibility: Works on both iOS and Android.
. Appetize.io Deployment: The app is available for online testing.

## Installation & Running the App
1. Clone the Repository
    git clone https://github.com/Abdulrahman843/mobile-desktop-stage0.git
    cd mobile-desktop-stage0/mobileApp
2️. Install Dependencies
    npm install
3️. Start Metro Bundler
    npx react-native start
4️. Run on an Android Emulator
    npx react-native run-android
For iOS (Mac Required):
cd ios
pod install
cd ..
npx react-native run-ios

## Building a Release APK
1. To generate a release APK for deployment:
cd android
.\gradlew assembleRelease
2. The APK will be found in:
android/app/build/outputs/apk/release/app-release.apk
3. Live Demo on Appetize.io
Test the app online:
Appetize.io Demo

## License
This project is licensed under the MIT License.

## Contributing
We welcome contributions! Please check out the CONTRIBUTING.md for guidelines.

## Author
Abdulrahman Laoye
GitHub Profile: https://github.com/Abdulrahman843
