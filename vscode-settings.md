# VS Code Settings

#### Fonts
* [Menlo](https://www.cufonfonts.com/font/menlo)
* [Monaco](https://www.cufonfonts.com/font/monaco)
* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)
  
#### Extensions
* Theme / Editor
  * [Ayu](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)
  * [Darcula Theme](https://marketplace.visualstudio.com/items?itemName=rokoroku.vscode-theme-darcula)
  * [Jetbrains Fleet Theme](https://marketplace.visualstudio.com/items?itemName=MichaelZhou.fleet-theme)
  * [Panda Theme](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda)
  * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * [JetBrains Icon Theme](https://marketplace.visualstudio.com/items?itemName=chadalen.vscode-jetbrains-icon-theme)
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  * [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
* Useful Tools
  * [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)
  * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
  * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
  * [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)
  * [Remote - Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
* Languages and Libraries
  * [Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django)
  * [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * [Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma)
  * [Python - Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  * [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

#### Settings
```json
{
  "editor.cursorBlinking": "blink",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorStyle": "underline",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontFamily": "Menlo, 'Anonymous Pro', Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.smoothScrolling": true,
  "editor.suggestSelection": "first",
  "editor.stickyScroll.enabled": false,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "extensions.ignoreRecommendations": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "git.openRepositoryInParentFolders": "never",
  "search.exclude": {
    "**/*.code-search": true,
    "**/bower_components": true,
    "**/node_modules": true
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.titleBarStyle": "custom",
  "workbench.colorTheme": "Jetbrains Fleet",
  "workbench.editor.editorActionsLocation": "titleBar",
  "workbench.iconTheme": "vscode-jetbrains-icon-theme-2023-dark",
  "workbench.list.smoothScrolling": true,
  "[dockerfile]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker"
  },
  "[dockercompose]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker"
  },
  "security.workspace.trust.untrustedFiles": "open"
}
```
#### Keybindings
```
```
