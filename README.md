# Shortcuts
To document unix shortcut commands

## General
Description | Shortcut | Notes
--- | --- | ---
Save a selected area as a screenshot to the desktop | `shift + cmd + 4` | 
Show dotfiles in directory (must be in finder) | `shift + cmd + .` | Only persists for window session

## Command line
Description | Command
--- | ---
Move Screenshot Directory | `defaults write com.apple.screencapture location [path/to/location]` <br/> `killall SystemUIServer` | 
Show dotfiles | `defaults write com.apple.Finder AppleShowAllFiles true` <br/> `killall Finder` |                                         
