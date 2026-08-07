# Taskbar Edge Fixer

[Русский](README.md) | [English](README.en.md)

<img align="right" src="assets/logo.png" alt="Taskbar Edge Fixer" width="220" height="220">

A small background utility that fixes a Windows issue where the auto-hidden
taskbar does not appear after moving the cursor to the bottom edge of the screen.

The issue is especially common with maximized browser windows, including Google
Chrome, and other applications. Taskbar Edge Fixer watches the bottom edge of the
screen and gently helps the taskbar appear without opening the Start menu or
stealing focus from the current application.

**Version:** 1.0.0  
**Author:** [CodoMagia](https://github.com/codomagia)  
**Support:** [Boosty](https://boosty.to/codomagia/donate)

Builds are available in
[Releases](https://github.com/codomagia/TaskbarEdgeFixer/releases).

## Demo

![Taskbar Edge Fixer demo](assets/demo.gif)

## Download

1. Open the [latest Release](https://github.com/codomagia/TaskbarEdgeFixer/releases/latest).
2. Download `TaskbarEdgeFixer-1.0.0.zip`.
3. Extract it and run `TaskbarEdgeFixer.exe`.

No installation is required. Administrator rights are not required.

## System requirements

- Windows 10 or Windows 11
- 64-bit system (x64)

## How to use

Run `TaskbarEdgeFixer.exe`. Control it from the notification area icon.

To test the main feature, enable Windows taskbar auto-hide and move the cursor to
the bottom edge of the monitor. If auto-hide is off, the program does nothing.

### Tray menu

- **Enabled** — watch the bottom edge
- **Settings** — options window
- **About** — version and program info
- **Exit** — full shutdown

Double-click the tray icon to open Settings.

### Settings

- **Poll interval**
- **Activation delay**
- **Re-arm distance**
- **Work on all monitors**
- **Start with Windows**
- **Do not raise the taskbar over a true fullscreen app**

## License

Copyright © 2026 CodoMagia. All rights reserved.

Allowed:
- freely download and use the program;
- redistribute the unmodified official distribution.

Not allowed:
- modifying the program and distributing modified copies;
- presenting the program as someone else’s or removing author attribution.
