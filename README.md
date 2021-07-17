# Dark Pines

<small>HTML & JavaScipt</small>
![Preview](imgs/preview.png)
<small>Font: Operator Mono w/ Ligatures</small>

> Darker take on the Base 16 Ocean theme by [Chris Kempson](https://github.com/chriskempson)

## Settings for minmal look:

`settings.json`

```json
    "window.menuBarVisibility": "compact",
    "editor.overviewRulerBorder": false,
    "editor.renderIndentGuides": false,
    "editor.matchBrackets": "never",
    "editor.folding": false,
    "editor.lightbulb.enabled": false,
    "breadcrumbs.icons": false,
    "breadcrumbs.symbolPath": "off",
```

## Additional Extensions for customizing VS Code:

Customize UI - _iocave_

GlassIt-VSC - _hikarin522_

Color Highlight - _Sergii Naumov_

<br />

Settings for those extensions

`settings.json`

```json
// Overrides VS Code's UI Font
"customizeUI.font.regular": "Consolas",

"customizeUI.stylesheet": {
  // Removes top left icon and all editor actions in the top right
  ".window-appicon, .tabs .editor-actions": "display: none",

  // Fixes spacing issue with monospaced fonts when in the quick open widget
  ".label-description": "white-space: unset !important",

  // Makes tabs fill available space
  ".tabs": "flex-direction: column; display: flex",
  ".tabs .sizing-fit": "flex-grow: 1; text-align: center;",
  ".tabs .monaco-icon-label-container": "flex: unset !important",
  ".tabs .monaco-icon-label": "justify-content: center"
},

"glassit.alpha": 240,

"color-highlight.markerType": "underline",
"color-highlight.matchWords": true,
"color-highlight.markRuler": false,
```

Any feedback is greatly appreciated! https://github.com/evan-leigh/dark-pines-theme
