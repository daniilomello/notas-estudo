# VScode Config

## Default

```json
{
  // Geral do Editor
  "editor.fontFamily": "Operator Mono, MonoLisa, Fira Code Retina, Input Mono, Fira Code",
  "editor.fontWeight": "300",
  "editor.fontSize": 18,
  "editor.lineHeight": 25,
  "editor.tabSize": 2,
  "editor.wordWrap": "wordWrapColumn",
  "editor.linkedEditing": true,
  "editor.colorDecorators": false,
  "editor.tabCompletion": "on",
  "editor.padding.top": 35,
  "editor.inlayHints.padding": true,
  "editor.fontLigatures": true,
  "editor.autoClosingBrackets": "always",
  "editor.autoClosingQuotes": "always",
  "editor.minimap.renderCharacters": true,
  "editor.renderWhitespace": "selection",
  "editor.renderLineHighlight": "gutter",
  "editor.parameterHints.enabled": false,
  "editor.suggestSelection": "first",
  "editor.inlineSuggest.enabled": true,
  "editor.formatOnSave": true,
  "editor.formatOnSaveMode": "modificationsIfAvailable",
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "editor.foldingImportsByDefault": true,
  "breadcrumbs.enabled": true,
  "explorer.confirmDragAndDrop": false,
  "explorer.sortOrder": "default",
  "window.title": "${activeEditorMedium}${separator}${rootName}",
  "window.newWindowDimensions": "inherit",
  "security.workspace.trust.startupPrompt": "never",
  "explorer.confirmDelete": false,
  "tabnine.experimentalAutoImports": true,
  "git.confirmSync": false,
  "path-intellisense.extensionOnImport": true,
  "workbench.colorCustomizations": {},
  "workbench.editor.highlightModifiedTabs": true,
  "workbench.editor.pinnedTabSizing": "compact",
  "workbench.editor.tabSizing": "shrink",
  "workbench.editor.untitled.hint": "hidden",
  "security.workspace.trust.untrustedFiles": "open",
  "git.openRepositoryInParentFolders": "never",
  "cSpell.enabled": false,
  "workbench.editor.enablePreview": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.fontFamily": "FiraCode Nerd Font",
  "terminal.integrated.fontSize": 15,
  "l13Projects.confirmDeleteProject": false,
  "diffEditor.renderSideBySide": false,
  "workbench.colorTheme": "oh-lucy",
  "workbench.productIconTheme": "fluent-icons",
  "diffEditor.ignoreTrimWhitespace": false,
  "explorer.compactFolders": false,
  "workbench.editorAssociations": {
    "*.ini": "default"
  },
  // Git
  "git.enableSmartCommit": true,
  "git.autofetch": true,
  // Ignorar
  "files.exclude": {
    "**/node_modules": true,
    "**/.next": false
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/.next": true
  },
  // HTML
  "html.autoClosingTags": true,
  "html.format.wrapAttributes": "auto",
  "html.format.wrapLineLength": 0,
  "html.hover.documentation": false,
  "html.hover.references": false,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features",
    "editor.formatOnSave": true
  },
  // Linter
  "css.lint.unknownAtRules": "ignore",
  "settingsSync.ignoredExtensions": ["christian-kohler.npm-intellisense"],
  // Prettier
  // "prettier.singleQuote": true,
  // "prettier.jsxSingleQuote": true,
  // "prettier.trailingComma": "all",
  // "typescript.preferences.quoteStyle": "single",
  // "typescript.format.semicolons": "insert",
  // "vs-code-prettier-eslint.prettierLast": true,
  // "prettier.bracketSpacing": false,
  // "prettier.singleAttributePerLine": true,
  // "javascript.preferences.quoteStyle": "single",
  // "html.completion.attributeDefaultValue": "singlequotes",
  "[typescriptreact]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    // "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  
  "[javascriptreact]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    // "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[javascript]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    // "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
    // "source.organizeImports": true
  },
  "[typescript]": {
    "editor.formatOnSave": true
  },
  // Emmet
  "emmet.includeLanguages": {
    "ejs": "html",
    "javascript": "javascriptreact",
    "*.js": "javascriptreact",
    "*.jsx": "javascriptreact",
    "*.ts": "javascriptreact",
    "*.tsx": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx",
    "ejs": "html",
    "nunjucks": "html",
    "njk": "html"
  },
  "files.associations": {
    "*.js": "javascript",
    "*.jsx": "javascriptreact",
    "*.ts": "typescript",
    "*.tsx": "typescriptreact",
    "*.html": "html"
  },
  "terminal.integrated.env.windows": {},
  "terminal.integrated.enableMultiLinePasteWarning": false,
  "editor.formatOnPaste": false,
  "editor.wordWrapColumn": 85,
  "editor.rulers": [85],
  "files.autoSave": "afterDelay",
  "RainbowBrackets.depreciation-notice": false,
  "window.zoomLevel": 1,
}

```


## Minimal

```json
{
  "workbench.colorTheme": "oh-lucy",
  "editor.fontFamily": "Operator Mono",
  "editor.fontSize": 18,
  "terminal.integrated.fontSize": 15,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.fontFamily": "FiraCode Nerd Font",
  "editor.fontWeight": "300",
  "eslint.format.enable": true,
  "editor.mouseWheelZoom": true,
  "tabnine.experimentalAutoImports": true,
  "RainbowBrackets.depreciation-notice": false,
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 85,
  "editor.rulers": [85],
  "editor.tabCompletion": "on",
  "editor.fontLigatures": true,
  "editor.suggestSelection": "first",
  "editor.formatOnSave": true, // optional
  "files.autoSave": "onFocusChange", // optional but recommended
  "vs-code-prettier-eslint.prettierLast": false, // set as "true" to run 'prettier' last not first
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },

   "files.exclude": {
    "**/node_modules": true,
    "**/.next": false
  },
  "search.exclude": {
    "**/node_modules": true,
    "**/.next": true
  },
}
```

### Cores
```js
"workbench.colorCustomizations": {
    "titleBar.activeBackground": "#6B7A88",
    "titleBar.inactiveBackground": "#6B7A88",
    "titleBar.activeForeground": "#000",
    "titleBar.inactiveForeground": "#000"
  },
```