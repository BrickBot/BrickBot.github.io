# Emulation of the LEGO MindStorms RCX
A number of the emulators support TCP communication in place of the IR communication.
While some tools have been updated to provide built-in support for TCP communication,
if you are using a tool that supports serial IR communication but not TCP communication,
it might be possible to use a null-modem or pseudo-terminal emulator
* On Window, try the [com0com project for Windows](http://com0com.sf.net/), which includes both a com2tcp component as well as hub4com component.
* On Linux, try `socat`  (e.g. `sudo apt-get install socat` on Debian/Ubuntu)
  + Start socat and leave it running
    - Serial-to-Serial exampple:
      - `socat -d -d PTY,raw,echo=0 PTY,raw,echo=0`
    - Serial-to-TCP Listener example:
      - `socat -d -d PTY,raw,echo=0 TCP4-LISTEN:<port>`
    - Serial-to-TCP Server exampple:
      - `socat -d -d PTY,raw,echo=0 TCP:<host>:<port>`
  + In scenarios where the IR echo might be expected, echo might need to be set to 1
    - If setting echo to 1 on one side, you will need to test which device echos, as the created pseudo devices are not always initialized in command-line order

Note that the program ir-server is included with the [BrickOS-Bibo project](https://github.com/BrickBot/brickOS-bibo)
and includes “echoing” that is meant to mimic the behavior of IR communication.
Additionally, there is also the [hubub](https://github.com/BrickBot/hubub) project that is included in this GitHub organization.

## Simulators & Emulators
### General Purpose Emulators
Should work with any RCX firmware.
* [BrickEmu](https://github.com/BrickBot/BrickEmu)
  + An emulator for LEGO MindStorms RCX bricks. It emulates processor and peripherals, so it runs the original ROM code, firmware, and programs.
  + IR communication is emulated over TCP, and interfacing with GDB is supported.
  + Works with any firmware, but includes additional support for BrickOS-like firmware, such as sideloading programs. 
* [RCXSimulator](https://github.com/BrickBot/RCXSimulator)
  + A Java-based emulator of the Lego MindStorms RCX, including support for GDB and for IR via pseudo-terminals or UDP.
  + Extra support for debugging capabilities, such as might be useful for OS/firmeware development.
### BrickOS Firmware Simulators
Simulates the behavior of the BrickOS firmware
* [LegoSim](https://github.com/BrickBot/LegoSim)
  + A UNIX-based Simulator for LegOS/BrickOS with an Applet-GUI
* [EmuLegOS](https://github.com/BrickBot/EmuLegOS)
  + An emulator for the LegOS (BrickOS) operating system used on the Lego MindStorms RCX.
### leJOS “World” Simulators
Simulates the behavior in a 2D world of an RCX running leJOS firmware
* [Intellejos](https://github.com/BrickBot/Intellejos)
  + An RCX Simulator for LeJOS, based on the earlier Intellego project, for learning to program in Java using the LeJOS platform.
* [Intellego](https://github.com/BrickBot/Intellego)
  + A tool for experimenting with robotic control techniques, providing a framework which enables researchers to develop controller programs for the Lego MindStorms RCX in Java, and test them either in simulation or in a real RCX robot with no alteration to the controller code.

## Emulator Tools & Utilities
* [getROM](https://github.com/BrickBot/getROM)
  + Tools and utilities for dumping the ROM from an RCX, which is often then used by RCX emulators.
