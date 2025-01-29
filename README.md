# 📱 Scannify - QR and Bar Code Scanner

<p align="center">
  <img src="assets/logos/scannify-logo.png" alt="Scannify Logo" width="200"/>
</p>

<p align="center">
  <strong>Scan, Analyze, Share - All in One App!</strong>
</p>

# Scannify 📱

Scannify is a versatile mobile application designed to effortlessly scan QR codes and barcodes. This project focuses on providing a user-friendly interface with advanced features and a sleek design.

## ✨ Features

* 🔍 **QR and Barcode Scanning**: Quickly scan and decode QR codes and various barcode formats.
* 🖼️ **Image Analysis with Gemini AI**: Scan any image and get an AI-powered description using Google's Gemini AI.
* 🏗️ **QR Code Generation**: Create QR codes on-demand for various purposes.
* 📜 **Scan History**: View and manage your scanning history with local database storage.
* 📤 **Share and Copy**: Easily share or copy scanned results and generated QR codes.
* 🎨 **User-Friendly Interface**: Intuitive design with smooth animations and transitions.
* 🚀 **Onboarding Experience**: Informative onboarding screens to guide new users.
* 🌙 **Dark Mode Support**: Comfortable viewing in low-light environments.
* 🔐 **One-click Login**: Simplified access using Google authentication.
* ☁️ **Backup and Restore**: Securely backup your scan history and settings to cloud storage for easy restoration on any device.

## 🛠️ Technologies Used

* 📱 Flutter SDK (>=3.3.0 <4.0.0)
* 🔄 Provider for state management
* 💾 SQLite for local data storage
* 🔥 Firebase for authentication and cloud services
* 🧠 Google Generative AI for image analysis
* 📦 Various Flutter packages for enhanced functionality

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Noctambulist007/CSE-3212_Project_Scannify.git
```

2. Navigate to the project directory:
```bash
cd scannify
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## 📦 Dependencies

Key packages used in this project include:

| Package | Purpose |
|---------|---------|
| `flutter_barcode_scanner` | 🔍 QR and barcode scanning |
| `qr_flutter` | 🏗️ Generating QR codes |
| `google_generative_ai` | 🧠 AI-powered image analysis |
| `provider` | 🔄 State management |
| `sqflite` | 💾 Local database storage |
| `firebase_core`, `firebase_auth`, `cloud_firestore` | 🔥 Firebase integration |
| `flutter_local_notifications` | 🔔 Push notifications |
| `animated_bottom_navigation_bar` | 🚀 Smooth navigation |
| `lottie` | 💫 Engaging animations |

For a full list of dependencies, please check the `pubspec.yaml` file.

## ⚙️ Configuration

1. Set up a Firebase project and add your `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) to the respective directories.
2. Configure your Gemini AI API key in the appropriate configuration file.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgements

* Flutter
* Firebase
* Google Generative AI

## 📞 Contact

For any queries or suggestions, please open an issue in this repository.

**Happy Scanning with Scannify!**
