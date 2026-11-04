# Illustrator plug-in releases

Built releases of two Adobe Illustrator plug-ins, Sign Library and OpenDimensions, published here by their release builds.
The installed plug-ins read the manifests below at startup to find updates. No source code lives in this repository.

| File | Contents |
|---|---|
| `signlibrary.json` | Latest Sign Library version, its release notes, and the download URL and SHA-256 checksum for each build |
| `signlibrary/<version>/` | The Sign Library zips (`win-2025`, `mac-2025`, ...) |
| `opendimensions.json`, `opendimensions/<version>/` | The same for OpenDimensions |

Every zip is checked against its SHA-256 before it is installed.
