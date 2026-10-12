# JjabView public updates

Windows x64 distribution packages for JjabView. This repository contains release packages and public update metadata.

Download the matching Client, Remote or Server ZIP from [Latest release](https://github.com/BTL-LaserInnovation/JJabView-Updates/releases/latest).

Close the applications before the first manual upgrade from 1.0.2 or earlier. Back up the role folder and retain installation settings when replacing it. Keep DLLs, runtime and codec-tools together. Version 1.0.3 and later check this feed at GUI startup and let you update now or later.

Portable packages do not install the optional privileged Remote desktop service. Updates retain settings and keep the previous installation as a recovery backup. Interactive UI/UAC and installed-service update checks remain manual.

Every stable release uses tag `v<major.minor.patch>` and includes three role ZIPs plus `jjabview-update.json` (schema 1, version, notes, role, assetName, size and SHA-256). Publish all four assets together. The application uses the public GitHub Releases API without distributing credentials.
