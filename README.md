# Hephaestus: The Windows development machine

## Introduction

An automation script for installing and configuring a Windows 10-based
development machine.

## Features

*   Installs browsers, browser extensions and chat clients:
    *   Google Chrome with LastPass
    *   Mozilla Firefox with LastPass
    *   Opera with LastPass
    *   Skype Classic
*   Installs multimedia and office applications:
    *   PeaZip
    *   Nomacs
    *   MPC-HC
    *   Microsoft Office 365 Personal
    *   Adobe Creative Cloud
    *   Steam
*   Installs developer applications and tools:
    *   Git
    *   Visual Studio Code
    *   JetBrains Toolbox
    *   Docker CE for Windows
*   Enables optional Windows features:
    *   Windows Subsystem for Linux (WSL)
    *   Hyper-V 
    *   Containers
*   Creates an initial system restore point when complete.
    
## Requirements

*   Windows 10 Professional
*   Hardware support for Hyper-V virtualization
*   Internet connectivity

## Recommendations

*   Perform a clean installation of Windows 10 Fall Creators Update or
    newer before running the script

## Installation

```powershell
Set-ExecutionPolicy RemoteSigned
.\Install-Hephaestus.ps1
```

## Etymology

Hephaestus is the Greek god of blacksmiths, carpenters, craftsmen,
artisans, sculptors, metallurgy, fire, and volcanoes. In Greek
mythology, he is the son of Zeus and Hera, brother of Athena,
and consort of Aphrodite. He built automatons of metal to work for him,
and made all the weapons of the gods. In some versions of the myth,
Prometheus stole the fire that he gave to man from Hephaestus's forge.
(Summary based on [Wikipedia](https://www.wikipedia.org/) article
"[Hephaestus](https://en.wikipedia.org/wiki/Hephaestus)")

## License

Source files are released under the terms of the license specified in
the repository, the copyright header at the top of each file, or if not
specified, under the [MIT license](https://opensource.org/licenses/MIT).

Content, design, layout, look-and-feel and assets may be the subject of
intellectual property rights reserved by the right holders, and are not
licensed for any purpose hereunder.
