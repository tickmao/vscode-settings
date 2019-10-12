# vscode-settings
个人vscode定制设置

![vscode](https://ae01.alicdn.com/kf/H87a8d6b48c4b40259b4a4007806638b7g.png)

### 基于Dracula编辑器主题和material-icon-theme的图标主题的个人编辑器定制页面。

> settings.json 文件物理存储位置
>
> - Windows: `%APPDATA%\Code\User\settings.json`
> - Mac: `$HOME/Library/Application Support/Code/User/settings.json`
> - Linux: `$HOME/.config/Code/User/settings.json`
>
> 依次点击菜单 `Code > Preferences > Settings` 或 快捷键 `command + ,` 进行设置。

    // 字体
    "editor.fontFamily": "'Fira Code', Source Code Pro, Menlo, Monaco, 'Courier New', monospace",

    // 软件主题配色
    "workbench.colorTheme": "Dracula", // 颜色主题
    "workbench.colorCustomizations": {
        "[Dracula]": {
            // 编辑区域背景
            "editor.background": "#282A36",
            "editor.foreground": "#c7d4dd",
            // 侧边栏
            "sideBar.background": "#21232D",
            "sideBar.foreground": "#c7d4dd",
            "sideBar.border": "#202020",
            // 侧边栏列表
            "list.inactiveSelectionBackground": "#282A36",
            "list.inactiveSelectionForeground": "#dfdfdf",
            "list.hoverBackground": "#282A36",
            "list.hoverForeground": "#dfdfdf",
            // peek 窗口
            "peekView.border": "#5b99fc9c",
            // 顶部 tab 栏
            // "tab.border": "#5D72F3",
            "tab.activeBackground": "#282A36",
            "tab.activeForeground": "#c7d4dd",
            "tab.inactiveBackground": "#21232D",
            "tab.activeBorder": "#5D72F3",
            "tab.hoverBackground": "#282A36",
            // "tab.hoverBorder": "#5b99fcb9",
            "tab.inactiveForeground": "#8e8e8e",
            // 最左侧工具栏
            "activityBar.background": "#21232D",
            // 状态栏
            "statusBar.background": "#21232D",
            "statusBar.foreground": "#c7d4dd",
            // panel 窗口
            // "panelTitle.activeBorder": "#5b99fc5b",
            "panelTitle.activeForeground": "#6d819c",
            // 光标
            "editorCursor.foreground": "#84B1ED",
            // 当前行
            "editor.lineHighlightBackground": "#393C4C",
            //缩进参考线
            // "editorIndentGuide.activeBackground": "#5b99fc33",
            // 行号栏的当前行
            "editorLineNumber.activeForeground": "#bfcbe0",
            // 行号
            "editorLineNumber.foreground": "#666",
            // 标尺
            "editorRuler.foreground": "#3f3f3f",
            // 快捷提示窗口
            "editorSuggestWidget.highlightForeground": "#84B1ED",
            "editorSuggestWidget.selectedBackground": "#333f5c",
            // 单击一个词时，其它相同单词
            "editor.selectionHighlightBackground": "#bc92ff1c",
            "editor.selectionBackground": "#70697ec9",
            "editor.selectionHighlightBorder": "#b5f1a159",
            // terminal 中的光标
            "terminalCursor.foreground": "#84B1ED",
            // 侧边栏中一块区域的标题
            "sideBarSectionHeader.background": "#21232D",
            // 区域获取焦点时
            "focusBorder": "#5b99fc36",
            // 标题栏颜色
            "titleBar.activeBackground": "#21232D",
            "titleBar.activeForeground":"#c7d4dd"
        }
    },

## 声明

仅用于学习个人使用，如有侵权请联系删除。E-mail：[lyle.lypm@gmail.com](mailto:lyle.lypm@gmail.com)

## 参与我们

如果有任何想法或需求，可以在 [issue](https://github.com/tickmao/vscode-settings/issues) 中告诉我们，欢迎各种小伙伴踊跃留言。