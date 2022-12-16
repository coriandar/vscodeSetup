## Extensions
    Catpuccin Theme
    Material Icon Theme
    One Monokai Theme
    Theme by Language
    Vim

## Shortcuts
    +--------------------+--------------------+
    | Move Line Down     | Alt + J            |
    +--------------------+--------------------+
    | Move Line Up       | Alt + K            |
    +--------------------+--------------------+
    | Copy Line Down     | Alt + D            |
    +--------------------+--------------------+
    | Delete Line        | Shift + Alt + D    |
    +--------------------+--------------------+
    | Indent Line        | Alt + L            |
    +--------------------+--------------------+
    | Outdent Line       | Alt + H            |
    +--------------------+--------------------+
    | Vim Toggle         | Super + Esc        |
    +--------------------+--------------------+

## User Settings
    {
        // Main
        "workbench.colorTheme": "Catppuccin Mocha",
        "workbench.iconTheme": "material-icon-theme",
        "editor.fontSize": 18,
        "editor.minimap.enabled": true,
        "editor.renderWhitespace": "all",
        "editor.lineNumbers": "relative",
        "editor.cursorBlinking": "solid",
        "editor.cursorStyle": "block-outline",
        "workbench.layoutControl.enabled": false,
        "workbench.activityBar.visible": true,

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