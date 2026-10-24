# Wardogs Recorder – releases

Installers of Wardogs Recorder, a Windows app that records kills in the PC shooter Wardogs
while OBS records and turns them into a kill list, markers and clips. The source is private;
this repository holds only the releases.

## Latest: 0.5.1

- Download: [Wardogs-Recorder_0.5.1_x64-setup.exe](https://github.com/rxm96/wardogs-recorder-releases/releases/download/v0.5.1/Wardogs-Recorder_0.5.1_x64-setup.exe)
- SHA-256: `b06a3d79d3315959b02bf52eb05ed263cce530b8636a44d3d098f4910f0b1ca4`
- [VirusTotal scan](https://www.virustotal.com/gui/file/b06a3d79d3315959b02bf52eb05ed263cce530b8636a44d3d098f4910f0b1ca4)

The installer is not code-signed. Unsigned installers are often flagged by one or two
heuristic engines on VirusTotal; the scan above is of exactly this file.

## Install

1. Download the installer above or from the
   [latest release](https://github.com/rxm96/wardogs-recorder-releases/releases/latest).
2. Run it. Windows may warn that the publisher is unknown ("More info", then "Run anyway").
3. Needs OBS 30.2 or later with the WebSocket server turned on.

After that the app updates itself: it looks for a new version a minute after start and every
six hours, and asks before it installs one.
