# Neirose downloads

This repository hosts standalone Windows installers for [Neirose](https://neirose.app), a local music player for Windows 11 x64.

## Downloads

Download installers from the [Releases page](https://github.com/korket/neirose-downloads/releases). Each release includes its versioned installer and SHA-256 checksum. Installation does not require Microsoft Store.

The standalone installer is unsigned. Windows may show an unknown-publisher or reputation warning, and some Windows security policies may prevent it from running. Microsoft Store remains available as an alternative through the Neirose website.

## Updates

The standalone app checks automatically for updates. Downloading and installing an update requires your choice. Update metadata is signed by Neirose, and the app verifies the installer size and SHA-256 checksum before launching it. These update signatures do not code-sign the Windows installer.

The stable update feed is hosted at `https://neirose.app/updates/stable-win-x64.json`. A published version's installer bytes are never replaced; fixes receive a new version.

## Help

See the [documentation](https://neirose.app/docs), [privacy information](https://neirose.app/privacy), and [support page](https://neirose.app/support).

This repository contains distribution assets, not the application's source code. Each release records the source revision used to build it.
