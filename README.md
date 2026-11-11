# The Atlaser

Released builds of The Atlaser, a desktop tool that packs images into texture atlases. Windows only.

## Installing

Download `The-Atlaser-<version>.zip` from the [latest release](https://github.com/Gwerano/The-Atlaser-releases/releases/latest), unzip it to a folder you can write to, such as Documents rather than Program Files, and run `The Atlaser.exe`. Newer versions download themselves.

## Files

- `The-Atlaser-<version>.zip`: the launcher and that version, ready to unzip.
- `the-atlaser-<version>.exe`: one version of the app. The launcher keeps each version as a separate file in the `verzie` folder.
- `the-atlaser-launcher.exe`: the launcher, saved as `The Atlaser.exe`.
- `versions.json`: the list of versions the app reads.

Every file is signed. The app refuses a file whose signature or SHA-256 does not match `versions.json`.
