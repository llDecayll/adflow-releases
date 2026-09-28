# AdFlow — Downloads

Advertising simulation & recommendation platform for planning, simulating and optimizing ad campaigns before you spend.

## Download

Get the latest version from **[Releases](https://github.com/llDecayll/adflow-releases/releases/latest)**:

| Platform | File |
|---|---|
| Mac with Apple Silicon (M1/M2/M3/M4) | `AdFlow-<version>-arm64.dmg` |
| Mac with Intel processor | `AdFlow-<version>-x64.dmg` |
| Windows 10/11 (64-bit) | `AdFlow-Setup-<version>.exe` |

Not sure which Mac you have?  → About This Mac → "Chip" (Apple M…) or "Processor" (Intel).

## Install

**Mac**
1. Open the `.dmg` and drag **AdFlow** into **Applications**.
2. First launch only: in Applications, **right-click AdFlow → Open → Open** (the app isn't notarized by Apple yet).
   If macOS says the app "is damaged", run once in Terminal: `xattr -cr /Applications/AdFlow.app`

**Windows**
1. Run `AdFlow-Setup-<version>.exe`. It installs for your user account and adds Desktop and Start Menu shortcuts.
2. If SmartScreen appears: **More info → Run anyway** (the installer isn't code-signed yet).

## Updates

AdFlow checks this page for new versions on launch. On Windows, updates download and install automatically (you'll be asked to restart). On Mac, download the new `.dmg` from Releases until the app is code-signed.

Your campaigns are stored locally on your computer and are kept when you update.
