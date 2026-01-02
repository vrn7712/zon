<p align="center">
  <img src="showcase.png" alt="Zon - Enter Your Zone" width="800"/>
</p>

<h1 align="center">Zon</h1>

<p align="center">
  <b>Enter Your Zone.</b><br>
  <i>A minimalist Pomodoro timer for Android</i>
</p>

<p align="center">
  <a href="https://github.com/vrn7712/Zon/releases/latest">
    <img src="https://img.shields.io/github/v/release/vrn7712/Zon?style=for-the-badge&logo=github&color=blue" alt="Release"/>
  </a>
  <img src="https://img.shields.io/badge/Platform-Android-34A853?style=for-the-badge&logo=android&logoColor=white" alt="Platform"/>
  <img src="https://img.shields.io/badge/Min%20SDK-27-4285F4?style=for-the-badge" alt="Min SDK"/>
  <img src="https://img.shields.io/badge/License-GPL%20v3-EA4335?style=for-the-badge" alt="License"/>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-installation">Installation</a> •
  <a href="#️-tech-stack">Tech Stack</a> •
  <a href="#-changelog">Changelog</a>
</p>

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🎯 Focus Timer
- **Pomodoro Technique** - Work in focused intervals
- **Customizable Sessions** - Set your own durations
- **Timer Presets** - Save multiple configurations
- **Auto-start** - Seamless workflow continuation

### 📊 Statistics & Analytics
- **Daily/Weekly/Monthly Charts** - Visualize trends
- **Yearly Heatmap** - GitHub-style calendar
- **Time-of-Day Breakdown** - Peak productivity insights
- **Manual Time Logging** - Add offline focus time

</td>
<td width="50%" valign="top">

### ✅ Task Management
- **Built-in Task List** - Organize work items
- **Subject Categories** - Math, Science, etc.
- **Priority Levels** - High, Medium, Low
- **Swipe to Delete** - Quick task removal

### 🎵 Focus Sounds
- **Ambient Music** - Relaxing backgrounds
- **Built-in Tracks** - Cozy Lofi, Study Music
- **Custom Audio** - Use your own files
- **Media Controls** - Play/pause from notification

</td>
</tr>
</table>

<details>
<summary><b>📱 More Features</b></summary>

### 🔔 Notifications & Alerts
- Session complete alerts with custom sounds
- Vibration feedback for silent environments
- Auto Do Not Disturb during focus

### 📱 Home Screen Widgets
- Timer control widget
- Daily stats widget
- Weekly history widget

### 🎨 Appearance
- Material 3 Expressive design
- Dynamic colors (Android 12+)
- Light, Dark & AMOLED themes
- Custom accent colors

### ⚙️ Other
- Always-On Display support
- Backup & Restore
- 15+ languages
- Completely offline, no ads

</details>

---

## 🆚 Why Zon?

<table>
<tr>
<th>Feature</th>
<th align="center">Zon</th>
<th align="center">Other Apps</th>
</tr>
<tr>
<td>🚫 <b>No Ads</b></td>
<td align="center">✅</td>
<td align="center">❌</td>
</tr>
<tr>
<td>📵 <b>Works Offline</b></td>
<td align="center">✅</td>
<td align="center">❌</td>
</tr>
<tr>
<td>🔓 <b>Open Source</b></td>
<td align="center">✅</td>
<td align="center">❌</td>
</tr>
<tr>
<td>💰 <b>All Features Free</b></td>
<td align="center">✅</td>
<td align="center">❌</td>
</tr>
<tr>
<td>🔒 <b>Privacy Focused</b></td>
<td align="center">✅</td>
<td align="center">❌</td>
</tr>
<tr>
<td>📱 <b>Home Screen Widgets</b></td>
<td align="center">✅</td>
<td align="center">⚠️</td>
</tr>
<tr>
<td>🎵 <b>Focus Sounds</b></td>
<td align="center">✅</td>
<td align="center">⚠️</td>
</tr>
<tr>
<td>✅ <b>Built-in Tasks</b></td>
<td align="center">✅</td>
<td align="center">⚠️</td>
</tr>
</table>

---

## 📸 Screenshots

<p align="center">
  <i>Coming soon</i>
</p>

---

## 📥 Installation

### Option 1: Download APK
Download the latest release from [GitHub Releases](https://github.com/vrn7712/Zon/releases/latest)

### Option 2: Build from Source
```bash
# Clone the repository
git clone https://github.com/vrn7712/Zon.git
cd Zon

# Build the APK
./gradlew assembleFossDebug
```

📦 APK location: `app/build/outputs/apk/foss/debug/zon.apk`

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Language** | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| **UI Framework** | ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) |
| **Design System** | ![Material 3](https://img.shields.io/badge/Material%203-757575?style=flat-square&logo=materialdesign&logoColor=white) |
| **Architecture** | MVVM + StateFlow |
| **Database** | ![Room](https://img.shields.io/badge/Room-4285F4?style=flat-square&logo=android&logoColor=white) |
| **Media Playback** | Media3 ExoPlayer |
| **Widgets** | Glance AppWidget |
| **Build System** | ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white) |

---

## 📋 Changelog

### v1.0 Flow (January 2026)
> *Initial Release*

#### ✨ Features
- Full Pomodoro timer with customizable sessions
- Comprehensive statistics with charts and heatmaps
- Task management with categories and priorities
- Manual focus time logging
- Built-in focus sounds (Cozy Lofi, Study Music)
- Home screen widgets
- Material 3 Expressive UI with dynamic colors
- Backup & restore functionality
- 15+ language translations

#### 🔧 Technical
- Migrated to Jetpack Compose
- Room database for persistence
- Kotlin Coroutines & Flow
- Media3 for audio playback

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

> *Based on [Tomato](https://github.com/nsh07/Tomato) by Nishant Mishra.*

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/vrn7712">Vrushal</a>
</p>

<p align="center">
  <a href="https://vrn7712.github.io/zon-website/">Website</a> •
  <a href="https://github.com/vrn7712/Zon/issues">Report Bug</a> •
  <a href="https://github.com/vrn7712/Zon/issues">Request Feature</a>
</p>
