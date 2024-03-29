# Ano Theme for [Visual Studio Code](http://code.visualstudio.com)

## Previev:

<a name='AnoThemeDark'></a>

### Ano Theme - Dark

#### Syntax

<img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/images/theme-dark-syntax.png' alt='theme-dark-syntax' />

#### Menu

<img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/images/theme-dark-menu.png' alt='theme-dark-menu' />

#### Terminal

<img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/images/theme-dark-terminal.png' alt='theme-dark-terminal' />

#### Overview

<img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/images/theme-dark-overview.png' alt='theme-dark-overview' />

#### Color Palette

<img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/images/ano-theme-bg.png' alt='palette' style='width: 100%' />

<a name='Installation'></a>

## Installation

1. Go to VS Marketplace.
2. Click on the 'Install' button.
3. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme).

<a name='RecommendedSettings'></a>

## Settings

These additional settings are optional and cater to personal preferences. Feel free to experiment and fine-tune them to create a coding environment that not only looks visually pleasing but also enhances your productivity and coding enjoyment.

Install [JetBrains Mono](https://www.jetbrains.com/lp/mono/#how-to-install) beforehand to set up the <code>editor.fontFamily</code>.

```js
// Controls the appearance of the editor
"editor.cursorWidth": 5,
"editor.minimap.enabled": false,
"editor.bracketPairColorization.enabled": true,
"editor.guides.bracketPairsHorizontal": false,
"editor.guides.bracketPairs": "active",
"editor.matchBrackets": "near",
"editor.multiCursorModifier": "ctrlCmd",

"editor.tabSize": 2,
"editor.insertSpaces": false,
"editor.detectIndentation": false,
"editor.wordWrap": "wordWrapColumn",
"editor.wordWrapColumn": 115,

// Controls the font family, requires `JetBrains Mono` font
"editor.fontFamily": "'JetBrains Mono', Consolas, 'Courier New', monospace",
"editor.fontSize": 20,
"editor.fontLigatures": true,
"editor.letterSpacing": 0.4,
```

<a name='OverrideThemeColors'></a>

## Override Theme Colors

In addition to the default color scheme provided by this VS Code theme, you have the flexibility to override specific colors and further customize the visual appearance of your coding environment. The "Override theme colors" feature allows you to personalize the theme by modifying specific color values. Explore code highlighting and structure in VS Code with `Inspect Editor Tokens and Scopes`. Gain deeper insights into your code editor's inner workings. Here are some examples of how you can utilize this features:

```js
// Modify colors such as syntax highlighting to suit your preferences.
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "support.type, meta.type.annotation, support.type.primitive, support.type.builtin",
      "settings": {
        "foreground": "#d5b496"
      }
    },
    // ...
  ]
},

// Tailor the visual aspects of the editor to make it more visually appealing and conducive to your coding workflow.
"workbench.colorCustomizations": {
  "editorCursor.foreground": "#1b8dff",
  // ...
},

```

<a name='Contributing'></a>

## Contributing

If you'd like to contribute to this theme, please read the [contributing guidelines](./CONTRIBUTING.md).

<a name='Supporting'></a>

## Supporting

<p align='center' >
	Like this free project? Consider supporting me to keep going.
</p>

<div align='center' style='display: flex; align-items: start; justify-content: center; gap: 10px; flex-wrap: wrap; margin-top: 20px'>
<a href='https://www.buymeacoffee.com/lifinhime' target='_blank'><img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/icons/buymeacoffee-orange.png' alt='Buy Me A Coffee' style='height: 40px !important; width: 140px !important; max-width: 150px !important'></a>&nbsp;&emsp;&nbsp;<a href='https://www.patreon.com/lifinhime' target='_blank'><img src='https://raw.githubusercontent.com/delafin/AnoTheme/main/icons/patreon.png' alt='Patreon' style='height: 40px !important;width: 160px !important; max-width: 170px !important;'></a>

</div>

<a name='License'></a>

## License

[MIT License](./LICENSE.txt) © Ano Theme
