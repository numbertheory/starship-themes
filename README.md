# starship-themes

My collected themes for Starship.rs.

## Inspiration

`starship_blue.toml` and `starship_green.toml` are taken from Starship's own [Tokyo Night Preset](https://starship.rs/presets/tokyo-night.html)


## Installation

1. Download and install [Starship.rs](https://starship.rs/guide/#%F0%9F%9A%80-installation).
2. Download and install a [NerdFont](https://www.nerdfonts.com/font-downloads). I use FiraCode Nerd Font.
3. Set up your terminal to use that NerdFont you've installed.
4. In your shell's RC file (.zshrc, .bashrc, etc.), add this:

```
# Starship
export STARSHIP_CONFIG=~/.config/starship_green.toml
eval "$(starship init zsh)"
```

5. Finally, copy the TOML files in this repo to the `~/.config/` directory, where your default starship config is. To switch themes, just change the STARSHIP_CONFIG value in your RC file to point to another template.