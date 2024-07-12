# Index of Projects for the LEGO MindStorms RCX

## Development Suites
* **Iconic/Visual Programming Environments**
  + [VisualNQC](https://github.com/BrickBot/VisualNQC)
    - An iconic language tool for the Lego MindStorms RCX
    - Generates NQC code as output, so can be used to transition from iconic program to text-based programming
    - Uses NQC to compile and deploy, which must also be installed
    - Written in Java, so runs on multiple platforms
    - Formerly known as fUNSoftware, it has been updated to better work with larger screen sizes
  + [actor-lab](https://github.com/BrickBot/actor-lab) **_Tethered Only; No Stand-Alone Capabilities_**
    - A parallel, object-orientated, iconic control language designed to introduce the ideas of control technology and robotics
  + [RoboLab for LabVIEW](http://www.legoengineering.com/robolab-for-labview/)
    - Commercial product released in collaboration with LEGO
    - [LabVIEW](https://decibel.ni.com/content/docs/DOC-15615)
    - [Installation and Setup Instructions](https://github.com/BrickBot/RoboLab)
  + [RCX PicoBlocks, by Playful Invention](https://web.archive.org/web/20230204110316/http://www.playfulinvention.com/rcx/)
    - Commercial product
    - Described as working only with Windows XP
* **Integrated Development Environments (IDEs)**
  + [RobotC](https://github.com/BrickBot/RobotC)
    - A powerful C-based programming language with a Windows environment for writing and debugging programs, and the only programming language at this level that offers a comprehensive, real-time debugger.
    - Includes its own version of firmware for the RCX
    - The last version that was released with RCX support is now available free of charge
  + [BricxCC](https://github.com/BrickBot/BricxCC/)
    - An IDE for the Lego MindStorms RCX, as well as the NXT, EV3, and HiTechnic SuperPro
    - Can work with NQC, BrickOS, and leJOS
  + [MacNQC](https://github.com/BrickBot/MacNQC)
    - A stand-alone version of the NQC compiler for the Macintosh OS
  + [Interactive C](https://web.archive.org/web/20171101054739/http://www.kipr.org/products/interactive-c) <sup>↗</sup>
    - Uses a modified version of ANSI C with several libraries and features that allow hobbyists to program small robotics platforms
    - Able to compile on the fly (c.f. [Wikipedia](https://en.wikipedia.org/wiki/Interactive_C))
  + [PRO-BOT](https://github.com/BrickBot/PRO-BOT)  **_Tethered Only; No Stand-Alone Capabilities_**
    - A program editor for the Lego MindStorms RCX programmable brick with the standard LEGO firmware, aimed at keeping a constant link between the PC and the brick
    - Bundles Phantom.dll with the installer
* **Modeling and Implementation**
  + [Times Tool](http://www.timestool.com/) <sup>↗</sup>
    - A tool set for modelling, schedulability analysis, synthesis of (optimal) schedules and executable code, supporting system specification, system analysis and code generation for the LegoOS (now BrickOS-Bibo) platform
* **Historical Reference Only / Superceded or No Longer Available**
  + [RCX Command Center](https://web.archive.org/web/20070204040037/http://www.cs.uu.nl/people/markov/lego/) <sup>↗</sup>
    - The predecessor to Bricx Command Center
  + [BrickCommand2](https://web.archive.org/web/20091023045530/http://www.geocities.com/Area51/Nebula/8488/lego.html) <sup>↗</sup>
    - A programming tool for Lego MindStorms RCX and Lego Cybermaster systems, offering more control over the brick than the software that comes with each system.
    - The setup installer was broken up into 3 separate zip file downloads, plus an additional update download; unfortunately, only 2 of the 3 setup zip files appear to have survived.
  + [PBrickDev](https://web.archive.org/web/20091024223614/http://geocities.com/pbrickdev/index.html)  <sup>↗</sup>
    - A complete programming environment for the RCX that used a graphical interface for programming, instead of writing code
    - The latest version used the Phantom.dll COM component by "Fenestra Software" instead of Lego's Spirit.ocx
  + [MindControl](http://web.archive.org/web/20020803004941/http://homepages.svc.fcj.hvu.nl/brok/legomind/robo/) <sup>↗</sup>
    - A Visual Basic program for controlling a Lego MindStorms RCX or Cybermaster unit
  + [NQCEdit](http://www.bitling.com/nqcedit.htm) <sup>↗</sup>
    - Little is currently known about this software; not even a website archive appears to have survived.

## Tools and Utilities
* [RCXDatalog](https://github.com/BrickBot/RCXDatalog)
  + A GUI-based Unix tool to interact with the Lego Mindstorms RCX brick. Using RCXDatalog, you can upload the datalog of the RCX and display it on your screen or print it to a PostScript printer. Plus, there are additional widgets to show light and touch sensor readings of the RCX.
* [Bound-T for the H8/300](https://github.com/BrickBot/Bound-T-H8-300)
  + A software tool that uses static analysis of machine code to compute upper bounds on the execution time (WCET) and stack usage of embedded programs

## Remote Control
* Windows
  + [JoyBricx](https://github.com/BrickBot/JoyBricx)
    - An application for remotely controlling Lego IR-controllable devices such as the RCX, Spybots, and Bionicle RC Fighter via a Lego IR tower using a joystick or game pad
  + [Dr. Vegetable’s Virtual Remote](https://web.archive.org/web/20161223173934/http://www.drvegetable.com/download_vremote.html) <sup>↗</sup>
    - A Windows program that emulates the LEGO MindStorms infrared remote control using your existing USB or RS-232 infrared tower
* Gnome
  + [BrickRC](https://github.com/BrickBot/BrickRC)
    - A simple Gnome application to remotely control the LEGO MindStorms RCX brick
* PalmOS
  + [PBrickLib](https://github.com/BrickBot/PBrickLib)
    - A shared library providing access to the Lego Mindstorms RCX controller brick (pbrick) using the Palm’s IrDA interface, allowing for applications from simple remote controls to complex applications using the Palm as a robot’s main processor and the RCX as an intelligent IO controller.
    - While not associated with this project, information has also been included about another PalmOS app for the RCX, Ellams Software’s Robotic Mover.
* Windows CE / Pocket PC
  + [WinCE-Cybercontrol](https://github.com/BrickBot/WinCE-Cybercontrol)
    - Control and manipulate the Lego MindStorms RCX and Lego Cybermaster from a Palm-size PC, Handheld PC, or Pocket PC system
* Web
  + [FaRCX](https://github.com/BrickBot/FaRCX)  ([original project](https://github.com/G33kDude/FaRCX) <sup>↗</sup>)
    - Control Lego MindStorms RCX robots from afar (e.g. over the Internet)

## Extensions Built on the Lego Firmware
* [NQC (Not Quite C)](https://github.com/BrickBot/nqc): A programming language for several Lego MindStorms products, including the RCX, CyberMaster, and Scout
  + **Text-Based Programming**
    - [NQC-libs](https://github.com/BrickBot/nqc-libs)
      * A collection of NQC libraries from various sources, plus some programs as well as full NQC tutorial with accompanying code samples.
    - [Ada-MindStorms](https://github.com/BrickBot/Ada-Mindstorms)
      * An Ada to NQC translator for the Lego Mindstorms RCX
  + **Iconic/Visual Programming**
    - [VisualNQC](https://github.com/BrickBot/VisualNQC)  (formerly fUNSoftWare)
      * An iconic language tool for the Lego MindStorms RCX, which generates NQC code and can facilitate handling the NQC compilation and deployment processes, too.
    - [etURP](https://github.com/BrickBot/etURP)
      * A program to create NQC (Not Quite C) files for LEGO Mindstorms robots, using a powerful language and interface to access the full potential of the Lego MindStorms RCX.
    - [QtNQC](https://github.com/BrickBot/QtNQC)
      * Appears to be a UI for NQC (no project description provided)
    - [Tern](https://github.com/BrickBot/Tern)
      * A tangible computer language designed to provide a painless introduction to computer programming, creating programs for robots like the Lego MindStorms RCX (also supports NXT).
  + **Add-Ins Supporting NQC**
    - [nqc.vim](https://github.com/BrickBot/nqc.vim)
      * gVim Menus for NQC (Not Quite C, version 2.3 r1 and newer) for the Lego MindStorms RCX
* [Visual Storms](https://web.archive.org/web/20070208030329/https://dotnet.di.unipi.it/MultipleContentView.aspx?code=161) / [Sharp Storms](https://web.archive.org/web/20070208175252/https://dotnet.di.unipi.it/MultipleContentView.aspx?code=106)
  + **[About](http://medialab.di.unipi.it/Project/visualstorms/resources.html)**
    - A system capable of translate .NET executables in programs that can be executed on the Lego Mindstorms RCX without having to change its firmware
    - Additional known information in this [LUGNET post](https://news.lugnet.com/robotics/rcx/?n=2963)
  + **Toolchain**
    - [CLIFileRW](https://github.com/BrickBot/CLIFileRW)
      * A .NET library developed for the CodeBricks research project that is specifically designed to read and rewrite .NET binaries and was used in conjuction with the Visual Storms / Sharp Storms projects
  + **UI Library**
    - [Magic Library](https://github.com/BrickBot/MagicLibrary): A user interface library for .NET
* [ASML: Asynchronous State Machine Language](https://github.com/BrickBot/ASML)
  + Execute Asynchronous State Machine (ASM) charts as RCX programs
* [Legolog](https://github.com/BrickBot/Legolog)
  + A Prolog-based system developed to allow experimentation with and demonstration of Cognitive Robotics research on the Lego MindStorms RCX
* [Lego/Scheme](https://github.com/BrickBot/Lego-Scheme)
  + An implementation of Scheme for the Lego MindStorms RCX
* [Mind Control](https://github.com/BrickBot/MindControl)
  + A Visual Basic program for controlling a Lego MindStorms RCX or Cybermaster unit
* [MostlyC](https://github.com/BrickBot/MostlyC)
  + A C-style language that includes a number of features not present in NQC: true subroutines, functions w/parameters, bool/float types, large const arrays, math library
* [SqLego](https://github.com/BrickBot/SqLego)
  + A little package for controling a Lego MindStorms RCX system directly from Squeak, inspired by the BotKit interface.
* [TclRCX](https://github.com/BrickBot/TclRCX)
  + An extension to the [Tcl interpreter](https://www.tcl.tk/) to let you issue commands to the RCX interactively or compile bytecode programs, download, and run them
* [pyRCX](https://github.com/BrickBot/pyRCX)
  + A collection of Python scripts and components for the Lego MindStorms RCX
* [Ghost.NET](https://github.com/BrickBot/Ghost.NET) **_Tethered Only; No Stand-Alone Capabilities_**
  + A .NET wrapper for Lego’s Ghost library, supporting tethered interaction with the RCX
  + Was originally part of AForge.NET, before being obsoleted and deprecated there
* [InteractiveVB](https://github.com/BrickBot/InteractiveVB) **_Tethered Only; No Stand-Alone Capabilities_**
  + Interactive control of a Lego Mindstorm RCX with Visual Basic
* [RCX Java API](https://github.com/BrickBot/RCX-Java-API) **_Tethered Only; No Stand-Alone Capabilities_**
  + A platform-independent Java library used to develop RCX applications
* [RCX.NET](https://github.com/BrickBot/RCX.NET) **_Tethered Only; No Stand-Alone Capabilities_**
  + Lets you use your favorite development environment (.NET) to send commands to your Lego MindStorms® RCX
* [RCXPort](https://github.com/BrickBot/RCXPort) **_Tethered Only; No Stand-Alone Capabilities_**
  + A Java interface to the Lego MindStorms RCX
* [VC++ Interface](https://github.com/BrickBot/VCpp-Interface) **_Tethered Only; No Stand-Alone Capabilities_**
  + A small direct interface that remote controls the RCX from within a Windows C program on the host computer
  + **Extensions**
    - [MSWBrick](https://github.com/BrickBot/MSWBrick)
      * Using the Lego MindStorms RCX with MSW Logo
      * Depends on and requires the Visual C++ interface provided by the [VC++ Interface](https://github.com/BrickBot/VCpp-Interface) project

## Extensions Built on Alternative Firmwares
* [librcx](https://github.com/BrickBot/librcx)
  + It would be fair to say that this represents the work that started it all for the RCX!
  + Intended to be a lowest-level driver for the Lego RCX, providing an interface between your C code and the RCX ROM, allowing you to easily explore the ROM interface.
* [Quite C](https://github.com/BrickBot/QuiteC)
  + Quite C is intended to be a repackaging and reordering of a miniOS (no multitasking!) for the Lego RCX. It provides an interface between your C code and the ROM. The intent is to allow you to write very large programs in C language (neural and pathfinder programs like) with Microsoft Windows platform. LegOS is too Unixish ;)
  + Each program appears to be created as its own firmware (SREC) file
* [BrickOS-Bibo](https://github.com/BrickBot/brickOS-bibo)
  + **About**
    - An alternative RCX operating system and firmware cloning brickOS. The kernel was written from scratch for better performance, but to the average brickOS programmer, changes should be transparent.  There is a lot of code borrowed from brickOS, and numerous patches originally targeted for brickOS have been conceptually incorporated.  While this project is based on bibo, as brickOS still seems to be the more recognizable name, it has been retained as part of the name.
    - Additional projects have added support for other programming languages, including the following::
      * C / C++  (_built-in_)
      * XS:Lisp  (_mostly built-in; additional work is needed to better support user programs_)
      * Esterel (_installation of binary prerequisties is necessary in order to compile programs for the RCX_)
      * Luster  (_currently a separate project_)
      * SCADE  (_currently a separate project_)
      * .NET  (_currently a separate project, [Lego.NET](https://www.dcl.hpi.uni-potsdam.de/research/lego.NET/)_)
  + **Add-ons and Extensions**
    - [scLego](https://github.com/BrickBot/scLego)
      * An Esterel back-end for Lego C with BrickOS-Bibo
      * Esterel demo programs are already included with BrickOS-Bibo; install the Esterel compiler and this back-end extension to be able to build and use them
  + **Toolchain**
    - [binutils-cil](https://github.com/BrickBot/binutils-cil)
      * Used in conjunction with the gcc-cil project to add CIL capabilties, for use with brickOS-bibo and Lego.NET
    - [gcc-cil](https://github.com/BrickBot/gcc-cil)
      * An "official" gcc branch that adds CIL capabilities to gcc, for use with brickOS-bibo and Lego.NET
* [leJOS](https://github.com/BrickBot/leJOS-RCX)
  + **About**
    - A tiny Java Virtual Machine for the Lego MindStorms RCX, containing a VM for Java bytecodes and additional software to load and run Java programs.
    - Grew out of the [TinyVM project](https://github.com/BrickBot/TinyVM)
  + **APIs**
    - [leJOS-RCX-Alt-API](https://github.com/BrickBot/leJOS-RCX-Alt-API)
      * An alternative to part of the standard leJOS API designed to fit an objects-early approach to teaching programming
  + **IDE Add-Ins**
    - [leJOS Development Toolset for Eclipse](https://github.com/BrickBot/leJOS-RCX-Eclipse)
      * Eclipse plug-ins that simplify developing Java code for the Lego MindStorms RCX using the leJOS JVM, offering easy configuration through a project wizard and a preference page, using Eclipse code building, and adding RCX-specific operations both for firmware and byte-code download.
  + **Tools & Utilities**
    - [leJOS-RCX-Tools](https://github.com/BrickBot/leJOS-RCX-Tools)
      * A visual interface for leJOS. RCXDownload automatically sets the JDK-, leJOS- and ClassPaths, compiles the chosen Java-Source, shows the compiler messages and is able to link and load both the compiled classes and the leJOS-firmware.
    - [leJOS-RCX-MindStormsTools](https://github.com/BrickBot/leJOS-RCX-MindStormsTools)
      * A small toolkit to aid in the uploading of Java programs to LEGO MindStorms RCX bricks, providing functionality of the leJOS library in the development environment for this purpose
    - [leJOS-RCX-TextLCDApplet](https://github.com/BrickBot/leJOS-RCX-TextLCDApplet)
      * Java Applet GUI for testing josx.platform.rcx.TextLCD
    - [lvi: leJOS Visual Interface](https://github.com/BrickBot/lvi)
      * The leJOS Visual Interface is a skin over the command-line commands for the leJOS firmware. It also is a simple editor that can have many files open at once.
  + **Support for More Current Java Versions**
    - [oversticht/lego-rcx-lejos](https://github.com/oversticht/lego-rcx-lejos) (external)
      * Based on leJOS v2.1 instead of v3.0-RC2 that is in the repository in this BrickBot organization
    - [HaikuVM](https://haiku-vm.sourceforge.net) / [Fork](https://github.com/chuckb/haikuVM) with [Gradle Plugin](https://github.com/chuckb/HaikuVMPlugin) (external)
      * A spinoff Java VM approach referenced by @oversticht
* [TinyVM](https://github.com/BrickBot/TinyVM)
  + A replacement firmware and VM that can execute Java programs in the Lego Mindstorms RCX, supporting several of the most useful features of the Java language.
  + Breaks the 32-variable limit imposed by the official Lego firmware (like other firmware replacements such as brickOS and pbForth also do)
  + No need to install a cross-compiler
  + The progenitor of [leJOS](https://github.com/BrickBot/leJOS)
* [pbForth](https://github.com/BrickBot/pbForth)
  + An incarnation of Forth that is designed to work with the LEGO MindStorms RCX brick as an alternative firmware for the RCX.
* [Asterix](https://github.com/BrickBot/Asterix)
  + A graphical user interface with support for real-time applications, built on top of a small, fast, and efficient real-time microkernel (RTOS)
* [colibri](https://github.com/BrickBot/colibri)
  + An Open Source RTOS Subset
* [ERIKA](https://github.com/BrickBot/erika)
  + E.R.I.K.A. Educational, an Embedded Real tIme Kernel Architecture for the Lego MindStorms RCX
* [LDCC](https://github.com/BrickBot/LDCC)
  + DCC capabilities for the Lego MindStorms RCX
* [OnScreenProgramming](https://github.com/BrickBot/OnScreenProgramming)
  + Facilitates programming a Lego Mindstorms RCX on its LCD screen via its View/Prgm buttons, without use of a computer
* [Pocket Programmer](https://github.com/BrickBot/PocketProgrammer/)
  + Greatly advanced the concept of [OnScreenProgramming](https://github.com/BrickBot/OnScreenProgramming)
  + Firmware is available but not the source code
* [TinySoar](https://github.com/BrickBot/TinySoar)
  + An implementation of the Soar artificial intelligence architecture that is intended to run on memory constrained devices.
* [tvm-rcx](https://github.com/BrickBot/tvm-rcx)
  + A Transterpreter Virtual Machine (TVM) wrapper for the Lego MindStorms RCX

## Communication
* [RCX-IR](https://github.com/BrickBot/RCX-IR)
  + Communicate with the Lego RCX controller without the need of a Lego IR tower, converting between the IrDA and cIR protocols. Includes support for Java Native Interface (JNI).
* [perl-LEGO-RCX](https://github.com/BrickBot/perl-LEGO-RCX)
  + Communicate with the Lego MindStorms RCX brick from a workstation through the IR tower.
* [LINX](https://github.com/BrickBot/LINX)
  + Control a Lego robot via Perl scripts from a webserver or console
* [legoshrink](https://github.com/BrickBot/legoshrink)
  + A program for communicating via the IR tower with your Lego Robot (RCX brick) using the legOS Network Protocol (LNP)
* [lnphost](https://github.com/BrickBot/lnphost)
  + A library supporting IR communication over the Lego MindStorms IR tower. It can be used from C programs on Posix compliant platforms, supports multiple protocols and is designed to be a replacement for lnpd.
* [lnpd](https://github.com/BrickBot/lnpd)
  + The LegOS Network Protocol Daemon, which allows for communication between brickOS-powered robots and host computers.
* [WinLNP-USB](https://github.com/BrickBot/WinLNP-USB)
  + LNP over USB for Windows devices
* [RCX LNP LIB](https://github.com/BrickBot/RCX-LNP-LIB)
  + A DLL that ecapsulates LNP communication code, along with an example Visual Basic application
* [hubub](https://github.com/BrickBot/hubub)
  + A simple TCP data reflector for quickly building distributed applications. It can broadcast data from one client to many (or many to many) with little system overhead. Written in heavily commented 'c', with example clients in TCL.

## Projects for Interacting with Other Devices
Some of these projects are currently hosted in external repositories but can be transferred or imported if there is interest
* [Power Functions Remote](https://github.com/BrickBot/PowerFunctions-Remote):  Use an RCX as a remote control for LEGO Power Functions 
* [RCX-PI](https://github.com/BrickBot/RCX-PI) (leJOS-based): an experimental API to integrate a Raspberry PI with a Lego MindStorms RCX by using smartphone sensors and cameras to allow seamless remote control and further robotics related development
* [RoboRemote](https://github.com/hanswannop/RoboRemote) <sup>↗</sup> (leJOS-based): Remotely contol an RCX using an attached smartphone, light sensors, leJOS, WebSockets, and Go
* [RemoteMindStorm](https://github.com/JSFernandes/RemoteMindstorm) <sup>↗</sup> (NQC-based):  Control an RCX via LeapMotion and voice, using a basic messaging scheme
  + Includes a number of binary *.jar and *.so files in version control
* [Rokenstorms: The Rokenbok/Mindstorms Radio Control Module Project](https://web.archive.org/web/20081219025330/http://www.stormyprods.com/lego/rokenbok.htm)


<!--

## TODO: Other projects, in additon to the section immediately above

* [Ultimate RoboLab](https://www.convict.lu/Jeunes/ultimate_stuff/Ultimate_intro.htm)
  + [Ultimate RoboLab Site (see also the "Download" tabs)](https://web.archive.org/web/20090727214457/https://www.ultimaterobolab.com/)

* [Use an Audio Output Jack to Send IR Commands](https://github.com/legokichi/webRCX)

* [UniBrick](https://github.com/JorgePe/UniBrick):  Universal LIRC controller for LEGO devices

* LeJOS-Derivative Projects Supporting More Current Java Versions
  + [oversticht/lego-rcx-lejos](https://github.com/oversticht/lego-rcx-lejos) (external)
    - Based on leJOS v2.1 instead of v3.0-RC2 that is in the repository in this BrickBot organization
    - See the main README for a discussion of running on more modern systems
  + [HaikuVM](https://haiku-vm.sourceforge.net) / [Fork](https://github.com/chuckb/haikuVM) with [Gradle Plugin](https://github.com/chuckb/HaikuVMPlugin) (external)
    - A spinoff Java VM approach referenced by @oversticht
* [Scratch for leJOS](https://github.com/swolla/scratch-lejos-rcx):  Create leJOS RCX programs using Scratch

* From Host Computer Setup on the [Quick Start Page](Quick-Start.md):
  +[pnc-rcx Tools and programs for building programs for the Lego Mindstorms RCX 1.0 (Hitachi H8300)](https://github.com/pnc/rcx)
  +[NQC on Mac OS X](https://github.com/Glitchbone/mindstorms-rcx-osx-tools)

-->
