# Gaffware Conduit (beta)

Conduit bridges Pioneer Pro DJ Link hardware to OSC (Open Sound Control) compatible visual software such as Resolume, TouchDesigner and Notch: BPM, beat position and track information, live from your players.

> **Beta software.** Thanks for testing! Expect rough edges, and please report anything odd.

## Download

Get the latest installer from **[Releases](https://github.com/gaffware/conduit/releases/latest)**.

Each release lists a SHA-256 checksum. To check your download, run this in PowerShell:

```powershell
Get-FileHash .\ConduitSetup.exe -Algorithm SHA256
```

### First-run warnings (expected during the beta)

The beta builds aren't code-signed yet, so Windows will be cautious:

- **"Windows protected your PC"** (SmartScreen): click **More info → Run anyway**.
- **Windows Defender Firewall prompt** showing *Unknown publisher*: allow access on **Private networks**. Conduit needs this to hear your players.

## Reporting a bug

Open a **[bug report](https://github.com/gaffware/conduit/issues/new/choose)**. The form asks for everything needed, including your log file:

- In Conduit: **Help → About → Open log folder**, or
- Paste `%APPDATA%\Gaffware\Conduit` into the File Explorer address bar.

Logs can contain track titles and artist names, so check them before attaching if that matters to you.

You'll need a free GitHub account to file an issue. If you'd rather not create one, email instead (below).

## Feedback and contact

General feedback, questions, or bug reports without a GitHub account: **feedback@gaffware.example**

## Credits

Pro DJ Link protocol research by James Elliott / [Deep Symmetry](https://github.com/Deep-Symmetry). Conduit wouldn't exist without it.

---
© 2026 Gaffware. Beta builds are provided for testing only.
