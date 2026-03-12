# H4rd-H4ck3r

This is a collection of dotfiles for r0s3le's H4rd-H4ck3r rice.
The config is still a work in progress, and will be added to after a few iterations.
This config is broken because of hardcoded filepaths (I know, bad r0s3le) will be fixed.

## Dependencies 

* sway/swayfx
* swaylock
* swayidle
* waybar
* rofi
* alacritty
* grim
* CozetteCrossedSeven https://github.com/the-moonwitch/Cozette

## Installation

In the config/ portion of this project are the main files for this project. Installing them to your `~/.config` (Or whatever directory handles your configurations) directory **SHOULD** make most of the changes take effect after reloading the window manager, but for all changes to be properly applied a reboot may be needed.

This setup assumes that the XDG_CONFIG_DIR environment variable is set to your config directory ie `~/.config`. This can be checked with `echo $XDG_CONFIG_DIR`.
If your environment is not configured this way, and you'd like it to be, you can achievethis by adding this line to your $HOME/.bashrc file, `export XDG_CONFIG_HOME=$HOME/.config`.

To install this environment and overwrite your current config run, 

`git clone https://github.com/r0s3le/H4rd-H4ck3r`
`cd H4rd-H4ck3r`
`cp -u config/* $HOME/.config/`

then reboot.
**THIS WILL OVERWRITE YOUR CONFIG**
Make a backup if youd like to keep it.


## Aspiratons 

Ideally, this project will come packaged with a script for easy installation and perhaps some different options depending on screen DPI. Maybe down the line it will get some nix flakes, but for now it will be focused mainly on arch. Progress will be incremental and slow going.


  
