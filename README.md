JodeTx Payment SDK
This Flutter module simulates a secure payment flow with custom UI for product and cart. Built for integration with native apps using Flutter Add-to-App (via AAR).

Features
2-screen UI: product list & cart

Accepts data via MethodChannel from native app

Sends payment result back to host

Packaged as .aar to hide Dart source code

Build Instructions

flutter pub get
flutter build aar
Use the generated AAR in your host Android app.
