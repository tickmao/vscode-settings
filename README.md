# vscode-settings
个人vscode定制设置

![vscode](https://ae01.alicdn.com/kf/H346f211dd631410db082021aca9b1055H.jpg)

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
    "workbench.iconTheme": "material-icon-theme", // 图标主题
    "workbench.colorTheme": "Dracula", // 颜色主题
    "workbench.colorCustomizations": {
        "[Dracula]": {
            // 编辑区域背景
            "editor.background": "#292D3E",
            "editor.foreground": "#c7d4dd",
            // 侧边栏
            "sideBar.background": "#292D3E",
            "sideBar.foreground": "#c7d4dd",
            "sideBar.border": "#292D3E",
            // 侧边栏列表
            "list.inactiveSelectionBackground": "#292D3E",
            "list.inactiveSelectionForeground": "#dfdfdf",
            "list.hoverBackground": "#292D3E",
            "list.hoverForeground": "#dfdfdf",
            // peek 窗口
            "peekView.border": "#5b99fc9c",
            // 顶部 tab 栏
            "tab.border": "#292D3E",
            "tab.activeBackground": "#292D3E",
            "tab.activeForeground": "#c7d4dd",
            "tab.inactiveBackground": "#292D3E",
            "tab.hoverBackground": "#292D3E",
            "tab.unfocusedHoverBackground": "#292D3E",
            "tab.hoverBorder": "#5b99fcb9",
            "tab.inactiveForeground": "#8e8e8e",
            "editorGroupHeader.tabsBackground": "#292D3E",
            "editorGroupHeader.tabsBorder":"#292D3E",
            "editorGroup.border": "#292D3E",
            "contrastBorder":"#292D3E",
            // 最左侧工具栏
            "activityBar.background": "#292D3E",
            "activityBar.foreground": "#c7d4dd",
            "activityBar.border": "#292D3E",
            // 状态栏
            "statusBar.background": "#292D3E",
            "statusBar.foreground": "#c7d4dd",
            "statusBar.border" : "#292D3E",
            // panel 窗口
            "panel.background": "#292D3E",
            "panel.border":"#292D3E",
            // 光标
            "editorCursor.foreground": "#84B1ED",
            // 当前行
            "editor.lineHighlightBackground": "#393C4C",
            //缩进参考线
            // "editorIndentGuide.activeBackground": "#5b99fc33",
            // 行号栏的当前行
            "editorLineNumber.activeForeground": "#dabfe0",
            // 行号
            "editorLineNumber.foreground": "#7e7d7e",
            // 标尺
            "editorRuler.foreground": "#7c5881",
            // 快捷提示窗口
            "editorSuggestWidget.highlightForeground": "#84B1ED",
            "editorSuggestWidget.selectedBackground": "#333f5c",
            // 单击一个词时，其它相同单词
            "editor.selectionHighlightBackground": "#70697ec9",
            "editor.selectionBackground": "#70697ec9",
            "editor.selectionHighlightBorder": "#b5f1a159",
            // terminal
            "terminalCursor.foreground": "#84B1ED",
            "terminal.background": "#292D3E",
            // 侧边栏中一块区域的标题
            "sideBarSectionHeader.background": "#292D3E",
            "sideBarSectionHeader.border": "#292D3E",
            // 区域获取焦点时
            "focusBorder": "#5b99fc36",
            // 标题栏颜色
            "titleBar.activeBackground": "#292D3E",
            "titleBar.activeForeground":"#c7d4dd",
            "titleBar.inactiveBackground": "#292D3E",
            "titleBar.inactiveForeground": "#c7d4dd",
            //滚动
            "scrollbar.shadow": "#292D3E",
            "editorOverviewRuler.border":"#292D3E",
        }
    },

## 声明

仅用于学习个人使用，如有侵权请联系删除。E-mail：[lyle.lypm@gmail.com](mailto:lyle.lypm@gmail.com)

## 参与我们

如果有任何想法或需求，可以在 [issue](https://github.com/tickmao/vscode-settings/issues) 中告诉我们，欢迎各种小伙伴踊跃留言。