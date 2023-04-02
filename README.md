# Exponent Discord Theme
[![GitHub downloads](https://img.shields.io/github/downloads/saltssaumure/xp-discord-theme/total?color=purple&label=GitHub%20downloads&style=flat-square)](https://github.com/Saltssaumure/xp-discord-theme/releases/latest "Latest release")
![Total size](https://img.shields.io/github/repo-size/saltssaumure/xp-discord-theme?style=flat-square "Total size")

***A Windows XP style Discord theme.***

| Light mode | Dark mode |
| ---------- | --------- |
| ![Screenshot of Exponent Discord Theme applied to Discord desktop client ](https://user-images.githubusercontent.com/29710355/229367843-ad03f107-ad47-4c63-9692-89cd781d40f8.png) | ![Screenshot of Exponent Discord Theme applied to Discord desktop client](https://user-images.githubusercontent.com/29710355/229367846-78bf3675-a091-4f60-8ff0-4427697a2ef2.png) |

## Installation

### BetterDiscord
1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download the theme file:
    - [GitHub](https://github.com/Saltssaumure/xp-discord-theme/releases/latest)
    - [BD Store](https://betterdiscord.app/theme/?id=823)
3. Place theme file in BetterDiscord's theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged](https://replugged.dev/).
2. Install the theme:
    - [GitHub](https://github.com/Saltssaumure/xp-discord-theme/releases/latest)
    - [Replugged.dev](https://replugged.dev/install?identifier=Saltssaumure/xp-discord-theme&source=github)

## Customisation (BetterDiscord only)

### Addons
- [ExponentBgImageAddon](https://raw.githubusercontent.com/Saltssaumure/xp-discord-theme/main/addon/ExponentBgImageAddon.theme.css) - enables custom background image in the main window.

### Settings 
1. Open `Settings` > `Themes` menu in Discord.
2. Click pencil icon on this theme.
3. Customise the variable values. See table below for reference.
4. Save changes and enjoy.

| Description                 | Variable name          | Valid values                               | Default value                                                                           |
|-----------------------------|------------------------|--------------------------------------------|-----------------------------------------------------------------------------------------|
| Wallpaper  image            | `--background-image`   | Any image link wrapped encased in `url()`. | `url(https://saltssaumure.github.io/xp-discord-theme/img/bliss.jpg)`                    |
| BSOD background colour      | `--bsod-color`         | Any CSS-recognised colour.                 | `navy`                                                                                  |
| BSOD text                   | `--bsod-text`          | Any quoted text. Use `\A` for new lines.   | [Read here](https://github.com/Saltssaumure/xp-discord-theme/blob/main/scss/top/_vars-css.scss) |
| Panel background colour     | `--xp-bg-color`        | Any CSS-recognised colour.                 | `#000` (dark) / `#FFF` (light)                                                          |
| Button highlight colour     | `--xp-bg-bright-color` | Any CSS-recognised colour.                 | `#203040` (dark) / `#F0EFED` (light)                                                    |
| Button background colour    | `--xp-bg-tint-color`   | Any CSS-recognised colour.                 | `#202020` (dark) / `#EBE8D7` (light)                                                    |
| Button shadow colour        | `--xp-bg-shade-color`  | Any CSS-recognised colour.                 | `#101010` (dark) / `#808080` (light)                                                    |
| Panel text colour           | `--xp-txt-color`       | Any CSS-recognised colour.                 | `#FFF` (dark) / `#000` (light)                                                          |
| Button/panel border colour  | `--xp-border-color`    | Any CSS-recognised colour.                 | `#1665CA` (dark) / `#000000` (light)                                                    |
| Panel settings icon colour  | `--xp-set-color`       | Any CSS-recognised colour.                 | `#FFFFFFB3` (dark) / `#000000B3` (light)                                                |
| Panel hovered item colour   | `--xp-hover-color`     | Any CSS-recognised colour.                 | `#102030` (dark) / `#D3D3D3` (light)                                                    |
| Panel top decoration colour | `--xp-zing-color`      | Any CSS-recognised colour.                 | `#A05000` (dark) / `#FFA500` (light)                                                    |

## License
- **Whole theme:** [GNU General Public License v3.0](https://github.com/Saltssaumure/xp-discord-theme/blob/main/LICENSE)
    - <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.
- **[HorizontalServerList](https://github.com/DiscordStyles/HorizontalServerList):** [MIT License](https://github.com/DiscordStyles/HorizontalServerList/blob/master/LICENSE.md)

## Questions or suggestions?
- Post [an issue](https://github.com/Saltssaumure/xp-discord-theme/issues) on GitHub.
- Post in `#theme-support` on [my support server](https://discord.gg/uy8nKQVatp).
