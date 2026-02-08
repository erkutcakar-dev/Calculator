# 🧮 Calculator - Modern Cross-Platform Calculator App

<div align="center">

![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-9.0-512BD4?style=for-the-badge&logo=dotnet)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-00D9FF?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A beautiful, modern calculator application built with .NET MAUI** ✨

[Features](#-features) • [Screenshots](#-screenshots) • [Tech Stack](#-tech-stack) • [Getting Started](#-getting-started) • [Architecture](#-architecture)

</div>

---

## 🌟 Features

### ✨ Core Functionality
- ➕ **Basic Operations**: Addition, subtraction, multiplication, division
- 🔢 **Number Input**: Intuitive number pad interface
- 🧹 **Clear Functions**: All Clear (AC) and Backspace support
- 📊 **Real-time Calculation**: Instant result display using Dangl.Calculator
- 💯 **Percentage Support**: Built-in percentage calculations

### 🎨 Design & UX
- 🌓 **Automatic Theme Switching**: Seamlessly syncs with system dark/light mode
- 🎯 **Modern UI**: Clean, minimalist design with smooth animations
- 📱 **Responsive Layout**: Optimized for all screen sizes
- 🎨 **Custom Color Scheme**: Beautiful color palette for both themes
- 🔤 **Custom Fonts**: Sublima font family for elegant typography

### 🏗️ Architecture
- 🏛️ **MVVM Pattern**: Clean separation of concerns
- 🔄 **PropertyChanged.Fody**: Automatic property change notifications
- 📦 **NuGet Packages**: Well-maintained dependencies
- 🎯 **Platform-Specific**: Optimized for Android, iOS, macOS, and Windows

---

## 🛠️ Tech Stack

### Frameworks & Libraries
- **.NET MAUI 9.0** - Cross-platform UI framework
- **Dangl.Calculator 2.2.0** - Mathematical expression evaluation
- **PropertyChanged.Fody 4.1.0** - Automatic INotifyPropertyChanged implementation
- **Microsoft.Maui.Controls** - UI controls and layouts

### Platforms Supported
- 🤖 **Android** (API 21+)
- 🍎 **iOS** (15.0+)
- 🪟 **Windows** (10.0.17763.0+)
- 💻 **macOS** (Mac Catalyst 15.0+)

---

## 🚀 Getting Started

### Prerequisites
- 📥 [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
- 🛠️ [Visual Studio 2022](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/)
- 📱 Platform-specific SDKs (Android SDK, Xcode for iOS, etc.)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/erkutcakar-dev/Calculator.git
   cd Calculator
   ```

2. **Restore NuGet packages**
   ```bash
   dotnet restore
   ```

3. **Build the project**
   ```bash
   dotnet build
   ```

4. **Run the application**
   ```bash
   dotnet run
   ```

### Building for Specific Platforms

#### Android 🤖
```bash
dotnet build -f net9.0-android
```

#### iOS 🍎
```bash
dotnet build -f net9.0-ios
```

#### Windows 🪟
```bash
dotnet build -f net9.0-windows10.0.19041.0
```

---

## 🏛️ Architecture

### MVVM Pattern
The application follows the **Model-View-ViewModel** architectural pattern:

```
📁 Calculator/
├── 📁 MVVM/
│   ├── CalcView.xaml          # View (UI)
│   ├── CalcView.xaml.cs       # View Code-Behind
│   └── CalcViewModel.cs       # ViewModel (Business Logic)
├── 📁 Resources/
│   ├── Styles/                # XAML Styles & Themes
│   ├── Fonts/                 # Custom Fonts
│   └── Images/                # App Assets
└── App.xaml                   # Application Resources
```

### Key Components

- **CalcViewModel**: Handles all calculation logic and state management
- **CalcView**: UI layout with responsive grid design
- **Resource Dictionaries**: Centralized styling and theming
- **Platform-Specific**: Android status bar customization

---

## 🎨 Theme System

### 🌓 Automatic Theme Detection
The app **automatically synchronizes** with your device's theme settings:
- 🌞 **Light Mode**: Clean, bright interface with subtle colors
- 🌙 **Dark Mode**: Elegant dark theme with optimized contrast
- 🔄 **Real-time Switching**: Changes instantly when system theme updates

### Color Palette
- **Dark Primary**: `#292d36`
- **Dark Secondary**: `#272b33`
- **Light Primary**: `#f2f2f2`
- **Light Secondary**: `#f7f7f7`
- **Accent Colors**: Yellow (`#f4ab41`) and Red (`#d3635e`)

---

## 📦 Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| Dangl.Calculator | 2.2.0 | Mathematical expression evaluation |
| PropertyChanged.Fody | 4.1.0 | Automatic property notifications |
| Microsoft.Maui.Controls | 9.0.x | UI framework |
| Microsoft.Extensions.Logging.Debug | 9.0.8 | Debug logging |

---

## 🎯 Features in Detail

### Calculation Engine
- ✅ Supports complex mathematical expressions
- ✅ Operator precedence handling
- ✅ Error handling for invalid expressions
- ✅ Real-time formula display

### User Interface
- ✅ Grid-based button layout
- ✅ Visual feedback on button press
- ✅ Smooth animations and transitions
- ✅ Accessible design principles

### Platform Integration
- ✅ Native look and feel on each platform
- ✅ Status bar color synchronization (Android)
- ✅ System theme integration
- ✅ Platform-specific optimizations

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔀 Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Dangl.Calculator](https://www.nuget.org/packages/Dangl.Calculator/) - Powerful calculation engine
- [PropertyChanged.Fody](https://github.com/Fody/PropertyChanged) - Property change notifications
- [.NET MAUI](https://dotnet.microsoft.com/apps/maui) - Cross-platform framework
- [Sublima Font](https://fonts.google.com/) - Beautiful typography

---

## 📸 Screenshots

### Light Theme 🌞
<!-- Placeholder for screenshot 1 - Light Theme -->
![Light Theme Screenshot 1](screenshots/light-theme-1.png)

![Light Theme Screenshot 2](screenshots/light-theme-2.png)

### Dark Theme 🌙
<!-- Placeholder for screenshot 3 - Dark Theme -->
![Dark Theme Screenshot 1](screenshots/dark-theme-1.png)

![Dark Theme Screenshot 2](screenshots/dark-theme-2.png)

---

## 📧 Contact & Connect

**👨‍💻 Developer**: [Erkut ÇAKAR](https://github.com/erkutcakar-dev)

**📧 Email**: [erkutcakar@gmail.com](mailto:erkutcakar@gmail.com)

**💼 LinkedIn**: [in/erkut-cakar](https://www.linkedin.com/in/erkut-cakar)

**📷 Instagram**: [@erkut.cakar](https://www.instagram.com/erkut.cakar)

**🌍 Location**: Kırklareli, Turkey 🇹🇷

**🔗 Project Link**: [https://github.com/erkutcakar-dev/Calculator](https://github.com/erkutcakar-dev/Calculator)

---

### 🚀 About the Developer

I'm a **.NET Developer** specializing in:
- 🔧 **Backend Development** with ASP.NET Core MVC
- 📱 **Cross-Platform Mobile Apps** with .NET MAUI
- 💻 **C#** and **SQL** programming
- 🏗️ **Clean Architecture** and **MVVM** patterns

Currently learning: **MongoDB, CQRS, Clean Architecture** 🌱

Looking to collaborate on: **Open Source Projects** 👯

---

<div align="center">

**Made with ❤️ by [Erkut ÇAKAR](https://github.com/erkutcakar-dev) using .NET MAUI**

⭐ **Star this repo if you find it helpful!**

🔗 **Follow me on GitHub**: [@erkutcakar-dev](https://github.com/erkutcakar-dev)

---

### 🌟 Show Your Support

If you like this project, please consider:
- ⭐ **Starring** this repository
- 🍴 **Forking** to create your own version
- 🐛 **Reporting** bugs or suggesting features
- 💬 **Sharing** with others who might find it useful

**Thank you for your support!** 🙏

⭐

<img width="407" height="942" alt="Ekran görüntüsü 2026-02-08 213057" src="https://github.com/user-attachments/assets/2d54139b-9b9c-4640-b852-6064cb02d972" />
<img width="413" height="945" alt="Ekran görüntüsü 2026-02-08 213045" src="https://github.com/user-attachments/assets/1f519239-9ee7-42b6-9fd9-d58a3ee37795" />

⭐

<img width="407" height="884" alt="Ekran görüntüsü 2026-02-08 213147" src="https://github.com/user-attachments/assets/f08d982a-3572-4dbf-867a-c6d080f347b9" />
<img width="399" height="872" alt="Ekran görüntüsü 2026-02-08 213132" src="https://github.com/user-attachments/assets/3d7d31e6-b118-4429-aab7-0adeaabf30b9" />

</div>
