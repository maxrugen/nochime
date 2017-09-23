# nochime
A script disabling the PowerChime on macOS. 🔇

Simply running the `defaults write com.apple.PowerChime ChimeOnAllHardware -bool false; killall PowerChime` command would not work nicely as the setting would reset on every bootup.

## Usage
Execute `nochime.sh`. That's it.