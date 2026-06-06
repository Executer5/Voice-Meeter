# VoiceMeeter

A professional virtual audio mixer designed for advanced audio routing, streaming, recording, and sound management on Windows systems.

## 🖼️ Preview

UI preview

---

## ⚠️ Disclaimer

VoiceMeeter is an independent audio mixing solution developed by VB-Audio.

Users are responsible for configuring audio devices correctly. Improper setup may result in audio routing issues, microphone problems, or recording errors.

Always download releases from trusted sources and ensure your audio drivers are up to date.

---

## 🩹 Support

For assistance, troubleshooting, or feature requests:

* Open an issue on GitHub
* Join the community Discord server
* Visit the official documentation and guides

---

## 🗺️ Overview

VoiceMeeter provides a powerful virtual mixing environment for Windows, allowing users to manage multiple audio inputs and outputs with ease.

Key areas include:

* Virtual audio routing
* Microphone processing
* Stream audio management
* Multi-device output support
* Recording and monitoring tools
* Low-latency audio control

Designed for streamers, content creators, gamers, and audio professionals.

---

## ✨ Features

⚡ Real-time audio routing

🎙️ Virtual microphone support

🔊 Multiple hardware outputs

🎛️ Advanced audio mixer

📦 Lightweight performance

🎚️ Volume and EQ controls

🎧 Audio monitoring

🌙 Modern interface

---

## 🚦 Status

Tested on:

✅ Windows 10

✅ Windows 11

Supported architectures:

✅ x64

✅ x86

---

## 🚀 Getting Started

### Installation

1. Download the latest release
2. Run the installer
3. Restart audio services if required
4. Configure your input and output devices

### Running

Launch:

```bash
VoiceMeeter.exe
```

---

## ⚙️ Configuration

Settings can be customized through the built-in control panel.

Example preferences:

```json
{
  "startup": true,
  "auto_connect": true,
  "monitoring": true
}
```

---

## 🎛️ Audio Routing

Supported functions:

* Virtual Inputs
* Hardware Inputs
* Virtual Outputs
* Hardware Outputs
* Audio Monitoring
* Streaming Integration

---

## 🛠️ Build From Source

### Requirements

Install:

* Visual Studio 2022
* Windows SDK
* CMake
* MSVC Build Tools

### Clone Repository

```bash
git clone https://github.com/USERNAME/VoiceMeeter.git
cd VoiceMeeter
```

### Build

```bash
cmake -S . -B build
cmake --build build --config Release
```

Compiled files will appear in:

```text
out/
```

---

## 📂 Project Structure

```text
VoiceMeeter/
├── src/
├── include/
├── assets/
├── configs/
├── build/
└── README.md
```

---

## 🤔 FAQ

### Does VoiceMeeter replace my audio drivers?

No. It works alongside existing audio drivers and devices.

### Can I use it for streaming?

Yes. VoiceMeeter is commonly used for streaming, recording, and virtual audio routing.

### Does it support multiple outputs?

Yes. Multiple physical and virtual outputs are supported.

---

## 🔗 Dependencies

### Libraries Used

* PortAudio
* ASIO SDK
* ImGui
* Windows Audio APIs
* DirectX SDK

---

## 📜 License

Licensed under the MIT License.

See LICENSE for more information.

---

## ⭐ Credits

Special thanks to all contributors, testers, and community members who helped improve the project.
