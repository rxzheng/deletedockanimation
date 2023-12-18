# deletedockanimation
How to stop the dock macOS animation from occuring on macOS.

If you want it to immediately appear and disappear, use:
```bash
defaults write com.apple.dock autohide-time-modifier -int 0; killall Dock
```
If you want it to have a slight delay (to click icon sometimes), use:
```bash
defaults write com.apple.dock autohide-time-modifier -float 0.15; killall Dock
```
