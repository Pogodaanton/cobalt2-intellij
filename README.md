# Cobalt2 for IntelliJ
An unofficial faithful re-implementation of [Cobalt2](https://github.com/wesbos/cobalt2-vscode) for JetBrains IDEs; forked from Dennis Koch's [version](github.com/pxlrbt/cobalt2-jetbrains)

## Key features:

*   Re-themed IDE using the color palette from Wes Bos' original theme [Cobalt2](https://github.com/wesbos/cobalt2-vscode)
*   Accompanying color scheme with extended support for many languages out-of-the-box
*   Adapted token colors to better accommodate languages outside of HTML/CSS/JS

## Contribution and Support

This plugin is authored by personal needs, hence **no support** is provided outside of the most UI-breaking issues. You are **encouraged to adapt the color scheme** for missing programming languages or legibility issues **and share them to the repository**. Below are steps to achieve this:

1.  Go to: `Settings -> Editor -> Color Scheme -> [Your desired language]`
2.  Adapt the color scheme to your liking
3.  Open the menu `Show Scheme Actions` by pressing the cog symbol next to the `Scheme` dropdown menu
4.  Choose `Export -> (.icls)` and save the file
5.  Rename the file, such that its extension changes from `.icls` to `.xml` (e.g. `Cobalt2.icls -> Cobalt2.xml`)

*   \[Windows\] You might have to disable "Hide extensions for known file types" in the Explorer for this. Consider doing the renaming in a JetBrains IDE instead

7.  Send a [pull-request](https://github.com/Pogodaanton/cobalt2-intellij/pulls) to the cobalt2-intellij git repository

### Color Palette and Consistency

When designing new color schemes, this theme strives to stay close to the original material, that is [Wes Bos' VSCode theme](https://github.com/wesbos/cobalt2-vscode). You may deviate from the token color rules if they harm legibility (e.g. using white foreground instead of light-blue because latter would visually clash with other colors 80% of the time), however, stay to the basic token colors and keep it simple (read: **don't unnecessarily introduce new colors**). You may play around with italics and bold settings per token.

All available token colors can be found at `Settings -> Editor -> Color Scheme -> General/Language Defaults`. Here are some of the most imporant ones:

|                               |           |                          |
|-------------------------------|-----------|--------------------------|
| Off-White (Default)           | `#E1EFFF` | (If in doubt, pick this) |
| Bronze (Keywords)             | `#FF9D00` |
| Gold (Function)               | `#FFC600` | (Primary contrast color) |
| Magenta (Interface)           | `#FF68B8` |
| Pink (Constant/Literal)       | `#FF628C` |
| Light-Blue (Labels)           | `#9EFFFF` |
| Light-Green (String)          | `#A5FF90` |
| Mint-Green (Misc. Identifier) | `#7cfcba` |
| Dark-Green (Misc. Identifier) | `#34c80f` |