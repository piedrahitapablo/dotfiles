# Dotfiles

## Installation

1. Initialize chezmoi
   ```bash
   chezmoi init --apply piedrahitapablo
   ```

## Mac setup

1. Install `brew`
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
1. Install packages from `Brewfile`
   ```bash
   brew bundle install
   ```
1. Install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)
   ```bash
   sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   ```
1. Install [powerlevel10k](https://github.com/romkatv/powerlevel10k)
   ```bash
   brew install powerlevel10k
   echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
   ```
1. Add source to `~/.zshrc`
   ```bash
   echo "source ~/.zsh_aliases" >>~/.zshrc
   echo "source ~/.zsh_env" >>~/.zshrc
   echo "source ~/.zsh_settings" >>~/.zshrc
   ```
1. Install [volta](https://volta.sh/)
   ```bash
   curl https://get.volta.sh | bash
   ```
   1. Install node
      ```bash
      volta install node
      volta install yarn
      volta install pnpm
      ```
1. Install [pre-commit](https://pre-commit.com/)
   ```bash
   pipx install pre-commit
   ```
1. Setup SSH access for GitHub
1. Setup neovim
   ```bash
   git clone git@github.com:piedrahitapablo/init.lua.git ~/.config/nvim
   ```
1. Install [Scroll Reverser](https://github.com/pilotmoon/Scroll-Reverser)
1. Install Docker

### Settings

- Dark mode: Auto
- Keyboard input: US International
- Dock
  - Magnification: Large
  - Automatically hide
  - Hide Suggestions
  - Remove unwanted apps
- Trackpad
  - Tracking speed: 4
  - Tap to click
