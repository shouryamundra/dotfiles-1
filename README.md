Stolen from [KingLuddite](https://github.com/kingluddite/dotfiles)

# What is this?

dotfiles are used to setup a fresh new dev environment

# Getting setup

## Run install bash script

From the `dotfiles` directory, run this in the terminal:

```
sh install.sh
```

### What that did

- Installed Homebrew
- Installed apps and dependencies (See Brewfile for full list)
- Install Oh-My-ZSH and plugins
- Install Powerlevel9K theme
- Install nerd-font for fancy ligatures in command line
- Created symlinks for our configuration files
- installed global npm dependencies

### Getting Nvim to work

Create a new init.vim in `.config/nvim`

Add this line

`source ~/dotfiles/init.vim`

You have to download the Plug plugin system via the instructions on the site [Install Plug](https://github.com/junegunn/vim-plug#neovim)
