# [VSCodium](https://vscodium.com) Setup

> This guide is intended to be used as a reference for setting up VSCodium.

<details>

<summary>What is VSCodium?</summary>

[VSCodium](https://github.com/vscodium/vscodium) is a free and open-source code editor based on [Visual Studio Code](https://github.com/microsoft/vscode), providing the same features and functionality without the proprietary [Microsoft](https://www.microsoft.com) branding and telemetry.

</details>
<details>

<summary>Can I Migrate from Visual Studio Code to VSCodium?</summary>

If you want to migrate from [Visual Studio Code](https://github.com/microsoft/vscode) to [VSCodium](https://github.com/vscodium/vscodium) follow this [Official Guide](https://github.com/VSCodium/vscodium/blob/a02839b466d8d01b8a61ea9611f0b74039538eae/DOCS.md#migrating-from-visual-studio-code-to-vscodium) from [VSCodium](https://github.com/vscodium/vscodium).

</details>

## Installing VSCodium

**Windows**
**Install**

```powershell
winget install -e --id VSCodium.VSCodium
```

**Linux**
**Install**

```bash
snap install codium --classic
```

## Configuring VSCodium

**Favourite**
**Fonts**

1. [JetBrains Mono](https://github.com/ryanoasis/nerd-fonts/releases?q=JetBrainsMono&expanded=true) of [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).
2. [Operator Mono Ligature](https://github.com/iammrmehedi/Operator-Mono-Ligature)

**Favourite**
**Themes**

1. [2077 theme](https://github.com/endormi/vscode-2077-theme) by [Endormi](https://github.com/endormi)
2. [Learn with Sumit Theme](https://marketplace.visualstudio.com/items?itemName=SumitSaha.learn-with-sumit-theme) by [Sumit Saha](https://github.com/learnwithsumit)

**Favourite**
**Extensions**

1. [Auto Close Tag](https://github.com/formulahendry/vscode-auto-close-tag.git) by [Formulahendry](https://github.com/formulahendry)
1. [Auto Rename Tag](https://github.com/formulahendry/vscode-auto-rename-tag.git)
by [Formulahendry](https://github.com/formulahendry)
1. [Better Comments](https://github.com/aaron-bond/better-comments.git) by [Aaron Bond](https://github.com/aaron-bond)
1. [Code Spell Checker](https://github.com/streetsidesoftware/vscode-spell-checker.git) by [Streetsidesoftware](https://github.com/streetsidesoftware)
1. [Codeium](https://open-vsx.org/extension/Codeium/codeium) by [Exafunction, Inc](https://www.exafunction.com/).
1. [Colorize](https://github.com/kamikillerto/vscode-colorize.git) by [Kamikillerto](https://github.com/kamikillerto).
1. [Fluent Icons](https://github.com/misolori/vscode-fluent-icons.git) by [Misolori](https://github.com/misolori).
1. [Highlight Maching Tag](https://github.com/vincaslt/vscode-highlight-matching-tag.git) by [VincasLT](https://github.com/vincaslt).
1. [HTML CSS Support](https://github.com/ecmel/vscode-html-css.git) by [Ecmel](https://github.com/ecmel).
1. [HTMLHint](https://github.com/htmlhint/HTMLHint.git) by [Htmlhint](https://github.com/htmlhint).
1. [indent-rainbow](https://github.com/oderwat/vscode-indent-rainbow.git) by [oderwat](https://github.com/oderwat).
1. [Material Icon Theme](https://github.com/PKief/vscode-material-icon-theme.git)
by [PKief](https://github.com/PKief).
1. [Path Intellisense](https://github.com/ChristianKohler/PathIntellisense.git) by [ChristianKohler](https://github.com/ChristianKohler).
1. [Polacode-2022](https://github.com/jeff-hykin/polacode.git) by [Jeff Hykin](https://github.com/jeff-hykin).
1. [Prettier](https://github.com/prettier/prettier-vscode.git) by [Prettier](https://github.com/prettier).
1. [Preview on Web Server](https://github.com/YuichiNukiyama/vscode-preview-server.git) by [YuichiNukiyama](https://github.com/YuichiNukiyama).
1. [Reload](https://github.com/natqe/reload) by [natqe](https://github.com/natqe).
1. [Markdown Preview Github Styling](https://github.com/mjbvz/vscode-github-markdown-preview-style.git) by [Matt Beiner](https://github.com/mjbvz)
1. [markdownlint](https://github.com/DavidAnson/vscode-markdownlint.git) by [DavidAnson](https://github.com/DavidAnson).

## Settings
>
> Latest version of this `settings.json` wil be found [here](https://gist.github.com/iammrmehedi/89ca447e35375c98e83889af3b85e205)

```json
{
  //* Workbench
  "window.menuBarVisibility": "toggle",
  "workbench.sideBar.location": "left",
  "window.autoDetectColorScheme": true,
  "workbench.list.smoothScrolling": true,
  "workbench.editor.labelFormat": "short",
  "workbench.editor.enablePreview": false,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.iconTheme": "material-icon-theme",
  "security.workspace.trust.untrustedFiles": "open",
  "workbench.colorTheme": "Learn with Sumit - Shades of Grey",

  //* Files, Explorer & breadcrumbs
  "breadcrumbs.enabled": false,
  "explorer.confirmDelete": true,
  "explorer.compactFolders": false,
  "files.autoSave": "afterDelay",
  "files.defaultLanguage": "{activeEditorLanguage}",

  //* Editor
  "editor.tabSize": 2,
  "editor.fontSize": 17,
  "editor.wordWrap": "on",
  "editor.cursorStyle": "line",
  "editor.glyphMargin": false,
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "editor.fontLigatures": true,
  "editor.mouseWheelZoom": true,
  "editor.formatOnPaste": false,
  "editor.smoothScrolling": true,
  "editor.minimap.enabled": false,
  "editor.renderWhitespace": "all",
  "editor.detectIndentation": true,
  "editor.cursorBlinking": "expand",
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "editor.guides.bracketPairs": true,
  "editor.wordBasedSuggestions": false,
  "editor.suggest.localityBonus": true,
  "editor.renderLineHighlight": "gutter",
  "editor.scrollbar.horizontal": "hidden",
  "editor.mouseWheelScrollSensitivity": 2,
  "editor.renderControlCharacters": false,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontFamily": "'Operator Mono Lig Book', 'FiraCode NFM', 'Ubuntu Mono', Consolas, Menlo",

  //* Terminal
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.cursorWidth": 3,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.copyOnSelection": false,
  "terminal.integrated.fontFamily": "'Operator Mono Lig Book', 'FiraCode NFM', 'Ubuntu Mono', Consolas, Menlo",
  // "terminal.integrated.drawBoldTextInBrightColors": false,
  // "terminal.integrated.enableFileLinks": false,

  //* Material Icon Theme Extension
  "material-icon-theme.folders.theme": "classic",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.folders.color": "#6273a6",

  //*CSpell Checker Extension
  "cSpell.enabled": true,
  "cSpell.language": "en",
  "cSpell.enableFiletypes": ["shellscript"],
  "cSpell.customDictionaries": {
    "project-words": {
      "name": "mh-codewords",
      "path": "${workspaceRoot}/mh-codewords.txt",
      "description": "Personal Coding Words",
      "addWords": true
    },
    "custom": true, // Enable the `custom` dictionary
    "internal-terms": false // Disable the `internal-terms` dictionary
  },

  //* Colorize
  "colorize.enable_search_variables": false,
  "colorize.hide_current_line_decorations": false,
  "colorize.colorized_colors": [
    // "BROWSERS_COLORS", // this is really annoying
    "HEXA",
    "RGB",
    "HSL"
  ],
  "colorize.languages": [
    "css",
    "sass",
    "scss",
    "less",
    "postcss",
    "sss",
    "stylus",
    "xml",
    "svg",
    "json",
    "html",
    "htm"
  ],
  "codeium.enableConfig": {
    "*": true,
    "plaintext": true,
    "Log": true,
    "xml": true
  },
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
  "indentRainbow.colorOnWhiteSpaceOnly": true,
  "redhat.telemetry.enabled": false
}
```
