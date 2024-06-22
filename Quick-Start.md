# Quick Start & Setup Guide for the LEGO MindStorms RCX

## Quick Start Menu
There are a lot of projects to explore, but where to start?

| You would like to… | Your computer type… | Suggested Project | Project Description |
|--------------------|---------------------|-------------------|---------------------|
| Program Using Visual Icons | Supports Java | VisualNQC | An iconic programming tool offering functionality similar to LEGO’s original Robotics Invention System software |
| Program Using an IDE with Debugging Support | Windows | RobotC | A full-featured Windows IDE offering the only support at this level for comprehensive, real-time debugging |
| Program Using a Multi-Platform IDE | Windows / Mac / \*nix | BricxCC | A multi-platform IDE that supports writing NQC code |
| Program Using a Java Environment | Supports Java | HaikuVM | A leJOS successor for programming the RCX using Java |
| Program Targeting Open Source RCX Firmware | Windows / Mac /\*nix | BrickOS-Bibo | Offers lower-level control of the RCX and supports multiple programming languages |

For the more technically inclined, or for more advanced educational scenarios, we strongly encourage reviewing the numerous other options available across this organization’s repositories.

# Important Prerequisites

## IR Tower Support Status
  + Linux:  Lego USB tower drivers have been included, so either the serial or USB IR tower may be used, regardless of CPU architecture or bitness
    - A Raspberry PI can be used, which educational scenarios in particular might find advantageous
  + Windows:  The short and simple—
    - 32-bit:  Either the serial IR tower or—after installing the drivers—the USB IR tower may be used
    - 64-bit:  Only works with the serial IR tower; if your computer does not have a serial port, you will need to use a USB-to-serial adapter

### Source Code Version Control
For projects hosted within this BrickBot organization, GitHub is used for version control.

Conversely to the driver issue, there is not currenly a version of GitHub Desktop for 32-bit Windows.
For those wanting an alternative to GitHub Desktop that also provides a 32-bit distribution,
the open source [GitAhead](http://gitahead.com/) project is suggested.


# Host Computer Setup
[Overview of Using the RCX with More Recent Operating Systems](http://www.johnholbrook.us/RCX_guide.html)

## Windows
* [RCX USB Tower Support, by Lego Engineering](http://www.legoengineering.com/rcx-usb-tower-support/)
* [Philo’s Archive of Lego MindStorms RCX Updates](https://www.philohome.com/sdk25/sdk25.htm)
* [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/about)

<!--
WSL now supports graphical capabilities
  - To run graphical Linux applications if using the Ubuntu bash shell
    1. Install [VcXsrv X-server for Windows](http://vcxsrv.sf.net/)
    2. Configure bash to use the local X server by updating `~/.bashrc`
    3. Run `echo "export DISPLAY=localhost:0.0" >> ~/.bashrc` to append the update to the `~/.bashrc` file
    4. To make the changes take effect, restart bash or run `. ~/.bashrc`
    5. For additional details, see [Running Graphical Linux Applications on WSL](https://seanthegeek.net/234/graphical-linux-applications-bash-ubuntu-windows/)
-->

## Linux
* [Linux Online - Lego Mindstorm with Linux Mini-HOWTO](http://www.linux.org/docs/ldp/howto/Lego/)
* [Using Lego Mindstorms on Ubuntu « Adrian Smith's Blog](http://www.17od.com/2013/01/13/using-lego-mindstorms-on-ubuntu/)
* [pnc-rcx Tools and programs for building programs for the Lego Mindstorms RCX 1.0 (Hitachi H8300)](https://github.com/pnc/rcx)
* Kernel Driver: [LegoUSB](http://legousb.sourceforge.net/) – This driver is now officially part of the Linux kernel as of Linux 2.6.1.

### Debian / Ubuntu
* [Lego-Related Packages for Debian, from the Debian Lego Team](https://qa.debian.org/developer.php?login=debian-lego-team%40lists.alioth.debian.org)

## Mac OS X
* [NQC on Mac OS X](https://github.com/Glitchbone/mindstorms-rcx-osx-tools)

## Raspberry Pi
* [Using NQC on a Raspberry Pi](https://minordiscoveries.wordpress.com/2014/01/20/using-nqc-on-a-raspberry-pi-to-program-a-lego-mindstorms-rcx-brick/)
