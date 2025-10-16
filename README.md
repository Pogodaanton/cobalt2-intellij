# Cobalt2 Theme (Reshaded) for IntelliJ

[![Build](https://github.com/Pogodaanton/cobalt2-intellij/workflows/Build/badge.svg)](https://github.com/Pogodaanton/cobalt2-intellij/actions/workflows/build.yml)
[![Version](https://img.shields.io/jetbrains/plugin/v/28023.svg)](https://plugins.jetbrains.com/plugin/28023)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/28023.svg)](https://plugins.jetbrains.com/plugin/28023)

<!-- Plugin description -->
An unofficial faithful re-implementation of [Cobalt2](https://github.com/wesbos/cobalt2-vscode) for JetBrains IDEs; forked from Dennis Koch's [version](https://github.com/pxlrbt/cobalt2-jetbrains)

## Key features:

*   IDE theming using the color palette from Wes Bos' original theme [Cobalt2](https://github.com/wesbos/cobalt2-vscode)
*   Accompanying color scheme with extended support for many languages out-of-the-box
*   Adapted token colors to better accommodate languages outside of HTML/CSS/JS

## Contribution and Support

This plugin is authored by personal needs, hence feature support from the theme author is only provided for select issues. **You are encouraged to adapt the color scheme** for missing programming languages or legibility issues yourself **and to share your changes with the repository**. Below are steps how to do that:

1.  Go to: `Settings -> Editor -> Color Scheme -> [Your desired language]`
2.  Adapt the color scheme to your liking; The [recommended color palette](https://github.com/Pogodaanton/cobalt2-intellij#color-palette-and-consistency) might help you
3.  Open the menu `Show Scheme Actions` by pressing the cog symbol next to the `Scheme` dropdown menu
4.  Choose `Export -> (.icls)` and save the file
5.  Rename the file, such that its extension changes from `.icls` to `.xml` (e.g. `Cobalt2.icls -> Cobalt2.xml`) (it's easiest to do the renaming in a JetBrains IDE)
6.  Send a [pull-request](https://github.com/Pogodaanton/cobalt2-intellij/pulls) to the git repository
<!-- Plugin description end -->

### Color Palette and Consistency

When designing new color schemes, this theme strives to stay close to the original material, that is [Wes Bos' VSCode theme](https://github.com/wesbos/cobalt2-vscode).

When choosing a color for a token, use the values listed in the table below.
Each color is assigned a token type.
You may deviate from these assignments if the color harms legibility in the context of the language.

> [!IMPORTANT] For Example:  
> Say the given programming language uses a lot of labels. By default, those would be assigned the color of light-blue.
> However, as it's a complimentary color, it will visually clash with the rest of the palette in the code.
> In this case, it is better to deviate from the rule and switch labels to a different color in the list.
> (Don't be afraid to use the default off-white color)

That said, please try not to introduce new colors all too often, as the goal to an extent is simplicity.
Instead, try playing around with italics and bold settings per token.

All available token colors can be found at `Settings -> Editor -> Color Scheme -> General/Language Defaults`. Here are some of the most important ones:

|                               |           |                          |
|-------------------------------|-----------|--------------------------|
| Off-White (Default)           | `#E1EFFF` | (If in doubt, pick this) |
| Bronze (Keywords)             | `#FF9D00` |                          |
| Gold (Function)               | `#FFC600` | (Primary contrast color) |
| Magenta (Interface)           | `#FF68B8` |                          |
| Purple (This/Self)            | `#FB94EE` |                          |
| Pink (Constant/Literal)       | `#FF628C` |                          |
| Light-Blue (Labels)           | `#9EFFFF` |                          |
| Light-Green (String)          | `#A5FF90` |                          |
| Mint-Green (Misc. Identifier) | `#7cfcba` |                          |
| Dark-Green (Misc. Identifier) | `#34c80f` |                          |

## Installation

- Using the IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "Cobalt2"</kbd> >
  <kbd>Install</kbd>
  
- Using JetBrains Marketplace:

  Go to [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/28023) and install it by clicking the <kbd>Install to ...</kbd> button in case your IDE is running.

  You can also download the [latest release](https://plugins.jetbrains.com/plugin/28023/versions) from JetBrains Marketplace and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

- Manually:

  Download the [latest release](https://github.com/Pogodaanton/cobalt2-intellij/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

## Credits

- Colors inspired from Wes Bos' Cobalt2 theme: https://github.com/wesbos/cobalt2-vscode
- Forked from Dennis Koch's IntelliJ theme: https://github.com/pxlrbt/cobalt2-jetbrains
- Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
[docs:plugin-description]: https://plugins.jetbrains.com/docs/intellij/plugin-user-experience.html#plugin-description-and-presentation
