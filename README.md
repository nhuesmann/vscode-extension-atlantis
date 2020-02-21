# Atlantis

[![version](https://img.shields.io/visual-studio-marketplace/v/nhuesmann.atlantis)](https://marketplace.visualstudio.com/items?itemName=nhuesmann.atlantis)
[![installs](https://img.shields.io/visual-studio-marketplace/i/nhuesmann.atlantis)](https://marketplace.visualstudio.com/items?itemName=nhuesmann.atlantis)
[![rating](https://img.shields.io/visual-studio-marketplace/r/nhuesmann.atlantis)](https://marketplace.visualstudio.com/items?itemName=nhuesmann.atlantis)

This theme happened because I did a clean install of VS Code and my favorite theme was no longer available (RIP Charcoal Oceanic Next with Babel Syntax Highlighting). Atlantis is based on that theme but is an evolution of it.

I have tested it in JavaScript, TypeScript, React, HTML, and CSS files. Markdown syntax highlighting is not configured, though I probably will do that eventually.

## Optimal Settings

I recommend using [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) as it makes it easier to understand nested code. If you use that extension and want the bracket colors to match the Atlantis theme colors, add the following to your VS Code `settings.json`:

```json
{
  ...
  "bracket-pair-colorizer-2.colors": [
    "#C792EA", // "Purple",
    "#F5D76B", // "Gold",
    "#7FB4FF"  // "Blue"
  ],
  ...
}
```

I also prefer bumping up the font weight to help the colors pop. I use `editor.fontWeight: "500"`.

## MAJOR CAVEAT

I made this for myself, I didn't design it for popular use. It suits my needs. I decided to go ahead and add a README in case someone else stumbles across it and decides to install. I don't plan on actively improving it unless I find an issue with it or want to slightly tweak the colors. I just thought I should make that clear :) that being said, if you do install it I hope you enjoy it!

## TODO:

- Add screenshots eventually (maybe) 🤷🏼‍♂️
