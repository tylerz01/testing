# MacBook Installation Guide

## Installation Requirements:

- VScode: https://code.visualstudio.com/
- Android Studio: https://developer.android.com/studio
- Flutter: https://docs.flutter.dev/get-started/install
- Dart: https://dart.dev/get-dart
- Xcode: Get it from the App Store
- Optional - Brew: https://docs.brew.sh/Installation
- Cocoapods: In terminal, run `sudo gem install cocoapods` or use `brew install cocoapods`

After you have made sure to set all paths correctly, you can move on to the next step.

## After Cloning the Project to Local Directory:

cd Path/to/Stoneye/sweetdream
flutter create .  ## (Ask admin for passcode for utils.zip)

flutter pub get

flutter run

## Useful Information:

### Diagnosing Your Development Environment

- Use `flutter doctor` to diagnose your development environment to ensure that it is appropriately set up for Flutter development.

### Clearing the Flutter SDK Cache

- Use `flutter clean` to clear the Flutter SDK cache.

### Fetching Latest Package Versions

- Use `flutter pub get` to fetch the latest versions of packages that satisfy the version constraints specified in your `pubspec.yaml` file.

### Updating Packages

- Use `flutter outdated` to update all the packages in your `pubspec.yaml` file to their latest compatible versions.
- Use `flutter pub upgrade` to apply the changes with `flutter outdated`.

## Potential Issues:

If `flutter run` doesn’t work automatically, launch Xcode and set it up properly (there is a section on setting up Xcode below). Then run:

flutter emulators --launch apple_ios_simulator

This will eventually launch the selected iPhone simulator.

## Setting up Xcode:

If you are on a Mac, go to the top menu, select Window, and then Devices & Simulators. Click on Simulators and then the + button in the bottom left corner.
