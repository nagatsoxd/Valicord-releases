# Valicord releases

Public distribution of Valicord for Windows x64. Development history remains private; every published version includes its corresponding source archive.

[Download the latest installer](https://github.com/nagatsoxd/Valicord-releases/releases/latest/download/Valicord-Loader.exe) · [Browse releases](https://github.com/nagatsoxd/Valicord-releases/releases)

Each release includes:

- `Valicord-Loader.exe`: installs Valicord into selected Discord, Discord PTB or Discord Canary clients.
- `valicord-update.json`: the version, pinned installer URL and SHA-256 digest used by automatic updates.
- `valicord-source-VERSION.zip`: corresponding source, dependency locks, build scripts and license notices.
- `SHA256SUMS.txt`: checksums for the distributed files.

Use the named `valicord-source-VERSION.zip` asset to rebuild Valicord. GitHub's automatic Source code links contain only this distribution repository.

Valicord is licensed under GPL-3.0-or-later. Original copyright notices and component licenses are included in the installer and corresponding-source ZIP. The initial installer with a configured update feed must be installed once; subsequent releases are detected automatically while Discord is running.
