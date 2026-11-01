<h1 align="center">Mase</h1>

<p align="center">A Web3 deck for Windows that replaces the taskbar. Native, no webview.</p>

Mase hides the Windows taskbar and puts one black shape at the bottom of the screen. It tucks away into a thin strip, opens when you touch the edge, and morphs between states on a single spring. When nothing is going on, Mase the flame peeks out from behind it.

## Features

- **Dock:** pinned and running apps, recently closed apps, minimized windows, Downloads and Trash, laid out like the macOS dock. Clicks follow macOS rules too: one click raises all of an app's windows, and `Alt` and `Ctrl` act as Option and Command. Rest on an app with several windows to pick one by name.
- **Quick settings:** on/off for Wi-Fi, Bluetooth, sound and hotspot, plus a detail page each: join networks, pair devices, per-app volume, hotspot name and password.
- **Notifications:** read and clear them from the dock.
- **Market tools:** search Hyperliquid's perpetual and spot markets, chart them across timeframes, and keep one on the dock with a live PnL.
- **Lightweight:** about 700 KB on disk and 35 MB of memory.

> [!IMPORTANT]
> **Buy and Sell are simulated.** Positions live in a local file and no order is ever sent. Prices come from Hyperliquid's public API and can lag or stop working at any time. PnL ignores fees, funding and spread. Nothing here is financial advice.

## Install

Requires Windows 11 (x64).

1. Download the latest `Mase-Setup-<version>.exe` from [Releases](https://github.com/Bargagana/mase-public/releases).
2. Run it. It installs per user, with no admin rights.
3. The installer isn't signed yet, so SmartScreen may warn you: choose **More info**, then **Run anyway**.

Mase checks this repository's releases for updates and shows one in the notifications page. It installs only when you click, and only if the file carries the developer's signature.

To uninstall, use **Settings > Apps > Installed apps**.

## Using it

- Touch the bottom edge of the screen, under the dock, to open it.
- Rest on the dots above the icons to preview a page. Keep resting on the preview, or click a dot, to open it.
- Right-click an icon for its menu.
- To quit, right-click an empty part of the dock and choose **Keluar dari Mase**. The Windows taskbar comes back.

> [!WARNING]
> Ending Mase from Task Manager leaves the taskbar hidden, because nothing gets a chance to restore it. If that happens, restart `explorer.exe`.

## Known limits

- The dock runs on the primary monitor only.
- Bluetooth can pair new devices, but connecting an already paired one opens Windows Settings.
- Text fields can't paste yet.

## About

The installer is free to use. The source code isn't published in this repository. Mase is an independent project and isn't affiliated with Apple or Microsoft.
