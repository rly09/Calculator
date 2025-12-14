# 🧰 Calcbunny - Calculator

> A beautiful, fast, and intuitive cross-platform calculator built with Flutter. Perfect for quick calculations, scientific operations, and everyday math needs!

[![Flutter](https://img.shields.io/badge/Flutter-3.6.1+-02569B?logo=flutter&logoColor=white)](https://flutter.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web%20%7C%20Windows%20%7C%20macOS%20%7C%20Linux-blue)](#platforms)

## 🚀 Features

- 💬 **Clean Interface** - Intuitive design with clear button layout
- 🔢 **Basic Operations** - Addition, subtraction, multiplication, and division
- 🔫 **Advanced Math** - Scientific calculator functions and operations
- 📱 **Cross-Platform** - Works seamlessly on iOS, Android, Web, Windows, macOS, and Linux
- ⚡ **Lightning Fast** - Instant calculations with smooth animations
- 🙋 **User-Friendly** - Easy-to-read display with large buttons
- 🗓️ **History** - View calculation history (optional feature)

## 📋 Platforms

Calcbunny Calculator runs on:

| Platform | Status | Notes |
|----------|--------|-------|
| 📱 iOS | ✅ Supported | Native iOS experience |
| 📱 Android | ✅ Supported | Full Android support |
| 🌐 Web | ✅ Supported | Browser-based calculator |
| 💻 Windows | ✅ Supported | Desktop application |
| 🖥️ macOS | ✅ Supported | Native macOS experience |
| 🐧 Linux | ✅ Supported | Desktop application |

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

- **Flutter SDK**: Version 3.6.1 or higher
- **Dart SDK**: Included with Flutter
- **Git**: For version control

For specific platform requirements, refer to the [Flutter installation guide](https://docs.flutter.dev/get-started/install).

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/rly09/Calculator.git
cd Calculator
```

### 2. Install Dependencies

```bash
flutter pub get
```

### 3. Run the Application

**For iOS:**
```bash
flutter run -d iphone
```

**For Android:**
```bash
flutter run -d android
```

**For Web:**
```bash
flutter run -d chrome
```

**For Windows:**
```bash
flutter run -d windows
```

**For macOS:**
```bash
flutter run -d macos
```

**For Linux:**
```bash
flutter run -d linux
```

## 📁 Project Structure

```
Calculator/
├── android/          # Android-specific code
├── ios/              # iOS-specific code
├── lib/              # Main application code
│   ├── main.dart     # Entry point
│   └── ...
├── web/              # Web-specific code
├── windows/          # Windows desktop code
├── macos/            # macOS desktop code
├── linux/            # Linux desktop code
├── pubspec.yaml      # Flutter dependencies
└── README.md         # This file
```

## 🎯 How to Use

### Basic Calculations

1. **Launch the App** - Open Calcbunny Calculator
2. **Enter Numbers** - Tap number buttons to enter values
3. **Select Operation** - Choose from available mathematical operations
4. **Get Result** - Press the equals button to see the result
5. **Clear** - Use the clear button (C) to reset for a new calculation

### Keyboard Shortcuts (Web & Desktop)

- **Numbers**: 0-9 keys
- **Operations**: +, -, *, /
- **Decimal**: . (period)
- **Equals**: Enter or =
- **Clear**: C or Escape
- **Backspace**: Delete last digit

### Display Features

- **Real-time Calculation** - See results as you type
- **Large Display** - Easy-to-read result window
- **Input Feedback** - Visual confirmation of buttons pressed
- **Error Handling** - Clear error messages for invalid operations

## 📚 Dependencies

Calcbunny uses a minimal set of dependencies:

### Core
- **flutter**: The Flutter SDK framework
- **cupertino_icons**: iOS-style icons

### Development
- **flutter_lints**: Linting rules for clean code
- **flutter_test**: Testing framework

For the complete list, see [`pubspec.yaml`](pubspec.yaml).

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

Please ensure your code follows the project's coding standards and includes appropriate tests.

## 📝 Code Style

This project follows the [Dart style guide](https://dart.dev/guides/language/effective-dart/style) and uses Flutter linting rules defined in `analysis_options.yaml`.

## 🐛 Bug Reports

Found a bug? Please [open an issue](https://github.com/rly09/Calculator/issues) with:
- Clear description of the problem
- Steps to reproduce
- Expected vs. actual behavior
- Device/platform and Flutter version details

## 🙋 FAQ

**Q: Can I use this calculator offline?**
A: Yes! The app works completely offline on all platforms.

**Q: Does it support scientific calculations?**
A: Yes! The calculator supports various mathematical operations for both basic and scientific use.

**Q: Is there a calculation history feature?**
A: Yes, the app keeps track of your calculation history for easy reference.

**Q: Can I clear my calculation history?**
A: Yes, you can clear the history from the app's settings or menu.

**Q: Is this production-ready?**
A: Yes! This is a fully functional production application suitable for everyday use.

**Q: Does it support keyboard input?**
A: Yes! On desktop and web versions, you can use your keyboard for faster input.

## 🏗️ Building for Production

### Android APK
```bash
flutter build apk --release
```

### iOS App
```bash
flutter build ios --release
```

### Web
```bash
flutter build web --release
```

### Windows
```bash
flutter build windows --release
```

### macOS
```bash
flutter build macos --release
```

### Linux
```bash
flutter build linux --release
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Flutter](https://flutter.dev/)
- Inspired by the need for a simple, reliable calculator
- Thanks to the Flutter community for excellent documentation and support
- Special thanks to all contributors and users

## 📞 Contact

Have questions or suggestions? Feel free to reach out:
- **GitHub**: [@rly09](https://github.com/rly09)
- **Issues**: [GitHub Issues](https://github.com/rly09/Calculator/issues)

---

<div align="center">

**[⬆ back to top](#-calcbunny---calculator)**

Made with ❤️ by [rly09](https://github.com/rly09)

Enjoy fast and easy calculations! 🧰💯

</div>
