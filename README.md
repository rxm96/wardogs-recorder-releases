# Wardogs Recorder – releases

Installers of Wardogs Recorder, a Windows app that records kills in the PC shooter Wardogs
while OBS records and turns them into a kill list, markers and clips. The source is private;
this repository holds only the releases.

## Latest: 0.10.1

- Download: [Wardogs-Recorder_0.10.1_x64-setup.exe](https://github.com/rxm96/wardogs-recorder-releases/releases/download/v0.10.1/Wardogs-Recorder_0.10.1_x64-setup.exe)
- SHA-256: `b965de109ecb0b7c6d15054b510baf171d798920074562d1c2440a017be3d195`
- [VirusTotal scan](https://www.virustotal.com/gui/file/b965de109ecb0b7c6d15054b510baf171d798920074562d1c2440a017be3d195)

The installer is not code-signed. Unsigned installers are often flagged by one or two
heuristic engines on VirusTotal; the scan above is of exactly this file.

## Install

1. Download the installer above or from the
   [latest release](https://github.com/rxm96/wardogs-recorder-releases/releases/latest).
2. Run it. Windows may warn that the publisher is unknown ("More info", then "Run anyway").
3. Needs OBS 30.2 or later with the WebSocket server turned on.

After that the app updates itself: it looks for a new version a minute after start and every
six hours, and asks before it installs one.

## Licences

The installer carries FFmpeg and FFprobe (GPL v3, the "essentials" build from gyan.dev) and
the fonts Inter and Barlow (SIL Open Font License). Their licence texts and where FFmpeg's
source is are in THIRD-PARTY-NOTICES.txt in the installation folder and under "Third-party
licences" in the app's Settings.
