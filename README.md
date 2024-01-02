# starship-themes

My collected themes for Starship.rs.

## Inspiration

`starship_blue.toml` and `starship_green.toml` are taken from Starship's own [Tokyo Night Preset](https://starship.rs/presets/tokyo-night.html)

## Features
- Icons to differentiate between operating systems.
- Multiple colors to differentiate between servers.
- Git status indicators built in:
    ![git status shown in terminal](screenshots/git_status_shown.png)


## Installation

1. Clone this repo locally.
2. Download and install [Starship.rs](https://starship.rs/guide/#%F0%9F%9A%80-installation).
3. Download and install a [NerdFont](https://www.nerdfonts.com/font-downloads). I use FiraCode Nerd Font.
4. Set up your terminal to use that NerdFont you've installed.
5. In your shell's RC file (.zshrc, .bashrc, etc.), add this:

```
# Starship
export STARSHIP_CONFIG=<path-to-cloned-repo>/starship_green.toml
eval "$(starship init zsh)"
```

6. To switch themes, just change the STARSHIP_CONFIG value in your RC file to point to another template.

## Screenshots

`starship_green.png`:
![starship_green.toml active in terminal](screenshots/green.png)

`starship_blue.png`:
![starship_blue.toml active in terminal](screenshots/blue.png)