# DAB Music Player 🎵

**High-Quality Music Streaming with Custom Native Audio Engine**

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://android.com)
[![Audio](https://img.shields.io/badge/Custom-Native_Audio-FF6B6B?style=for-the-badge)]()

---

## 🎯 Overview

DAB Music Player is a premium Flutter-based music streaming application that delivers uncompromising audio quality through our custom native audio engine. Built for audiophiles who demand the best listening experience on Android devices.

### ✨ Key Features

- 🎵 **Professional Audio Quality** - Custom native audio engine for superior sound
- 📱 **Native Android Integration** - Seamless device integration
- 🎨 **Modern UI/UX** - Beautiful, intuitive interface
- 📚 **Unlimited Libraries** - Organize your music without limits
- 🔍 **Advanced Search** - Find music across your entire collection
- 🎤 **Lyrics Support** - Synced and non-synced lyrics display
- 🔄 **Background Playback** - Continuous music even when phone is off
- 🎛️ **Audio Controls** - Professional-grade playback controls

---

## 📦 Latest Release - Patch v2.9.0

### �️ Patch Highlights
- ✅ **Search Function Update** – Search function updated with New API
- ✅ **Playback Queue Fixes** – seamless auto-advance across favorites and albums
- ✅ **Cloudflare Hardening** – resilient streaming with smart header + cookie reuse
- ✅ **Long Download Reliability** – album queues and hi-res tracks finish without stalling
- ✅ **Mini Player Stability** – now playing state stays in sync across the app

 | [📋 Previous Release v2.7.0](RELEASE_NOTES_v2.7.0.md)

## ⭐ Repository Stars

[![Star History Chart](https://api.star-history.com/svg?repos=holmesisback/Dab-Android-Beta-V2&type=Date)](https://star-history.com/#holmesisback/Dab-Android-Beta-V2&Date)

---

## 🏗️ Architecture

### **Frontend**
- **Framework**: Flutter 3.x
- **Language**: Dart
- **UI Components**: Material Design 3
- **State Management**: Provider + ValueNotifier
- **Dependency Injection**: GetIt + Injectable

### **Backend Integration**
- **API**: RESTful API (https://dab.yeet.su/api)
- **Authentication**: JWT tokens with secure storage
- **Network**: Dio with custom interceptors
- **Caching**: Smart cache management for optimal performance

### **Audio Engine**
- **Core**: Custom Native Audio Engine (Native C++)
- **Platform Bridge**: Method Channels (Kotlin ↔ Dart)
- **Features**: High-res audio, low latency, professional effects
- **Formats**: FLAC, MP3, WAV, and more

---


## 📁 Project Structure

```
lib/
├── main.dart                           # App entry point
├── src/
│   ├── core/                          # Core utilities
│   │   ├── di/                        # Dependency injection
│   │   ├── error/                     # Error handling
│   │   └── services/                  # Core services
│   ├── features/                      # Feature modules
│   │   ├── auth/                      # Authentication
│   │   ├── home/                      # Home screen & discovery
│   │   ├── library/                   # Music libraries
│   │   │   ├── data/                  # Data layer
│   │   │   ├── domain/                # Business logic
│   │   │   └── presentation/          # UI layer
│   │   ├── lyrics/                    # Lyrics functionality
│   │   ├── player/                    # Music player
│   │   │   ├── services/              # Audio services
│   │   │   └── presentation/          # Player UI
│   │   └── search/                    # Search functionality
│   └── shared/                        # Shared components
│       ├── widgets/                   # Reusable widgets
│       └── utils/                     # Utility functions

android/
├── app/src/main/
│   ├── kotlin/                        # Kotlin native code
│   │   └── com/dab/android/           # Native audio integration
│   ├── cpp/                           # C++ audio engine
│   └── AndroidManifest.xml           # App configuration
```

---

## 🎵 Audio Features

### ** Native Audio Engine**
- **Ultra-low latency**: < 50ms audio pipeline
- **High-resolution support**: Up to 32-bit/384kHz
- **Professional effects**: EQ, reverb, compression
- **Seamless streaming**: Adaptive bitrate streaming
- **Format support**: FLAC, MP3, WAV, OGG, and more

### **Playback Features**
- 🎛️ **Gapless playback** - Seamless track transitions
- 🔄 **Queue management** - Dynamic playlist control
- 📱 **Media controls** - Lock screen and notification controls
- 🎨 **Now playing** - Rich metadata display with album art
- 📊 **Audio visualization** - Real-time spectrum analysis

---

## 🔧 Key Technologies

| Component | Technology | Purpose |
|-----------|------------|---------|
| UI Framework | Flutter 3.x | Cross-platform UI |
| Audio Engine | Native C++ Library | Professional audio |
| Native Bridge | Method Channels | Flutter ↔ Native |
| Network | Dio + Interceptors | API communication |
| Storage | Hive + Shared Preferences | Local data storage |
| Images | Cached Network Image | Optimized image loading |
| Animations | Flutter Animations | Smooth transitions |
| Fonts | Google Fonts | Beautiful typography |

---

## 📱 Platform Support

### **Android Compatibility**
- **Minimum**: Android 5.0 (API 21)
- **Target**: Android 14 (API 34)
- **Optimized for**: Android 12+
- **Special support**: MIUI, Samsung One UI 7+

### **Device Requirements**
- **RAM**: 2GB minimum, 4GB recommended
- **Storage**: 100MB app + cache space
- **Network**: Internet connection for streaming
- **Audio**: Standard Android audio stack

---

## 🎨 UI/UX Features

### **Design System**
- **Material Design 3** - Modern Google design language
- **Dark/Light Themes** - Adaptive to system preferences
- **Dynamic Colors** - Material You color theming
- **Smooth Animations** - 60fps transitions and effects
- **Accessibility** - Screen reader and navigation support

### **User Experience**
- 🚀 **Fast Loading** - < 1 second app startup
- 🎵 **Instant Search** - Real-time search results
- 📱 **Gesture Controls** - Intuitive swipe and tap controls
- 🔄 **Background Sync** - Seamless library updates
- 💾 **Offline Mode** - Cached content playback

---

## 🐛 Known Issues & Fixes

### **Resolved in v2.7.0**
- ✅ **Library track limitation** - Now supports unlimited tracks
- ✅ **Pagination errors** - Robust loading for large libraries
- ✅ **Memory optimization** - Better handling of large datasets
- ✅ **API efficiency** - Reduced redundant network calls

### **Current Limitations**
- 📱 **iOS Support** - Android only (Flutter web in development)
- 🌐 **Offline Sync** - Limited offline functionality
- 🎵 **Local Files** - Streaming only (local file support planned)

---

## 🚀 Performance Metrics

| Metric | Target | Current | Status |
|--------|--------|---------|--------|
| App Startup | < 2s | ~1.5s | ✅ |
| Track Loading | < 1s | ~0.5s | ✅ |
| Library Loading | < 3s | ~2s | ✅ |
| Memory Usage | < 150MB | ~120MB | ✅ |
| Battery Impact | Minimal | Optimized | ✅ |

---

## 🤝 Contributing

### **Development Guidelines**
1. **Code Style**: Follow Dart official guidelines
2. **Architecture**: Clean Architecture with feature modules
3. **Testing**: Unit tests for business logic, widget tests for UI
4. **Documentation**: Comprehensive code documentation

### **Pull Request Process**
1. Fork the repository
2. Create feature branch (`feature/amazing-feature`)
3. Make changes with tests
4. Submit pull request with description

---

## 📄 License

This project is licensed under the [LICENSE](LICENSE) file in the root directory.

---

## 📞 Support & Contact

### **Getting Help**
- 🐛 **Bug Reports**: Create detailed issue reports
- 💡 **Feature Requests**: Suggest improvements
- 📧 **Direct Contact**: [support@dabmusic.app](mailto:support@dabmusic.app)
- 💬 **Community**: Join our Discord server

### **Links**
- 🌐 **Website**: [https://dabmusic.app](https://dabmusic.app)
- 📱 **Play Store**: Coming soon
- 🎵 **API Docs**: [API Documentation](api-documentation.html)

---

## 🎵 Experience Premium Audio

**DAB Music Player** - *Where audiophile dreams meet mobile reality*

*Built with ❤️ for music lovers who accept nothing less than perfection.*
