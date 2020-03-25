# Welcome to BrickBot!
The page provides an index to the repositories comprising the BrickBot organization, as well as links to related resources.

All projects imported to this GitHub organization have been curated to varying degrees as part of the import process.
Please feel free to join and contribute in whatever way you can, whether that might be cleaning up
or updating documenation, converting text files to Markdown, setting up wikis, or updating code to
work with the latest host platforms.

The initial seventy-plus (70+) projects gathered under this BrickBot organization on GitHub were largely collected by Matthew Sheets.


## Disclaimer
Neither this organization nor any of its included projects are associated in any way with Lego or any other companies.  Follow [this link to access the official Lego MindStorms Website](http://mindstorms.lego.com/).

Some sites referenced only by link do not have a repository setup to due to identified redistribution restrictions.


## Notes
No version of the Lego USB tower driver for 64-bit Windows is known to exist.
Conversely, there is not currenly a version of GitHub Desktop for 32-bit Windows.
For those wanting an alternative to GitHub Desktop that also provides a 32-bit distribution,
the open source [GitAhead](http://gitahead.com/) project is suggested.

* * *

# Index of Resources

## Available
* [Designs](https://github.com/BrickBot/BrickBot.github.io/tree/master/Designs):  Links and files for various robot designs
* [Documentation](https://github.com/BrickBot/BrickBot.github.io/tree/master/Documentation):  Official techincal documentation from Lego and Renesas
* [Education](https://github.com/BrickBot/BrickBot.github.io/tree/master/Education/):  Resources for those using the RCX in education
* [Firmware](https://github.com/BrickBot/BrickBot.github.io/tree/master/Firmware):  Archive of notable RCX firmware images
* [Media](https://github.com/BrickBot/BrickBot.github.io/tree/master/Media):  Archived images, sounds, video, etc.
* [Other Software](https://github.com/BrickBot/BrickBot.github.io/tree/master/Software):  Archived drivers, updates, system prerequisites
  - For general Lego software from LEGO:  [LEGO Digital Designer](https://www.lego.com/en-us/ldd)
  - For general third-party Lego software:  [LDraw.org Third-Party Software](https://ldraw.org/downloads-2/third-party-software.html)  (also visit the main [LDraw website](https://ldraw.org/) while there)
  - For Robotics Software from LEGO:  [Brick Factory](https://www.brickfactory.info/iso/)

## Missing/Wanted
For a few projects known to exist, the source no longer seems to be available.  Might you have a copy?
If so, please let us know by [posting a new issue here](https://github.com/BrickBot/BrickBot.github.io/issues/new/choose)!
* [Visual Storms / Sharp Storms](http://medialab.di.unipi.it/Project/visualstorms/resources.html) <sup>↗</sup>
  - A system capable of translate .NET executables in programs that can be executed on the Lego Mindstorms RCX without having to change its firmware
  - Additional known information in this [LUGNET post](https://news.lugnet.com/robotics/rcx/?n=2963) <sup>↗</sup>
* [MindStorms Tools](https://web.archive.org/web/20120130101715/http://ddi.uni-paderborn.de/index.php?id=4800&L=1), <sup>↗</sup>  which included the following individual tools:
  - Together MindstormsTool (TMT): modul for the Together ControlCenter 4.0 or higher
  - BlueJ MindstormsTool (BJMT): extension for the BlueJ integrated environment 1.3 or higher
  - Java MindstormsTool (JMT): the MindstormsTool with an own source code editor
  - Small MindstormsTool (SMT): the stand alone version of the tool
* Phantom: An alterative to Spirit.ocx

## Help Needed
Interested in helping out?  Below are a few of the many ways that you can contribute.
1. Debian Packaging:  With Debian packages, we are able to support a reasonable cross-section of systems, including Debian/Ubuntu Linux, Windows (via Windows Subsystem for Linux), and Raspberry Pi.  Some specific projects to package include the following:
   1. [nqc](https://github.com/BrickBot/nqc)
   2. [VisualNQC](https://github.com/BrickBot/VisualNQC)
   3. [binutils-cil](https://github.com/BrickBot/binutils-cil) for h8300-hms
   4. [gcc-cil](https://github.com/BrickBot/gcc-cil) for h8300-hms with g++
   5. [brickOS-bibo](https://github.com/BrickBot/brickOS-bibo)
   6. [brickEmu](https://github.com/BrickBot/brickEmu)
   7. [leJOS-RCX](https://github.com/BrickBot/leJOS-RCX)
   8. [Intellejos](https://github.com/BrickBot/Intellejos)
2. ReadMe/documentation cleanup and formatting:  The vast majority of these projects were developed before Markdown and GitHub conventions were developed
3. Testing/validation of projects on current platforms
4. Issues that have been filed within individual projects

* * *

# Index of Repositories

## Development Suites
* **Text-Based Programming**
  - [RobotC](https://github.com/BrickBot/RobotC)
    + A powerful C-based programming language with a Windows environment for writing and debugging programs, and the only programming language at this level that offers a comprehensive, real-time debugger.
    + Includes its own version of firmware for the RCX
  - [BricxCC](http://bricxcc.sourceforge.net/) <sup>↗</sup>
    + An IDE for the Lego MindStorms RCX, as well as the NXT, EV3, and HiTechnic SuperPro
    + Project not yet forked, as there have been occasional updates to support newer devices, but it can be forked if there is interest
  - [Interactive C](https://web.archive.org/web/20171101054739/http://www.kipr.org/products/interactive-c) <sup>↗</sup>
    + A program which uses a modified version of ANSI C with several libraries and features that allow hobbyists to program small robotics platforms.
    + Able to compile on the fly (c.f. [Wikipedia](https://en.wikipedia.org/wiki/Interactive_C))
  - [PRO-BOT](http://mapageweb.umontreal.ca/cousined/lego/4-RCX/PRO-BOT/) <sup>↗</sup>  **_Tethered Only; No Stand-Alone Capabilities_**
    + A program editor for the Lego MindStorms RCX programmable brick aimed at keeping a constant link between the PC and the brick
* **Iconic/Visual Programming**
  - [VisualNQC](https://github.com/BrickBot/VisualNQC)
    + An iconic language tool for the Lego MindStorms RCX, which generates NQC code.
  - [actor-lab](https://github.com/BrickBot/actor-lab) **_Tethered Only; No Stand-Alone Capabilities_**
    + A parallel, object-orientated, iconic control language designed to introduce the ideas of control technology and robotics
* **Modeling and Implementation**
  - [Times Tool](http://www.timestool.com/) <sup>↗</sup>
    + A tool set for modelling, schedulability analysis, synthesis of (optimal) schedules and executable code, supporting system specification, system analysis and code generation for the LegoOS (now BrickOS-Bibo) platform
* **Historical Reference Only / Superceded or No Longer Available**
  - [RCX Command Center](https://web.archive.org/web/20070204040037/http://www.cs.uu.nl/people/markov/lego/) <sup>↗</sup>
    + The predecessor to Bricx Command Center
  - [BrickCommand2](https://web.archive.org/web/20091023045530/http://www.geocities.com/Area51/Nebula/8488/lego.html) <sup>↗</sup>
    + A programming tool for Lego MindStorms RCX and Lego Cybermaster systems, offering more control over the brick than the software that comes with each system.
    + The setup installer was broken up into 3 separate zip file downloads, plus an additional update download; unfortunately, only 2 of the 3 setup zip files appear to have survived.
  - [PBrickDev](https://web.archive.org/web/20091024223614/http://geocities.com/pbrickdev/index.html)  <sup>↗</sup>
    + A complete programming environment for the RCX that used a graphical interface for programming, instead of writing code
    + The latest version used the Phantom.dll COM component by "Fenestra Software" instead of Lego's Spirit.ocx
  - [MindControl](http://web.archive.org/web/20020803004941/http://homepages.svc.fcj.hvu.nl/brok/legomind/robo/) <sup>↗</sup>
    + A Visual Basic program for controlling a Lego MindStorms RCX or Cybermaster unit
  - [NQCEdit](http://www.bitling.com/nqcedit.htm) <sup>↗</sup>
    + Little is currently known about this software; not even a website archive appears to have survived.

## Tools and Utilities
* [lvi: leJOS Visual Interface](https://github.com/BrickBot/lvi)
  - The leJOS Visual Interface is a skin over the command-line commands for the leJOS firmware. It also is a simple editor that can have many files open at once.
* [RCXDatalog](https://github.com/BrickBot/RCXDatalog)
  - A GUI-based Unix tool to interact with the Lego Mindstorms RCX brick. Using RCXDatalog, you can upload the datalog of the RCX and display it on your screen or print it to a PostScript printer. Plus, there are additional widgets to show light and touch sensor readings of the RCX.
* [Bound-T for the H8/300](https://github.com/BrickBot/Bound-T-H8-300)
  - A software tool that uses static analysis of machine code to compute upper bounds on the execution time (WCET) and stack usage of embedded programs

## Remote Control
* Windows
  - [JoyBricx](https://github.com/BrickBot/JoyBricx)
    + An application for remotely controlling Lego IR-controllable devices such as the RCX, Spybots, and Bionicle RC Fighter via a Lego IR tower using a joystick or game pad
  - [Dr. Vegetable’s Virtual Remote](https://web.archive.org/web/20161223173934/http://www.drvegetable.com/download_vremote.html) <sup>↗</sup>
    + A Windows program that emulates the LEGO MindStorms infrared remote control using your existing USB or RS-232 infrared tower
* Gnome
  - [BrickRC](https://github.com/BrickBot/BrickRC)
    + A simple Gnome application to remotely control the LEGO MindStorms RCX brick
* PalmOS
  - [PBrickLib](https://github.com/BrickBot/PBrickLib)
    + A shared library providing access to the Lego Mindstorms RCX controller brick (pbrick) using the Palm’s IrDA interface, allowing for applications from simple remote controls to complex applications using the Palm as a robot’s main processor and the RCX as an intelligent IO controller.
    + While not associated with this project, information has also been included about another PalmOS app for the RCX, Ellams Software’s Robotic Mover.
* Windows CE / Pocket PC
  - [WinCE-Cybercontrol](https://github.com/BrickBot/WinCE-Cybercontrol)
    + Control and manipulate the Lego MindStorms RCX and Lego Cybermaster from a Palm-size PC, Handheld PC, or Pocket PC system

## Extensions Built on the Lego Firmware
* [NQC (Not Quite C)](https://github.com/BrickBot/nqc): A programming language for several Lego MindStorms products, including the RCX, CyberMaster, and Scout
  - **Text-Based Programming**
    + [NQC-libs](https://github.com/BrickBot/nqc-libs)
      * A collection of NQC libraries from various sources, plus some programs as well as full NQC tutorial with accompanying code samples.
    + [Ada-MindStorms](https://github.com/BrickBot/Ada-Mindstorms)
      * An Ada to NQC translator for the Lego Mindstorms RCX
  - **Iconic/Visual Programming**
    + [VisualNQC](https://github.com/BrickBot/VisualNQC)  (formerly fUNSoftWare)
      * An iconic language tool for the Lego MindStorms RCX, which generates NQC code and can facilitate handling the NQC compilation and deployment processes, too.
    + [etURP](https://github.com/BrickBot/etURP)
      * A program to create NQC (Not Quite C) files for LEGO Mindstorms robots, using a powerful language and interface to access the full potential of the Lego MindStorms RCX.
    + [QtNQC](https://github.com/BrickBot/QtNQC)
      * Appears to be a UI for NQC (no project description provided)
    + [Tern](https://github.com/BrickBot/Tern)
      * A tangible computer language designed to provide a painless introduction to computer programming, creating programs for robots like the Lego MindStorms RCX (also supports NXT).
  - **Add-Ins Supporting NQC**
    + [nqc.vim](https://github.com/BrickBot/nqc.vim)
      * gVim Menus for NQC (Not Quite C, version 2.3 r1 and newer) for the Lego MindStorms RCX
* Visual Storms / Sharp Storms  ** _MISSING/WANTED_ **
  - **About**
    + A system capable of translate .NET executables in programs that can be executed on the Lego Mindstorms RCX without having to change its firmware
  - **Toolchain**
    + [CLIFileRW](https://github.com/BrickBot/CLIFileRW)
      * A .NET library developed for the CodeBricks research project that is specifically designed to read and rewrite .NET binaries and was used in conjuction with the Visual Storms / Sharp Storms projects
* [ASML: Asynchronous State Machine Language](https://github.com/BrickBot/ASML)
  - Execute Asynchronous State Machine (ASM) charts as RCX programs
* [Legolog](https://github.com/BrickBot/Legolog)
  - A Prolog-based system developed to allow experimentation with and demonstration of Cognitive Robotics research on the Lego MindStorms RCX
* [Lego/Scheme](https://github.com/BrickBot/Lego-Scheme)
  - An implementation of Scheme for the Lego MindStorms RCX
* [Mind Control](https://github.com/BrickBot/MindControl)
  - A Visual Basic program for controlling a Lego MindStorms RCX or Cybermaster unit
* [MostlyC](https://github.com/BrickBot/MostlyC)
  - A C-style language that includes a number of features not present in NQC: true subroutines, functions w/parameters, bool/float types, large const arrays, math library
* [SqLego](https://github.com/BrickBot/SqLego)
  - A little package for controling a Lego MindStorms RCX system directly from Squeak, inspired by the BotKit interface.
* [TclRCX](https://github.com/BrickBot/TclRCX)
  - An extension to the [Tcl interpreter](https://www.tcl.tk/) to let you issue commands to the RCX interactively or compile bytecode programs, download, and run them
* [pyRCX](https://github.com/BrickBot/pyRCX)
  - A collection of Python scripts and components for the Lego MindStorms RCX
* [AForge.NET](https://github.com/BrickBot/AForge.NET) **_Tethered Only; No Stand-Alone Capabilities_**
  - A C# framework designed for developers and researchers in the fields of Computer Vision and Artificial Intelligence - image processing, neural networks, genetic algorithms, machine learning, robotics, etc.
* [InteractiveVB](https://github.com/BrickBot/InteractiveVB) **_Tethered Only; No Stand-Alone Capabilities_**
  - Interactive control of a Lego Mindstorm RCX with Visual Basic
* [RCX Java API](https://github.com/BrickBot/RCX-Java-API) **_Tethered Only; No Stand-Alone Capabilities_**
  - A platform-independent Java library used to develop RCX applications
* [RCX.NET](https://github.com/BrickBot/RCX.NET) **_Tethered Only; No Stand-Alone Capabilities_**
  - Lets you use your favorite development environment (.NET) to send commands to your Lego MindStorms® RCX
* [RCXPort](https://github.com/BrickBot/RCXPort) **_Tethered Only; No Stand-Alone Capabilities_**
  - A Java interface to the Lego MindStorms RCX
* [VC++ Interface](https://github.com/BrickBot/VCpp-Interface) **_Tethered Only; No Stand-Alone Capabilities_**
  - A small direct interface that remote controls the RCX from within a Windows C program on the host computer
  - **Extensions**
    + [MSWBrick](https://github.com/BrickBot/MSWBrick)
      * Using the Lego MindStorms RCX with MSW Logo
      * Depends on and requires the Visual C++ interface provided by the [VC++ Interface](https://github.com/BrickBot/VCpp-Interface) project

## Extensions Built on Alternative Firmwares
* [librcx](https://github.com/BrickBot/librcx)
  - It would be fair to say that this represents the work that started it all for the RCX!
  - Intended to be a lowest-level driver for the Lego RCX, providing an interface between your C code and the RCX ROM, allowing you to easily explore the ROM interface.
* [BrickOS-Bibo](https://github.com/BrickBot/brickOS-bibo)
  - **About**
    + An alternative RCX operating system and firmware cloning brickOS. The kernel was written from scratch for better performance, but to the average brickOS programmer, changes should be transparent.  There is a lot of code borrowed from brickOS, and numerous patches originally targeted for brickOS have been conceptually incorporated.  While this project is based on bibo, as brickOS still seems to be the more recognizable name, it has been retained as part of the name.
    + Additional projects have added support for other programming languages, including the following::
      * C / C++  (_built-in_)
      * XS:Lisp  (_mostly built-in; additional work is needed to better support user programs_)
      * Esterel (_installation of binary prerequisties is necessary in order to compile programs for the RCX_)
      * Luster  (_currently a separate project_)
      * SCADE  (_currently a separate project_)
      * .NET  (_currently a separate project, [Lego.NET](https://www.dcl.hpi.uni-potsdam.de/research/lego.NET/)_)
  - **Add-ons and Extensions**
    + [scLego](https://github.com/BrickBot/scLego)
      * An Esterel back-end for Lego C with BrickOS-Bibo
      * Esterel demo programs are already included with BrickOS-Bibo; install the Esterel compiler and this back-end extension to be able to build and use them
  - ** Toolchain **
    + [binutils-cil](https://github.com/BrickBot/binutils-cil)
        * Used in conjunction with the gcc-cil project to add CIL capabilties, for use with brickOS-bibo and Lego.NET
    + [gcc-cil](https://github.com/BrickBot/gcc-cil)
        * An "official" gcc branch that adds CIL capabilities to gcc, for use with brickOS-bibo and Lego.NET
* [leJOS](https://github.com/BrickBot/leJOS-RCX)
  - **About**
    + A tiny Java Virtual Machine for the Lego MindStorms RCX, containing a VM for Java bytecodes and additional software to load and run Java programs.
    + Grew out of the [TinyVM project](https://github.com/BrickBot/TinyVM)
  - **APIs**
    + [leJOS-RCX-Alt-API](https://github.com/BrickBot/leJOS-RCX-Alt-API)
      * An alternative to part of the standard leJOS API designed to fit an objects-early approach to teaching programming
  - **IDE Add-Ins**
    + [leJOS Development Toolset for Eclipse](https://github.com/BrickBot/leJOS-RCX-Eclipse)
      * Eclipse plug-ins that simplify developing Java code for the Lego MindStorms RCX using the leJOS JVM, offering easy configuration through a project wizard and a preference page, using Eclipse code building, and adding RCX-specific operations both for firmware and byte-code download.
  - **Utilities**
    + [leJOS-RCX-Tools](https://github.com/BrickBot/leJOS-RCX-Tools)
      * A visual interface for leJOS. RCXDownload automatically sets the JDK-, leJOS- and ClassPaths, compiles the chosen Java-Source, shows the compiler messages and is able to link and load both the compiled classes and the leJOS-firmware.
    + [leJOS-RCX-MindStormsTools](https://github.com/BrickBot/leJOS-RCX-MindStormsTools)
      * A small toolkit to aid in the uploading of Java programs to LEGO MindStorms RCX bricks, providing functionality of the leJOS library in the development environment for this purpose
    + [leJOS-RCX-TextLCDApplet](https://github.com/BrickBot/leJOS-RCX-TextLCDApplet)
      * Java Applet GUI for testing josx.platform.rcx.TextLCD
* [pbForth](https://github.com/BrickBot/pbForth)
  - An incarnation of Forth that is designed to work with the LEGO MindStorms RCX brick as an alternative firmware for the RCX.
* [Asterix](https://github.com/BrickBot/Asterix)
  - A graphical user interface with support for real-time applications, built on top of a small, fast, and efficient real-time microkernel (RTOS)
* [colibri](https://github.com/BrickBot/colibri)
  - An Open Source RTOS Subset
* [ERIKA](https://github.com/BrickBot/erika)
  - E.R.I.K.A. Educational, an Embedded Real tIme Kernel Architecture for the Lego MindStorms RCX
* [LDCC](https://github.com/BrickBot/LDCC)
  - DCC capabilities for the Lego MindStorms RCX
* [OnScreenProgramming](https://github.com/BrickBot/OnScreenProgramming)
  - Facilitates programming a Lego Mindstorms RCX on its LCD screen via its View/Prgm buttons, without use of a computer
* [Quite C](https://github.com/BrickBot/QuiteC)
  - Quite C is intended to be a repackaging and reordering of a miniOS (no multitasking!) for the Lego RCX. It provides an interface between your C code and the ROM. The intent is to allow you to write very large programs in C language (neural and pathfinder programs like) with Microsoft Windows platform. LegOS is too Unixish ;)
  - Each program appears to be created as its own firmware (SREC) file
* [TinySoar](https://github.com/BrickBot/TinySoar)
  - An implementation of the Soar artificial intelligence architecture that is intended to run on memory constrained devices.
* [TinyVM](https://github.com/BrickBot/TinyVM)
  - A replacement firmware and VM that can execute Java programs in the Lego Mindstorms RCX, supporting several of the most useful features of the Java language.
  - Breaks the 32-variable limit imposed by the official Lego firmware (like other firmware replacements such as brickOS and pbForth also do)
  - No need to install a cross-compiler
  - The progenitor of [leJOS](https://github.com/BrickBot/leJOS)
* [tvm-rcx](https://github.com/BrickBot/tvm-rcx)
  - A Transterpreter Virtual Machine (TVM) wrapper for the Lego MindStorms RCX

## Communication
* [FaRCX](https://github.com/BrickBot/FaRCX)
  - Control Lego MindStorms RCX robots from afar (e.g. over the Internet)
* [RCX-IR](https://github.com/BrickBot/RCX-IR)
  - Communicate with the Lego RCX controller without the need of a Lego IR tower, converting between the IrDA and cIR protocols. Includes support for Java Native Interface (JNI).
* [perl-LEGO-RCX](https://github.com/BrickBot/perl-LEGO-RCX)
  - Communicate with the Lego MindStorms RCX brick from a workstation through the IR tower.
* [LINX](https://github.com/BrickBot/LINX)
  - Control a Lego robot via Perl scripts from a webserver or console
* [legoshrink](https://github.com/BrickBot/legoshrink)
  - A program for communicating via the IR tower with your Lego Robot (RCX brick) using the legOS Network Protocol (LNP)
* [lnphost](https://github.com/BrickBot/lnphost)
  - A library supporting IR communication over the Lego MindStorms IR tower. It can be used from C programs on Posix compliant platforms, supports multiple protocols and is designed to be a replacement for lnpd.
* [lnpd](https://github.com/BrickBot/lnpd)
  - The LegOS Network Protocol Daemon, which allows for communication between brickOS-powered robots and host computers.
* [WinLNP-USB](https://github.com/BrickBot/WinLNP-USB)
  - LNP over USB for Windows devices
* [RCX LNP LIB](https://github.com/BrickBot/RCX-LNP-LIB)
  - A DLL that ecapsulates LNP communication code, along with an example Visual Basic application
* [hubub](https://github.com/BrickBot/hubub)
  - A simple TCP data reflector for quickly building distributed applications. It can broadcast data from one client to many (or many to many) with little system overhead. Written in heavily commented 'c', with example clients in TCL.

## Emulators
A number of  the emulators support TCP communication in place of the IR communication.
While some tools have been updated to provide built-in support for TCP communication,
if you are using a tool that supports serial IR communication but not TCP communication,
it might be possible to use a null-modem emulator such as the [com0com project for Windows](http://com0com.sf.net/),
which includes both a com2tcp component as well as hub4com component.

Note that the program ir-server is included with the [BrickOS-Bibo project](https://github.com/BrickBot/brickOS-bibo)
and includes “echoing” that is meant to mimic the behavior of IR communication.
Additionally, there is also the [hubub](https://github.com/BrickBot/hubub) project that is included in this GitHub organization.

* [getROM](https://github.com/BrickBot/getROM)
  - Tools and utilities from dumping the ROM from an RCX, which is often then used by RCX emulators.
* [BrickEmu](https://github.com/BrickBot/BrickEmu)
  - An emulator for LEGO MindStorms RCX bricks. It emulates processor and peripherals, so it runs the original ROM code, firmware, and programs.
* [RCXSimulator](https://github.com/BrickBot/RCXSimulator)
  - A Java-based emulator of the Lego MindStorms RCX
* [Intellejos](https://github.com/BrickBot/Intellejos)
  - An RCX Simulator for LeJOS, based on the earlier Intellego project, for learning to program in Java using the LeJOS platform.
* [Intellego](https://github.com/BrickBot/Intellego)
  - A tool for experimenting with robotic control techniques, providing a framework which enables researchers to develop controller programs for the Lego MindStorms RCX in Java, and test them either in simulation or in a real RCX robot with no alteration to the controller code.
* [LegoSim](https://github.com/BrickBot/LegoSim)
  - A UNIX-based Simulator for LegOS/BrickOS with an Applet-GUI
* [EmuLegOS](https://github.com/BrickBot/EmuLegOS)
  - An emulator for the LegOS (BrickOS) operating system used on the Lego MindStorms RCX.

## Integrations
* [RCX-PI](https://github.com/BrickBot/RCX-PI)
  - An experimental API to integrate a Raspberry PI with a Lego MindStorms RCX by using smartphone sensors and cameras to allow seamless remote control and further robotics related development.


* * *

# Host OS Setup Help

## Windows
* [RCX USB Tower Support, by Lego Engineering](http://www.legoengineering.com/rcx-usb-tower-support/)
* [Philo’s Archive of Lego MindStorms RCX Updates](https://www.philohome.com/sdk25/sdk25.htm)
* [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/about)
  - To run graphical Linux applications if using the Ubuntu bash shell
    1. Install [VcXsrv X-server for Windows](http://vcxsrv.sf.net/)
    2. Configure bash to use the local X server by updating `~/.bashrc`
    3. Run `echo "export DISPLAY=localhost:0.0" >> ~/.bashrc` to append the update to the `~/.bashrc` file
    4. To make the changes take effect, restart bash or run `. ~/.bashrc`
    5. For additional details, see [Running Graphical Linux Applications on WSL](https://seanthegeek.net/234/graphical-linux-applications-bash-ubuntu-windows/)

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


* * *

# RCX Links and Resources
The links below are a mostly uncurated collection of RCX-related websites and postings.  To retrieve some links, it may be necessary to use [archive.org](archive.org).

## Communities
* [RCX Subforum on LUGNET](https://news.lugnet.com/robotics/rcx/)
* [r/mindstorms](http://mindstorms.reddit.com/): General to Lego MindStorms, but does include some RCX topics
* [“Bricks” StackExchange](https://bricks.stackexchange.com/): General to Lego, but does include some RCX discussion

## Information and FAQs
* [About the Lego MindStorms Robotics Invention System](https://web.archive.org/web/20060223231555/http://www.pulsar.org/archive/stormwatch/AboutLegoMindstorms.html)
* [Expanded MindStorms FAQ at MROB](http://www.mrob.com/pub/lego/msfaq.html)

## Assorted RCX Info
* [PBrick Info](https://pbrick.info/) (check the links in the website header and along the side, too, and not just the blog posts on the landing page)
* [Philo’s Home Page](https://www.philohome.com/)

## Human Interest
* [Geeks in Toyland](https://www.wired.com/2006/01/geeks-in-toyland/)
* [Is Iron Man an RCX Robot?](https://deeperdesign.wordpress.com/2010/02/26/is-iron-man-made-of-lego/)

## Technical Resources
[Additional list of RCX resources](http://user.it.uu.se/~tobiasa/lego-resources.html), some of which are no longer available without use of archive.org
* [RCX Internals](http://www.mralligator.com/rcx/)
  - [RCX Tools](http://www.mralligator.com/rcx/tools.html)
* [LEGO MINDSTORMS Internals](https://web.archive.org/web/20190816230906/http://www.crynwr.com/lego-robotics/)
* [RCX Manual](https://web.archive.org/web/20190703224522/http://legolab.daimi.au.dk/CSaEA/RCX/Manual.dir/RCXManual.html)
* [How to LNP](http://www.cs.brown.edu/courses/cs148/old/2004fall/brickOS/HOWTO/lnp.html)
* [Notes on LNP](https://web.archive.org/web/20040627230632/http://www.docs.uu.se/docs/undergrad/instances/spring2002/RTSystemDvpMnp/assignments/notes_on_lnp.html)
* [Lego RCX Firmware Disassembler](http://web.archive.org/web/20011029155757/http://www.geocities.com/ResearchTriangle/Thinktank/4411/)

## Sensors and Multiplexors
* [Philo: Lego MindStorms Compatible Sensor Devices](https://www.philohome.com/sensors.htm)
* [Compass Sensor](http://www.convict.lu/Jeunes/CompassSensor.htm)
* [Danny's Mindstorms Page](http://unitutor.unisi.it/~danny/)
* [Homebrew lego sensors](https://web.archive.org/web/20090106131819/http://www.stormyprods.com/lego/)
* [LEGO sensor page](http://www.barello.net/ARC/projects/LEGO/)
* [LePoMux](http://www.lepomux.org/)
* [Line Tracking Sensor From Sven Horstmann](http://www.extremenxt.com/linetrak.htm)
* [Michael Gasperi's LEGO Mindstorms Sensor Input Page](http://www.extremenxt.com/lego.htm)
* [Sensors](http://www.convict.lu/Jeunes/Sensors.htm)
* [TFM's Home Page](http://www.akasa.bc.ca/tfm/) – See the "My LEGO Workshop (MindStorms)" link for the following:
  - Temperature Sensor
  - Resisotr Switch pad
  - Motor/Light Block
  - Motor/Sensor Expander – 6 motor ports!

## Hardware Hacks
* [Cutting Electric Plates](http://www.abs-robotics.com/tips/electric/cutplate.htm)
* [IR_tower_japan](http://web.archive.org/web/20060207165221/http://oase.uci.kun.nl/~mientki/Lego_Knex/Lego_electronica/IR_tower/IR_tower.htm)
* [Lego Rotation Sensor Internals and Fix](http://www.philohome.com/sensors/legorot.htm)
* [RCX Power Booster Schematic](http://news.lugnet.com/robotics/?n=22861)
* [RCXCAM_Journal](http://www.convict.lu/Jeunes/RCXCam/RCXCam_Journal.htm)
* [Smeagol Sub-projects Mars rover](http://www.mobnets.rwth-aachen.de/smeagol/sub-mars.php)
* [Wireless Radio Communication](http://www.robotics.sk/maine.php?page=/projects/rcxbt/)

## Firmware/Languages Lists
* [Quick Start Guide](https://web.archive.org/web/20090502162540/http://www.ee.adfa.edu.au/staff/hrp/teaching/LegoMindstorm/LegoHelpHRP.html)
* [Old listing of various programming languages for the RCX, retrieved via archive.org](http://web.archive.org/web/20070411223240/http://club.lego.com/messageboards/ShowPost.aspx?PostID=390806)

## General GitHub Tips
* [Synchronizing a Fork](https://github.community/t5/How-to-use-Git-and-GitHub/Syncing-a-fork-leaves-me-one-commit-ahead-of-upstream-master/m-p/17711#M5346)


[StackOverflow-DetachFork]: # (https://stackoverflow.com/q/16052477)

[GitHub-DetachFork]: # (https://help.github.com/en/github/setting-up-and-managing-your-github-profile/why-are-my-contributions-not-showing-up-on-my-profile#commit-was-made-in-a-fork)

[Markdown-Comments]: # (https://stackoverflow.com/a/32190021)

[Private Download Link for Lego.NET]: # (http://www.dcl.hpi.uni-potsdam.de/research/lego.NET/download.htm?&uid=002dd0fd1cfe6c5608f41fc466b25aae)


* * *

# RCX Accessories

## Power
For RCX bricks with a power port, the Lego recommendation was their 9V AC Adapter part # 9833.

* * *

# Third-Party Vendors
This GitHub organization is not associated with any of these vendors in any way;
links are provided as a reference.  Note that the vendors might no longer be offering RCX-compatible components.

## Hardware
* [HiTechnic Products](http://www.hitechnic.com/)
* [Sensors for Lego NXT, RCX, and VEX Robots](http://www.techno-stuff.com/)
* [www.mindsensors.com](http://www.mindsensors.com/)

## Software
* [RCX PicoBlocks, by Playful Invention](https://www.playfulinvention.com/rcx/)
* [RoboLab for LabVIEW](http://www.legoengineering.com/robolab-for-labview/)
  - [LabVIEW](https://decibel.ni.com/content/docs/DOC-15615)

## General Lego
* [BrickLink](https://www.bricklink.com/)
