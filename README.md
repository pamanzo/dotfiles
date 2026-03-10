# dotfiles

personal configuration files managed with gnu stow.

## installation

### 1. clone the repository
clone this repo into your home directory:

```bash
git clone [https://github.com/pablovid/dotfiles.git](https://github.com/pamanzo/dotfiles.git) ~/dotfiles
cd ~/dotfiles
```


### 2. install stow
```bash
sudo pacman -S stow
```

### 3. deploy configurations
```bash
stow alacritty hypr lf nvim rofi waybar zsh
```

### 4. to remove symlinks
```bash
stow -D module_name
```

