# Wardogs Recorder – releases

Installers of Wardogs Recorder, a Windows app that records kills in the PC shooter Wardogs
while OBS records and turns them into a kill list, markers and clips. The source is private;
this repository holds only the releases.

## Latest: 0.10.0

- Download: [Wardogs-Recorder_0.10.0_x64-setup.exe](https://github.com/rxm96/wardogs-recorder-releases/releases/download/v0.10.0/Wardogs-Recorder_0.10.0_x64-setup.exe)
- SHA-256: `2037a5e97a4c5c5cb87d72a397d04dccd669f95562f8dbff3178bd99f8d3cf3b`
- [VirusTotal scan](https://www.virustotal.com/gui/file/2037a5e97a4c5c5cb87d72a397d04dccd669f95562f8dbff3178bd99f8d3cf3b)

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
