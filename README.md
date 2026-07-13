# Cabana Buddy 🌴

The little menu-bar app that shares what you're building into your **Cabana** room —
live project cards from your coding agent, no terminal required.

## Download for macOS

### [⬇️ Get the latest release](../../releases/latest)

- **Apple Silicon** (M1/M2/M3/M4) → `…macOS-arm64.dmg`
- **Intel** → `…macOS-intel.dmg`

Open the `.dmg`, drag **Cabana Buddy** to Applications, then launch it — it lives in
your menu bar 🐱. Click **Connect to Cabana**, pick your room, then **Share a folder**.

### First launch (the app isn't notarized yet)

macOS will say it's from an unidentified developer. Either:

- **Right-click** the app in Applications → **Open** → **Open**, or
- If it still won't open, clear the download flag once in Terminal:
  ```
  xattr -dr com.apple.quarantine "/Applications/Cabana Buddy.app"
  ```

Then it opens normally every time.

## What it does

- Streams your Claude Code activity into your room as a live project card.
- Secrets are redacted before anything leaves your machine.
- Prompt-sharing is off by default, per project.

Made with 🌴 at **cabana.fyi**.
