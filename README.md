<div align="center">

# DAB Android

### Professional High-Fidelity Music Streaming for Android

![Platform](https://img.shields.io/badge/Platform-Android%209.0%2B-green?style=for-the-badge&logo=android)
![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

**Audiophile-grade music player powered by native audio engine**  
*Stunning design • Studio-quality sound • Professional features*

[🌐 Website](https://dabmusic.xyz) • [📱 Download](github.com/holmesisback/Dab-Android-Beta-V2/releases/latest) • [☕ Support](https://ko-fi.com/devsherlock)

</div>

---

## ⚠️ Disclaimer

> **Legal Notice & Responsibility**
>
> DAB Android is an independent application developed for educational, personal, and research purposes only. This project is intended to demonstrate technical skills in Flutter, audio processing, and API integration.
>
> This application **does NOT host, store, upload, or distribute any media content**. All content displayed or streamed through the app is obtained from **third-party APIs and external services**.
>
> DAB Android acts strictly as a **client interface** that connects users to publicly available or externally provided resources.
>
> The developer:
>
> - ❌ Does **not own, control, or operate** any third-party servers or APIs  
> - ❌ Does **not provide or upload any copyrighted material**  
> - ❌ Is **not responsible** for the legality, accuracy, or availability of third-party content  
>
> By using this application, you acknowledge and agree that:
>
> - ✅ You are using this app **at your own risk and responsibility**  
> - ✅ You are responsible for ensuring that your usage complies with **local laws and regulations**  
> - ✅ Any misuse, copyright infringement, or illegal activity is **solely the responsibility of the end user**  
>
> If you are a content owner and believe your rights are being violated, please contact the respective third-party service providers directly.

---

## 🎯 Overview

DAB Android is a premium Flutter-based music streaming application engineered for Android devices, delivering studio-quality audio through our proprietary native audio engine. Combining professional audio processing with a sophisticated glassmorphic dark theme, DAB offers an unparalleled listening experience for music enthusiasts who refuse to compromise on quality.

---

### ✨ Core Features

#### 🎵 **Audio Excellence**
- **Native Audio Engine** - Professional-grade audio library for pristine sound quality
- **High-Resolution Audio** - Support for FLAC, MP3, WAV, OGG and more formats
- **Ultra-Low Latency** - Optimized audio pipeline for real-time responsiveness
- **Gapless Playback** - Seamless transitions between tracks
- **Secure Streaming** - Encrypted HTTPS audio delivery

#### 🎨 **Premium UI/UX**
- **Glassmorphic Design** - Sophisticated frosted glass effects with gradient backgrounds
- **OLED-Optimized Dark Theme** - True black (#000000) for battery efficiency and visual comfort
- **Smooth Animations** - 60fps staggered entrance effects and bouncing scroll physics
- **Professional Typography** - Lufga font family with optimized letter spacing
- **Dual Shadow System** - Depth-enhancing black shadows with white highlights
- **Clean Design Language** - Minimalist black/white palette with strategic transparency

#### 🔍 **Advanced Search & Discovery**
- **Intelligent Search** - Real-time search across artists, albums, and tracks
- **Rate Limit Management** - Smart retry logic with exponential backoff (30 req/min)
- **Rectangular Category Tabs** - Glassmorphic tab design with smooth transitions
- **Auto-Suggestions** - Contextual search recommendations
- **Error Recovery** - "Try Again" UI for network errors and rate limiting

#### 📚 **Content Management**
- **Album Detail View** - Comprehensive track listings with audio quality badges (MAX)
- **Artist Profiles** - Complete discography with animated album cards
- **Track Options** - Advanced playback, queue, and download management
- **Related Content** - "More Albums by Artist" with intelligent recommendations
- **Cover Art Validation** - URL verification with graceful fallback handling
- **Multi-Field Parsing** - Robust API response handling for varying data structures

#### 📥 **Download & Offline**
- **Album Downloads** - Complete album download with glassmorphic bottom sheets
- **Quality Selection** - Choose audio format and bitrate before download
- **Progress Tracking** - Real-time download status with pause/resume support
- **Local Storage** - Efficient SQLite-based library management
- **Cache Management** - Automatic cleanup and optimization

#### 🎛️ **Playback Controls**
- **Queue Management** - Dynamic playlist editing and reordering
- **Repeat & Shuffle** - Advanced playback modes with state persistence
- **Media Controls** - Lock screen, notification, and Bluetooth integration
- **Background Playback** - Continuous audio even when screen is off
- **Audio Session** - Proper Android audio focus handling

---

## 🚀 Key Technical Highlights

### **Performance Optimizations**
- 🔥 **Native Audio** - Zero-overhead C++ audio processing
- ⚡ **Lazy Loading** - On-demand image and data loading
- 🧹 **Memory Management** - Aggressive disposal of unused resources
- 📦 **APK Size** - Code splitting and tree shaking (< 50MB)
- 🔄 **Efficient Scrolling** - ListView.builder with const constructors
- 💾 **Smart Caching** - LRU cache for images and API responses

### **Error Handling & Resilience**
- 🛡️ **Mounted Checks** - Prevent setState-after-dispose errors
- 🔄 **Retry Logic** - Exponential backoff for failed API requests
- 🚨 **Rate Limit Detection** - Custom UI for 429 errors with "Try Again"
- 🖼️ **Image Validation** - URL verification with fallback to placeholder
- 📊 **Debug Logging** - Comprehensive logging for troubleshooting
- ⚠️ **Graceful Degradation** - App continues with reduced functionality on errors

### **Search Optimization**
- 🎯 **Debounced Requests** - 300ms delay to reduce API calls
- 📋 **Category Separation** - Organized results (Top, Artists, Albums, Tracks)
- ⏱️ **Request Throttling** - Intelligent rate limit management (30/min)

---

## 🔧 Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Framework** | Flutter 3.x | Cross-platform Android UI |
| **Language** | Dart | Application logic |
| **Native Audio** | Proprietary Engine | Professional audio processing |
| **Native Bridge** | Kotlin Method Channels | Flutter ↔ Native communication |
| **HTTP Client** | Dio + Interceptors | API requests with retry logic |
| **State Management** | Provider, Bloc, Riverpod | Reactive UI updates |
| **Dependency Injection** | GetIt + Injectable | Service locator pattern |
| **Database** | SQLite (sqflite) | Local music library |
| **Secure Storage** | flutter_secure_storage | Encrypted token storage |
| **Cache** | Hive + SharedPreferences | Settings and metadata |
| **Images** | CachedNetworkImage | Optimized artwork loading |
| **Animations** | Flutter Animations | Smooth 60fps transitions |
| **Typography** | Lufga Font Family | Professional text rendering |
| **Blur Effects** | BackdropFilter + ImageFilter | Glassmorphic UI elements |
| **JSON Parsing** | json_serializable | Model code generation |
| **Testing** | flutter_test + mockito | Unit and widget tests |

---

## 📄 License & Credits

### **License**
This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

### **Project Links**
- 🌐 **Official Website**: https://dabmusic.xyz
- 📱 **API Endpoint**: https://dab.yeet.su/api

---

<div align="center">

### Support the Project

[![Ko-fi](https://files.catbox.moe/apck19.jpg)](https://ko-fi.com/devsherlock)

*Every contribution helps us continue developing premium features*

---

### Connect With Us

🌐 [Website](https://dabmusic.xyz)  💬 [Discord](https://discord.gg/gnhABwsHrJ) 

**Version 3.0.0** | **Android 9.0+** | **Last Updated: February 2026**

<sub>© 2026 DAB Music Player. All rights reserved.</sub>  
<sub>Made with ❤️ by joe for passionate listeners</sub>

</div>
