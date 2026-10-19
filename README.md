# Wardogs Recorder – releases

Installers of Wardogs Recorder, a Windows app that records kills in the PC shooter Wardogs
while OBS records and turns them into a kill list, markers and clips. The source is private;
this repository holds only the releases.

## Install

1. Download `Wardogs-Recorder_<version>_x64-setup.exe` from the
   [latest release](https://github.com/rxm96/wardogs-recorder-releases/releases/latest).
2. Run it. Windows may warn that the installer isn't signed by a known publisher
   ("More info", then "Run anyway").
3. Needs OBS 30.2 or later with the WebSocket server turned on.

After that the app updates itself: it looks for a new version a minute after start and every
six hours, and asks before it installs one.
