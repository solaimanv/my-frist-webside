# ⚡ Visual Studio Code Customization

> Personal collection of VS Code settings, extensions, themes, and keyboard shortcuts — designed to boost productivity and make coding more enjoyable.

---

## 📝 Why?

I've been a loyal user of **Visual Studio Code** since **2018**, and it has become my preferred code editor.  
Its **speed**, **flexibility**, and **cross-platform reliability** make it my go-to tool.  

Over the years, I’ve customized VS Code extensively — tweaking its appearance, configuring settings, and installing essential extensions to fit my workflow.  

I even built my own personalized theme since I couldn’t find one that was *perfectly me*.  
Every time I set up a new environment, I used to configure everything manually — now I’ve uploaded all my settings here so I can reuse them anytime.

> 💡 Feel free to explore, copy, or adapt anything from this setup for your own use.

---

## ⚙️ VS Code Settings (`settings.json`)

```json
{
  "editor.fontSize": 20,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorBlinking": "expand",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "workbench.colorCustomizations": {
    "editorGroupHeader.tabsBackground": "#2c2c54",
    "activityBar.background": "#2c2c54",
    "sideBar.background": "#141422",
    "minimap.background": "#141422",
    "tab.activeBackground": "#706fd3",
    "tab.inactiveBackground": "#191846",
    "terminal.border": "#2c2c54",
    "terminal.background": "#2c2c54",
    "statusBar.background": "#474787",
    "scrollbarSlider.background": "#474787",
    "scrollbarSlider.hoverBackground": "#706fd3"
  },
  "editor.tokenColorCustomizations": {
    "comments": "#95afc0"
  },
  "editor.linkedEditing": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": true,
  "editor.hover.enabled": false,
  "window.zoomLevel": 1,
  "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.generateMap": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Andromeda",
  "workbench.editor.enablePreview": false,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.fontSize": 20,
  "diffEditor.wordWrap": "on",
  "security.workspace.trust.untrustedFiles": "open",
  "prettier.proseWrap": "always",
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "screencastMode.onlyKeyboardShortcuts": true,
  "screencastMode.mouseIndicatorColor": "#f1c40f",
  "screencastMode.verticalOffset": 0,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}



 Extension                       | Author

| ------------------------------- | --------------------- |
| Auto Close Tag                  | Jun Han               |
| Auto Import - ES6, TS, JSX, TSX | Sergey Korenuk        |
| Auto Rename Tag                 | Jun Han               |
| Debugger for Chrome             | Microsoft             |
| ESLint                          | Microsoft             |
| indent-rainbow                  | oderwat               |
| HTML CSS Support                | ecmel                 |
| JavaScript (ES6) Code Snippets  | charalampos karypidis |
| Live Server                     | Ritwick Dey           |
| Live Sass Compiler              | Glenn Marks           |
| Material Icon Theme             | Philipp Kief          |
| npm Intellisense                | Christian Kohler      |
| Path Intellisense               | Christian Kohler      |
| Postman                         | Postman               |
| Prettier - Code Formatter       | Prettier              |
| ReactJS Code Snippets           | charalampos karypidis |
| Simple React Snippets           | Burke Holland         |
| Snipped                         | Jefferson Licet       |
| Stylelint                       | Stylelint             |
| WordPress Snippets              | wpprotools.io         |
| VSCode React Refactor           | planbcoding           |
| Tailwind CSS IntelliSense       | Tailwind Labs         |


| Theme            | Description                               |

| ---------------- | ----------------------------------------- |
| **Andromeda** 👈 | My personal favorite — clean and balanced |
| Dracula Official | Classic and eye-friendly                  |
| Night Owl        | Great for late-night coding               |
| Shades of Purple | Colorful and vibrant                      |
| SynthWave '84    | Retro neon vibes                          |
| Ayu              | Minimal and elegant                       |


| Action                     | Windows / Linux     | Mac                    |

| HTML Boilerplate           | `! + TAB`           | `! + TAB`              |
| Open File Palette          | `Ctrl + P`          | `cmd + P`              |
| Add Cursors to All Matches | `Ctrl + Shift + L`  | `cmd + Shift + L`      |
| Undo                       | `Ctrl + U`          | `cmd + U`              |
| Select Current Line        | `Ctrl + L`          | `cmd + L`              |
| Zen Mode                   | `Ctrl + K Z`        | `cmd + K Z`            |
| Toggle Sidebar             | `Ctrl + B`          | `cmd + B`              |
| Search Global Files        | `Ctrl + Shift + F`  | `Ctrl + Shift + F`     |
| Find on File               | `Ctrl + F`          | `cmd + F`              |
| Find & Replace             | `Ctrl + H`          | `cmd + H`              |
| Delete Previous Word       | `Ctrl + Backspace`  | `cmd + Backspace`      |
| Move Line Up/Down          | `Alt + ↑/↓`         | `option + ↑/↓`         |
| Add Multiple Cursors       | `Ctrl + Alt + ↑/↓`  | `cmd + option + ↑/↓`   |
| Comment Line               | `Ctrl + /`          | `cmd + /`              |
| Duplicate Line             | `Alt + Shift + ↑/↓` | `option + Shift + ↑/↓` |
| Split View                 | `Ctrl + \`          | `cmd + \`              |
| Switch Between Views       | `Ctrl + 1, 2...`    | `cmd + 1, 2...`        |
| Open Terminal              | `` Ctrl + ` ``      | `` cmd + ` ``          |
| Show Suggestions           | `Ctrl + Space`      | `cmd + Space`          |
| Close Tab                  | `Ctrl + W`          | `cmd + W`              |
| Close All Tabs             | `Ctrl + Shift + W`  | `cmd + Shift + W`      |

---
💾 Setup Instructions

Copy the JSON from the settings.json
 section.

Open VS Code → press Ctrl + , (or Cmd + , on Mac).

Click on the top-right Open Settings (JSON) icon.

Paste the configuration and save.

Install the extensions listed above.

Restart VS Code and enjoy your new setup! 🚀

💜 Credits & Author

👨‍💻 Created by: [solaiman]
📅 Since: 2025
🌐 Editor: Visual Studio Code
💬 Feel free to open issues or pull requests if you have better customization ideas!

Would you like me to make this README design **more visual** (with badges, icons, and color sections like GitHub profile READMEs)?  
I can upgrade it to a **premium-style version** with shields.io badges, theme previews, and emoji sections.

