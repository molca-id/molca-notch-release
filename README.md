# Molca Notch releases

Installers and the landing page of Molca Notch. The app updates itself from the releases of this repository.

- **Windows:** download `MolcaNotch-Setup-<version>.exe` from the [latest release](https://github.com/molca-id/molca-notch-release/releases/latest). The installer is not code-signed: if SmartScreen warns, choose *More info* > *Run anyway*.
- **macOS / Linux:** coming soon.

## Landing page

`index.html` is the landing page (GitHub Pages, branch `main`, folder `/`). It reads the newest version from the latest release, so it needs no edit for a normal release; `VERSION` in its script is only the fallback when the GitHub API cannot be reached.
