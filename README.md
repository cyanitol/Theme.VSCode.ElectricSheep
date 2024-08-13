# Electric Sheep - A Visual Studio Code Theme

## Description
Electric Sheep is a dark theme for Visual Studio Code.  It is designed to be
readable, higher contrast, draw your attention to the code, lightweight, and
look 'not bad'.

## Installation
* Explore it live at VSCode.dev:  
  https://vscode.dev/editor/theme/JMWeeks.electric-sheep
* Download it from the Visual Studio Marketplace:  
  https://marketplace.visualstudio.com/items?itemName=JMWeeks.electric-sheep
* Manual Installation (source):  
  Copy the source code into `<user home>/.vscode/extensions`folder and restart 
  Code.
* Manual Installation (VSIX): Download the VSIX file and install via the 
  "Install from VSIX..." option.

### Inspiration
Inspiration for this theme comes from the following sources:

* Textmate Color Theme by Wimer Hazenburg:  
  http://www.monokai.nl/blog/2006/07/15/textmate-color-theme/
* File Icon Theme by Emmanuel Beziat:  
  https://github.com/EmmanuelBeziat/vscode-great-icons
* Abyss Theme by Brandon Padgett:  
  https://github.com/gerane/VSCodeThemes/tree/master/gerane.Theme-Abyss

### Programming Friendly Fonts
The following programming friendly fonts look good with this theme:
* JetBrains Mono:  
  https://github.com/cyanitol/Miscellaneous.Contrib.Font.JetBrainsMono
* IBM Plex:  
  https://github.com/cyanitol/Miscellaneous.Contrib.Font.IBMPlex
* Geist:  
  https://github.com/cyanitol/Miscellaneous.Contrib.Font.Geist
* Hack:  
  https://github.com/cyanitol/Miscellaneous.Contrib.Font.Hack
* Mononoki:  
  https://github.com/madmalik/mononoki/tree/main
* Fira:  
  https://github.com/cyanitol/Miscellaneous.Contrib.Font.Fira
* Fira Code:  
  https://github.com/cyanitol/Miscellaneous.Contrib.Font.FiraCode

## Development Notes
* Key Files
    * `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
    * `themes/ElectricSheep-color-theme.json` - the color theme definition file.
    * `icons.json` - icon definition file.
* Run & Modify
    * Press `F5` to open a new window with the extension loaded.
    * Open `File > Preferences > Color Themes` and pick your color theme.
    * Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
    * Changes to the theme file are automatically applied to the Extension Development Host window.
* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.
    * To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.