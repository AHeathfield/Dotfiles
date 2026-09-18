# Dotfiles

- This is just a singular place to store all the configs and use GNU stow to symlink them

## How to Stow
See this [link](https://gist.github.com/andreibosco/cb8506780d0942a712fc)

1. Locate the config from the `${HOME}` directory.

2. Create a dir in dotfiles where you want to store the config. Ex. `mkdir nvim`

3. Move the config into your new directory. Ex. `mv ${HOME}/.config/nvim ${HOME}/Dotfiles/nvim`

4. Finally while inside the Dotfiles directory run: `stow nvim`
