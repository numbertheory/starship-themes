# Custom Starship Themes

This directory is reserved for local, user-specific [Starship](https://starship.rs) configuration files.

> [!NOTE]
> All `*.toml` files within this directory are ignored by Git (see [`.gitignore`](../.gitignore)).
> Any custom themes or modifications you place here will remain local to your machine and will not be tracked or committed to the repository.

---

## 🚀 How to Use

### 1. Create or Copy a Theme
You can create a new `.toml` file from scratch or duplicate one of the base themes from the repository root:

```bash
# Example: Copy a base theme as a starting point
cp ../starship_blue.toml ./my-custom-theme.toml
```

### 2. Configure Your Shell
Set the `STARSHIP_CONFIG` environment variable in your shell configuration file (`~/.bashrc`, `~/.zshrc`, `~/.config/fish/config.fish`, etc.) to point to your custom theme:

```bash
# Starship Custom Config
export STARSHIP_CONFIG="/path/to/starship-themes/custom/my-custom-theme.toml"
eval "$(starship init zsh)"  # Replace 'zsh' with your shell (e.g. bash, fish)
```

### 3. Apply Changes
Reload your shell configuration or start a new terminal session:

```bash
source ~/.zshrc  # or source ~/.bashrc
```
