# youtube_flutter

Recreating the YouTube UI in Flutter

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

Install Flutter and run
```
flutter doctor
```
Make sure the requirements specified above are satisfied.

Navigate to project directory and run
```
flutter clean
```
This is to remove previous build and also to restore the app as per Flutter update.

Open the project in Android Studio or VSCode and make sure you have Flutter pre-requisites needed for running the app, including the Dart and Flutter extension and manually run the files. For iOS devices, open the project in XCode and navigate to iOS files and open up Runner.xcproj and set up team and signing on XCode and run the program.

Certain issues might arise while running the app on macOS and XCode, hence first follow the clean command on project directory and then run
```
pod install
```
then run
```
flutter build ios
```
After the commands are run, run the Runner on XCode.
