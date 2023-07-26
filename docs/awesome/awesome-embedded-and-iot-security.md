<div class="github-widget" data-repo="fkie-cad/awesome-embedded-and-iot-security"></div>
<div align="center">
	<img width="500" height="350" src="https://raw.githubusercontent.com/fkie-cad/awesome-embedded-and-iot-security/master/iot_awesome_logo.svg?sanitize=true" alt="Awesome">
  <br />
</div>

## Awesome Embedded and IoT Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 &gt; 关于嵌入式和物联网安全的精选资源列表. 该列表包含软件和硬件工具、书籍、研究论文等.

僵尸网络喜欢 [Mirai](https://github.com/fkie-cad/awesome-embedded-and-iot-security/blob/master/<https://en.wikipedia.org/wiki/Mirai_(malware) &gt;) 已经证明，嵌入式和物联网设备需要更高的安全性. 此列表将帮助初学者和专家找到有关该主题的有用资源.  
如果你是初学者，你应该看看<ins> *图书*</ins> 和<ins> *实例探究*</ins> 部分.  
如果您想立即开始自己的分析，您应该给出<ins> *分析框架*</ins> 一试.
它们易于使用，您无需成为专家即可获得第一个有意义的结果.

&gt; 标有 :euro: 的项目是商业产品.



## Software Tools

用于分析嵌入式/物联网设备和固件的软件工具.

### Analysis Frameworks

- [EXPLIoT](https://gitlab.com/expliot_framework/expliot) - Pentest 框架，如 Metasploit，但专门用于物联网.
- [FACT - The Firmware Analysis and Comparison Tool](https://fkie-cad.github.io/FACT_core/) - 全功能静态分析框架，包括固件提取、使用不同插件的分析以及不同固件版本的比较.
  - [Improving your firmware security analysis process with FACT](https://passthesalt.ubicast.tv/videos/improving-your-firmware-security-analysis-process-with-fact/) - 会议谈论 FACT :tv:.
- [FwAnalyzer](https://github.com/cruise-automation/fwanalyzer)  - 根据自定义规则分析固件的安全性. 旨在作为 DevSecOps 中的附加步骤，类似于 CI.
- [HAL – The Hardware Analyzer](https://github.com/emsec/hal) - 门级网表的综合逆向工程和操作框架.
- [HomePWN](https://github.com/ElevenPaths/HomePWN) - 用于物联网设备渗透测试的瑞士军刀.
- [IoTSecFuzz](https://gitlab.com/invuls/iot-projects/iotsecfuzz) - 物联网层安全分析自动化框架：硬件、软件和通信.
- [Killerbee](https://github.com/riverloopsec/killerbee) - 测试和审计 ZigBee 和 IEEE 802.15.4 网络的框架.
- [PRET](https://github.com/RUB-NDS/PRET) - 打印机开发工具包.
- [Routersploit](https://github.com/threat9/routersploit) - 专用于利用嵌入式设备的框架.

### Analysis Tools

- [Binwalk](https://github.com/ReFirmLabs/binwalk) - 在二进制文件中搜索“有趣”的东西，以及提取任意文件.
- [emba](https://github.com/e-m-b-a/emba) - 分析嵌入式设备的基于 Linux 的固件.
- [Firmadyne](https://github.com/firmadyne/firmadyne) - 尝试模拟和渗透固件.
- [Firmwalker](https://github.com/craigz28/firmwalker) - 在提取的固件图像中搜索有趣的文件和信息.
- [Firmware Slap](https://github.com/ChrisTheCoolHut/Firmware_Slap) - 通过混合分析和函数聚类发现固件中的漏洞.
- [Ghidra](https://ghidra-sre.org/)  - 软件逆向工程套件； 如果您提供二进制文件的 CPU 体系结构和字节顺序，则可以处理任意二进制文件.
- [Radare2](https://github.com/radare/radare2) - 软件逆向工程框架，还可以处理流行的格式和任意二进制文件，具有广泛的命令行工具集.
- [Trommel](https://github.com/CERTCC/trommel) - 在提取的固件图像中搜索有趣的文件和信息.

### Extraction Tools

- [FACT Extractor](https://github.com/fkie-cad/fact_extractor) - 自动检测容器格式并执行相应的提取工具.
- [Firmware Mod Kit](https://github.com/rampageX/firmware-mod-kit/wiki) - 多种容器格式的提取工具.
- [The SRecord package](http://srecord.sourceforge.net/) - 用于操作 EPROM 文件的工具集合（可以转换许多二进制格式）.

### Support Tools

- [JTAGenum](https://github.com/cyphunk/JTAGenum) - 将 JTAG 功能添加到 Arduino.
- [OpenOCD](http://openocd.org/) - 免费开放的片上调试、在系统编程和边界扫描测试.

### Misc Tools

- [Cotopaxi](https://github.com/Samsung/cotopaxi) - 一套用于使用特定网络物联网协议对物联网设备进行安全测试的工具.
- [dumpflash](https://github.com/ohjeongwook/dumpflash) - 低级 NAND 闪存转储和解析实用程序.
- [flashrom](https://github.com/flashrom/flashrom) - 用于检测、读取、写入、验证和擦除闪存芯片的工具.
- [Samsung Firmware Magic](https://github.com/chrivers/samsung-firmware-magic) - 解密三星 SSD 固件更新.

## Hardware Tools

- [Bus Blaster](http://dangerousprototypes.com/docs/Bus_Blaster) - 检测硬件调试端口并与之交互，例如 [UART](https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter) 和 [JTAG](https://en.wikipedia.org/wiki/JTAG).
- [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - 检测 UART 和 JTAG 等硬件调试端口并与之交互.
- [Shikra](https://int3.cc/products/the-shikra)  - 检测 UART 和 JTAG 等硬件调试端口并与之交互. 在其他协议中.
- [JTAGULATOR](http://www.grandideastudio.com/jtagulator/) - 快速检测 JTAG 引出线.
- [Saleae](https://www.saleae.com/) - Easy to use Logic Analyzer that support many protocols :euro:.
- [Ikalogic](https://www.ikalogic.com/pages/logic-analyzer-sp-series-sp209) - Saleae 逻辑分析仪的替代品 :euro:.
- [HydraBus](https://hydrabus.com/hydrabus-1-0-specifications/) - 类似于 BusPirate 但具有 NFC 功能的开源多工具硬件.
- [ChipWhisperer](https://newae.com/chipwhisperer/) - 检测 Glitch/Side-channel 攻击.
- [Glasgow](https://github.com/GlasgowEmbedded/Glasgow) - 用于探索和调试不同数字接口的工具.
- [J-Link](https://www.segger.com/products/debug-probes/j-link/models/model-overview/) - J-Link 为多个不同的 CPU 内核提供 USB 供电的 JTAG 调试探针 :euro:.

### Bluetooth BLE Tools

- [UberTooth One](https://greatscottgadgets.com/ubertoothone/) - 适用于蓝牙实验的开源 2.4 GHz 无线开发平台.
- [Bluefruit LE Sniffer](https://www.adafruit.com/product/2269) - 易于使用的低功耗蓝牙嗅探器.

### ZigBee Tools

- [ApiMote](http://apimote.com)  - ZigBee 安全研究硬件，用于了解和评估 IEEE 802.15.4/ZigBee 系统的安全性. 杀手蜂兼容.
 - Atmel RZUSBstick - 停产产品. 幸运的是，如果你有一个！  - 用于开发、调试和演示各种低功耗无线应用的工具，包括 IEEE 802.15.4、6LoWPAN 和 ZigBee 网络. 杀手蜂兼容.
- [Freakduino](https://freaklabsstore.com/index.php?main_page=product_info&cPath=22&products_id=219&zenid=fpmu2kuuk4abjf6aurt3bjnfk4) - 低成本电池供电的无线 Arduino 板，可以变成 IEEE 802.15.4 协议嗅探器.

### SDR Tools

- [RTL-SDR](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/)  - 适合初学者的最便宜的 SDR. 它是一种基于计算机的无线电扫描仪，用于接收频率从 500 kHz 到 1.75 GHz 的实时无线电信号.
- [HackRF One](https://greatscottgadgets.com/hackrf/) - 软件无线电外设能够传输或接收 1 MHz 至 6 GHz（半双工）的无线电信号.
- [YardStick One](https://greatscottgadgets.com/yardstickone/) - 半双工低于 1 GHz 的无线收发器.
- [LimeSDR](https://www.crowdsupply.com/lime-micro/limesdr) - 软件无线电外设能够传输或接收 100 KHz 至 3.8 GHz（全双工）的无线电信号.
- [BladeRF 2.0](https://www.nuand.com/bladerf-2-0-micro/) - 软件无线电外设能够传输或接收 47 MHz 至 6 GHz（全双工）的无线电信号.
- [USRP B Series](https://www.ettus.com/product-categories/usrp-bus-series/) - 软件无线电外设能够传输或接收 70 MHz 至 6 GHz（全双工）的无线电信号.

### RFID NFC Tools

- [Proxmark 3 RDV4](https://www.proxmark.com/)  - 强大的通用 RFID 工具. 从低频 (125kHz) 到高频 (13.56MHz) 标签.
- [ChamaleonMini](http://chameleontiny.com/) - 用于 NFC 安全分析的可编程便携式工具.
- [HydraNFC](https://hydrabus.com/hydranfc-1-0-specifications/)  - 强大的 13.56MHz RFID/NFC 平台. 读/写/破解/嗅探/模拟.

## Books

- 2020，Fotios Chantzis、Evangel Deirme、Ioannis Stais、Paulino Calderon、Beau Woods： [Practical IoT Hacking](https://www.amazon.com/Fotios-Chantzis-ebook/dp/B085BVVSN6/)
- 2020 年，贾斯珀·范·沃登伯格，科林·奥弗林： [The Hardware Hacking Handbook: Breaking Embedded Security with Hardware Attacks](https://nostarch.com/hardwarehacking)
- 2019 年，亚戈汉森： [The Hacker's Hardware Toolkit: The best collection of hardware gadgets for Red Team hackers, Pentesters and security researchers](https://github.com/yadox666/The-Hackers-Hardware-Toolkit/blob/master/TheHackersHardwareToolkit.pdf)
- 2019 年，阿迪亚古普塔： [The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things](https://www.apress.com/us/book/9781484242995)
- 2018，Mark Swarup Tehranipoor： [Hardware Security: A Hands-on Learning Approach](https://www.elsevier.com/books/hardware-security/bhunia/978-0-12-812477-2)
- 2018 年，马克·卡尼： [Pentesting Hardware - A Practical Handbook (DRAFT)](https://github.com/unprovable/PentestHardware)
- 2018, Qing Yang, Lin Huang [Inside Radio: An Attack and Defense Guide](https://link.springer.com/book/10.1007/978-981-10-8447-8)
- 2017，阿迪亚古普塔，亚伦古兹曼： [IoT Penetration Testing Cookbook](https://www.packtpub.com/networking-and-servers/iot-penetration-testing-cookbook)
- 2017, Andrew Huang: [The Hardware Hacker: Adventures in Making and Breaking Hardware](https://nostarch.com/hardwarehackerpaperback)
- 2016 年，克雷格·史密斯： [The Car Hacker's Handbook: A Guide for the Penetration Tester](https://nostarch.com/carhacking)
- 2015 年，吴敬忠： [The Art of PCB Reverse Engineering](https://visio-for-engineers.blogspot.com/p/order.html)
- 2015 年，Nitish Dhanjan： [Abusing the Internet of Things: Blackouts, Freakouts, and Stakeouts](https://shop.oreilly.com/product/0636920033547.do)
- 2015 年，约书亚赖特，约翰尼卡奇： [Hacking Wireless Exposed](https://www.mhprofessional.com/9780071827638-usa-hacking-exposed-wireless-third-edition-group)
- 2014 年，Debdeep Mukhopadhyay： [Hardware Security: Design, Threats, and Safeguards](https://www.taylorfrancis.com/books/9780429066900)
- 2014 年，杰克·甘斯勒： [The Firmware Handbook (Embedded Technology)](https://www.elsevier.com/books/the-firmware-handbook/ganssle/978-0-7506-7606-9)
- 2013, Andrew Huang: [Hacking the XBOX](https://nostarch.com/xboxfree)

## Research Papers

<!--lint ignore match-punctuation-->
- 2020 年，Dare 等人： [SAFER: Development and Evaluation of an IoT Device Risk Assessment Framework in a Multinational Organization](https://dl.acm.org/doi/abs/10.1145/3414173)
- 2019 年，Agarwal 等人： [Detecting IoT Devices and How They Put Large Heterogeneous Networks at Security Risk](https://www.mdpi.com/1424-8220/19/19/4107)
- 2019 年，Almakhdhub 等人： [BenchIoT: A Security Benchmark for the Internet of Things](https://nebelwelt.net/publications/files/19DSN.pdf)
- 2019 年，Alrawy 等人： [SoK: Security Evaluation of Home-Based IoT Deployments](https://alrawi.github.io/static/papers/alrawi_sok_sp19.pdf)
- 2019 年，Abbasi 等人： [Challenges in Designing Exploit Mitigations for Deeply Embedded Systems](https://ieeexplore.ieee.org/abstract/document/8806725)
- 2019，Song 等人： [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04A-1_Song_paper.pdf)
- 2018 年，Muench 等人： [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://www.eurecom.fr/en/publication/5417/download/sec-publi-5417.pdf)
- 2017 年，O&#39;Meara 等人： [Embedded Device Vulnerability Analysis Case Study Using Trommel](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=509271)
- 2017 年，雅各布等人： [How to Break Secure Boot on FPGA SoCs through Malicious Hardware](https://eprint.iacr.org/2017/625.pdf)
- 2017 年，Costin 等人： [Towards Automated Classification of Firmware Images and Identification of Embedded Devices](http://s3.eurecom.fr/docs/ifip17_costin.pdf)
- 2016 年，Kammerstetter 等人： [Embedded Security Testing with Peripheral Device Caching and Runtime Program State Approximation](https://www.thinkmind.org/download.php?articleid=securware_2016_2_10_30082)
- 2016 年，Chen 等人： [Towards Automated Dynamic Analysis for Linux-based Embedded Firmware](https://www.dcddcc.com/docs/2016_paper_firmadyne.pdf)
- 2016 年，Costin 等人： [Automated Dynamic Firmware Analysis at Scale: A Case Study on Embedded Web Interfaces](http://s3.eurecom.fr/docs/asiaccs16_costin.pdf)
- 2015 年，Shoshitaishvili 等人：[Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://www.ndss-symposium.org/wp-content/uploads/2017/09/11_1_2.pdf)
- 2015 年，帕普等人： [Embedded Systems Security: Threats, Vulnerabilities, and Attack Taxonomy](http://www.cse.psu.edu/~pdm12/cse597g-f15/readings/cse597g-embedded_systems.pdf)
- 2014 年，Zaddach 等人： [Avatar: A Framework to Support Dynamic Security Analysis of Embedded Systems' Firmwares](http://www.eurecom.fr/en/publication/4158/download/rs-publi-4158.pdf)
- 2014 年，Alimi 等人： [Analysis of embedded applications by evolutionary fuzzing](http://ieeexplore.ieee.org/document/6903734/)
- 2014 年，Costin 等人： [A Large-Scale Analysis of the Security of Embedded Firmwares](http://www.s3.eurecom.fr/docs/usenixsec14_costin.pdf)
- 2013 年，戴维森等人： [FIE on Firmware: Finding Vulnerabilities in Embedded Systems using Symbolic Execution](https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_davidson.pdf)

## Case Studies

<!--lint ignore no-repeat-punctuation-->
 
- [Binary Hardening in IoT products](https://cyber-itl.org/2019/08/26/iot-data-writeup.html)
- [Cracking Linksys “Encryption”](http://www.devttys0.com/2014/02/cracking-linksys-crypto/)
- [Deadly Sins Of Development](https://youtu.be/nXyglaY9N9w) - 会议演讲展示了几个关于真正糟糕实施的真实世界的例子：电视：.
- [Dumping firmware from a device's SPI flash with a buspirate](https://www.iotpentest.com/2019/06/dumping-firmware-from-device-using.html)
- [Hacking the DSP-W215, Again](http://www.devttys0.com/2014/05/hacking-the-dspw215-again/)
- [Hacking the PS4](https://cturt.github.io/ps4.html) - 介绍 PS4 的安全性.
- [IoT Security@CERN](https://doi.org/10.5281/zenodo.1035034)
- [Multiple vulnerabilities found in the D-link DWR-932B](https://pierrekim.github.io/blog/2016-09-28-dlink-dwr-932b-lte-routers-vulnerabilities.html)
- [Pwning the Dlink 850L routers and abusing the MyDlink Cloud protocol](https://pierrekim.github.io/blog/2017-09-08-dlink-850l-mydlink-cloud-0days-vulnerabilities.html)
- [PWN Xerox Printers (...again)](https://www.fkie.fraunhofer.de/content/dam/fkie/de/documents/xerox_phaser_6700_white_paper.pdf)
- [Reversing Firmware With Radare](https://www.bored-nerds.com/reversing/radare/automotive/2019/07/07/reversing-firmware-with-radare.html)
- [Reversing the Huawei HG533](http://jcjc-dev.com/2016/04/08/reversing-huawei-router-1-find-uart/)

## Free Training

- [CSAW Embedded Security Challenge 2019](https://github.com/TrustworthyComputing/csaw_esc_2019) - CSAW 2019 嵌入式安全挑战赛 (ESC).
- [Embedded Security CTF](https://microcorruption.com) - 微腐败：嵌入式安全 CTF.
- [Hardware Hacking 101](https://github.com/rdomanski/hardware_hacking/tree/master/my_talks/Hardware_Hacking_101) - Workshop @ BSides Munich 2019.
- [IoTGoat](https://github.com/scriptingxss/IoTGoat) - IoTGoat 是一种基于 OpenWrt 的故意不安全的固件.
- [Rhme-2015](https://github.com/Riscure/RHme-2015) - First riscure Hack me 硬件 CTF 挑战.
- [Rhme-2016](https://github.com/Riscure/Rhme-2016) - Riscure Hack me 2 是一个低级别的硬件 CTF 挑战.
- [Rhme-2017/2018](https://github.com/Riscure/Rhme-2017) - Riscure Hack Me 3 嵌入式硬件 CTF 2017-2018.

## Websites

- [Hacking Printers Wiki](http://hacking-printers.net/wiki/index.php/Main_Page) - 所有打印机.
- [OWASP Embedded Application Security Project](https://owasp.org/www-project-embedded-application-security/) - 开发最佳实践和硬件和软件工具列表.
- [OWASP Internet of Things Project](https://owasp.org/www-project-internet-of-things/) - IoT 常见漏洞和攻击面.
- [Router Passwords](https://192-168-1-1ip.mobi/default-router-passwords-list/) - 按制造商排序的默认登录凭据数据库.
- [Siliconpr0n](https://siliconpr0n.org/) - 所有 IC 反转的 Wiki/Archive.

### Blogs

<!--lint ignore no-repeat-punctuation-->

- [RTL-SDR](https://www.rtl-sdr.com/)
- [/dev/ttyS0's Embedded Device Hacking](http://www.devttys0.com/blog/)
- [Exploiteers](https://www.exploitee.rs/)
- [Hackaday](https://hackaday.com)
- [jcjc's Hack The World](https://jcjc-dev.com/)
- [Quarkslab](https://blog.quarkslab.com/)
- [wrong baud](https://wrongbaud.github.io/)
- [Firmware Security](https://firmwaresecurity.com/)
- [PenTestPartners](https://www.pentestpartners.com/internet-of-things/)
- [Attify](https://blog.attify.com/)
- [Patayu](https://payatu.com/blog)
- [GracefulSecurity - Hardware tag](https://gracefulsecurity.com/category/hardware/)
- [Black Hills - Hardware Hacking tag](https://www.blackhillsinfosec.com/tag/hardware-hacking/)

### Tutorials and Technical Background

- [Azeria Lab](https://azeria-labs.com/) - 其他 ARM 相关教程.
- [JTAG Explained](https://blog.senr.io/blog/jtag-explained#) - 绕过受保护登录 shell 的 UART 和 JTAG 演练.
- [Reverse Engineering Serial Ports](http://www.devttys0.com/2012/11/reverse-engineering-serial-ports/) - 关于如何在 PCB 上发现调试焊盘的详细教程.
- [UART explained](https://www.mikroe.com/blog/uart-serial-communication) - 对 UART 协议的深入解释.

### YouTube Channels
- [Flashback Team](https://www.youtube.com/c/FlashbackTeam) - 两位黑客解释了他们逐步发现和利用嵌入式设备漏洞的方法.
- [StackSmashing](https://www.youtube.com/c/stacksmashing) - 嵌入式设备的逆向工程和硬件黑客攻击.

## Conferences

专注于嵌入式和/或物联网安全的会议.

- [Hardwear.io](https://hardwear.io/) 
 	- 欧盟，海牙，9 月.
	- 美国，圣克拉拉，六月.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/fkie-cad/awesome-embedded-and-iot-security/blob/master/contributing.md) 第一的.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，Fraunhofer FKIE 已放弃所有版权和
本作品的相关或邻接权利.
