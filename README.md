# astronvim_config

My AstroNvim Config.

## Dependencies

- npm
- nodejs

### Install command

```bash
sudo apt install npm nodejs -y
```

## Installation

```bash
rm -rf ~/.config/nvim/
rm -rf ~/.local/share/nvim/
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
git clone https://github.com/rykersun/astronvim_config.git ~/.config/nvim/lua/user
nvim +PackerSync
```
