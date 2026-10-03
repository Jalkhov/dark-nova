# Dark Nova

A modern dark theme for Pale Moon, inspired by the [Mozilla Firefox Nova](https://blog.mozilla.org/en/firefox/new-firefox-design-is-here/) redesign.

Forked from [Dark Moon](https://github.com/Lootyhoof/darkmoon), which is based on [White Moon](https://github.com/Lootyhoof/whitemoon).

## Features

- Nova-inspired design language: rounded surfaces, softer interaction states and more breathing room.
- Dark palette with a subtle cool tint and a customizable accent colour.
- [Lucide](https://lucide.dev/) line icons across the toolbar and browser chrome.
- Restyled tabs, address bar, bookmarks, menus, popups, autocomplete and find bar.

## TODO / known issues

These areas are not fully styled yet and are tracked here for future work:

- **Page Info window** — the *Page Info* dialog (General, Media, Security and Headers tabs) still uses the inherited White Moon styling and icons.
- **Developer Tools (F12)** — the menu entries are iconized, but the DevTools panels themselves (Inspector, Web Console, Debugger, Style Editor, Performance, Network, …) still need to be adapted to the Nova look. Styling them is possible from the theme, so it is planned.
- **Legacy sprites** — some tree and places icons still use the old `places.svg` sprite instead of Lucide.

## Building

Simply download the contents of the "src" folder and pack the contents into a .zip file. Then, rename the file to .xpi and drag into the browser.

On Unix systems (or Windows 10, with [WSL](https://docs.microsoft.com/en-us/windows/wsl/about)) you can optionally run `build.sh` instead. Running this as-is will produce a .xpi file ending in `-dev`, and if run from the command line and appending a version (e.g. `./build.sh 3.0.0`) will append that version to the filename instead.

## Download

You can grab the latest release from the Releases section of this repository.
