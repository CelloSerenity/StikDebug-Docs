iloader allows us to create a pairing file for programs like StikDebug to talk to your device remotely. This pairing file is device-specific, time-specific and required to use StikDebug, otherwise StikDebug will not function correctly. 
> [!WARNING]
> Caution, if you update or reset your iDevice, your pairing file will expire and you will need to reimport it. This also occurs at random times. This is simply because of how Apple's software works, and there is nothing we can do at this point to fix it.

## Prerequisites
### On your Mac
1. Download and install iloader for Mac ([M-Series](https://github.com/nab138/iloader/releases/latest/download/iloader-darwin-aarch64.dmg) or [Intel](https://github.com/nab138/iloader/releases/latest/download/iloader-darwin-x64.dmg)).
2. Open Terminal, run `sudo xattr -c ./Applications/iloader.app`, and enter your password if prompted.

### On your Windows PC
1. Download and install [iTunes](https://apple.co/ms).
2. Download the iloader installer ([exe](https://github.com/nab138/iloader/releases/latest/download/iloader-windows-x64.exe) or [msi](https://github.com/nab138/iloader/releases/latest/download/iloader-windows-x64.msi)).
3. Run the installer.

### On your Linux Machine
1. Download and install `usbmuxd` (may be preinstalled for your distro, otherwise install with your package manager).
2. Download and install iloader for your distro ([Debian/Ubuntu](https://github.com/nab138/iloader/releases/latest/download/iloader-linux-amd64.deb), [Fedora/openSUSE](https://github.com/nab138/iloader/releases/download/v0.1.3/iloader-linux-x86_64.rpm), [other](https://github.com/nab138/iloader/releases/latest/download/iloader-linux-amd64.AppImage)).

## Importing your pairing file
1. For best results, connect your iDevice to your computer via USB cable, but if your device appears wirelessly that works too.
2. Click "Manage Pairing File".
3. To the right of "StikDebug" and any other apps you wish, click "Place Pairing File". "Pairing file placed successfully!" should appear in green.
