# Cobalt2 Theme (Reshaded) for IntelliJ

![Build](https://github.com/Pogodaanton/cobalt2-intellij/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID)

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
6. Send a [pull-request](https://github.com/Pogodaanton/cobalt2-intellij/pulls) to the git repository
<!-- Plugin description end -->

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

## Installation

- Using the IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "Cobalt2"</kbd> >
  <kbd>Install</kbd>
  
- Using JetBrains Marketplace:

  Go to [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) and install it by clicking the <kbd>Install to ...</kbd> button in case your IDE is running.

  You can also download the [latest release](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID/versions) from JetBrains Marketplace and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

- Manually:

  Download the [latest release](https://github.com/Pogodaanton/cobalt2-intellij/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

## Credits

- Colors inspired from Wes Bos' Cobalt2 theme: https://github.com/wesbos/cobalt2-vscode
- Forked from Dennis Koch's IntelliJ theme: https://github.com/pxlrbt/cobalt2-jetbrains

---
Plugin based on the [IntelliJ Platform Plugin Template][template].

## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [ ] Get familiar with the [template documentation][template].
- [x] Adjust the [pluginGroup](./gradle.properties) and [pluginName](./gradle.properties), as well as the [id](./src/main/resources/META-INF/plugin.xml) and [sources package](./src/main/kotlin).
- [x] Adjust the plugin description in `README` (see [Tips][docs:plugin-description])
- [ ] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html?from=IJPluginTemplate).
- [ ] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [ ] Set the `MARKETPLACE_ID` in the above README badges. You can obtain it once the plugin is published to JetBrains Marketplace.
- [ ] Set the [Plugin Signing](https://plugins.jetbrains.com/docs/intellij/plugin-signing.html?from=IJPluginTemplate) related [secrets](https://github.com/JetBrains/intellij-platform-plugin-template#environment-variables).
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html?from=IJPluginTemplate).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.


[template]: https://github.com/JetBrains/intellij-platform-plugin-template
[docs:plugin-description]: https://plugins.jetbrains.com/docs/intellij/plugin-user-experience.html#plugin-description-and-presentation
