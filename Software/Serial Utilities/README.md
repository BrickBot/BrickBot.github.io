# Serial Utilities
While not directly related to the RCX, these utilities can be of use
in working with serial or USB Infrared towers and can even open up
new ways of interacting with an RCX via an IR tower.  Coupled with
IR-Server in the BrickOS-Bibo repository, a sampling of new scenarios
and capabilities include the following:
* Communicate with remote RCX devices
* Enable apps without USB serial support to use USB towers
* Enable apps without TCP serial support to work with emulators (which use TCP for their IR connection)
* Runs apps on a computer without driver support while connecting an IR tower to a computer with driver support

Due to driver signing issues that are known to exist with the releases posted
on the legacy SourceForge project site for these utilities, multiple different
versions of these releases have been posted here in [this folder](./).


As the [com0com SourceForge project](https://com0com.sourceforge.net/) has not been updated in quite some time,
below is a curated list of links to forks of one or more of the com0com sub-projects.
* Full suite (com0com, hub4com, com2tcp)
  + [datamancer](https://github.com/datamancer/com0com)
    - Updated projects to Visual Studio 2015 for all components
    - Includes selected patches and minor modifications
  + [Import from SourceForge with commit history](https://github.com/paulyc/com0com)
  + [Mirror](https://github.com/vovsoft/com0com) of binary uploads of releases of com0com v3.0.0 and hub4com v2.0.0 (the functionality of com2tcp can be replicated by appropriately configuring hub4com) 
* com0com only
  + [apal0934](https://github.com/apal0934/com0com): Refactored and updated for Visual Studio 2022 and WDK/SDK building processes
    - Notes fixing various issues
    - Enables 9-bit communication
  + [KangLin](https://github.com/KangLin/com0com): Updated for MSVC 2015 + WDK 10
  + [Import from SourceForge with commit history](https://github.com/tanvir-ahmed-m4/com0com)
* com2tcp only (NOTE: hub4com is capable of providing all the functionality of com2tcp)
  + [u-blox](https://github.com/u-blox/com2tcp): Updated to compile under Microsoft Visual Studio C++ 2017
* hub4com only
  + [hub4com-mingw](https://github.com/dogtopus/hub4com-mingw): A fork of hub4com that builds with MinGW
* Extensions and utilities
  + [NullModemEmulator](https://github.com/hsu-net/NullModemEmulator): A .NET library for interfacing with com0com ([NuGet package](https://www.nuget.org/packages/Hsu.NullModemEmulator))
  + [Com0com.Redirector](https://github.com/jiangfenglin/Com0com.Redirector): A GUI convenience app for com2tcp/hub4com with several forks (uncertain of the most current)
    - [Raggles](https://github.com/Raggles/Com0com.Redirector)
    - [datamancer](https://github.com/datamancer/MainPower.Com0com.Redirector): Latest updates are not as recent
  + [rskibbe.IO.Ports.Com.Virtual.Windows.Com0Com](https://github.com/robbelroot/rskibbe.IO.Ports.Com.Virtual.Windows.Com0Com): A helper library for working with com0com
  + [com0com Docker with Windows Container](https://github.com/mason-chase/docker-com0com-windows)
  + [comtrace2csv](https://github.com/tajfutas/comtrace2csv): Converts hub4com trace data to CSV
  + [ngrok4com](https://github.com/abakum/ngrok4com)
    - A hub4com GUI and KiTTY helper for configuring remote devices by serial port
	- Helps KiTTY communicate with a hub4com over firewalls via [ngrok.com](https://ngrok.com/)

Additionally, the [hubub project](https://github.com/BrickBot/hubub) (archived here under the BrickBot organization)
has the potential to offer additional TCP communication capabilities.
