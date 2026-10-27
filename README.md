# Dark Nova

A modern dark theme for Pale Moon, inspired by the [Mozilla Firefox Nova](https://blog.mozilla.org/en/firefox/new-firefox-design-is-here/) redesign.

> [!NOTE]
> The theme has been tested on **Linux** with the **GTK3** build of Pale Moon, and on **Windows 11** by [Lootyhoof](https://github.com/Lootyhoof). macOS styling is included but has not been verified yet — feedback and bug reports for it are welcome.

Forked from [Dark Moon](https://github.com/Lootyhoof/darkmoon), which is based on [White Moon](https://github.com/Lootyhoof/whitemoon).

## Features

- Nova-inspired design language: rounded surfaces, softer interaction states and more breathing room.
- Dark palette with a subtle cool tint and a customizable accent colour.
- [Lucide](https://lucide.dev/) line icons across the toolbar, menus, trees and browser chrome.
- Dark Developer Tools, enabled by default.
- Restyled tabs, address bar, bookmarks, menus, popups, autocomplete, find bar, scrollbars, in-content pages, Page Info, the Permissions Manager, the add-ons manager and the preferences windows.

## TODO / known issues

These areas are not fully styled yet and are tracked here for future work:

- **Developer Tools (F12)** — the palette and most controls follow Nova; a few panels (Debugger, Style Editor, Storage) and the Browser Toolbox may still need detail work.
- **Platforms** — verified on **Linux / GTK3** and on **Windows 11** (by [Lootyhoof](https://github.com/Lootyhoof)); macOS still needs testing.
- **About Pale Moon window** (`about:`) — the three bottom links (End-user rights, Licensing information, Release notes) still use native link styling; restyle them as Nova buttons. The artwork and header are left untouched on purpose.
- **File picker and dialog icons** — the file picker and a few dialogs still use inherited raster artwork instead of Lucide icons.

## Building

Simply download the contents of the "src" folder and pack the contents into a .zip file. Then, rename the file to .xpi and drag into the browser.

On Unix systems (or Windows 10, with [WSL](https://docs.microsoft.com/en-us/windows/wsl/about)) you can optionally run `build.sh` instead. Running this as-is will produce a .xpi file ending in `-dev`, and if run from the command line and appending a version (e.g. `./build.sh 3.0.0`) will append that version to the filename instead.

## Download

Dark Nova is available from the official Pale Moon Add-ons site:

- **https://addons.palemoon.org/addon/dark-nova/**

You can also grab the latest release from the Releases section of this repository.
