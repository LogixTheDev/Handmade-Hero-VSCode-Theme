# Handmade Hero Visual Studio Code Theme

## v2.0 (W.I.P)

A theme for Visual Studio Code, based around the Handmade Hero series by Casey Muratori.
This is a simple settings.json file to be created as `.vscode/settings.json` in your projects.

This theme was built on top of the [Spacebox (Pulsar)](https://marketplace.visualstudio.com/items?itemName=SpaceBox.spacebox-theme) theme. I don't know if it's relevant, but I also have [Spacebox UI Enhancer](https://marketplace.visualstudio.com/items?itemName=SpaceBox.spacebox-ui) installed.

### Preview
![win32_handmade cpp - handmade-hero - Visual Studio Code 20_10_2024 20_17_26](https://github.com/user-attachments/assets/76483a43-eeea-4d62-86d0-769181699ff5)

<em>Note: I can't guarantee the colour accuracy of this screenshot, as Windows HDR is very very janky when it comes to screenshots, however I used Game Bar to capture it, which [apparently](https://www.reddit.com/r/OLED_Gaming/comments/yrw3s2/comment/ivwlf3v/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) works best, and I can confirm that on my monitor the screenshot displays exactly the same colours as in VSC.</em>

### Fonts
By default, I have the font set to [Fira Code](https://github.com/tonsky/FiraCode). However, in his tutorials, Casey uses [Liberation Mono](https://www.fontsquirrel.com/fonts/liberation-mono). Feel free to choose, or use your own. Either way, you will need to install your chosen font on your system.

<em>Note: (Windows users who want to use Fira Code) This font does have additional installation requirements, which seem to be true for Windows 11. [Read more](https://github.com/tonsky/FiraCode/wiki/Installing#windows).</em>

### Colours

<em>Note: I've made the `static` keyword bright red for a reason. This is to ensure you don't accidentally use it in shipping code. As per the tutorials, Casey points out that this keyword has multiple uses, and behaves differently in different contexts, so
he redefines it to have separate meanings.</em>

### Adaptation
Feel absolutely free to yoink this settings file and adapt it as you see fit -- it's just a starting point.

Currently, it only supports C++, so if you open files from other languages, expect default theme colours.

If you'd like to:
- Modify the theme to look nicer? Go for it! But please (optionally) share your changes with me, and let me know if I have your permission to update this repo with your changes if I like them.
- Adapt the theme to support other languages? That would be very beneficial.
- Make a theme extension from this? Please add support for other languages first, but then I have no objections.

### Extensions
This settings file contains definitions for the following extensions. They are optional, but recommended.
- [Todo-Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) by Gruntfuggly
- [Bracket Lens](https://marketplace.visualstudio.com/items?itemName=wraith13.bracket-lens) by wraith13
- [Custom Line Highlight](https://marketplace.visualstudio.com/items?itemName=Logix.custom-line-highlight) by... well, by me!
- [Indented Block Highlighting](https://marketplace.visualstudio.com/items?itemName=byi8220.indented-block-highlighting) by byi8220
