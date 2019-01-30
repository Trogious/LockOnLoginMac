# LockOnLoginMac
launchctl script to lock screen on Mac OSX immediately after login

### Requirements
Go to `System Settings -> Security & Privacy -> General` and enable: `Require password immediately after sleep or screen saver begins`.

### Installation
Copy `net.swmud.trog.lockonlogin.plist` to `~/Library/LaunchAgents/`.

### Test
Run `launchctl load ~/Library/LaunchAgents/net.swmud.trog.lockonlogin.plist` and see if the display goes to sleep.
