<img width="100" src="https://user-images.githubusercontent.com/11070996/147922657-3c079672-edbd-4993-a645-f71a2739b18c.png#gh-dark-mode-only"/>
<img width="100" src="https://user-images.githubusercontent.com/11070996/147922660-890e2d96-26ee-4358-afc4-8421e9a05d5d.png#gh-light-mode-only"/>

# Chikamichi

A very simple Chrome extension that enables fuzzy search of browsing histories and bookmark and tab. Inspired by [Sidekick](https://www.meetsidekick.com/) search dialog.  
The Japanese meaning of `chikamichi` is a shorter way.

## ✨ Features

- ⚡️ Fuzzy search your browsing history and bookmark and tab. powered by [Fuse.js](https://fusejs.io/)
- 🔐 All processing is done within the browser. No history data will be sent to the any server.

## 🎬 Demo

https://user-images.githubusercontent.com/11070996/151462764-4c196ea8-e5d0-4190-be9b-e5d79bf454ab.mp4

## 📦 Install

Please install from:
- [Firefox Add-Ons Repository (AMO)](https://addons.mozilla.org/firefox/addon/chikamichi/)
- [Chrome Web Store](https://chrome.google.com/webstore/detail/chikamichi/gkhobepjbiepngbeikhbpnfgjcjgmgha)

## 💻 Usage

### Shortcuts

| shortcut                              | action                                   |
|---------------------------------------|------------------------------------------|
| `Alt + k`                             | Open search dialog                       |
| `↓` or `↑` (`Ctrl + n` or `Ctrl + p`) | Select history                           |
| `Enter`                               | Open the selected hisotry url            |
| `Ctrl + Enter`                        | Open the selected history url in new tab |

### Search commands

| commands | action                |
|----------|-----------------------|
| `/h`     | Search only histories |
| `/b`     | Search only bookmarks |
| `/t`     | Search only tabs      |

## 👨‍💻 Contributing
Contributions are welcome 🎉 We accept contributions via Pull Requests.

## 💕 Thanks
This extension uses the following library.

* [Viteese-webext](https://github.com/antfu/vitesse-webext)
* [Fuse.js](https://fusejs.io/)
