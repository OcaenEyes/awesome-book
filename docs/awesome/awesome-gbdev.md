<div class="github-widget" data-repo="gbdev/awesome-gbdev"></div>
## ![GameboyIcon](http://i.imgur.com/ROUq7NT.gif) Awesome Game Boy Development

#### [Join us on Discord](https://discord.gg/tKGMPNr) [![Discord Badge](https://img.shields.io/badge/dynamic/json.svg?label=chat&colorB=green&suffix=%20online&query=presence_count&uri=https://discordapp.com/api/guilds/303217943234215948/widget.json)](https://discord.gg/tKGMPNr)

精选的 Game Boy（彩色）开发资源、工具、文档、相关项目和开源 ROM. 灵感来自 [awesome](https://github.com/sindresorhus/awesome) 列出事情.

您可以找到此列表的（更酷的）网络版本 [here](https://gbdev.github.io/resources).


- [Introduction](#introduction)
  - [Disambiguation](#disambiguation)
- [Community](#community)
- [Documentation](#documentation)
  - [Misc](#misc)
  - [Opcodes](#opcodes)
  - [Game Boy Color](#game-boy-color)
  - [Hardware](#hardware)
  - [Peripherals](#peripherals)
  - [Cartridges](#cartridges)
- [Emulator Development](#emulator-development)
  - [Testing](#testing)
- [Software Development](#software-development)
  - [Assemblers](#assemblers)
  - [Compilers](#compilers)
    - [Experimental/Proof of Concepts](#experimentalproof-of-concepts)
  - [Emulators](#emulators)
  - [Tools](#tools)
    - [Engines](#engines)
    - [Development tools](#development-tools)
    - [Graphics utilities](#graphics-utilities)
    - [Hardware and ROM utilities](#hardware-and-rom-utilities)
    - [Music drivers and trackers](#music-drivers-and-trackers)
- [Programming](#programming)
  - [ASM](#asm)
    - [Sources](#sources)
    - [Timings](#timings)
    - [Boilerplates](#boilerplates)
    - [Syntax highlighting packages](#syntax-highlighting-packages)
  - [C](#c)
- [Homebrews](#homebrews)
  - [ASM](#asm-1)
  - [C](#c-1)
  - [GB Studio](#gb-studio) 
  - [Demos](#demos)
- [Reverse Engineering](#reverse-engineering)
  - [Game Disassemblies](#game-disassemblies)
- [Game Boy Camera](#game-boy-camera)
  - [Retrieving Images](#retrieving-images)
  - [Changing the camera's behavior](#changing-the-cameras-behavior)
  - [Post-processing](#post-processing)
- [Related projects](#related-projects)
  - [Directories](#directories)
  - [Websites](#websites)
- [About](#about)
  - [Contribute](#contribute)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)
  - [Sponsors](#sponsors)

## Introduction

- [The Game Boy, a hardware autopsy](https://www.youtube.com/playlist?list=PLu3xpmdUP-GRDp8tknpXC_Y4RUQtMMqEu)
- [The Ultimate Game Boy Talk](https://media.ccc.de/v/33c3-8029-the_ultimate_game_boy_talk)


> ### Disambiguation
>
> #### Game Boy Advance
>
&gt; Game Boy Advance 开发由另一个项目涵盖， [awesome-gbadev](https://github.com/gbdev/awesome-gbadev) 列表.
 &gt; 但是，GBA *可以运行* GB/GBC 游戏. 与本机硬件相比，它以稍微不同的方式执行此操作：此列表的模拟器开发部分对此进行了介绍.
>
> #### Game Boy Color and Super Game Boy
>
&gt; 此列表专注于原始的 *Game Boy*（GB 或 DMG，1989），*Game Boy Color*（GBC 或 CGB）和 *Super Game Boy* (SGB) 是非常相似的系统，有一些重要的区别，例如：
>
&gt;- 不同的硬件规格；
&gt;- 特定的硬件和软件功能；
&gt;- 特定寄存器；
&gt;- 特定的错误、怪癖和可利用的行为.
>
&gt;如果您的目标是为 SGB 或 GBC 开发您的软件，或者您想知道它如何在其他系统上运行，您可能想利用并适应这些差异，请查看 [Game Boy Color](#game-boy-color) 类别并查找对 GBC/CGB 和 SGB 的具体参考.


## Community

- [Chat channels](https://gbdev.io/chat)
- [Forum](https://gbdev.gg8.se/forums/)

## Documentation

- [**Pan Docs**](https://gbdev.github.io/pandocs/)  - 向公众提供的 Game Boy 的单一、最全面的技术参考. 由社区更正、更新和维护.
- [The Cycle-Accurate Game Boy Docs](https://github.com/AntonioND/giibiiadvance/blob/master/docs/TCAGBD.pdf) - AntonioND 的精确文档，用于制作周期精确的 Game Boy 模拟器.
- [Complete Technical Reference](https://gekkio.fi/files/gb-docs/gbctr.pdf) - 通过 Gekkio.
- [Game Boy Architecture: A Practical Analysis](https://www.copetti.org/writings/consoles/game-boy/) - 罗德里戈·科佩蒂 (Rodrigo Copetti).
- [Game Boy Project Report](http://www.cs.columbia.edu/~sedwards/classes/2019/4840-spring/reports/GameBoy.pdf) - 硬件报告 [emulator](https://github.com/kitsuneh/SVGameBoy) （在 Terasic DE1-SoC 板上）作为哥伦比亚大学 CSEE4840 嵌入式系统设计课程的最终项目开发.

#### Opcodes

- [gb-opcodes](https://gbdev.github.io/gb-opcodes/optables/) - 操作码表
- [RGBDS opcodes reference](https://rgbds.gbdev.io/docs/gbz80.7) - 所有指令的参考，包括简短说明、周期和字节计数以及标志修改的解释.

### Game Boy Color

- [Bootstrap ROM](https://tcrf.net/Game_Boy_Color_Bootstrap_ROM)
- [Unused Palettes](https://tcrf.net/Notes:Game_Boy_Color_Bootstrap_ROM)
- [Colorization palettes in the BIOS](https://forums.nesdev.com/viewtopic.php?p=114388&sid=c3d4ce08cfd9d9c834958d4f148750c3#p114388)
- [Boot ROM Disassembly](https://gist.github.com/drhelius/6063265)
- [GBC Hicolour notes](https://romhack.github.io/doc/gbcHiColour/) - 关于 Game Boy Color 的 Hicolour 模式技巧及其在 GBC 游戏“Crystalis”中的实现的技术说明.

### Hardware

- [DMG Schematics](http://gbdev.gg8.se/wiki/articles/DMG_Schematics) - 硬件原理图.
- [The Game Boy Project](http://marc.rawer.de/Gameboy/Docs/GBProject.pdf) - 提供有关实现三个 8 位双向并行端口的硬件和详细结构信息的研究.
- [Related custom hardware](https://github.com/Gekkio/gb-hardware) - 通过 Gekkio.
- [ESP8266 GB Dev Board](https://github.com/applefreak/esp8266-gameboy-dev-board) - 用于 Game Boy 配件开发的开发板，由 ESP8266 提供支持.
- [ESP8266 GB Printer](https://github.com/applefreak/esp8266-gameboy-printer) - 模拟 GB 打印机并允许您使用 WiFi 检索图像的设备.
- [fruttenboel](http://verhoeven272.nl/fruttenboel/Gameboy/index.html) - 包含大量硬件信息的页面、用于与控制台和其他相关项目交互的自定义​​板.
- [Game Boy hardware database](https://gbhwdb.gekkio.fi/) - 各种类型的 Game Boy 控制台的数据和照片.
- [dmg-schematics](https://github.com/msinger/dmg-schematics)  - DMG-CPU B 芯片的原理图和带注释的覆盖图，从芯片照片中提取，使用 KiCad 制作. 还包含 Electric VLSI 库，其中包含一些单元和存储器的布局.

### Peripherals

- [Dan Docs](https://shonumi.github.io/dandocs.html) - 模糊的 Game Boy 硬件文档.
- [Edge of Emulation](https://shonumi.github.io/articles.html) ，一系列关于模拟和研究 Game Boy 配件的文章. 也可作为 [technical documents](https://github.com/shonumi/gbe-plus/tree/master/src/docs/technical) 在 GBE 仿真器文档中.
  - [Mobile Adapter GB](https://shonumi.github.io/articles/art14.html) - Game Boy Color 上的互联网连接和 DLC.
  - [The Game Boy Printer](https://shonumi.github.io/articles/art2.html)
  - [Pocket Sonar](https://shonumi.github.io/articles/art13.html) - 带有内置声纳硬件的蓝色手推车.
  - [Zok Zok Heroes](https://shonumi.github.io/articles/art8.html)  - Zok Zok Heroes 的 Full Changer，一种运动激活的配件.
  - [Infrared Madness](https://shonumi.github.io/articles/art11.html) - Game Boy Color 上的红外通信.
  - [Game Boy 4-Player Adapter](https://shonumi.github.io/articles/art9.html) - DMG-07.
  - [Barcode Boy](https://shonumi.github.io/articles/art7.html) - 第一个 Game Boy 卡片扫描仪.
  - [Barcode Taisen Bardigun](https://shonumi.github.io/articles/art6.html) - 90 年代后期的 DMG-GBC 条码阅读器.
- [DMG-07 Technical Documentation](https://raw.githubusercontent.com/shonumi/gbe-plus/master/src/docs/technical/DMG_07.txt)
- [Game Boy Camera RE](https://github.com/AntonioND/gbcam-rev-engineer) - 有关 GB 相机和用于使用 Arduino 对其进行逆向工程的工具的文档.
- [Creating photo realistic images with neural networks and a Gameboy Camera](http://www.pinchofintelligence.com/photorealistic-neural-network-gameboy/)
- [The Game Boy Printer](https://shonumi.github.io/articles/art2.html) - 关于打印机硬件、通信协议和游戏用于实现打印功能的常用例程的深入技术文档.
- [Ben Heck Reverse Engineers Game Boy Printer](https://www.youtube.com/watch?v=43FfJvd-YP4) （勘误表：使用过的热敏纸已过期，实际可打印 4 种颜色）.
- [Arduino Game Boy Printer Emulator](https://github.com/mofosyne/arduino-gameboy-printer-emulator) - 通过带有 Arduino 的 Game Boy Link 电缆模拟 Game Boy 打印机.
- [Mobile Game Boy Adapter](https://bulbapedia.bulbagarden.net/wiki/Mobile_Game_Boy_Adapter)
- [GB KISS LINK MODEM](http://nectaris.tg-16.com/GB-KISS-LINK-FAQ-hudson-gameboy-nectaris.html)

### Cartridges

- [GB Flash Cartridges for Sale](https://bbbbbr.github.io/GameBoy-Flash-Carts/) - 可用的现成 Game Boy Flash 墨盒列表.
- [AntonioND's docs](https://github.com/AntonioND/giibiiadvance/tree/master/docs) - 更正了有关墨盒头数据的示意图和信息.
- [Gekkio's Game Boy cartridge types](http://gekkio.fi/blog/2015-02-14-mooneye-gb-gameboy-cartridge-types.html) - 现有墨盒类型的概述.
- Gekkio 的墨盒分析：
  - [DMG-BEAN-02](http://gekkio.fi/blog/2015-05-18-mooneye-gb-cartridge-analysis-dmg-bean-02.html);
  - [MBC1](http://gekkio.fi/blog/2015-05-17-mooneye-gb-cartridge-analysis-fortress-of-fear.html);
  - [no MBC](http://gekkio.fi/blog/2015-02-28-mooneye-gb-cartridge-analysis-tetris.html).
- Tauwasser 的 wiki 上某些墨盒类型的引出线、寄存器描述和 VHDL 代码：
  - [MBC1](https://wiki.tauwasser.eu/view/MBC1)
  - [MBC2](https://wiki.tauwasser.eu/view/MBC2)
  - [MMM01](https://wiki.tauwasser.eu/view/MMM01)
- [Game Boy Cartridges Schematics](http://www.devrs.com/gb/files/gb.html) - MBC2 和 MBC3 类型的示意图.
- [Cartridges PCB photos](https://imgur.com/a/D5bpC)
- [MBC1+RAM+Battery cartridge Schematic](http://www.devrs.com/gb/files/mbc1.gif) - Jeff Frohwein 的第一张示意图.
- [MBC1 and MBC2 cartridges circuits](http://fms.komkon.org/GameBoy/Tech/Carts.html) - 以及这些 MBC 库如何切换和控制 RAM 的说明.
- [GB Rom List](CartridgeList.csv) - 发布的每款游戏的导航表及其卡带的详细信息.
- [Game Boy cartridge PCB photos](http://gekkio.fi/blog/2016-03-19-game-boy-cartridge-pcb-photos.html)


#### Custom cartridges

- [Emulating a GameBoy Cartridge](https://dhole.github.io/post/gameboy_cartridge_emu_1/) - 使用开发板 STM32F4 模拟 Game Boy 卡带的功能.
- [Wolf](http://www.happydaze.se/wolf/) - 带协处理器的 Game Boy 卡带.
- [Homebrew-Gameboy-Cartridge](https://github.com/dwaq/Homebrew-Gameboy-Cartridge) - 使用 Atmel AT49F040 作为 ROM 的盒式 PCB 的 Eagle 库、原理图和电路板文件.
- [Homebrew Gameboy Color Cartridge](https://github.com/Xyl2k/Gameboy-Color-Cartridge) - EEPROM 驱动盒的电路板布局.
- [Nekocart](https://github.com/zephray/NekoCart-GB) - 使用 Xilinx CPLD 作为 MBC5 的开源闪存盒（[Post](https://hackaday.io/project/41160-nekocart-cpld-gameboy-cartridge)).
- [Reiner Ziegler's Game Boy page](http://reinerziegler.de.mirrors.gg8.se/)  - 商业和自制的可编程墨盒和编程系统. 提供教程、接线和原理图.
- [Gameboy-MBC5-MBC1-Hybrid](https://github.com/insidegadgets/Gameboy-MBC5-MBC1-Hybrid) - MBC5/MBC1 混合墨盒的 CPLD 实现.

#### Misc

- [Introduction to Game Boy Hacking](http://pepijndevos.nl/sha2017/workshop.pdf) - 介绍基本组装、调试和逆向工程的研讨会.
- [GBSOUND.txt](https://github.com/bwhitman/pushpin/blob/master/src/gbsound.txt) - 详细介绍 Game Boy 声音引擎的文档.
- [gbdev FAQs](http://www.devrs.com/gb/files/faqs.html) - 必须由 Jeff Frohwein 阅读.
- [Game Boy Bootrom](http://www.neviksti.com/DMG/DMG_ROM.asm) - 评论了 DMG bootrom 的转储.
- [Differences between the Z80 and the gameboy's processor](http://www.z80.info/z80gboy.txt)
- [Gameboy 2BPP Graphics Format](http://www.huderlem.com/demos/gameboy2bpp.html) - 有关 Game Boy 如何将 VRAM 磁贴数据解释为彩色像素的信息.

## Emulator Development


- [Reverse Engineering fine details of Game Boy hardware](https://www.youtube.com/watch?v=GBYwjch6oEE) - Gekkio 在 Disobey 2018 上的 43 分钟演讲（[errata](https://gekkio.fi/blog/2018-02-05-errata-for-reverse-engineering-fine-details-of-game-boy-hardware.html)).
- [Emulation of Nintendo Game Boy](https://github.com/Baekalfen/PyBoy/blob/master/PyBoy.pdf) - 从构建模拟器的角度概述 Game Boy 硬件.
- [DMG-01](https://rylev.github.io/DMG-01/public/book/)  - Rust 中的教育性 Gameboy 模拟器和解释其开发的配套书籍.  *[Oh Boy! Creating a Game Boy Emulator in Rust](https://media.ccc.de/v/rustfest-rome-3-gameboy-emulator)- 是在 Rust Fest 18 上就​​此发表的演讲.
- [Building a Game Boy emulator in JavaScript](http://imrannazar.com/gameboy-Emulation-in-JavaScript) - 一步一步的教程.
- [Writing a Game Boy emulator, Cinoop](https://cturt.github.io/cinoop.html)
- [0dmg](https://jeremybanks.github.io/0dmg/2018/05/23/getting-started.html) - 通过构建部分 Game Boy 模拟器来学习 Rust.
- [RealBoy Emulator](https://realboyemulator.wordpress.com/posts/) - 关于 RealBoy 模拟器的设计和实现的一系列帖子.
- [Codeslinger](http://www.codeslinger.co.uk/pages/projects/gameboy.html) - 另一个系列的帖子记录了模拟器的构建.
- [Why did I spend 1.5 months creating a Gameboy emulator?](http://blog.rekawek.eu/2017/02/09/coffee-gb/) - 博客文章.
- [binjgb rewind](https://binji.github.io/2017/12/31/binjgb-rewind.html) - 实施 *rewind- 功能.
- [binjgb on the web](https://binji.github.io/2017/02/26/binjgb-on-the-web-part-1.html) - 将 binjgb 模拟器移植到 Web Assembly. [(Part 2)](https://binji.github.io/2017/02/27/binjgb-on-the-web-part-2.html)
- [binjgb debugging hangs](https://binji.github.io/2017/05/03/debugging-hangs.html) - 对仿真怪癖的调查.
- [Decoding Gameboy Z80 opcodes](https://gb-archive.github.io/salvage/decoding_gbz80_opcodes/Decoding%20Gamboy%20Z80%20Opcodes.html) - 如何通过算法解码 Game Boy 指令（而不是编写一个巨大的 switch-case 语句）.
- [Porting a GO Game Boy emulator to WebAssembly](https://djhworld.github.io/post/2018/09/21/i-ported-my-gameboy-color-emulator-to-webassembly/)
- [About swotGB](https://mitxela.com/projects/swotgb/about) - 关于用 JavaScript 开发 Game Boy 模拟器的说明.
- [List of open source emulators](EMULATORS.md)
- [Game Boy Doctor](https://github.com/robert/gameboy-doctor)  - 一个命令行工具，用于将来自您的模拟器的日志与来自已知正确的模拟器的日志进行比较. 对于 Blargg 的测试 ROM 的逐行调试很有用.

### Testing

- [Blargg's test roms](http://gbdev.gg8.se/files/roms/blargg-gb-tests/)
- [Gekkio's test roms](https://gekkio.fi/files/mooneye-gb/latest/)
- [SameSuite](https://github.com/LIJI32/SameSuite)
- [Mealybug Tearoom Tests](https://github.com/mattcurrie/mealybug-tearoom-tests)
- [GB Accuracy Tests](http://tasvideos.org/EmulatorResources/GBAccuracyTests.html)
- [144p Test Suite](https://github.com/pinobatch/240p-test-mini/tree/master/gameboy) - 将 Artemio Urbina 的 240p 测试套件移植到 Game Boy.
- [MBC3 RTC test ROM](https://github.com/aaaaaa123456789/rtc3test)
- [dmg-acid2](https://github.com/mattcurrie/dmg-acid2) 和 [cgb-acid2](https://github.com/mattcurrie/cgb-acid2) - 基本 PPU 渲染测试.

## Software Development

The [Choosing tools for Game Boy development](https://gbdev.io/guides/tools.html) 文章概述了 Game Boy 的可用开发工具.

### Assemblers

- [RGBDS](https://github.com/gbdev/rgbds) - 汇编程序和链接程序包. [Documentation](https://rgbds.gbdev.io/docs/).
- [ASMotor](https://github.com/csoren/asmotor)  - 针对 Game Boy 和其他 CPU 的汇编引擎和开发系统. 由原 RGBDS 作者撰写. [Documentation](https://github.com/asmotor/asmotor/tree/develop#further-reading).
- [wla-dx](https://github.com/vhelin/wla-dx) - 另一个 GB-Z80/Z80/... 多平台交叉汇编程序包. [Documentation](http://www.villehelin.com/wla.txt).

### Compilers

- [GBDK](https://github.com/gbdk-2020/gbdk-2020/)  - 由更新版本的 SDCC 工具链提供支持的 GBDK（Game Boy 开发工具包）得到维护和现代化. 提供 C 编译器、汇编器、链接器和一组库. 
  - [API docs: Getting Started](https://gbdk-2020.github.io/gbdk-2020/docs/api/docs_getting_started.html)
  - [Examples](https://github.com/mrombout/gbdk_playground)
  - [Documentation, links and tools](https://gbdk-2020.github.io/gbdk-2020/docs/api/docs_links_and_tools.html)
- [Turbo Rascal Syntax Error](https://lemonspawn.com/turbo-rascal-syntax-error-expected-but-begin/) - 用于为 8 / 16 位计算机系列开发游戏/演示的完整套件（IDE、编译器、编程语言、资源编辑器），包括 Game Boy 和 Game Boy Color.

#### Experimental/Proof of Concepts

- [RGBDS-Live](https://daid.github.io/rgbds-live/) - 用于试用 RGBDS 的浏览器内编码环境.
- [Wiz](https://github.com/wiz-lang/wiz) - 一种高级汇编语言，用于在复古控制台平台（Game Boy、NES、Atari 2600 等）上编写自制软件.
- [gbforth](https://github.com/ams-hackers/gbforth) - 基于 Forth 的 Game Boy 开发工具包.
- [gbasm-rs](https://gitlab.com/BonsaiDen/gbasm-rs) - 用于 Game Boy z80 汇编代码的基于 Rust 的固执己见的编译器.
- [gbasm](https://github.com/BonsaiDen/gbasm) - 用于 Game Boy z80 汇编代码的基于 JavaScript 的编译器.
- [tniASM](http://www.tni.nl/products/tniasm.html) - 宏汇编器.
- [Assembler](https://github.com/ulrikdamm/Assembler) - 用 Swift 编写的汇编程序.
- [llvm-gbz80](https://github.com/Bevinsky/llvm-gbz80) / [clang-gbz80](https://github.com/Bevinsky/clang-gbz80) - 到 GBZ80 CPU 的 Clang/LLVM 端口（类似于已弃用 [euclio/llvm-gbz80](https://github.com/euclio/llvm-gbz80)).
- [gbdk-go](https://github.com/pokemium/gbdk-go)  - 编译器将 Go 程序翻译成 C 代码. 输出的C代码通过GBDK内置到GB ROM中.

### Emulators

- [BGB](https://bgb.bircd.org/)  - 强大的模拟器和调试器. 提供准确的硬件仿真.
- [SameBoy](https://github.com/LIJI32/SameBoy) - 精确的模拟器，具有广泛的强大调试功能.
- [Mooneye GB](https://github.com/Gekkio/mooneye-gb) - Rust 中的研究项目和模拟器.
- [mGBA](https://github.com/mgba-emu/mgba) - 现代跨平台 GBA 模拟器，也可以运行 GB/GBC 游戏.
- [Binjgb](https://github.com/binji/binjgb)  - 通过大部分测试的 5Kloc 模拟器.  *倒带功能. 使用 WebAssembly 在浏览器中运行.
- [Gambatte](https://github.com/gb-archive/gambatte) - 跨平台和准确的模拟器.

- [MetroBoy](https://github.com/aappleby/MetroBoy) - 整个 Game Boy 的可玩电路级模拟.
- [gbe-plus](https://github.com/shonumi/gbe-plus) - 一个最近重写的模拟器，它在保留晦涩配件的功能方面付出了巨大的努力（例如 IR 链接、Mobile Network GB、Barcode Boy、GB Printer、本地和在线 GB Serial Link Cable，...）
- [Emulicious](https://emulicious.net/) - 提供准确的仿真并包括强大的工具，例如分析器和 ASM 和 C 的源代码级调试，通过 [VS Code debug adapter](https://marketplace.visualstudio.com/items?itemName=emulicious.emulicious-debugger).

[Complete list of open source emulators](EMULATORS.md)

### Tools

#### Engines

- [ZGB](https://github.com/Zal0/ZGB) - 用于为原始 Game Boy 创建游戏的小引擎（扩展 gbdk，更多信息 [here](http://zalods.blogspot.com/2017/01/zgb-little-engine-for-game-boy.html)).
- [Retr0 GB](https://bitbucket.org/HellSuffering/retr0-gb/) - 用于创建游戏的引擎（扩展 GBDK）.

#### Development tools

- [GBExtended](https://www.tensi.eu/thomas/programming/utilities/gbx_library/gbx_library.html) - 扩展 gbdk 的 C 库.
- [gbdk-lib-extension](https://github.com/ProGM/gbdk-lib-extension) - Michael Hope 的 Game Boy 开发工具包的一小部分资源和工具.
- [Dot Matrix Game Editor](http://www.dotmatrixgame.com/) - 用于 Game Boy 编程的 IDE，使用名为 GBL 的类 C 语言，具有许多其他功能，如瓦片和地图提取、WLA-DX 汇编等.
- [mgbdis](https://github.com/mattcurrie/mgbdis) - 具有 RGBDS 兼容输出的 Game Boy ROM 反汇编程序.
- [ROM Header Utility](http://catskull.net/GB-Logo-Generator/) - 检查和修改 ROM 标头数据（包括徽标）的在线工具.
- [romusage](https://github.com/bbbbbr/romusage)  - 用于从 .map、.noi 或 ihx 文件估算 Game Boy ROM 使用情况（可用空间）的命令行工具. 适用于 GBDK-2020 和 RGBDS.
- [awake](https://github.com/devdri/awake) - 游戏男孩反编译器.
- [Game Boy Text Tools](https://github.com/raphaklaus/gameboy-text-tools) - 用 Node.js 编写的用于文本操作和翻译 Game Boy ROM 的工具集.
- [evscript](https://github.com/eievui5/evscript) - 用于 Game Boy 的脚本语言，可用于敌方 AI、对话、动画和协程.
- [evunit](https://github.com/eievui5/evunit) - 汇编代码的单元测试程序.
- [opcode_count](https://github.com/rondnelson99/opcode_count) - 使用 Python 和 Emulicious 生成关于哪些 CPU 指令最常运行的统计数据

#### Graphics utilities

- [Game Boy Tile Data Generator](https://github.com/chrisantonellis/gbtdg) - HTML5 / JS 网络应用程序，可将位图图像转换为适合在基于图块的图形应用程序（特别是 GB）中使用的十六进制数据.
- [Harry Mulder's GB Development](http://www.devrs.com/gb/hmgd/intro.html) - Game Boy Tile Designer (GBTD) 和 Game Boy Map Builder (GBMB) 工具的一些来源和主页.
- [GBTiles](https://github.com/bashaus/gbtiles) - 将使用 Harry Mulder&#39;s Tile Designer (GBTD) 创建的 .GBR 文件和使用 Harry Mulder&#39;s Map Builder (GBMB) 创建的 .GBM 文件转换为不同的格式，以用于 Game Boy 和 GBDK.
- [bmp2cgb](https://github.com/gitendo/bmp2cgb) - 用于 Game Boy Color 开发的图形转换器，提供实时调色板调整.
- [png2gb](https://github.com/LuckyLights/png2gb) - 将图像文件转换为 game boy .c 数组的 CLI 工具.
- [GB-convert](https://github.com/exezin/gb-convert) - Game Boy 磁贴转换和地图编辑器工具（转换为组件）.
- [brewtool](http://make.vg/brewtool/) - 原始编辑器/转换器工具的集合，用于制作用于自制 ROM 开发的资产.
- [vtGBte](https://github.com/paul-arutyunov/vtGBte) - 一个简约的 ncurses 磁贴编辑器.
- [tpp1](https://github.com/TwitchPlaysPokemon/tpp1) - 自定义 GB/GBC 内存/硬件映射器的定义和规范，作为 MBC 的功能超集.
- [libstdgb](https://github.com/delwink/libstdgb) - 有用的 Game Boy 操作 (SDCC) 的 AC 库.
- [Tilemap GB](https://github.com/bbbbbr/gimp-tilemap-gb) - 用于导入和导出 GBMB 和 GBTD tilemaps 和 tilesets（作为位图图像或 .GBM/.GBR 文件）的 GIMP 图像编辑器插件.
- [Tilemap Helper](https://github.com/bbbbbr/gimp-tilemap-helper) - 用于优化瓦片地图和瓦片集的 GIMP 图像编辑器插件.
- [Tilemap Studio](https://github.com/Rangi42/tilemap-studio)  - 用于 Game Boy、Color、Advance 和 SNES 项目的拼贴图编辑器. 用 FLTK 用 C++ 编写. 
- [Superfamiconv](https://github.com/Optiroc/SuperFamiconv) - 灵活且可组合的图块图形转换器，支持 Super Nintendo、Game Boy、Game Boy Color、Game Boy Advance、Mega Drive 和 PC Engine 格式.

#### Hardware and ROM utilities

- [cart-dumper](https://github.com/Palmr/cart-dumper) - Game Boy Cartridge Dumper ROM.
- [gbcamextract](https://github.com/jkbenaim/gbcamextract) - 从 Game Boy 相机保存中提取照片.
- [Game Boy LCD sniffing](https://github.com/svendahlstrand/game-boy-lcd-sniffing) - 使用逻辑分析仪嗅探 Game Boy 的 LCD.
- [swapdump](https://github.com/sanqui/swapdump) - Game Boy flashcarts 的诊断实用程序.
- [Gameboy-LinkUp](https://github.com/JustinLloyd/Gameboy-LinkUp) - Game Boy LinkUp 串行电缆联网项目.

#### Music drivers and trackers

- [DevSound](https://github.com/DevEd2/DevSound) - 可嵌入自制程序中的声音驱动程序，支持脉冲宽度操作、琶音和多波形.
- [Carillon Player](http://gbdev.gg8.se/files/musictools/Aleksi%20Eeben/Carillon%20Editor.zip) - 音乐引擎.
- [GBT PLAYER](https://github.com/AntonioND/gbt-player) - 音乐播放器库和转换器套件.
- [mmlgb](https://github.com/SimonLarsen/mmlgb) - Nintendo Game Boy 的 MML 解析器和 GBDK 声音驱动程序.
- [XPMCK](https://github.com/bazzinotti/XPMCK) - 基于 MML 的音乐编译器，支持 Game Boy 和 Game Boy Color.
- [GBSoundSystem](https://github.com/gbdev/GBSoundSystem) - 用于 GameBoy Tracker（又名 Paragon 5 音乐播放器）的现代化音频驱动程序.
- [hUGETracker](https://github.com/SuperDisk/hUGETracker) - 基于 OpenMPT 的音乐跟踪器，专注于易用性、紧凑输出和自制游戏中的可嵌入性.
- [CBT-FX](https://github.com/datguywitha3ds/CBT-FX) - 兼容FX-Hammer音效的GBDK-2020音效驱动.

## Programming

使用指南中描述的开发工具链为 Game Boy 开发软件的指南、教程和工具 [Software Development](#software-development) 章节.

### ASM

- **[gb asm tutorial](https://eldred.fr/gb-asm-tutorial)** - 分步教程，构建多个 ROM 以配合其解释.
- [ASMSchool](http://gameboy.mongenel.com/asmschool.html) - Duo 提供的一组关于 GB/GBC 汇编编码和反汇编的课程.
- [hardware.inc](https://github.com/tobiasvl/hardware.inc) - 标准包含文件，其中包含用于 RGBDS 项目的 Game Boy 硬件定义.
- [Assembly tutorial by David Pello](https://gb-archive.github.io/salvage/tutorial_de_ensamblador/tutorial_de_ensamblador_la_decadence.html)  - 学习为 gb 生成工作 asm 代码的好文档. 许多重要主题的简要说明. 许多带有注释源代码的示例.
- [assemblydigest](https://github.com/assemblydigest/gameboy) - 探索 Game Boy 编程技术：
  - [Making an Empty Game Boy ROM (in Wiz)](http://assemblydigest.tumblr.com/post/77203696711/tutorial-making-an-empty-game-boy-rom-in-wiz)
  - [Making Art for the Game Boy](http://assemblydigest.tumblr.com/post/77404621743/tutorial-making-art-for-the-game-boy)
- [Beginner's Guide to Reverse Engineering GB](http://web.archive.org/web/20150511145100/http://www.bennvenn.com/Beginners_Guide_To_Reverse_Engineering.htm) - 一些关于拆卸和逆向工程的入门技巧.
- [FlappyBoy: Making a simple Game Boy Game](http://voidptr.io/blog/2017/01/21/GameBoy.html)
- [Super Game Boy development](https://imanoleasgames.blogspot.no/2016/12/games-aside-1-super-game-boy.html) - 一步一步的教程来实现 Super Game Boy 功能（框架和调色板）.
- [GameBoy programming tutorial: Hello World!](https://peterwynroberts.wordpress.com/2014/05/11/gameboy-programming-tutorial-hello-world/) - 一步一步的教程.
- [DMGreport](https://github.com/lancekindle/DMGreport) - 汇编游戏编程教程.
- [OAM DMA tutorial](https://gbdev.gg8.se/wiki/articles/OAM_DMA_tutorial) - 如何在汇编中使用 OAM DMA 的示例.
- [Game Boy Assembly Programming for the Modern Game Developer](https://github.com/ahrnbom/gbapfomgd) - 一本关于在 Assembly 中制作 Game Boy 游戏的电子书.

#### Sources

代码片段、效果、概念证明和通常不完整的游戏.

- [dev'rs ASM section](http://www.devrs.com/gb/asmcode.php) - 许多工作演示和资源.
- [EmmaEwert's experiments](https://github.com/EmmaEwert/gameboy)  - 原型程序的集合，大部分只是玩玩. 其中包括日光效果、透明度和天气效果.
- [DeadCScroll](https://github.com/gb-archive/DeadCScroll) - 关于如何使屏幕摆动以及其他“光栅效果”的详细教程

#### Timings

- [Nitty Gritty Gameboy Cycle Timing](http://blog.kevtris.org/blogfiles/Nitty%20Gritty%20Gameboy%20VRAM%20Timing.txt)
- [Mode3 Sprite Timing](https://www.reddit.com/r/EmuDev/comments/59pawp/gb_mode3_sprite_timing/)
- [GameBoy Color DMA-Transfers v0.0.1](http://gameboy.mongenel.com/dmg/gbc_dma_transfers.txt)
- [STAT interrupt timings](http://gameboy.mongenel.com/dmg/istat98.txt)
- [Video Timing](https://github.com/jdeblese/gbcpu/wiki/Video-Timing)

#### Boilerplates and libraries

- [rgbds-template](https://github.com/nezticle/rgbds-template) - Basic hello-world example for Game Boy using RGBDS.
- [Game Boy Assembly Language Primer](http://www.devrs.com/gb/files/galp.zip) - 带有内存定义、复制例程和 IBM 字体 tilemap 的简单模板代码.
- [bootstrap.gb](https://github.com/yenatch/bootstrap.gb) - 一个 Game Boy 项目示例.
- [Gameboy Boilerplate](https://github.com/junebug12851/GameboyBoilerplateProj) - 样板项目可以更快地进入游戏的实际汇编代码.
- [GingerBread](https://github.com/ahrnbom/gingerbread)  - 用于制作您自己的 Game Boy 游戏的软件库. 它是为了与书一起使用 [Game Boy Assembly Programming for the Modern Game Developer](https://github.com/ahrnbom/gbapfomgd) 这也兼作文档.
- [gb-vwf](https://github.com/ISSOtm/gb-vwf) - 打印可变宽度文本的库，附带一个演示.
- [gb-boilerplate](https://github.com/ISSOtm/gb-boilerplate) - 用于启动 Game Boy 项目的模板，为基础设施提供 Makefile.
- [gb-starter-kit](https://github.com/ISSOtm/gb-starter-kit) - 对上述内容的扩展，包括基础库代码以及更快上手.
- [gb-template](https://github.com/gb-archive/gb-template) - 具有手柄输入、DMA 传输和地图/瓦片数据加载等基本功能的模板.

#### Syntax highlighting packages

- [gbz80-highlight](https://github.com/ISSOtm/gbz80-highlight) - Notepad+- 和 gedit 用于 RGBDS 汇编的语法高亮文件.
- [Vim syntax file for the Game Boy assembler RGBASM](http://www.vim.org/scripts/script.php?script_id=819) - RGBDS 汇编的 Vim 语法突出显示.
- [Vim syntax file for RGBDS](https://github.com/Leandros/dotfiles/blob/master/.vim/syntax/rgbds.vim) - 另一个用于 RGBDS 汇编的 Vim 语法高亮文件.
- [sublime-rgbds](https://packagecontrol.io/packages/RGBDS) - 用于 RGBDS 的 Sublime Text 3 包，包括语法突出显示和一些完成片段.
- [Z80 Assembly support for Visual Studio Code](https://github.com/Imanolea/z80asm-vscode)
- [rgbds-vscode](https://github.com/DonaldHays/rgbds-vscode) - Visual Studio Code language extension for RGBDS GBZ80 Assembly.
- [rgbds-mode](https://github.com/japanoise/rgbds-mode) - 用于 RGBDS 汇编的 Emacs 主要模式.

### C

- [8-Bit Wonderland](https://github.com/gb-archive/salvage/blob/master/misc/8bit_wonderland.pdf) - 关于 Game Boy 如何工作以及如何开始为其开发工作代码的精心编写的介绍性文档.
- [Grooves Game Boy Programming](https://github.com/gbdk-salvage/grooves-game-boy-programming) - 一套完整的关于在 Game Boy 游戏中实现各种游戏机制的课程.
- [How to Write a Simple Side Scrolling Game](http://pastebin.com/F3tHLj68) - 旧的（但仍然相关的）教程.
- [Just another simple tutorial](http://pastebin.com/gzT47MPJ)
- [GBDK Tutorial](https://refreshgames.co.uk/2016/04/18/gameboy-tutorial-rom/) - 用于 GBDK 入门的相当小的游戏演示.
- [GBDK Sprite](http://gbdev.gg8.se/wiki/articles/GBDK_Sprite_Tutorial) - 展示了一个让多个精灵显示和制作动画的工作流程.
- [GBDK Color](http://gbdev.gg8.se/wiki/articles/GBDK_Color_Tutorial) - 通过为精灵、背景和窗口层添加颜色，扩展您对 Game Boy 基本精灵的了解.
- [GBDK Joypad](http://gbdev.gg8.se/wiki/articles/GBDK_Joypad_Tutorial) - 详细介绍了使用 GBDK 的手柄.
- [Game Boy home of Flavor](https://web.archive.org/web/20210427064949/www.personal.triticom.com/~erm/GameBoy/) - 一些完整的游戏和资源.
- [GBDK Configuring and Programming Tutorial](https://videlais.com/2016/07/03/programming-game-boy-games-using-gbdk-part-1-configuring-programming-and-compiling/) - 配置 GBDK、使用图块、碰撞精灵、GBTD、GBMB、内存管理和 ROM Banking.
- [Simplified GBDK examples](https://github.com/mrombout/gbdk_playground)
- [GBDK Programming Video Tutorials](https://www.youtube.com/playlist?list=PLeEj4c2zF7PaFv5MPYhNAkBGrkx4iPGJo) - 一系列视频教程，向初学者介绍如何使用 GBDK 进行编程.
- [Larold's Jubilant Junkyard](https://laroldsjubilantjunkyard.com/tutorials/) - 详细的基于 GBDK-2020 的教程合集.

## Homebrews

完整的开源游戏.

- [Homebrew Hub](https://hh.gbdev.io)  - 以社区为主导的尝试，旨在收集、存档和保存为 Game Boy 发布的所有未经许可的自制游戏. 参赛作品可在线播放.

### ASM

- [Tuff](https://github.com/BonsaiDen/Tuff.gb)
- [2048-gb](https://github.com/Sanqui/2048-gb)
- [Snake](https://bitbucket.org/Sanqui/snake/src/?at=master)
- [Lazerpong](https://github.com/huderlem/lazerpong)
- [Geometrix](https://github.com/AntonioND/geometrix)
- [µCity](https://github.com/AntonioND/ucity)
- [Carazu](https://github.com/mholtkamp/carazu)
- [Snake-gb](https://github.com/DonaldHays/snake-gb)
- [GB303](https://github.com/furrtek/GB303) - 用于 Nintendo Game Boy 的基于 GB303 波表的 TB-303 风格合成器.
- [Sushi](https://github.com/JustSid/Sushi)
- [Flappy-boy-asm](https://github.com/bitnenfer/flappy-boy-asm)
- [kupman](https://github.com/dubvulture/gbdev) 和其他一些项目.
- [Adjustris](https://github.com/tbsp/Adjustris)
- [exeman](https://github.com/exezin/exeman/)
- [Aevilia](https://github.com/ISSOtm/Aevilia-GB)
- [GBSlides](https://github.com/Kartones/gameboy) - 一个简单的类似 Game Boy Powerpoint 的幻灯片查看器.
- [Pokered-gbc](https://github.com/dannye/pokered-gbc) - Pokémon Red 重制版，完全支持 GBC.
- [ToyToy](https://github.com/tslanina/Retro-GameBoyColor-ToyToy)
- [StefaN](https://github.com/tslanina/Retro-GameBoyColor-StefaN) - Fourway Breakout 克隆.
- [Galaxia](https://github.com/tslanina/Retro-GameBoyColor-Galaxia)
- [desgb](https://github.com/sanqui/desgb) - DES 加密.
- [superhappyfunbubbletime](https://github.com/l0k1/superhappyfunbubbletime)
- [minesweepGB](https://github.com/lancekindle/minesweepGB)
- [Libbet and the Magic Floor](https://github.com/pinobatch/libbet)
- [waveform-gb](https://github.com/dannye/waveform-gb)  - 程序可视化波通道使用的波形. 可以自由编辑波形，并立即更新波形的播放.
- [vectroid.gb](https://gitlab.com/BonsaiDen/vectroid.gb) - 使用 gbasm 开发.
- [PlantBoy](https://github.com/gb-archive/plantboy)
- [Death Planet](https://makrill.itch.io/death-planet)
- [Quartet](https://makrill.itch.io/quartet) - Game Boy (Color) 和 Super Game Boy 的益智游戏.
- [Dangan](https://snorpung.itch.io/dangan-gb)

### C

- [FlappyBoy](https://github.com/bitnenfer/FlappyBoy)
- [flappybird-gameboy](https://github.com/pashutk/flappybird-gameboy)
- [fbgb](https://github.com/gb-archive/fbgb)
- [Novascape](https://web.archive.org/web/20171002042716/http://ludumdare.com/compo/ludum-dare-34/?action=preview&uid=6823)
- [Squishy the Turtle](https://github.com/cppchriscpp/SquishyTheTurtle)
- [Quadratino](https://github.com/avivace/quadratino)
- [Doctor How](https://github.com/elfgames/doctorhow)
- [Super Princess' 2092 Exodus](https://github.com/Zal0/gbjam2016) - ([ZGB engine](https://github.com/Zal0/ZGB/)).
- [GBsnake](https://github.com/brovador/GBsnake)
- [gb-mines](https://github.com/andreasjhkarlsson/gb-mines)
- [oranges](http://www.atari2600land.com/gameboy/oranges.html)
- [red hot princess carnage](https://github.com/Imanolea/bitbitjam3_red_hot_princess_carnage)
- [loderunner](https://www.tensi.eu/thomas/programming/games/loderunner/loderunner.html)
- [Hives](https://refreshgames.co.uk/2017/04/24/ludum-dare-38-entry-hives/)
- [Bubble Factory](https://github.com/DonaldHays/bubblefactory) - *Vanilla- SDCC（不是 gbdk）.
- [GBC Atari Boxing](https://github.com/rubfi/gbc-atari-boxing) - Game Boy（彩色）的 Atari 2600 Boxing 克隆版.
- [GB raycaster, Vision-8](https://github.com/haroldo-ok/really-old-stuff/tree/master/gameboy) - 和其他一些项目.
- [Tobu Tobu Girl Deluxe](https://github.com/SimonLarsen/tobutobugirl-dx) - Game Boy (Color) 的街机平台游戏.
- [Burly Bear vs. The Mean Foxes](http://sebastianmihai.com/gameboy-burly-bear.html) ([GBC](http://sebastianmihai.com/gameboy-color-burly-bear.html) 港口）
- [PostBot](https://github.com/MasterIV/PostBot)
- [Guns & Riders](https://github.com/kanfor/gunsridersgameboy)
- [Dino's Offline Adventure](https://github.com/gingemonster/DinosOfflineAdventure) - 谷歌浏览器离线游戏的克隆.
- [dino-gb](https://github.com/rnegron/dino-gb) - Chrome 游戏的另一个克隆.
- [Evoland.gb](https://github.com/flozz/evoland.gb) - Evoland 第一层的港口.
- [Petris](https://github.com/bbbbbr/Petris) - 一款适合 Game Boy Color 的漂亮宠物益智游戏（[itch.io](https://bbbbbr.itch.io/petris)).
- [Infinity](https://github.com/gb-archive/infinity-gbc)  - 主要由 Affinix Software 在 1999 年至 2001 年间开发的角色扮演游戏.该游戏从未找到发行商并最终被取消. 最近发布了完整的源代码、开发工具和工作流程.
- [Black Castle](https://gbdev.gg8.se/forums/viewtopic.php?id=743) - Game Boy 的横向卷轴平台游戏（[itch.io](https://user0x7f.itch.io/black-castle)).
- [Genesis](https://gbdev.gg8.se/forums/viewtopic.php?id=674) - Game Boy 的 Shmup ([itch.io](https://user0x7f.itch.io/genesis)).
- [Indestructo Tank!](https://antonylavelle.itch.io/indestructotank-gb)
- [Super JetPak DX](https://pocketpixel.design/super-jetpak-dx-game-boy-rom.html)
- [Powa!](https://aiguanachein.itch.io/powa) - Game Boy（彩色）的横向卷轴平台游戏（[ZGB engine](https://github.com/Zal0/ZGB/)).
- [Cavern](https://thegreatgallus.itch.io/cavern-mvm-9) - ([ZGB engine](https://github.com/Zal0/ZGB/)).
- [Mona and the Witch's Hat Deluxe](https://ctneptune.itch.io/mona-and-the-witchs-hat-dx) - ([ZGB engine](https://github.com/Zal0/ZGB/)).
- [The Bouncing Ball](https://gamejolt.com/games/the-bouncing-ball-gb/86699)
- [DMG Deals Damage](https://drludos.itch.io/dmg-deals-damage)

### GB Studio

- [Soul Void](https://kadabura.itch.io/soul-void) - 互动恐怖小说.
- [Deadeus](https://izma.itch.io/deadeus)
- [SUPER IMPOSTOR BROS.](https://lumpytouch.itch.io/super-impostor-bros)

### Demos

- [Back to Color](https://github.com/AntonioND/back-to-color)
- [beach-gbc](https://github.com/vegard/beach-gbc)
- [CUTE DEMO](https://github.com/mills32/CUTE_DEMO)
- [`10 PRINT` Game Boy](https://github.com/svendahlstrand/10-print-game-boy)
- [Roboto Demo](https://github.com/naavis/roboto-demo)
- [matrix-rain-gb](https://github.com/wtjones/matrix-rain-gb) - 汇编器中的 Matrix 数字雨效果.
- [GBVideoPlayer](https://github.com/LIJI32/GBVideoPlayer) - 一个技术演示，演示如何破解 Game Boy LCD 控制器，使 Game Boy Color 播放彩色全动态视频和音乐.
- [GBVideoPlayer2](https://github.com/LIJI32/GBVideoPlayer2) - 上述演示的第二次迭代，增加了分辨率，添加了*立体声 PCM 音频，并引入了视频压缩*.

## Reverse Engineering

- [Reverse engineering Kirby's Dreamland 2](http://ecc-comp.blogspot.it/2016/03/reverse-engineering-kirbys-dreamland-2.html)
- [pokemontools](https://github.com/pret/pokemon-reverse-engineering-tools) - 一个 python 模块，为各种神奇宝贝游戏提供各种逆向工程组件.
- [Reverse Engineering a Gameboy ROM with radare2](https://www.megabeets.net/reverse-engineering-a-gameboy-rom-with-radare2) - 使用 radare2 对 Game Boy ROM 挑战进行逆向工程的演练.
- [Disassembling Link's Awakening](http://kemenaran.winosx.com/posts/category-disassembling-links-awakening/) - 一系列关于拆解 Link 的 Awakening DX 的博文.
- [Reverse Engineering the GameBoy Tetris](https://github.com/h3nnn4n/Reverse-Engineering-the-GameBoy-Tetris)
- [DMA hijacking](https://gbdev.io/guides/dma_hijacking) - 一种简单的技术，允许您在大多数 GB/SGB/CGB 游戏中运行自定义代码，前提是您有 ACE 漏洞.

### Game Disassemblies

- [Pokémon Red/Blue](https://github.com/pret/pokered)
- [Pokémon Crystal](https://github.com/pret/pokecrystal)
- [Pokémon Yellow](https://github.com/pret/pokeyellow)
- [Pokémon Gold and Silver](https://github.com/pret/pokegold)
- [Pokémon Pinball](https://github.com/pret/pokepinball)
- [Pokémon TCG](https://github.com/pret/poketcg)
- [pokegold-spaceworld](https://github.com/pret/pokegold-spaceworld) - Pokémon Gold and Silver 1997 Space World 演示.
- [Link's Awakening DX](https://github.com/mojobojo/LADX-Disassembly)
- [Oracle of Ages](https://github.com/drenn1/ages-disasm)
- [Tetris](https://github.com/vinheim3/tetris-gb-disasm) - 完整的俄罗斯方块拆解.
- [FX Hammer](https://github.com/DevEd2/FXHammer-Disasm)
- [Harvest Moon 3](https://github.com/sanqui/hm3)
- [Final Fantasy Adventure](https://github.com/daid/FFA-disassembly)

## Game Boy Camera

### Retrieving images

Game Boy 打印机仿真（例如从相机中检索图像）：

- [Arduino Gameboy Printer Emulator](https://github.com/mofosyne/arduino-gameboy-printer-emulator) - 通过 gameboy 链接电缆模拟 gameboy 打印机. 
- [ESP8266 Game Boy Printer](https://github.com/applefreak/esp8266-gameboy-printer) - 一种模拟 Gameboy 打印机并让您使用由 ESP8266 供电的 WiFi 检索图像的设备.
- [WiFi GBP Emulator](https://github.com/HerrZatacke/wifi-gbp-emulator) - 一个 GameBoy 打印机模拟器，它通过 WiFi 连接提供接收到的数据.
- [Game Boy WiFi Printer - D1 Mini Shield](https://github.com/cristofercruz/gbp-esp-shield-pcb) - 适用于 D1 mini/mini Pro ESP8266 板的 Game Boy 打印机接口屏蔽. 
- [Game Boy Printer Sniffer](https://github.com/mofosyne/GameboyPrinterSniffer) - 嗅探 Game Boy 和打印机之间的数据包通信.

### Changing the camera's behavior

改进和/或操纵相机质量和行为的方法：

- [Game Boy Camera Canon EF Lens Mount](http://ekeler.com/game-boy-camera-canon-ef-mount)
- [Game Boy Camera to Canon Lens mount](https://www.thingiverse.com/thing:4337362) - 基于以上.
- [game-boy-camera-frame-replacer](https://github.com/cristofercruz/game-boy-camera-frame-replacer) - 操纵相机的 ROM 以包含自定义帧

### Post processing

- [Game Boy Printer Paper Simulation](https://github.com/mofosyne/GameboyPrinterPaperSimulation) - 生成数字印刷图像的仿印刷图像.
- [Game Boy Printer Web](https://github.com/HerrZatacke/gb-printer-web) - 适用于 Game Boy 相机的图库应用程序：从导出或墨盒转储中导入图片并选择调色板.

## Related projects

- [GB Studio](https://www.gbstudio.dev/) - 拖放游戏创建者，无需任何知识，可视化脚本.
  - [Resources to get started](https://gbstudiocentral.com/resources/)
  - [Dedicated Discord](https://discord.gg/knRryZWGcm)
- [ArduinoBoy](https://github.com/trash80/Arduinoboy) - 从 Arduino 到 Game Boy 的串行通信 (MIDI)，用于 LittleSoundDJ、Nanoloop 和 mGB 等音乐应用程序.
- [papiGB](https://github.com/diegovalverde/papiGB) - 从零开始的 Game Boy Classic 全功能 FPGA 实现.
- [fpgaboy](https://github.com/trun/fpgaboy) - 在 FPGA 上实施任天堂的 Game Boy 控制台.
- [Piglet](https://github.com/danShumway/Piglet)  - 一个 LUA 驱动的 AI，可以通过实验来玩经典的 Game Boy 彩色游戏. 在积极发展中.
- [Ostrich](https://github.com/PumpMagic/ostrich) - 用 Swift 编写的 Game Boy 音响系统播放器.
- [mGB](https://github.com/trash80/mGB) - 一个 Game Boy 卡带程序，使 Game Boy 可以充当完全支持 MIDI 的声音模块.
- [GBVisualizer](https://github.com/LIJI32/GBVisualizer) - 演示如何使用两个未记录的 Game Boy 颜色寄存器，绰号为 PCM12 (FF76) 和 PCM34 (FF77)，可用于读取 4 个 APU 通道的当前 PCM 幅度.
- [ArduinoGameBoy](https://github.com/drhelius/arduinogameboy) - Arduino based Game Boy cartridge reader and writer.
- [gameboy-brainfuck](https://github.com/bitnenfer/gameboy-brainfuck) - Brainf*ck 翻译.
- [gbfk](https://github.com/elseyf/gbfk) - Brainf*ck 解释器，带输入.
- [gb-save-states](https://github.com/mattcurrie/gb-save-states) - 在原始硬件上玩游戏时为 Game Boy 游戏添加保存状态支持的补丁.
- [gbcpu](https://github.com/jdeblese/gbcpu) - 实现 Game Boy 指令集和功能的 CPU 和外围设备.
- [Digitized Speech in Game Boy Games](https://youtube.com/watch?v=1lzHfLYzyRM)
- [Sniffing Game Boy serial traffic with an STM32F4](https://dhole.github.io/post/gameboy_serial_1/)
- [Virtual Game Boy Printer with an STM32F4](https://dhole.github.io/post/gameboy_serial_2/)
- [Printing on the Game Boy Printer using an STM32F4](https://dhole.github.io/post/gameboy_serial_3/)
- [Programming Game Boy Chinese cartridges with an STM32F4](https://dhole.github.io/post/gameboy_cartridge_rw_1/)
- [Pokemon Pocket Computer:](https://tilde.town/~minerobber/techwriteups/pokemonpc.html) - 它是什么以及如何使用它来制作作弊代码.
- [Booting the Game Boy with a custom logo](https://dhole.github.io/post/gameboy_custom_logo/) - 绕过任天堂标志检查.
 - 2017 年制作 Game Boy 游戏：“Sheep It Up!” 验尸（[part 1](https://www.gamasutra.com/blogs/DoctorLudos/20171207/311143/), [part 2](https://www.gamasutra.com/blogs/DoctorLudos/20180213/314554/))
- [Nintendo's fake logos](http://fuji.drillspirits.net/?post=87) - 每个墨盒都必须显示真实标识才能被视为有效并可以运行，但显然有些公司设法利用了检查系统.
- [liblsdj](https://github.com/stijnfrishert/liblsdj) - 用于与 LSDj 保存格式 (.sav)、歌曲文件 (.lsdsng) 等进行交互的实用程序库.
- [lsdpatch](https://github.com/jkotlinski/lsdpatch) - 用于修改 LSDj ROM 图像上的示例、字体和调色板的工具.
- [Game Boy video effects](https://github.com/ChaosCabbage/crazy-gameboy-video-experiments) - 一些使用 STAT 中断进行有趣视频操作的小实验.
- [gbos](https://github.com/ekimekim/gbos) - Game Boy 的基本操作系统.
- [Work Master OS](https://translate.google.com/translate?hl=&sl=ru&tl=en&u=https%3A%2F%2Fweb.archive.org%2Fweb%2F20081226145726%2Fhttp%3A%2F%2Fworkmaster.ru%2Findex.php%3Fp%3D8&sandbox=1) - 俄罗斯多任务操作系统.
- [Game Boy Link Cable Breakout Board](https://github.com/Palmr/gb-link-cable)
- [GBCartFlasher firmware](https://github.com/Tauwasser/GBCartFlasher)
- [VerilogBoy](https://github.com/zephray/VerilogBoy/) - Game Boy 兼容控制台 Verilog RTL 实现.
- [GBCamcorder](https://github.com/furrtek/GBCamcorder) - 使用 GameBoy 相机卡带的 Lo-Fi 便携式视频录像机.
- [GBCartRead](https://github.com/insidegadgets/GBCartRead) - 从/向 GameBoy 卡带读取 ROM、读取 RAM 或写入 RAM.
- [GBxCart-RW](https://github.com/insidegadgets/GBxCart-RW) - 一种用于通过 USB 从您的 PC 读取游戏 ROM、保存游戏和恢复 GB、GBC 和 GBA 卡的保存的设备.
- [Dumping the Super Game Boy Boot ROM](http://www.its.caltech.edu/~costis/sgb_hack/)

### Directories

- [Archive of related files](http://gbdev.gg8.se/files/)
- [The Game Boy Archive](https://github.com/gb-archive)  - Game Boy 相关软件、硬件和文献库. 旨在反映和保存过去三十年的旧的和零散的贡献.
- [The Game Boy Archive - Salvage](https://github.com/gb-archive/salvage) - 软件、旧文章、常见问题解答和各种文档的历史存档.

### Websites

- [devrs.com/gb](http://devrs.com/gb) - 老家的场景：示例、资源、完整的文档、指南、教程和各种工具.
- [pdroms.de](http://pdroms.de/news/gameboy/) - Game Boy 发布.
- [Handheld Underground](http://hhug.me) - 未经许可的游戏，关于 Game Boy 的博客文章，hhugboy 模拟器的主页.


## About

### Contribute

看一眼 [Contribution Guidelines](CONTRIBUTING.md).

### License

根据 **GPLv3** 获得许可.
See [LICENSE](LICENSE) 了解更多信息.

### Acknowledgements

谢谢 [every](https://github.com/avivace/awesome-gbdev/graphs/contributors) Jeff Frohwein、Pascal Felber、KOOPa、Pan of Anthrox、GABY、Marat Fayzullin、Paul Robson、BOWSER、Nevixti、Martin “Nocash” Korth、Nitro2k01、Duo、Chris Antonellis、Michael Hope、Beware、Jonathan “Lord Nightmare” Gevaryahu、Carsten Sorense、Sindre Aamås、Otaku No Zoku、GeeBee.

### Sponsors

特别感谢我们的朋友 [DigitalOcean](https://www.digitalocean.com/) 和 [Incube8 Games](https://incube8games.com/)，赞助我们 Game Boy 开发社区的开源活动.
