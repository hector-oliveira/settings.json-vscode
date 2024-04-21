## Configurações Para O Visual do VsCode

Extensão Necessária:

```
apc
```

## Seettings.json

```bash
{
  "symbols.folders.associations": {
    "functions": "folder-blue",
    "hooks": "folder-target",
    "interfaces": "folder-blue-outline",
    "interface": "folder-blue-outline",
    "themes": "folder-blue-code",
    "data": "folder-database",
    "services": "folder-yellow",
    "typescript": "folder-blue-code",
    "ts": "folder-blue-code",
    "javascript": "folder-yellow-code",
    "js": "folder-yellow-code",
    "tests": "folder-red-code",
    "build": "folder-purple-outline",
    "builder": "folder-purple-outline",
    "classes": "folder-red",
    "class": "folder-red",
    ".pnpm": "folder-yellow",
    "@types": "folder-blue",
    "nodemon": "folder-green"
  },
  "symbols.files.associations": {
    "*.test.tsx": "react-test",
    "*.test.jsx": "react-test",
    "*.test.ts": "ts-test"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "explorer.fileNesting.patterns": {
    "package.json": ".eslint*, .prettier*, tsconfig*, vite*, .babel*, jest*, package-lock*, yarn*, pnpm-lock*, bun.lockb",
    "tailwind.config*": "tailwind.config*, postcss.config*"
  },
  "apc.listRow": {
    "height": 26
  },
  "apc.electron": {
    "titleBarStyle": "hidden"
  },
  "apc.header": {
    "height": 36
  },
  "apc.font.family": "Inter",
  "apc.stylesheet": {
    ".title-label > h2": "display: none",
    ".editor-actions": "display: none"
  },
  "window.titleBarStyle": "native",

  /* GENERAL CONFIGURATION */
  "editor.tabSize": 2,
  "workbench.iconTheme": "symbols",
  "symbols.hidesExplorerArrows": false,
  "workbench.colorTheme": "Min Dark",
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.rulers": [80, 120],
  "workbench.startupEditor": "newUntitledFile",
  "editor.cursorStyle": "block",
  "editor.cursorBlinking": "smooth",
  "editor.renderLineHighlight": "gutter",
  "editor.fontLigatures": true,
  "workbench.editor.labelFormat": "short",
  "explorer.compactFolders": false,
  "workbench.editor.enablePreview": false,
  "breadcrumbs.enabled": false,
  "workbench.activityBar.location": "hidden",
  "editor.minimap.enabled": false,
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "workbench.statusBar.visible": false,
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "explorer.fileNesting.enabled": true,
  "codeium.enableCodeLens": false,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrains Mono",
  "terminal.integrated.fontWeight": "bold",
  "terminal.integrated.defaultProfile.windows": "Windows PowerShell",
  "editor.wordWrap": "bounded",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.bracketPairColorization.enabled": true,
  "hediet.vscode-drawio.resizeImages": null
}

```
