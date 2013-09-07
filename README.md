MacOSX-ZNC-Launcher
===================

An Apple launchd(8) script to start the ZNC IRC bouncer at boot time.

To install:

1. Check the first item in the ProgramArguments array to make sure that the path to your copy of znc is right.
2. Copy the launchd plist file, in.znc.plist to the system LaunchDaemons directory, /Library/LaunchDaemons.
3. Load the script by hand: launchctl load /Library/LaunchDeamons/in.znc.plist

That should do it.
