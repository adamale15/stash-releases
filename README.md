# Stash releases

Windows installers, Linux AppImage and Debian/RPM packages, signed desktop update metadata, and Android APKs for Stash.

Download the latest packages from [Releases](https://github.com/adamale15/stash-releases/releases/latest).

- **Omarchy and other Linux desktops:** use the AppImage. Make it executable with `chmod +x Stash_*.AppImage`, then launch it from a stable location. Debian/Ubuntu and Fedora/RHEL packages are also available. Linux sessions use a running, unlocked Secret Service keyring such as GNOME Keyring or KWallet.
- **Windows and Linux AppImage:** use **Update** in the desktop app for future releases. Debian/RPM installations use their package manager or a downloaded replacement installer.
- **Android:** install the latest APK over your existing app.

`SHA256SUMS.txt` lists release asset checksums. AppImage and Windows updater payloads have cryptographic signatures.

This repository distributes release artifacts. Application source code is maintained separately.
