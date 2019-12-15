# Flutter_Firebase_Auth_Sign_Example

Notes:

1) main.dart and signIn.dart is the main files.
2) home.dart is the navigator page after user signed-in.

Instruction:

0) Makesure you have added your app by clicking 'Add App' button in the Firebase settings (then select Android icon for Android project).
1) Add 'firebase_auth: ^0.15.2' to 'pubspec.yaml' file. Then run 'flutter pub get' in the terminal.
2) Copy-paste 'google-services.json' (download from firebase) into 'android/app' folder.
3) Add "apply plugin: 'com.google.gms.google-services'" at the last line on 'build.gradle' file (android/app)
4) Add "classpath 'com.google.gms:google-services:4.3.2'" at 'dependencies' on 'build.gradle' file (android)
