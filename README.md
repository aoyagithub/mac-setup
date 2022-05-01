# Setup

1. Sign in with Apple ID

1. Install [Homebrew](https://brew.sh/index_ja) `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

1. Install Homebrew bundler `brew tap Homebrew/bundle`

1. Copy Brewfile to `~/.Brewfile` and run `brew bundle --file ~/.Brewfile`

## Hot Corners

```
defaults write com.apple.dock wvous-tl-corner -int 4
defaults write com.apple.dock wvous-tl-modifier -int 0
defaults write com.apple.dock wvous-tr-corner -int 2
defaults write com.apple.dock wvous-tr-modifier -int 0
defaults write com.apple.dock wvous-bl-corner -int 11
defaults write com.apple.dock wvous-bl-modifier -int 0
defaults write com.apple.dock wvous-br-corner -int 12
defaults write com.apple.dock wvous-br-modifier -int 0
killall Dock

#  0: no-op
#  2: Mission Control
#  3: Show application windows
#  4: Desktop
#  5: Start screen saver
#  6: Disable screen saver
#  7: Dashboard
# 10: Put display to sleep
# 11: Launchpad
# 12: Notification Center
```
