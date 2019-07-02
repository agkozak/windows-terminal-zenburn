# Zenburn Color Schemes for [Windows Terminal](https://github.com/microsoft/terminal)

[![MIT License](img/mit_license.svg)](https://opensource.org/licenses/MIT)
[![Github Stars](https://img.shields.io/github/stars/agkozak/windows-terminal-zenburn.svg)](https://github.com/agkozak/windows-terminal-zenburn/stargazers)

## Zenburn

![Zenburn (Low-Contrast)](img/zenburn.png)

## High-Constrast Zenburn

![High-Contrast Zenburn](img/high_contrast_zenburn.png)

## Installation

In Windows Terminal, open Settings. That should allow you to edit your `profiles.json`. At the bottom of that file, a number of color schemes are defined. You will want to add Zenburn and High Contrast Zenburn to them.

The last color scheme should end with a close curly quote (`}`). Add a comma after that, and then enter the Zenburn color scheme definitions so that you have something like the following:

```json
},
{
    "background" : "#3A3A3A",
    "black" : "#1E2320",
    "blue" : "#506070",
    "brightBlack" : "#709080",
    "brightBlue" : "#94BFF3",
    "brightCyan" : "#93E0E3",
    "brightGreen" : "#C3BF9F",
    "brightPurple" : "#EC93D3",
    "brightRed" : "#DCA3A3",
    "brightWhite" : "#FFFFFF",
    "brightYellow" : "#F0DFAF",
    "cyan" : "#8CD0D3",
    "foreground" : "#DCDCCC",
    "green" : "#60B48A",
    "name" : "Zenburn",
    "purple" : "#DC8CC3",
    "red" : "#D78787",
    "white" : "#DCDCCC",
    "yellow" : "#DFAF8F"
},
{
    "background" : "#1C1C1C",
    "black" : "#1E2320",
    "blue" : "#506070",
    "brightBlack" : "#709080",
    "brightBlue" : "#94BFF3",
    "brightCyan" : "#93E0E3",
    "brightGreen" : "#C3BF9F",
    "brightPurple" : "#EC93D3",
    "brightRed" : "#DCA3A3",
    "brightWhite" : "#FFFFFF",
    "brightYellow" : "#F0DFAF",
    "cyan" : "#8CD0D3",
    "foreground" : "#DCDCCC",
    "green" : "#60B48A",
    "name" : "High-Contrast Zenburn",
    "purple" : "#DC8CC3",
    "red" : "#D78787",
    "white" : "#DCDCCC",
    "yellow" : "#DFAF8F"
}
```

Now all you need to do is to pick a Windows Terminal profile to apply a Zenburn color scheme to. In `profiles.json`, find the section that starts with `"profiles" :`. Scroll down, looking at the `"name"` of each profile until you find the one you want. Then go up a little bit and find its `"colorScheme"`. Change its value to `"Zenburn"` for standard, low-contrast Zenburn, or `"High-Contrast Zenburn"` for High-Contrast Zenburn. Save `profiles.json`; the changes should apply immediately.
