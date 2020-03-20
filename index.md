# Welcome to BrickBot!
The page provides an index to the repositories comprising the BrickBot organization, as well as links to related resources.

All projects imported to GitHub have been curated to varying degrees as part of the import process.
Please feel free to join and contribute in whatever way you can, whether that might be cleaning up
or updating documenation, converting text files to Markdown, setting up wikis, or updating code to
work with the latest host platforms.

The initial 60+ projects gathered under this BrickBot organization on GitHub were collected by Matthew Sheets.


## Disclaimer
Neither this organization nor any of its included projects are associated in any way with Lego or any other companies.  Follow [this link to access the official Lego MindStorms Website](http://mindstorms.lego.com/).

Some sites referenced only by link do not have a repository setup to due to identified redistribution restrictions.


## Notes
No known version of the Lego USB tower driver for 64-bit Windows is known to exist.
Conversely, there is not currenly a version of GitHub Desktop for 32-bit Windows.
For those wanting an alternative to GitHub Desktop that also provides a 32-bit distribution,
the open source [GitAhead](http://gitahead.com/) project is suggested.


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
* **Iconic/Visual Programming**
  - [VisualNQC](https://github.com/BrickBot/VisualNQC)
    + An iconic language tool for the Lego MindStorms RCX, which generates NQC code.
  - [actor-lab](https://github.com/BrickBot/actor-lab) **_Tethered Only; No Stand-Alone Capabilities_**
    + A parallel, object-orientated, iconic control language designed to introduce the ideas of control technology and robotics
* **Modeling and Implementation**
  - [Times Tool](http://www.timestool.com/) <sup>↗</sup>
    + A tool set for modelling, schedulability analysis, synthesis of (optimal) schedules and executable code, supporting system specification, system analysis and code generation for the LegoOS (now BrickOS-Bibo) platform

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
      * A collection of NQC libraries from various sources
    + [Ada-MindStorms](https://github.com/BrickBot/Ada-Mindstorms)
      * An Ada to NQC translator for the Lego Mindstorms RCX
  - **Iconic/Visual Programming**
    + [VisualNQC](https://github.com/BrickBot/VisualNQC)
      * An iconic language tool for the Lego MindStorms RCX, which generates NQC code.
    + [etURP](https://github.com/BrickBot/etURP)
      * A program to create NQC (Not Quite C) files for LEGO Mindstorms robots, using a powerful language and interface to access the full potential of the Lego MindStorms RCX.
    + [QtNQC](https://github.com/BrickBot/QtNQC)
      * Appears to be a UI for NQC (no project description provided)
    + [Tern](https://github.com/BrickBot/Tern)
      * A tangible computer language designed to provide a painless introduction to computer programming, creating programs for robots like the Lego MindStorms RCX (also supports NXT).
  - **Add-Ins Supporting NQC**
    + [nqc.vim](https://github.com/BrickBot/nqc.vim)
      * gVim Menus for NQC (Not Quite C, version 2.3 r1 and newer) for the Lego MindStorms RCX
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
* [BrickOS-bibo](https://github.com/BrickBot/brickOS-bibo)
  - An alternative RCX operating system and firmware that is a brickOS clone.  The kernel was written from scratch to give better performance, but to the average brickOS programmer, not much should change.  There is a lot of code borrowed from brickOS, and numerous patches originally targeted for brickOS have been conceptually incorporated.  While this project is based on bibo, as brickOS still seems to be the more recognizable name, it has been retained as part of the name.
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
* [pylnp](https://github.com/BrickBot/pylnp)
  - A Python extension for LNP that enables writing Python scripts on Linux that talk to LNP-compatible applications on the RCX via the IR link
* [WinLNP-USB](https://github.com/BrickBot/WinLNP-USB)
  - LNP over USB for Windows devices
* [RCX LNP LIB](https://github.com/BrickBot/RCX-LNP-LIB)
  - A DLL that ecapsulates LNP communication code, along with an example Visual Basic application

## Emulators
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
* [EmuLegOS}(https://github.com/BrickBot/EmuLegOS)
  - An emulator for the LegOS (BrickOS) operating system used on the Lego MindStorms RCX.

## Integrations
* [RCX-PI](https://github.com/BrickBot/RCX-PI)
  - An experimental API to integrate a Raspberry PI with a Lego MindStorms RCX by using smartphone sensors and cameras to allow seamless remote control and further robotics related development.


* * *

# RCX Accessories

## Power
For RCX bricks with a power port, the Lego recommendation was their 9V AC Adapter part # 9833.

* * *

# Host OS Setup Help

## Windows
* [RCX USB Tower Support, by Lego Engineering](http://www.legoengineering.com/rcx-usb-tower-support/)
* [Philo’s Archive of Lego MindStorms RCX Updates](https://www.philohome.com/sdk25/sdk25.htm)

## Linux
* [Linux Online - Lego Mindstorm with Linux Mini-HOWTO](http://www.linux.org/docs/ldp/howto/Lego/)
* [Using Lego Mindstorms on Ubuntu « Adrian Smith's Blog](http://www.17od.com/2013/01/13/using-lego-mindstorms-on-ubuntu/)
* [pnc-rcx Tools and programs for building programs for the Lego Mindstorms RCX 1.0 (Hitachi H8300)](https://github.com/pnc/rcx)
* Kernel Driver: [LegoUSB](http://legousb.sourceforge.net/) – This driver is now officially part of the Linux kernel as of Linux 2.6.1.

## Mac OS X
* [NQC on Mac OS X](https://github.com/Glitchbone/mindstorms-rcx-osx-tools)

## Raspberry Pi
* [Using NQC on a Raspberry Pi](https://minordiscoveries.wordpress.com/2014/01/20/using-nqc-on-a-raspberry-pi-to-program-a-lego-mindstorms-rcx-brick/)


* * *

# RCX Links and Resources
The links below are a mostly uncurated collection of RCX-related websites and postings.  To retrieve some links, it may be necessary to use [archive.org](archive.org).

## Information and FAQs
* [About the Lego MindStorms Robotics Invention System](https://web.archive.org/web/20060223231555/http://www.pulsar.org/archive/stormwatch/AboutLegoMindstorms.html)
* [Expanded MindStorms FAQ at MROB](http://www.mrob.com/pub/lego/msfaq.html)

## Assorted RCX Info
* [PBrick Info](https://pbrick.info/) (check the links in the website header and along the side, too, and not just the blog posts on the landing page)
* [Philo’s Home Page](https://www.philohome.com/)

## Human Interest
* [Geeks in Toyland](https://www.wired.com/2006/01/geeks-in-toyland/)

## Technical Resources
[Additional list of RCX resources](http://user.it.uu.se/~tobiasa/lego-resources.html), some of which are no longer available without use of archive.org
* [RCX Internals](http://www.mralligator.com/rcx/)
  - [RCX Tools](http://www.mralligator.com/rcx/tools.html)
* [LEGO MINDSTORMS Internals](https://web.archive.org/web/20190816230906/http://www.crynwr.com/lego-robotics/)
* [RCX Manual](https://web.archive.org/web/20190703224522/http://legolab.daimi.au.dk/CSaEA/RCX/Manual.dir/RCXManual.html)
* [How to LNP](http://www.cs.brown.edu/courses/cs148/old/2004fall/brickOS/HOWTO/lnp.html)
* [Notes on LNP](https://web.archive.org/web/20040627230632/http://www.docs.uu.se/docs/undergrad/instances/spring2002/RTSystemDvpMnp/assignments/notes_on_lnp.html)
* [Lego RCX Firmware Disassembler](http://web.archive.org/web/20011029155757/http://www.geocities.com/ResearchTriangle/Thinktank/4411/)

## Education
* [LEGO Education Home](http://www.lego.com/education/)
* [Lego Engineering Home](http://www.legoengineering.com/)
* [Mindstorms in Education](http://www.crynwr.com/lego-robotics/education.html)
* [NASA Robotics - Robotics Alliance Project](http://robotics.nasa.gov/)
   -[Robotics Curriculum Clearinghouse - Lesson Plans and Educational Resources](http://robotics.nasa.gov/rcc/)

## Robot Designs
* [Philo Designs](https://www.philohome.com/mindstorms.htm)
* [A Lego-robot with camera controlled by Matlab overview](http://web.abo.fi/fak/tkf/rt/robot/index.php?content=0)
* [Adder](http://web.archive.org/web/20010609003439/http://prelude.psy.umontreal.ca/~cousined/lego/1-Varia/adder/adder.html)
* [Andreas Junghans - Lego Mindstorms](http://www.lucid-cake.net/mindstorms/index_en.html)
* [Ben Jacksons Mindstorms Creations](http://www.ben.com/LEGO/rcx/)
* [Chattanooga Robotics Web Site - BOT-BOX](http://www.chattabot.org/botbox.html)
* [Creating a Spider Robot using LEGO-Mindstorms](http://web.archive.org/web/20080206072202/http://schalburg.homepage.dk/Spider/Spider.html)
* [Design and development of LEGO Mindstorms based nomadic services](http://telemedicine.ewi.utwente.nl/education/completed_master_assignments/vantol_small.pdf)
* [format c: Robots Rocket Launcher](http://www.formatc.somee.com/roborocket.asp)
* [JP Brown’s Serious LEGO](http://jpbrown.i8.com/)
* [Lego Mindstorms](http://www.marioferrari.org/lego_mindstorm.html)
* [LEGO Models and Robotics](http://www.hempeldesigngroup.com/lego/index.html)
* [Lego RCX LIDAR Station Isotopia](http://xenon.arcticus.com/lego-rcx-lidar-station)
* [Lego Robots Tips and Tricks](http://people.cs.uu.nl/markov/lego/tips/index.html)
* [Lego Technic Home page](http://www.mapageweb.umontreal.ca/cousined/lego/)
* [LIDAR Display for Lego RCX LIDARStation Isotopia](http://xenon.arcticus.com/lidar-display-lego-rcx-lidarstation)
* [Mark Crosbies Homepage](http://www.mastincrosbie.com/mark/lego/BrickOS/BrickOS.html)
* [Mark’s LEGO NXT Projects](http://mastincrosbie.com/Marks_LEGO_projects/LEGO_Projects.html)
* [Peter Smolders’ Lego Hexapod](https://www.petersmolders.net/projects/robots/lego-hexapod/)
* [RCX-Project](http://cs.uni-salzburg.at/~ck/teaching/ESE-Winter-2004/rcxrobot/)
* [Robert Munafos LEGO(r) Creations at MROB](http://www.mrob.com/pub/lego/)
* [The Straight and Narrow - OReilly Media](http://www.oreillynet.com/pub/a/network/2000/05/22/LegoMindstorms.html)
* [Three Speed Automatic Transmission](http://www.last-outpost.com/~malakai/lego/)

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
