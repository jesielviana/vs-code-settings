# Arquivo de configuração do VS Code 

Utilize essas configurações para deixar o VS Code bem limpo. O arquivo de configuração abaixo usa as seguintes dependências:

- [Apc Customize UI++](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension)
- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Fluent Icons](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.fluent-icons)
- [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)

Veja o print abaixo do settings.json de como fica o visual do VS Code com essas configurações.

settings.json

```json
{
  "editor.fontSize": 15,
  "editor.lineHeight": 1.8,
  "files.autoSave": "afterDelay",
  "javascript.suggest.autoImports": true,
  "editor.glyphMargin": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "extensions.ignoreRecommendations": true,
  "typescript.tsserver.log": "off",
  "files.associations": {
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "css"
  },
  "symbols.files.associations": {
    "*.module.ts": "nest",
    "*.guard.ts": "typescript",
    "*.spec.ts": "ts-test",
    "*.e2e-spec.ts": "ts-test",
    "vitest.config.e2e.ts": "vite",
    ".env.example": "gear"
  },
  "tailwindCSS.experimental.classRegex": [
    [
      "tv\\(([^)]*)\\)",
      "[\"'`]([^\"'`]*).*?[\"'`]"
    ]
  ],
  "editor.parameterHints.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.suggestSelection": "first",
  "explorer.confirmDelete": false,
  "terminal.integrated.showExitAlert": false,
  "editor.formatOnSave": true,
  "typescript.suggest.autoImports": true,
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  "workbench.editor.labelFormat": "short",
  "editor.fontLigatures": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "editor.acceptSuggestionOnCommitCharacter": false,
  "explorer.compactFolders": false,
  "git.enableSmartCommit": true,
  "editor.accessibilitySupport": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "'Monaspace Neon', 'monospace', monospace",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.organizeImports": "explicit",
    "source.fixAll": "explicit"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql"
  ],
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": false,
  "workbench.productIconTheme": "fluent-icons",
  "editor.fontFamily": "'Monaspace Neon', 'monospace', monospace",
  "editor.tabSize": 2,
  "security.workspace.trust.untrustedFiles": "newWindow",
  "files.exclude": {
    "**\/CVS": true,
    "**\/.DS_Store": true,
    "**\/.hg": true,
    "**\/.svn": true,
    "**\/.git": true,
    ".vscode": true
  },
  "workbench.iconTheme": "symbols",
  "update.mode": "start",
  "terminal.integrated.gpuAcceleration": "off",
  "terminal.integrated.defaultProfile.osx": "fish",
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "git.openRepositoryInParentFolders": "always",
  "symbols.hidesExplorerArrows": false,
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "workbench.editor.empty.hint": "hidden",
  "update.showReleaseNotes": false,
  "security.promptForLocalFileProtocolHandling": false,
  "workbench.activityBar.location": "hidden",
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.patterns": {
    "package.json": "yarn.lock, package-lock, .eslint*, lint-*, .prettier*, prettier*,tsconfig*, vite*, pnpm-lock*, bun.lockb, nest*, next*",
    "tailwind.config.js": "tailwind.config*, postcss.config*",
    ".env.local": ".env*",
    ".env": ".env*"
  },
  "explorer.fileNesting.enabled": true,
  "workbench.colorTheme": "Dracula",
  "workbench.statusBar.visible": false,
  "workbench.layoutControl.enabled": false,
  "window.commandCenter": false,
  "window.menuBarVisibility": "toggle",
  "window.title": "${folderName}",
  "workbench.editor.enablePreview": false,
  "window.restoreFullscreen": true,
  "window.titleBarStyle": "native",
  "apc.electron": {
    "titleBarStyle": "hidden",
    "frame": false
  },
  "apc.header": {
    "height": 36,
    "fontSize": 14,
  },
  "apc.listRow": {
    "height": 24
  },
  "apc.font.family": "Inter",
}
```
### Print
![Print do VS Code com as configurações acima](https://raw.githubusercontent.com/jesielviana/vs-code-settings/5a87251514812186c60e565f877aa00f98069fed/vscode.png)

