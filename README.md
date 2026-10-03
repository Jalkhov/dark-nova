# Dark Nova

A modern dark theme for Pale Moon, inspired by the [Mozilla Firefox Nova](https://blog.mozilla.org/en/firefox/new-firefox-design-is-here/) redesign.

> [!WARNING]
> So far this theme has **only been tested on Linux** with the **GTK3** build of Pale Moon. Windows and macOS styling is included but has not been verified — feedback and bug reports for those platforms are welcome.

Forked from [Dark Moon](https://github.com/Lootyhoof/darkmoon), which is based on [White Moon](https://github.com/Lootyhoof/whitemoon).

## Features

- Nova-inspired design language: rounded surfaces, softer interaction states and more breathing room.
- Dark palette with a subtle cool tint and a customizable accent colour.
- [Lucide](https://lucide.dev/) line icons across the toolbar, menus, trees and browser chrome.
- Dark Developer Tools (opt-in via the shipped default pref).
- Restyled tabs, address bar, bookmarks, menus, popups, autocomplete, find bar, scrollbars and in-content pages.

## TODO / known issues

These areas are not fully styled yet and are tracked here for future work:

- **Developer Tools (F12)** — the palette and most controls follow Nova; a few panels (Debugger, Style Editor, Storage) and the Browser Toolbox may still need detail work.
- **Platforms** — only **Linux / GTK3** has been tested so far; Windows and macOS need verification.
- **Misc assets** — a few remaining dialogs/notifications may still use inherited artwork.

## Building

Simply download the contents of the "src" folder and pack the contents into a .zip file. Then, rename the file to .xpi and drag into the browser.

On Unix systems (or Windows 10, with [WSL](https://docs.microsoft.com/en-us/windows/wsl/about)) you can optionally run `build.sh` instead. Running this as-is will produce a .xpi file ending in `-dev`, and if run from the command line and appending a version (e.g. `./build.sh 3.0.0`) will append that version to the filename instead.

## Download

You can grab the latest release from the Releases section of this repository.
