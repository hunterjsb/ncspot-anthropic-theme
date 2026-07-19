# ncspot-anthropic-theme

A dark [ncspot](https://github.com/hrkfdn/ncspot) theme using Anthropic/Claude's brand palette — warm dark background, terracotta (`#DA7756`) accents, cream text.

## Usage

Copy the `[theme]` table from `theme.toml` into your ncspot `config.toml`:

- Native install: `~/.config/ncspot/config.toml`
- Flatpak: `~/.var/app/io.github.hrkfdn.ncspot/config/ncspot/config.toml`

Restart ncspot to apply.

## Transparency

`background` (and the other `*_bg` fields) are set to `"default"` rather than a
solid color, so ncspot doesn't paint over your terminal. Terminal cell colors
have no alpha channel, so real transparency has to come from your terminal
emulator's own opacity setting — e.g. in Konsole, a color scheme's `[General]`
section supports `Opacity=0.92`.
