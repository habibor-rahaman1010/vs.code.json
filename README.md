//update third version......
{
    // code-editor-author-Habibor-Rahaman.
    "update.mode": "none",
    "update.enableWindowsBackgroundUpdates": false,
    "workbench.iconTheme": "vscode-icons",
    "editor.fontLigatures": true,
    "editor.fontFamily": "Operator Mono Lig",
  
    "launch": {

      "version": "0.2.0",
      "configurations": [],
      "compounds": []
    },
  
    "editor.minimap.enabled": false,
    "editor.fontSize": 16,
    "editor.wordWrap": "on",
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.fontWeight": "600",
    
    "explorer.confirmDragAndDrop": false,
    "vsicons.dontShowNewVersionMessage": true,
  
    //coursor
    "editor.cursorSmoothCaretAnimation": true,
    "editor.cursorBlinking": "expand",
  
    //terminal
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.fontWeight": "400",
    // "terminal.integrated.fontFamily": "monospace",
  
    // terminal customization
    "workbench.colorCustomizations": {
      "terminal.background": "#11111b",
      "terminal.foreground": "#c6d3d6",
      "terminalCursor.foreground": "#00d9ff", //terminal coursor color
      "editor.background": "#11111b", // body background color
      "editorCursor.foreground": "#00e1ff", // coursor color
      "sideBar.background": "#1f1f2c", //sidebar background color
      "activityBar.background": "#2b2b44",
      "titleBar.activeBackground": "#2b2b44",
      "tab.inactiveBackground": "#1a1a27",
      "tab.activeBackground": "#021331",
      "editorGroupHeader.tabsBackground": "#1a1a27",
      "editorGroupHeader.border": "#000000D0"
    },
    "explorer.confirmDelete": false,
    "terminal.explorerKind": "integrated",
    "liveServer.settings.donotShowInfoMsg": true,
    // "[javascript]": {
    //   "editor.defaultFormatter": "esbenp.prettier-vscode",
    // },

    // custom setup variable, oparatros, string, numbers, comments color....
    "editor.tokenColorCustomizations": {

      // custom setup variable, oparatros
      "textMateRules": [
        {
          "scope": "keyword.operator",
          "settings": {
            "foreground": "#16B4C6"
          }
        },

        {
          "scope": "comment",
          "settings": {
            "foreground": "#2a687a",
            "fontStyle": "italic",
          }
        },

        {
          "scope": "variable.parameter",
          "settings": {
            "fontStyle": "italic",
          }
        },
      ] 
    },
  }
