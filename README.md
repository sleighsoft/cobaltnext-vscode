# CobaltNext Theme for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version/dline.CobaltNext.svg)](https://marketplace.visualstudio.com/items?itemName=dline.CobaltNext)

![Preview](https://raw.githubusercontent.com/davidleininger/cobaltnext-vscode/master/images/screenshot.png)

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Cobalt Next`.
3. Click **Install** to install it.
4. Click **Reload** to reload the your editor
5. File > Preferences > Color Theme > **CobaltNext** or change it in User Settings.
6. Optional: Use the recommended settings below for best experience

## Recommended Settings

```js
{
  "color-highlight.markerType": "underline", // requires Color Highlight Extension
  "color-highlight.markRuler": false, // requires Color Highlight Extension
  "editor.colorDecorators": false, // using Color Hightlight instead
  "editor.cursorBlinking": "solid",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 3,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 22,
  "editor.fontFamily": "Operator Mono, Menlo, monospace",
  "editor.fontSize": 15,
  "editor.fontWeight": "300",
  "editor.matchBrackets": false, // using Subtle Match Brackets instead
  "editor.tabSize": 2,
  "files.trimTrailingWhitespace": true,
  "subtleBrackets.styles": { // requires Subtle Match Bracket Extension
    "global": {
      "borderColor": "#fac863",
      "borderWidth": "2px"
    }
  },
  "terminal.integrated.fontFamily": "Inconsolata for Powerline",
  "terminal.integrated.fontSize": 14,
  "window.title": "${dirty} ${activeEditorMedium}${separator}${rootName}",
  "workbench.colorTheme": "Cobalt Next",
  "workbench.editor.tabSizing": "shrink",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",
}
```

### Suggested Extensions For Theme
* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
* [Subtle Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets)

### Suggested Terminal Settings

![Terminal Preview](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/terminal.png?raw=true)

[ZSH](http://ohmyz.sh/) is a great shell and it adds support for git. I would suggest using the [Cobalt2 Theme](https://github.com/wesbos/Cobalt2-iterm) for ZSH. Make sure to get [Inconsolata for Powerline](https://github.com/powerline/fonts/blob/master/Inconsolata/Inconsolata%20for%20Powerline.otf) so that you can get all of the special characters in prompt.

## VS Code Icon

Want to change up your VS Code Icon to match your theme? _Done._

![VS Code Icon Preview](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-cobaltnext.png?raw=true)

[Download the .icns file.](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-cobaltnext.icns) (Mac)

[Download the .ico file.](https://github.com/davidleininger/cobaltnext-vscode/blob/master/images/vscode-cobaltnext.ico) (Win)

**Enjoy!**
