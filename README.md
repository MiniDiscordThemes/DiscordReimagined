[preview]:          https://minidiscordthemes.github.io/Snippets/DiscordReimagined/preview.png
[previewColor]:     https://minidiscordthemes.github.io/Snippets/DiscordReimagined/preview-systemcolor.png
[SystemColor]:      https://github.com/MiniDiscordThemes/SystemColor

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length

[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://vencord.dev/

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-css-dl]:    https://img.shields.io/github/downloads/MiniDiscordThemes/DiscordReimagined/DiscordReimagined.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/DiscordReimagined/net.saltssaumure.DiscordReimagined.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/DiscordReimagined?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/DiscordReimagined
[issues]:           https://github.com/MiniDiscordThemes/DiscordReimagined/issues
[license]:          https://github.com/MiniDiscordThemes/DiscordReimagined/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/DiscordReimagined/blob/main/DiscordReimagined.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.DiscordReimagined "Replugged store page"
[release-css-gh]:   https://github.com/MiniDiscordThemes/DiscordReimagined/releases/latest/download/DiscordReimagined.theme.css "Get latest release"
[release-asar-gh]:  https://github.com/MiniDiscordThemes/DiscordReimagined/releases/latest/download/net.saltssaumure.DiscordReimagined.asar "Get latest release"

# Discord Reimagined Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![CSS GitHub downloads][shield-css-dl]][release-css-gh]
[![Asar GitHub downloads][shield-asar-dl]][release-asar-gh]
[![Total repository size][shield-repo-size]][github]

***A theme based on [Discord Re-imagined (Concept)](https://www.youtube.com/watch?v=7gyZyg3jC2w) by Concept Central.***

|                      Default                       |           [With SystemColor][SystemColor]           |
| :------------------------------------------------: | :-------------------------------------------------: |
| ![DiscordReimagined with default colours][preview] | ![DiscordReimagined with SystemColor][previewColor] |

## Installation

### [BetterDiscord][BetterDiscord]
<details><summary>Click to expand</summary>

1. Download `DiscordReimagined.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details><summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.DiscordReimagined.asar`:
    - [GitHub][release-asar-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details><summary>Click to expand</summary>

#### Local
1. Download `DiscordReimagined.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/DiscordReimagined/DiscordReimagined.theme.css`
</details>

## Customisation

| Variable                        | Description        | Valid values              | Default value |
| ------------------------------- | ------------------ | ------------------------- | ------------- |
| `--reimagine-channellist-width` | Channel list width | Any [length][css-length]. | `360px`       |
| `--reimagine-header-height`     | Header height      | Any [length][css-length]. | `60px`        |
| `--reimagine-server-size`       | Server size        | Any [length][css-length]. | `54px`        |

### BetterDiscord
<details><summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details><summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-20 of [`DiscordReimagined.theme.css`][.theme.css].
4. Edit the variable values and save.
</details>

### Vencord
<details><summary>Click to expand</summary>

#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `DiscordReimagined.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`DiscordReimagined.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
This theme is licensed under the [MIT license][license].

## Credits
### Sources
- [Discord Re-imagined (Concept)](https://www.youtube.com/watch?v=7gyZyg3jC2w) by Concept Central

### Themes
[hsl]:  https://github.com/DiscordStyles/HorizontalServerList
[clw]:  https://github.com/MiniDiscordThemes/Snippets/blob/main/themes/ChannelListWidth
[msb]:  https://github.com/MiniDiscordThemes/Snippets/blob/main/themes/MinimalSearchbar
[mt]:   https://github.com/MiniDiscordThemes/Snippets/blob/main/themes/ModTitle
[mdt]:  https://github.com/MiniDiscordThemes
[s]:    https://github.com/Saltssaumure

- [HorizontalServerList][hsl] by [DiscordStyles](https://github.com/DiscordStyles) ([Gibbu](https://github.com/Gibbu)) - MIT license
- [ChannelListWidth][clw] by [MiniDiscordThemes][mdt] ([Saltssaumure][s]) - MIT license
- [MinimalSearchbar][msb] by [MiniDiscordThemes][mdt] ([Saltssaumure][s]) - MIT license
- [ModTitle][mt] by [MiniDiscordThemes][mdt] ([Saltssaumure][s]) - MIT license

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].