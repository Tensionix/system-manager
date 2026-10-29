# Audion System Manager

[English README](README_EN.md) · [User Guide](USER_GUIDE_EN.md) | [Русский README](README_RU.md) · [Руководство](USER_GUIDE_RU.md)

One window for the developer environment on Windows: **PowerShell 7**, **Windows Terminal**, **Python 3.12, 3.13 and 3.14**, **VS Code**, **Git** with **GitHub CLI**, and the agents of the console **Claude Code**, **Codex**, **Grok Build**, **Antigravity CLI**. Each program can be installed for the system or unpacked as a portable folder — with every option a package manager does not give, and with the Audion settings. With buttons: no black console window, no command-line switches.

## Why

A package manager installs a program but does not set it up. An installer wizard offers options nobody remembers half a year later. And the settings after the install are put together again on every machine. The program takes all of that on itself.

| Section | For the system | Portable |
|---|---|---|
| POWERSHELL 7 | the MSI for the whole machine with every option: Explorer menus, PATH, event log, updates through Microsoft Update; the Audion profile | the zip of the release in a folder |
| TERMINAL | Windows Terminal from the Store (or through WinGet) and the Audion settings in every terminal found; the default terminal; Cascadia Nerd Font | the zip of the release in a folder, settings beside it |
| PYTHON | 3.12, 3.13 or 3.14, side by side: the python.org installer for all users, every version into its own folder, the path at the front of PATH, the py launcher, no Store stubs; pip of every Python | python.org's full archive with pip |
| VS CODE | the installer for the machine or the profile with every box of its wizard, the settings, keys and snippets, the extensions by the lists | the archive in a folder with its data folder, updated without losing the settings |
| GIT | Git for Windows with every box of its wizard; GitHub CLI with sign-in in the browser; the Audion Git settings, the personal ones left alone | PortableGit in a folder, GitHub CLI beside it |

The **AI CLI** section installs and updates Claude Code, Codex, Grok Build and Antigravity CLI with their authors' installers, and signs in and out with your subscription (OAuth in the browser) by a button for each.

Administrator rights are asked for only for an install for the whole machine — by the UAC prompt of the installer. Downloads go to `Download`, portable builds to `Portable`: **the folder can be carried to another machine whole**.

## Starting

`Start.exe`. The details are in the [user guide](USER_GUIDE_EN.md).
