## Extensions
```
Catppuccin Theme
Material Icon Theme
Vim
Quokka.js
One Monokai Theme
Theme by Language
```

## Shortcuts
```
+--------------------+--------------------+
| Move Line Down     | alt + j            |
+--------------------+--------------------+
| Move Line Up       | alt + k            |
+--------------------+--------------------+
| Indent Line        | alt + l            |
+--------------------+--------------------+
| Outdent Line       | alt + h            |
+--------------------+--------------------+
| Vim Toggle         | super + esc        |
+--------------------+--------------------+
// retire | Copy Line Down     | alt + d            |
// retire | Delete Line        | shift + alt + d    |
+--------------------+--------------------+
```

## vimrc
vim.opt.nu = true
vim.opt.relativenumber = true

set nu
set rnu

nnoremap j jzz
nnoremap k kzz
nnoremap <C-d> <C-d>zz
nnoremap <C-u> <C-u>zz

## User Settings
```json
{
    // Main
    "workbench.colorTheme": "Catppuccin Mocha",
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontSize": 16,
    "editor.minimap.enabled": true,
    "editor.wordWrap": "off",
    "diffEditor.wordWrap": "off",
    "editor.renderWhitespace": "all",
    "editor.lineNumbers": "relative",
    "editor.cursorBlinking": "solid",
    "editor.cursorStyle": "block-outline",
    "workbench.layoutControl.enabled": false,
    "workbench.activityBar.visible": true,
    "workbench.startupEditor": "none",
    "vim.vimrc.enable": true,
    // "vim.vimrc.path": "/path/to/.vimrc"
    // "terminal.integrated.fontSize": 14,

    // Indenting
    "editor.tabSize": 4,
    "editor.detectIndentation": false,
    "editor.insertSpaces": true,

    // Themeing
    "theme-by-language.themes": {
        "*": "Catppuccin Mocha",
        "markdown": "One Monokai"
    },
    "workbench.colorCustomizations": {
        "[One Monokai]": {
            "activityBar.background": "#11111b",
            "sideBar.background": "#181825",
            "sideBarSectionHeader.background": "#181825",
            "editor.background": "#1e1e2e",
            "minimap.background": "#1b1b29",
            "editorGroupHeader.tabsBackground": "#11111b",
            "tab.activeBackground": "#1e1e2e",
            "tab.inactiveBackground": "#181825",
            "titleBar.activeBackground": "#11111b"
        }
    }
}
```