# Launchpad 重置

```bash
rm ~/Library/Application\ Support/Dock/*.db && killall Dock
defaults write com.apple.dock ResetLaunchPad -bool true && killall Dock
```