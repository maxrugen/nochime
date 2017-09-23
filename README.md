# nochime
A script disabling the PowerChime on macOS with some help of a LaunchDaemon. 🔇



Simply running the `defaults write com.apple.PowerChime ChimeOnAllHardware -bool false; killall PowerChime` command would not work nicely as the setting would reset on every bootup.

## Usage
Execute `nochime.sh`. That's it.