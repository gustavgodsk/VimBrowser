# <img src="./static/icons/icon128.png" align="absmiddle" width="100"> VimBrowser (browser extension)

Adds basic vim motions for quick navigation in the browser

You can add the extension here: Chrome Webshop (soon) and Firefox (soon)

# Keybindings
```javascript
{
    left: "h",
    down: "j",
    up: "k",
    right: "l",
    history_back: "H",
    history_forward: "L",
    top: "gg",
    bottom: "G",
    reload: "r",
    remove_focus: "<Ctrl-c>"
    // You can add more here...
}
```

**TODO**
- [ ] search: "/" (similar to ctrl+f)

# Configuration

Click on the extension icon to configure keybindings etc.

# Contributing

**1.** Make a local copy of the project
```bash
git clone https://github.com/gustavgodsk/VimBrowser.git
```

**2.** Make your changes to `scripts/vimmotions.js`

**3.** Test changes locally by refreshing the script at `chrome://extensions` (Chrome) or `about:debugging#/runtime/this-firefox` (Firefox)

**4.** Submit a pull request on GitHub

# Manual Installation

Download the files and save them in a folder.

### Chrome
1. Go to chrome://extensions in Chrome.
2. Toggle Developer mode on in the top right corner.
3. Click Load unpacked.
4. Select the folder.
5. Click the Reload icon (the circular arrow).

### Firefox
1. Go to about:debugging#/runtime/this-firefox in Firefox.
2. Click Load Temporary Add-on....
3. Locate the folder and select manifest.json.
4. Click Reload.
