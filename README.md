# VCS Desktop for Windows

**VCS — Volume. Confluence. Statistics.** · by Anthony D. Layne · [Layne Capital](https://layne.capital)

The desktop app for VCS members: one window and a tray icon around the VCS engine on your computer. Pick your markets,
press **Start**, and VCS shows each setup's stage, plan and next step in plain words.

## Download

**[Download VCS for Windows](https://github.com/layne-capital/vcs-desktop/releases/latest/download/VCS-Setup-x64.exe)** —
always the latest version · [all releases](https://github.com/layne-capital/vcs-desktop/releases)

## You need

- Windows 10 or 11, 64-bit
- A VCS membership — the **VCS BOT** folder you receive as a member ([request access](https://tally.so/r/jadlr1))
- Node.js 20 or newer ([nodejs.org](https://nodejs.org))
- TradingView Desktop

## Install

1. Run `VCS-Setup-x64.exe` from File Explorer. It installs for your Windows user only (no admin rights) and puts **VCS** on
   your desktop and in the Start menu.
2. The installer is not code-signed yet, so Windows may show **"Windows protected your PC"** or **"unknown publisher"**.
   Choose **More info → Run anyway**.
3. Open **VCS**. The first time, press **Choose your VCS folder** and pick your **VCS BOT** folder. VCS connects by itself.

Not a member yet? The app shows **Request access** on its first screen.

## Check your download

Each release lists the SHA-256 of its installer. In PowerShell:

```powershell
Get-FileHash .\VCS-Setup-x64.exe -Algorithm SHA256
```

The result must match the release notes.

## Independent virus scan

Every release is scanned on VirusTotal by its SHA-256, and the report link is in its release notes.

- **1.1.4:** [VirusTotal report](https://www.virustotal.com/gui/file/7a3ba29bd21b9a87d0da8ce26327fbba1a8b4197196ab17e087817a05bcc618c) — Microsoft Defender,
  Kaspersky, ESET, Bitdefender and CrowdStrike report it clean. A few machine-learning scanners can flag a new, unsigned
  installer; those are false positives and have been reported to their vendors.

## What this is — and isn't

- This repository holds the desktop installer only. The VCS engine, its indicators and its research are members-only and
  are never published here.
- VCS is **analysis and alerts only**. It never places, changes or cancels an order and is not connected to any broker
  account.
- Nothing here is financial advice, and no win rate or edge is claimed.

© 2026 Anthony D. Layne · Layne Capital. All rights reserved.
