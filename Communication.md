# Communication and the LEGO MindStorms RCX

## Projects Extending Communication Capabilities
* Virtual Serial Port Utilities:  For connection between different software suites, ensure RFC 2217 compliance for best compatibility
  + Windows
    - [com0com (open source)](https://github.com/BrickBot/Archive/releases/tag/com0com):  A suite of drivers and tools offering virtual serial ports, serial port redirection, and more.
      * The related hub4com project offers an RFC 2217 compliant mode
    - [HW VSP 3 (freeware single-port version)](https://www.hw-group.com/software/hw-vsp3-virtual-serial-port):  A software driver that adds a virtual serial port (e.g. COM5)
      to the operating system and redirects the data from this port via a TCP/IP network to another hardware interface, which is specified by its IP address and port number.
      * Supports RFC 2217
      * Can run standalone or as a service
  + Windows Subsystem for Linux
    - [Serial COM Connections with WSL v1](https://www.hanselman.com/blog/connect-to-a-device-over-serial-com-port-on-windows-10-with-wsl1-tty-devices-with-windows-terminal-and-minicom)
  + Linux – [StackOverflow Post](https://stackoverflow.com/q/52187)
    - [ser2net (open source)](https://github.com/cminyard/ser2net):  A program for allowing connections between gensio accepters and gensio connectors
      * Generally, this would be a network connections to serial ports or IPMI Serial Over Lan (SOL) connections, but there are lots of gensios and lots of options. See gensio(5) for information on gensios.
      * Docker container support is available.
      * Supports RFC 2217 via the telnet gensio.
    - [cyclades-serial-client (open source)](http://cyclades-serial.sourceforge.net/):  Creates a virtual serial port which connects to the server over a network.
      * The [inverse of ser2net](https://github.com/cminyard/ser2net#using)
    - [sercd (open source)](http://sercd.sourceforge.net/):  An RFC 2217-compliant serial port redirector for sharing a serial port through a network.
    - [tty0tty (open source)](https://github.com/lcgamboa/tty0tty):  A Linux null-modem emulator  [no RFC 2217 compliance noted]
    - [Remserial (open source)](http://lpccomp.bc.ca/remserial/):  Acts as a communications bridge between a TCP/IP network port and a Linux device such as a serial port.
    - [unmerged socat patch (open source)](http://www.dest-unreach.org/socat/contrib/socat-rfc2217.html):  A patch for socat adding RFC 2217 compliance
    - [VSPDL](https://tibbo.com/support/downloads/vspdl.html):  Virtual Serial Port Driver for Linux
  + Cross-platform
    - [Perle TruePort](https://www.perle.com/downloads/trueport.shtml):  Redirects serial COM/TTY based traffic over Ethernet to remote IOLAN(s).
  + Inter-platform Connections
    - [Connecting to Serial Port (COM port) over a Network](https://gist.github.com/DraTeots/e0c669608466470baa6c)
      * Info specific to com0com driver status is outdated; please refer to the com0com link above for better installers.
* Virtual "IR Reflectors" / TCP Hubs
  + [ir-server host utility in BrickOS-Bibo](https://github.com/BrickBot/brickOS-bibo/):  Communicate between physical, remote, and/or multiple virtual RCX devices and hosts.
  + [hubub](https://github.com/BrickBot/hubub):  A simple TCP data reflector for quickly building distributed applications. It can broadcast data from one client to many (or many to many) with little system overhead.


## LNP: The LegOS Network Protocol
* [How to LNP](http://www.cs.brown.edu/courses/cs148/old/2004fall/brickOS/HOWTO/lnp.html)
* [Notes on LNP](https://web.archive.org/web/20040627230632/http://www.docs.uu.se/docs/undergrad/instances/spring2002/RTSystemDvpMnp/assignments/notes_on_lnp.html)

## Communicating across the LEGO Ecosystem
* LEGO IR Sniffing
  + [Decoding Old LEGO Infrared Protocols](https://ofalcao.pt/blog/2017/decoding-old-lego-infrared-protocol)
  + [Decoding the RCX Infrared Command Protocol](https://ofalcao.pt/blog/2017/decoding-rcx-ir-command-protocol)
* LEGO Visual Light Link (VLL)
  + [Visual Light Link Programming the LEGO Micro Scout with the RCX](http://www.elecbrick.com/vll/)
    - RCX 2.0 firmware includes support for sending VLL commands
* LEGO Binonicle
  + [RCX Control of Bionicle 8539 Manas Receivers](https://web.archive.org/web/20080510121133/http://www.doucettenet.com/lego/manas.pdf)

## Hardware Hacks for RCX Communication
[BrickOS-Bibo Patch # 33](https://news.lugnet.com/robotics/rcx/legos/?n=4057), incorporated by Matthew Sheets, included Bluetooth-facilitating capabilities
* [Serial IR Tower Hacks](http://web.archive.org/web/20060207165221/http://oase.uci.kun.nl/~mientki/Lego_Knex/Lego_electronica/IR_tower/IR_tower.htm)
* [Board-Soldering Communication Hacks](http://www.convict.lu/Jeunes/RCXCam/RCXCam_Journal.htm)

### Radio Frequency (RF) Wireless
* [Wireless RCX IR Tower](https://www.eurobricks.com/forum/index.php?/forums/topic/42828-wireless-rcx-ir-tower/)
* [Smeagol Sub-projects Mars rover](https://web.archive.org/web/20080324192255/http://www.mobnets.rwth-aachen.de/smeagol/sub-mars.php)
* [Wireless Radio Communication via Bluetooth](http://www.robotics.sk/maine.php?page=/projects/rcxbt/)
* [Hardware Hacks to Setup a Bluetooth Connection](https://web.archive.org/web/20051207031919/http://www-date.uni-paderborn.de/pub/people/dasas/Beh03.pdf)  (_in German_)
