> [!WARNING]  
> This application is not affiliated with or endorsed by Discord Inc. Use of modified versions of the Discord app may violate Discord’s terms of service. Use at your own risk.

> [!CAUTION]
> The only official places to download BunnyManager are this GitHub repository and [this repository](https://github.com/pyoncord/Bunny#installing). Any other website offering downloads or claiming to be us are not controlled by us.

<div align="center">

  <img src="images/bunny_logo.png" alt="Bunny logo" width="200px" style="border-radius: 50%" />
  
  # Bunny Manager

Easily install Bunny on Android

[![Latest release](https://img.shields.io/github/v/release/pyoncord/BunnyManager?color=3AB8BA&display_name=release&label=Latest&style=for-the-badge)](https://github.com/pyoncord/BunnyManager/releases/latest)

---

  <br>

![Debug build status](https://img.shields.io/github/actions/workflow/status/pyoncord/BunnyManager/build-debug.yml?label=Debug%20Build&logo=github&style=for-the-badge&branch=main)
[![Stars](https://img.shields.io/github/stars/pyoncord/BunnyManager?logo=github&style=for-the-badge)](https://github.com/pyoncord/BunnyManager/stargazers)
[![Discord](https://img.shields.io/discord/1196075698301968455?logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/XjYgWXHb9Q)

  <br>
  
  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pyoncord/BunnyManager?logo=github&logoColor=%23fff&style=for-the-badge)
  ![Downloads (latest)](https://img.shields.io/github/downloads/pyoncord/BunnyManager/latest/total?style=for-the-badge&logo=github&label=Downloads%20(Latest)&color=blue)
  ![Total downloads](https://img.shields.io/github/downloads/pyoncord/BunnyManager/total?style=for-the-badge&logo=github&label=Downloads%20(Total)&color=blue)
  ![GitHub top language](https://img.shields.io/github/languages/top/pyoncord/BunnyManager?style=for-the-badge)

  <br>

  <img src="images/screenshot_home.jpg" width="200px">
  
</div>

## Overview

BunnyManager is a user-friendly application for Android that allows you to download and manage modified versions of the Discord app for **non-rooted devices.** Enhance your Discord experience with custom features and tweaks that are not available in the official app.

## Build

#### Prerequisites

- [Git](https://git-scm.com/downloads)
- [JDK 17](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)
- [Android SDK](https://developer.android.com/studio)

#### Instructions

1. Clone the repo
   - `git clone https://github.com/pyoncord/BunnyManager.git && cd BunnyManager`
2. Build the project
   - Linux: `chmod +x ./gradlew && gradlew assembleDebug`
   - Windows: `./gradlew assembleDebug`
3. Install on device
   - [Enable USB debugging](https://developer.android.com/studio/debug/dev-options) and plug in your phone
   - Run `adb install app/build/outputs/apk/debug/app-debug.apk`

## Contributing

We welcome contributions to this open-source project, and you don't need programming skills to participate.

Here are a few things you can do:

- [Test and report issues](https://github.com/pyoncord/BunnyManager/issues/new/choose)
<!-- - [Translate the app into your language](https://crowdin.com/project/vendetta-manager) -->

## Special thanks

- [@rushii](https://github.com/rushiiMachine/) - For the installer, zip library and a portion of patching.
- [@Xinto](https://github.com/X1nto/) - For the preference manager.
- [@Wing](https://github.com/wingio) - For the overall maintenance of the upstream repository.

## License

Bunny Manager is licensed under the Open Software License version 3.0

[![License: OSL v3](https://img.shields.io/badge/License-OSL%20v3-blue.svg?style=for-the-badge)](https://github.com/pyoncord/BunnyManager/blob/main/LICENSE)
