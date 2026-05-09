# AHK - Universal Joystick Remapper (UJR)

> Legacy project: UJR is no longer maintained and has been superseded by [UCR](https://github.com/evilC/UCR).

UJR is a stand-alone AutoHotkey application for mapping buttons and axes from one or more physical joysticks onto a virtual joystick, including support for inversion, deadzones, sensitivity, axis merging, and axis splitting.

## Project status

- This repository is kept for historical reference and source availability.
- New development has moved to [UCR](https://github.com/evilC/UCR).
- Expect limited or no fixes for new issues in UJR.

## Getting started

1. Install [vJoy](https://vjoystick.sourceforge.net/).
2. Configure the virtual device with the axes and buttons you need.
3. Run the compiled `ujr.exe`, or use `ujr.ahk` if you already have the required AutoHotkey environment and supporting libraries.

Full legacy setup and usage instructions are available in [/README.txt](./README.txt).

## Source tree

- [/ujr.ahk](./ujr.ahk) - main AutoHotkey source
- [/README.txt](./README.txt) - original installation and usage guide
- [/changelog.txt](./changelog.txt) - release history
- [/test_trim.m](./test_trim.m) - legacy trim-mode test script

## Security notes

- UJR checks for updates by reading a version text file from `evilc.com`.
- Any other unexpected network activity should be treated as suspicious.
- Review [/SECURITY.md](./SECURITY.md) before using this project in a sensitive environment.

## Support and alternatives

If you need an actively maintained remapping tool, use [UCR](https://github.com/evilC/UCR) instead of starting new work on UJR.

## Screenshot

![UJR Main window](http://evilc.com/files/ahk/vjoy/ujr.png)
