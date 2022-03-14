# VS Code Extensions

## Themes

- [Community Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-community-material-theme)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

## Global

- [Advanced New File](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

## PHP Framework

- [Laravel Extension Pack](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-extension-pack)
- [Laravel Blade Spacer](https://marketplace.visualstudio.com/items?itemName=austenc.laravel-blade-spacer)
- [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
- [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)

## Javascript Framework

- [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- [React Extension Pack](https://marketplace.visualstudio.com/items?itemName=jawandarajbir.react-vscode-extension-pack)
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

## Fonts

- [Cascadia Code](https://github.com/microsoft/cascadia-code)
- [Fira Code](https://github.com/tonsky/FiraCode)
  ```terminal
  brew tap homebrew/cask-fonts
  brew install --cask font-fira-code
  ```

## Settings.json

```json
{
  "workbench.colorTheme": "Community Material Theme Darker High Contrast",
  "workbench.iconTheme": "material-icon-theme",
  "editor.formatOnSave": true,
  "editor.wordWrap": "on",
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "explorer.confirmDelete": false,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.enableSmartCommit": true,
  "explorer.confirmDragAndDrop": false,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "bracketPairColorizer.depreciation-notice": false,
  "bracket-pair-colorizer-2.depreciation-notice": false,
  "svelte.ask-to-enable-ts-plugin": false,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.activityBar.visible": false,
  "workbench.startupEditor": "none",
  "editor.lineHeight": 24,
  "files.autoSave": "onWindowChange",
  "editor.fontFamily": "Cascadia Code",
  "editor.fontLigatures": true,
  "editor.fontWeight": "normal",
  "breadcrumbs.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "workbench.tree.renderIndentGuides": "none",
  "editor.tabCompletion": "onlySnippets",
  "blade.format.enable": true,
  "[blade]": {
    "editor.defaultFormatter": "onecentlin.laravel-blade"
  },
  "zenMode.centerLayout": false,
  "editor.tabSize": 2
}
```
