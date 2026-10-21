# Wardogs Recorder – releases

Installers of Wardogs Recorder, a Windows app that records kills in the PC shooter Wardogs
while OBS records and turns them into a kill list, markers and clips. The source is private;
this repository holds only the releases.

## Latest: 0.4.0

- Download: [Wardogs-Recorder_0.4.0_x64-setup.exe](https://github.com/rxm96/wardogs-recorder-releases/releases/download/v0.4.0/Wardogs-Recorder_0.4.0_x64-setup.exe)
- SHA-256: `f64b55d50bb2fcdcd3d57a71240a2d779be13f1daf8c6dee8f40f292eae2832c`
- [VirusTotal scan](https://www.virustotal.com/gui/file/f64b55d50bb2fcdcd3d57a71240a2d779be13f1daf8c6dee8f40f292eae2832c)

The installer is not code-signed. Unsigned installers are often flagged by one or two
heuristic engines on VirusTotal; the scan above is of exactly this file.

## Install

1. Download the installer above or from the
   [latest release](https://github.com/rxm96/wardogs-recorder-releases/releases/latest).
2. Run it. Windows may warn that the publisher is unknown ("More info", then "Run anyway").
3. Needs OBS 30.2 or later with the WebSocket server turned on.

After that the app updates itself: it looks for a new version a minute after start and every
six hours, and asks before it installs one.
