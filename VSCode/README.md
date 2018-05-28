My VSCode config
----------------

[Read More: VS Code 初体验](https://sanbaofengs.com/2018/02/09/vsc-experience/)

```js
{
    "workbench.colorTheme": "Material Theme",
    "workbench.statusBar.visible": true,
    "editor.minimap.enabled": false,
    "editor.fontFamily": "Operator Mono",
    // Enables font ligatures
    "editor.fontLigatures": true,
    // Controls whether the editor should render whitespace characters
    "editor.renderWhitespace": "boundary",
    "editor.fontSize": 12,
    "workbench.fontAliasing": "antialiased",
    "workbench.iconTheme": "eq-material-theme-icons",
    "sublimeTextKeymap.promptV3Features": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.formatOnPaste": true,
    "workbench.colorCustomizations": {
        "editor.selectionBackground": "#406068"
    },
    "workbench.activityBar.visible": true,
    // The number of spaces a tab is equal to. This setting is overriden
    // based on the file contents when `editor.detectIndentation` is true.
    "editor.tabSize": 4,
    // Insert spaces when pressing Tab. This setting is overriden
    // based on the file contents when `editor.detectIndentation` is true.
    "editor.insertSpaces": true,
    // When opening a file, `editor.tabSize` and `editor.insertSpaces`
    // will be detected based on the file contents. Set to false to keep
    // the values you've explicitly set, above.
    "editor.detectIndentation": false,
    "window.zoomLevel": 0,
    "explorer.confirmDragAndDrop": false,
    "files.trimFinalNewlines": true,
    "explorer.confirmDelete": false,
    "files.insertFinalNewline": true,
    "files.autoSave": "onFocusChange",
    "materialTheme.cache.workbench.settings": {
        "themeColours": "Default High Contrast"
    },
    "workbench.startupEditor": "newUntitledFile",
    "emmet.showAbbreviationSuggestions": true,
    "emmet.showExpandedAbbreviation": "always",
    "emmet.triggerExpansionOnTab": true,
    "emmet.syntaxProfiles": {
        "vue-html": "html",
        "vue": "html"
    },
    "emmet.includeLanguages": {
        "vue-html": "html",
        "vue": "html"
    },
    "terminal.integrated.rightClickBehavior": "selectWord"
}
```
