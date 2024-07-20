# Grow the Legacy of the LEGO MindStorms RCX!

## Missing/Wanted
For a few projects known to exist, the source no longer seems to be available.  Might you have a copy?
If so, please let us know by [posting a new issue here](https://github.com/BrickBot/BrickBot.github.io/issues/new/choose)!
* [Pocket Programmer](https://www.navina.ch/workshop/rcx/rcx.html) <sup>↗</sup>
  + Greatly advanced the concept of [OnScreenProgramming](https://github.com/BrickBot/OnScreenProgramming)
  + Firmware is available but not the source code
* [MindStorms Tools](https://web.archive.org/web/20120130101715/http://ddi.uni-paderborn.de/index.php?id=4800&L=1), <sup>↗</sup>  which included the following individual tools:
  + Together MindstormsTool (TMT): module for the Together ControlCenter 4.0 or higher
  + BlueJ MindstormsTool (BJMT): extension for the BlueJ integrated environment 1.3 or higher
  + Java MindstormsTool (JMT): the MindstormsTool with an own source code editor
  + Small MindstormsTool (SMT): the stand alone version of the tool
* [Phantom](https://web.archive.org/web/20101213054842/http://members.cox.net/pbrick-alpha/Phantom.htm): An alterative to Spirit.ocx
* [RCXSimulator](https://www4.cs.fau.de/~felser/RCXSimulator/) <sup>↗</sup>
  - A Java-based emulator of the Lego MindStorms RCX, including support for GDB and for IR via pseudo-terminals or UDP

## Contribute to Projects
Interested in helping out?  Below are a few of the many ways that you can contribute.
1. Enhancment of existing projects
   + WebPBrick
     - [Blockly](https://developers.google.com/blockly/)
       * [Custom Blockly Blocks](https://developers.google.com/blockly/guides/create-custom-blocks/overview)
       * [Drop-Down Menus](https://developers.google.com/blockly/guides/create-custom-blocks/fields/built-in-fields/dropdown):  Includes supporting dynamic menus
       * [Procedures](https://developers.google.com/blockly/guides/create-custom-blocks/procedures/overview)
         + [Custom Procedure Blocks](https://developers.google.com/blockly/guides/create-custom-blocks/procedures/creating-custom-procedure-blocks)
     - Web
       * Flexbox:  [Support](https://caniuse.com/?search=flexbox) / [Documentation](https://www.w3.org/TR/css-flexbox-1/) / [Example](https://codepen.io/roy23/pen/QMZmZP)
       * [Golden Layout](https://golden-layout.com/):  IDE-style subwindows and tabs
       * [jQWidgets](https://jqwidgets.com/):  Tabs and movable splitters
         + [Use `collapse: false` on a div to prevent it from being collapsed over](https://jqwidgets.com/community/topic/how-to-change-the-splitter-behavior-to-toggle-on-its-default-side/)
       * [jQuery User Interface](https://jqueryui.com/):  Tabs
       * [WebPack](https://webpack.js.org/)
       * [Electron](https://www.electronjs.org/)
       * [GitHub Pages Publishing](https://github.com/marketplace/actions/upload-github-pages-artifact)
   + BrickOS - integrate support for additional programming languages from currently-separate projects
2. Packaging:  Looking to be able to support a reasonable cross-section of systems,
   including [openSUSE Tumbleweed (rolling)](https://search.opensuse.org/packages/),
   [Debian](https://packages.debian.org/index)/[Ubuntu](https://packages.ubuntu.com/)
   (Debian LEGO team [list](https://alioth-lists.debian.net/pipermail/debian-lego-team/)
   and [repos](https://salsa.debian.org/debian-lego-team/)),
   Windows (via Windows Subsystem for Linux), and Raspberry Pi.
   As reference, some of these packages had previously been created for the [SliTaz distribution](https://pkgs.slitaz.org/).
   Some specific projects to package include the following:
   + For Standard LEGO Firmware
     1. [NQC](https://github.com/BrickBot/nqc)
     2. [VisualNQC](https://github.com/BrickBot/VisualNQC)
     3. WebPBrick
   + For BrickOS Environment
     1. binutils 2.16.1 for h8300-hitachi-hms
     2. gcc 3.4.6 for h8300-hitachi-hms
     3. [binutils-cil](https://github.com/BrickBot/binutils-cil) for h8300-hitachi-hms
     4. [gcc-cil](https://github.com/BrickBot/gcc-cil) for h8300-hitachi-hms, with g++
     5. [brickOS-bibo](https://github.com/BrickBot/brickOS-bibo)  [Debian/Ubuntu also includes an old [lnpd package](https://packages.ubuntu.com/noble/lnpd)]
     6. [brickEmu](https://github.com/BrickBot/brickEmu)
     7. [gdb]() for h8300-hitachi-hms
     8. [gdb-dev]() for h8300-hitachi-hms
   + For Java / leJOS Environment
     1. [leJOS-RCX](https://github.com/BrickBot/leJOS-RCX)
     2. [Intellejos](https://github.com/BrickBot/Intellejos)
3. ReadMe/documentation cleanup and formatting:  The vast majority of these projects were developed before Markdown and GitHub conventions were developed
4. Testing/validation of projects on current platforms
5. Issues that have been filed within individual projects
