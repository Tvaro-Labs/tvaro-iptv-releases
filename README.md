<p align="center">
  <a href="https://tvaro.live">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/logo-light.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/logo-dark.svg">
      <img alt="Tvaro IPTV Player" src="assets/logo-dark.svg" width="380">
    </picture>
  </a>
</p>

<p align="center">
  A calm, remote-first IPTV player for your own subscription.
</p>

<p align="center">
  <a href="https://github.com/Tvaro-Labs/tvaro-iptv-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Tvaro-Labs/tvaro-iptv-releases?label=release&color=27272a"></a>
  <a href="https://github.com/Tvaro-Labs/tvaro-iptv-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Tvaro-Labs/tvaro-iptv-releases/total?color=27272a"></a>
  <a href="#download"><img alt="Platforms" src="https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android%20%7C%20Samsung%20%7C%20LG-27272a"></a>
</p>

<p align="center">
  <a href="https://tvaro.live"><b>tvaro.live</b></a>
  &nbsp;·&nbsp;
  <a href="#download"><b>Download</b></a>
  &nbsp;·&nbsp;
  <a href="CHANGELOG.md"><b>Changelog</b></a>
  &nbsp;·&nbsp;
  <a href="https://tvaro.live/docs/"><b>Help</b></a>
</p>

Tvaro IPTV Player brings your live TV, TV guide, movies and series together in one calm, consistent app. It is designed for the big screen and a TV remote first, and works just as well with a keyboard and mouse on your desktop. Add your own Xtream Codes account or M3U playlist, or explore the built-in demo first.

> [!IMPORTANT]
> Tvaro IPTV Player does not include, sell or recommend any channels, playlists or subscriptions. You need your own source from a provider you are authorised to use.

## Download

| Platform | Package | Get it |
| --- | --- | --- |
| **Windows** 10 and 11 (64-bit) | Installer (`.exe`) | [Latest release](https://github.com/Tvaro-Labs/tvaro-iptv-releases/releases/latest) |
| **macOS** (Apple Silicon) | Disk image (`.dmg`) | [Latest release](https://github.com/Tvaro-Labs/tvaro-iptv-releases/releases/latest) |
| **Linux** (64-bit) | `.deb`, `.rpm` or `.AppImage` | [Latest release](https://github.com/Tvaro-Labs/tvaro-iptv-releases/releases/latest) |
| **Android** phones, tablets, Android TV, Google TV and Fire TV | Android app (`.apk`) | [tvaro.live/apk](https://tvaro.live/apk) |
| **Samsung** TVs (Tizen 5.0 or later, 2019 and newer) | Installed from your computer | [Tvaro TV Installer](https://tvaro.live/tv-installer/) |
| **LG** TVs (webOS) | Installed from your computer | [Tvaro TV Installer](https://tvaro.live/tv-installer/) |

Only the latest version is published. File names include the version number, for example `Tvaro.IPTV.Player_<version>_x64-setup.exe`. Other files attached to a release are used by the built-in updaters and the TV Installer, so you don't need to download them.

### Tvaro TV Installer

Samsung and LG TVs are set up from a Windows, Mac or Linux computer on the same home network as your TV. The free Tvaro TV Installer finds your TV, guides you through Developer Mode and installs Tvaro IPTV Player.

[Windows](https://updates.tvaro.live/installer/windows) · [macOS](https://updates.tvaro.live/installer/macos) · [Linux `.deb`](https://updates.tvaro.live/installer/linux-deb) · [Linux `.rpm`](https://updates.tvaro.live/installer/linux-rpm) · [Linux `.AppImage`](https://updates.tvaro.live/installer/linux-appimage)

These links always point to the latest version of the installer.

## Features

- **Live TV and guide.** Three guide layouts (Preview, Full grid and Split), catch-up, pause and rewind on supported channels, and reminders before a programme starts.
- **Your channels, your way.** Favorites, up to 12 custom groups, hidden channels, channel number entry and previous channel.
- **Movies and series.** Resume where you left off, Continue Watching, Up Next with autoplay, watched markers and skip intro.
- **A player that stays out of the way.** Four player styles, audio and subtitle tracks with your preferred languages, external subtitles, playback speed and a sleep timer.
- **Profiles and parental controls.** Up to five profiles with an optional PIN each, a parental PIN, adult content locks and per-category locks.
- **Bring your own subscription.** Xtream Codes accounts, M3U and M3U8 playlists, and up to eight XMLTV guide links merged into one guide. Add several accounts and switch between them.
- **Make it yours.** Seven themes, optional background patterns, and English and Arabic with a full right-to-left layout.
- **Private by design.** No Tvaro account to create. Saved logins, playlist links and guide links are encrypted on your device.
- **Try it first.** A built-in demo lets you explore every screen before adding your own source.

See the full list at [tvaro.live/features](https://tvaro.live/features/).

## System requirements

| Platform | Requirement |
| --- | --- |
| Windows | Windows 10 or 11, 64-bit |
| macOS | A Mac with Apple Silicon (M1 or later) running macOS 11 Big Sur or later |
| Linux | A 64-bit (x86_64) distribution such as Ubuntu 22.04 or later, Debian 12 or a recent Fedora |
| Android | Android 9 or later, or Fire OS 7 or later |
| Samsung TV | A Samsung smart TV from 2019 or later, running Tizen 5.0 or newer |
| LG TV | An LG smart TV with webOS that can install the Developer Mode app from LG Content Store (needs a free LG developer account) |
| Subscription | Your own Xtream Codes account or M3U playlist |

## Installation

Windows and macOS may warn you the first time you open a new app from a smaller developer. This is expected.

**Windows.** Run `Tvaro.IPTV.Player_<version>_x64-setup.exe`. It installs for your user account and doesn't need admin rights. If SmartScreen says it protected your PC, select **More info**, then **Run anyway**.

**macOS.** Open `Tvaro.IPTV.Player_<version>_aarch64.dmg` and drag **Tvaro IPTV Player** into **Applications**. If macOS says it can't verify the app, right-click it in Applications, choose **Open**, then **Open** again. On macOS 15 and later, go to **System Settings › Privacy & Security** and select **Open Anyway**. If macOS says the app is damaged, run:

```sh
xattr -dr com.apple.quarantine "/Applications/Tvaro IPTV Player.app"
```

**Linux.** Install the package for your distribution, or run the AppImage on any 64-bit distribution:

```sh
sudo apt install ./Tvaro.IPTV.Player_<version>_amd64.deb
sudo dnf install ./Tvaro.IPTV.Player-<version>-1.x86_64.rpm
chmod +x Tvaro.IPTV.Player_<version>_amd64.AppImage && ./Tvaro.IPTV.Player_<version>_amd64.AppImage
```

**Android phones and tablets.** Open [tvaro.live/apk](https://tvaro.live/apk) in your browser, open the downloaded file and tap **Install**. If Android asks, allow your browser to install unknown apps.

**Android TV, Google TV and Fire TV.** Install the free **Downloader** app, allow it to install unknown apps, then enter `tvaro.live/apk` and install Tvaro when the download finishes. Step-by-step guides are on the [download page](https://tvaro.live/download/).

**Samsung and LG TVs.** Install the [Tvaro TV Installer](https://tvaro.live/tv-installer/) on a computer on the same network as your TV, then select **Find my TV** and follow the steps. Samsung TVs ask you to sign in once with your Samsung account.

## Updates

- **Desktop:** the app checks for updates in the background, verifies that each update is signed, and installs it when nothing is playing. You can turn automatic updates off in **Settings › About**.
- **Android:** install the latest APK from [tvaro.live/apk](https://tvaro.live/apk) over the one you have. Your profiles, accounts and settings stay.
- **Samsung and LG TVs:** the Tvaro TV Installer tells you when a newer version is available for a TV and updates it with one click.

## Support

- Read the [documentation](https://tvaro.live/docs/) and [troubleshooting guide](https://tvaro.live/docs/troubleshooting/).
- Found a problem? [Open an issue](https://github.com/Tvaro-Labs/tvaro-iptv-releases/issues/new/choose) with your platform and app version (**Settings › About**). If you sent logs from **Diagnostics**, include your support code.

## Legal

Tvaro IPTV Player is a media player only. It does not provide any channels, playlists, subscriptions or other content. Use it only with sources you are authorised to access.

Samsung, Tizen, LG, webOS, Android, Android TV, Google TV, Fire TV, Windows, macOS and Linux are trademarks of their respective owners. Tvaro is not affiliated with or endorsed by them.

This repository hosts releases only. © 2026 Tvaro. All rights reserved. See the [privacy policy](https://tvaro.live/privacy/) and [terms of use](https://tvaro.live/terms/).
