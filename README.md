# Personal TMUX Configuration

This repository hosts my personal `tmux` config

**NOTE:** you must `chmod +x tmux-runconf.sh` for the reload script to work

## Config Contents:
- Plugin Manager: tpm
- Theme: Dracula
- Prefix Key: `ctrl+f`
- Horizontal Pane: prefix + `h` (goes to current directory)
- Vertical Pane: prefix + `v` (goes to current directory)
- Mouse Mode: on
- Switch Panes: `alt` + "h", "j", "k", "l"
- Reload Config: prefix + `R`
- Alt Reload: `tmux-runconf.sh` script
- More Colors: Set the terminal to have 256-bit color support
- Window Renumbering: Set base index to 1
- Pane Renumbering: Set base index to 1
- Tab changes color to Cyan when active
- Resize Pane Splits: `alt` + z

## Plugins
- Dracula Theme
- Dracula Powerline
- tmux-prefix-highlight
- tpm 
