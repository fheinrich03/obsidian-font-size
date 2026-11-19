# Obsidian Font Size Adjuster

> [!important]
> This is a maintained copy of [RyotaUshio/obsidian-font-size](https://github.com/RyotaUshio/obsidian-font-size) by [Ryota Ushio](https://github.com/RyotaUshio), released under the MIT License.
> All credit for the original plugin goes to the original author.
>
> **Changes in this copy:** Obsidian 1.15 moved the font size from the vault config (`baseFontSize`) to a per-device setting, which broke all three commands.
> This copy uses Obsidian's new `getBaseFontSize()` / `setBaseFontSize()` and falls back to the old API on older Obsidian versions.

This [Obsidian.md](https://obsidian.md) plugin adds the `Increment font size` & `Decrement font size` commands,
which allows you to adjust font size from hotkeys or the command palette without opening the appearance settings.

Note that they are different from Obsidian's built-in `Zoom in` & `Zoom out` commands; while these zooming commands
change the size of all UI elements, the `Increment font size` & `Decrement font size` commands only affect the editor font size.

I recommend the following hotkeys (in the case of macOS with a US-layout keyboard):
- `Zoom in`: `Cmd`+`=`
- `Zoom out`: `Cmd`+`-`
- `Increment font size`: `Cmd`+`Shift`+`=`
- `Decrement font size`: `Cmd`+`Shift`+`-`

> [!note]
> If you like this plugin, don't forget to star the [original repository](https://github.com/RyotaUshio/obsidian-font-size)! I'd also appreciate it if you could [support me](#support-development).

## Installation

Install this copy with [BRAT](https://github.com/TfTHacker/obsidian42-brat): *Add beta plugin* → `fheinrich03/obsidian-font-size`.
It keeps the plugin ID `font-size`, so it replaces the original plugin and keeps your hotkeys.

## Support development

If you find [Ryota Ushio's plugins](https://ryotaushio.github.io/the-hobbyist-dev/) useful, please support the original author to ensure they continue to work!

<a href="https://github.com/sponsors/RyotaUshio" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" alt="GitHub Sponsors" style="width: 180px; height:auto;"></a>

<a href="https://www.buymeacoffee.com/ryotaushio" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="width: 180px; height:auto;"></a>
