<div class="github-widget" data-repo="paralax/awesome-honeypots"></div>
## Awesome Honeypots [![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

很棒的蜜罐以及相关组件等的精选列表，分为 Web、服务等类别，重点关注免费和开源项目.

每个类别中的项目没有预先设定的顺序，顺序是按贡献顺序排列的. 如果您想贡献，请阅读 [guide](https://github.com/paralax/awesome-honeypots/blob/master/CONTRIBUTING.md).

发现更多精彩列表，请访问 [sindresorhus/awesome](https://github.com/sindresorhus/awesome).


- [Awesome Honeypots ![Awesome Honeypots](https://github.com/sindresorhus/awesome)](#awesome-honeypots-)

## Related Lists

- [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools) - 在网络流量分析中很有用.
- [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis) - 这里有一些重叠用于工件分析.

## Honeypots

- 数据库蜜罐

  - [Delilah](https://github.com/SecurityTW/delilah) - 用 Python 编写的 Elasticsearch Honeypot（最初来自 Novetta）.
  - [ESPot](https://github.com/mycert/ESPot) - 用 NodeJS 编写的 Elasticsearch 蜜罐，捕获每次利用 CVE-2014-3120 的尝试.
  - [ElasticPot](https://gitlab.com/bontchev/elasticpot) - Elasticsearch 蜜罐.
  - [Elastic honey](https://github.com/jordan-wright/elastichoney) - 简单的 Elasticsearch 蜜罐.
  - [MongoDB-HoneyProxy](https://github.com/Plazmaz/MongoDB-HoneyProxy) - MongoDB 蜜罐代理.
  - [NoSQLpot](https://github.com/torque59/nosqlpot) - 建立在 NoSQL 风格数据库之上的蜜罐框架.
  - [mysql-honeypotd](https://github.com/sjinks/mysql-honeypotd) - 用 C 编写的低交互 MySQL 蜜罐.
  - [MysqlPot](https://github.com/schmalle/MysqlPot) - MySQL 蜜罐，仍处于非常早期的阶段.
  - [pghoney](https://github.com/betheroot/pghoney) - 低交互 Postgres 蜜罐.
  - [sticky_elephant](https://github.com/betheroot/sticky_elephant) - 中等交互 postgresql 蜜罐.
  - [RedisHoneyPot](https://github.com/cypwnpwnsocute/RedisHoneyPot) - Redis 协议的高交互蜜罐解决方案.

- 网络蜜罐

  - [Express honeypot](https://github.com/christophe77/express-honeypot) - 使用 NodeJS 和 Express 的 RFI 和 LFI 蜜罐.
  - [EoHoneypotBundle](https://github.com/eymengunay/EoHoneypotBundle) - Symfony2 表单的蜜罐类型.
  - [Glastopf](https://github.com/mushorg/glastopf) - Web 应用程序蜜罐.
  - [Google Hack Honeypot](http://ghh.sourceforge.net) - 旨在针对使用搜索引擎作为针对您的资源的黑客工具的攻击者进行侦察.
  - [HellPot](https://github.com/yunginnanet/HellPot) - 试图使访问其位置的机器人和客户端崩溃的蜜罐.
  - [Laravel Application Honeypot](https://github.com/msurguy/Honeypot) - Laravel 应用程序的简单垃圾邮件预防包.
  - [Nodepot](https://github.com/schmalle/Nodepot) - NodeJS Web 应用程序蜜罐.
  - [PasitheaHoneypot](https://github.com/Marist-Innovation-Lab/PasitheaHoneypot) - RestAPI蜜罐.
  - [Servletpot](https://github.com/schmalle/servletpot) - Web 应用程序蜜罐.
  - [Shadow Daemon](https://shadowd.zecure.org/overview/introduction/) - 适用于 PHP、Perl 和 Python 应用程序的模块化 Web 应用程序防火墙/高交互蜜罐.
  - [StrutsHoneypot](https://github.com/Cymmetria/StrutsHoneypot) - 基于 Struts Apache 2 的蜜罐以及 Apache 2 服务器的检测模块.
  - [WebTrap](https://github.com/IllusiveNetworks-Labs/WebTrap) - 旨在创建欺骗性网页，以欺骗攻击者并将攻击者重定向到远离真实网站的位置.
  - [basic-auth-pot (bap)](https://github.com/bjeborn/basic-auth-pot) - HTTP 基本身份验证蜜罐.
  - [bwpot](https://github.com/graneed/bwpot) - 易碎的 Web 应用程序 honeyPot.
  - [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot) - 伪造 Django 管理员登录屏幕，通知管理员尝试未经授权的访问.
  - [drupo](https://github.com/d1str0/drupot) - Drupal 蜜罐.
  - [honeyhttpd](https://github.com/bocajspear1/honeyhttpd) - 基于 Python 的 Web 服务器蜜罐构建器.
  - [honeyup](https://github.com/LogoiLab/honeyup) - 上传者蜜罐的设计看起来像是网站安全性很差.
  - [owa-honeypot](https://github.com/joda32/owa-honeypot) - 基于 Outlook Web 蜜罐的基本烧瓶.
  - [phpmyadmin_honeypot](https://github.com/gfoss/phpmyadmin_honeypot) - 简单有效的 phpMyAdmin 蜜罐.
  - [shockpot](https://github.com/threatstream/shockpot) - 用于检测 Shell Shock 漏洞尝试的 WebApp 蜜罐.
  - [smart-honeypot](https://github.com/freak3dot/smart-honeypot) - PHP 脚本演示了智能蜜罐.
  - Snare/Tanner - Glastopf 的继承者
    - [Snare](https://github.com/mushorg/snare) - 超级下一代高级反应蜜罐.
    - [Tanner](https://github.com/mushorg/tanner) - 评估 SNARE 事件.
  - [stack-honeypot](https://github.com/CHH/stack-honeypot) - 在响应中插入垃圾邮件机器人陷阱.
  - [tomcat-manager-honeypot](https://github.com/helospark/tomcat-manager-honeypot)  - 模仿 Tomcat 管理器端点的蜜罐. 记录请求并保存攻击者的 WAR 文件以供以后研究
  - WordPress 蜜罐
    - [HonnyPotter](https://github.com/MartinIngesen/HonnyPotter) - WordPress 登录蜜罐，用于收集和分析失败的登录尝试.
    - [HoneyPress](https://github.com/kungfuguapo/HoneyPress) - Docker 容器中基于 Python 的 WordPress 蜜罐.
    - [wp-smart-honeypot](https://github.com/freak3dot/wp-smart-honeypot) - WordPress 插件可通过更智能的蜜罐减少垃圾评论.
    - [wordpot](https://github.com/gbrindisi/wordpot) - WordPress 蜜罐.
  - [Python-Honeypot](https://github.com/OWASP/Python-Honeypot) - OWASP 蜜罐，自动欺骗框架.

- 服务蜜罐
  - [ADBHoney](https://github.com/huuck/ADBHoney) - 低交互蜜罐，模拟运行 Android 调试桥 (ADB) 服务器进程的 Android 设备.
  - [AMTHoneypot](https://github.com/packetflare/amthoneypot) - 针对英特尔 AMT 固件漏洞 CVE-2017-5689 的蜜罐.
  - [ddospot](https://github.com/aelth/ddospot) - NTP、DNS、SSDP、Chargen 和基于 UDP 的通用放大 DDoS 蜜罐.
  - [dionaea](https://github.com/DinoTools/dionaea) - 捕蝇草蜜罐之家.
  - [dhp](https://github.com/ciscocsirt/dhp) - 简单的 Docker Honeypot 服务器模拟 Docker HTTP API 的小片段.
  - [DolosHoneypot](https://github.com/Marist-Innovation-Lab/DolosHoneypot) - SDN（软件定义网络）蜜罐.
  - [Ensnare](https://github.com/ahoernecke/ensnare) - 易于部署 Ruby 蜜罐.
  - [honeycomb_plugins](https://github.com/Cymmetria/honeycomb_plugins) - Honeycomb 的插件存储库，Cymmetria 的蜜罐框架.
  - [honeyntp](https://github.com/fygrave/honeyntp) - NTP 记录器/蜜罐.
  - [honeypot-camera](https://github.com/alexbredo/honeypot-camera) - 观察相机蜜罐.
  - [honeypot-ftp](https://github.com/alexbredo/honeypot-ftp) - FTP 蜜罐.
  - [honeypots](https://github.com/qeeqbox/honeypots)  - 一个 pypi 包中有 25 个不同的蜜罐！  （dns、ftp、httpproxy、http、https、imap、mysql、pop3、postgres、redis、smb、smtp、socks5、ssh、telnet、vnc、mssql、elastic、ldap、ntp、memcache、snmp、oracle、sip 和 irc ）.
  - [honeytrap](https://github.com/honeytrap/honeytrap) - 用Go编写的高级蜜罐框架，可以与其他蜜罐软件连接.
  - [HoneyPy](https://github.com/foospidy/HoneyPy) - 低交互蜜罐.
  - [Honeygrove](https://github.com/UHH-ISS/honeygrove) - 基于 Twisted 的多用途模块化蜜罐.
  - [Honeyport](https://github.com/securitygeneration/Honeyport) - 用 Bash 和 Python 编写的简单 honeyport.
  - [Honeyprint](https://github.com/glaslos/honeyprint) - 打印机蜜罐.
  - [ListenSSH](https://github.com/GhostSlayer/ListenSSH) - 轻松向 AbuseIPDB 报告任何端口上的所有连接尝试.
  - [Lyrebird](https://hub.docker.com/r/lyrebird/honeypot-base/) - 现代高交互蜜罐框架.
  - [MICROS honeypot](https://github.com/Cymmetria/micros_honeypot) - 低交互蜜罐，用于检测 Oracle Hospitality Applications (MICROS) 的 Oracle Hospitality Simphony 组件中的 CVE-2018-2636.
  - [node-ftp-honeypot](https://github.com/christophe77/node-ftp-honeypot) - JS 中的 FTP 服务器蜜罐.
  - [pyrdp](https://github.com/gosecure/pyrdp) - RDP 中间人和 Python 3 库，能够实时或事后观察连接.
  - [RDPy](https://github.com/citronneur/rdpy) - 用 Python 实现的 Microsoft 远程桌面协议 (RDP) 蜜罐.
  - [SMB Honeypot](https://github.com/r0hi7/HoneySMB) - 高交互性 SMB 服务蜜罐，能够捕获类似恶意软件的恶意软件.
  - [Tom's Honeypot](https://github.com/inguardians/toms_honeypot) - 低交互Python蜜罐.
  - [troje](https://github.com/dutchcoders/troje/) - 蜜罐在单独的 LXC 容器中运行与服务的每个连接.
  - [WebLogic honeypot](https://github.com/Cymmetria/weblogic_honeypot) - 低交互蜜罐可检测 Oracle 融合中间件的 Oracle WebLogic Server 组件中的 CVE-2017-10271.
  - [WhiteFace Honeypot](https://github.com/csirtgadgets/csirtg-honeypot) - 基于 Twisted 的 WhiteFace 蜜罐.
 
- 分布式蜜罐

  - [DemonHunter](https://github.com/RevengeComing/DemonHunter) - 低交互蜜罐服务器.

- 反蜜罐的东西

  - [kippo_detect](https://github.com/andrew-morris/kippo_detect) - 检测 kippo 蜜罐存在的攻击性组件.

- ICS/SCADA 蜜罐

  - [Conpot](https://github.com/mushorg/conpot) - ICS/SCADA 蜜罐.
  - [GasPot](https://github.com/sjhilt/GasPot) - Veeder Root Gaurdian AST，常见于石油和天然气行业.
  - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - 为工业网络构建蜜罐.
  - [gridpot](https://github.com/sk4ld/gridpot) - 用于表现真实的电网蜜网的开源工具.
  - [scada-honeynet](http://www.digitalbond.com/blog/2007/07/24/scada-honeynet-article-in-infragard-publication/) - 模仿流行 PLC 的许多服务，更好地帮助 SCADA 研究人员了解暴露的控制系统设备的潜在风险.

- 其他/随机

  - [CitrixHoneypot](https://github.com/MalwareTech/CitrixHoneypot) - 检测并记录 CVE-2019-19781 扫描和利用尝试.
  - [Damn Simple Honeypot (DSHP)](https://github.com/naorlivne/dshp) - 具有可插入处理程序的蜜罐框架.
  - [dicompot](https://github.com/nsmfoo/dicompot) - DICOM 蜜罐.
  - [IPP Honey](https://gitlab.com/bontchev/ipphoney) - 用于互联网打印协议的蜜罐.
  - [Log4Pot](https://github.com/thomaspatzke/Log4Pot) - 针对 Log4Shell 漏洞 (CVE-2021-44228) 的蜜罐.
  - [Masscanned](https://github.com/ivre/masscanned)  - 让我们进行扫描. 专注于网络扫描仪和机器人的低交互蜜罐. 它与 IVRE 集成得很好，可以构建 GreyNoise 的自托管替代方案.
  - [medpot](https://github.com/schmalle/medpot) - HL7/FIR 蜜罐.
  - [NOVA](https://github.com/DataSoft/Nova) - 使用蜜罐作为探测器，看起来像一个完整的系统.
  - [OpenFlow Honeypot (OFPot)](https://github.com/upa/ofpot) - 将未使用的 IP 的流量重定向到基于 POX 构建的蜜罐.
  - [OpenCanary](https://github.com/thinkst/opencanary) - 模块化和去中心化的蜜罐守护进程，运行多个金丝雀版本的服务，在服务被（滥用）使用时发出警报.
  - [ciscoasa_honeypot](https://github.com/cymmetria/ciscoasa_honeypot) 用于 Cisco ASA 组件的低交互蜜罐，能够检测 CVE-2018-0101、DoS 和远程代码执行漏洞.
  - [miniprint](https://github.com/sa7mon/miniprint) - 中等交互打印机蜜罐.

- 僵尸网络C2工具

  - [Hale](https://github.com/pjlantz/Hale) - 僵尸网络命令和控制监视器.
  - [dnsMole](https://code.google.com/archive/p/dns-mole/) - 分析 DNS 流量并可能检测僵尸网络命令和控制服务器活动以及受感染的主机.

- IPv6攻击检测工具

  - [ipv6-attack-detector](https://github.com/mzweilin/ipv6-attack-detector/) - Google Summer of Code 2012 项目，由 Honeynet 项目组织支持.

- 动态代码检测工具包

  - [Frida](https://www.frida.re) - 注入 JavaScript 以探索 Windows、Mac、Linux、iOS 和 Android 上的本机应用程序.

- 将网站转换为服务器蜜罐的工具

  - [HIHAT](http://hihat.sourceforge.net/) - 将任意 PHP 应用程序转换为基于 Web 的高交互蜜罐.

- 恶意软件收集器

  - [Kippo-Malware](https://bruteforcelab.com/kippo-malware) - Python 脚本将下载以 URL 形式存储在 Kippo SSH 蜜罐数据库中的所有恶意文件.

- 分布式传感器部署

  - [Community Honey Network](https://communityhoneynetwork.readthedocs.io/en/stable/)  - CHN 旨在使蜜罐和蜜罐管理工具的部署变得简单、灵活. 默认的部署方法使用 Docker Compose 和 Docker，只需几个简单的命令即可进行部署.
  - [Modern Honey Network](https://github.com/threatstream/mhn) - 多 Snort 和蜜罐传感器管理，使用虚拟机网络、小型 SNORT 安装、隐秘的 dionaeas 和集中管理服务器.

- 网络分析工具

  - [Tracexploit](https://code.google.com/archive/p/tracexploit/) - 重放网络数据包.

- 记录匿名器

  - [LogAnon](http://code.google.com/archive/p/loganon/) - 日志匿名库，有助于使匿名日志在日志和网络捕获之间保持一致.

- 低交互蜜罐（路由器后门）

  - [Honeypot-32764](https://github.com/knalli/honeypot-for-tcp-32764) - 路由器后门蜜罐 (TCP 32764).
  - [WAPot](https://github.com/lcashdol/WAPot) - 可用于观察指向家庭路由器的流量的蜜罐.

- 蜜网农场流量重定向器

  - [Honeymole](https://web.archive.org/web/20100326040550/http://www.honeynet.org.pt:80/index.php/HoneyMole) - 部署多个传感器，将流量重定向到集中的蜜罐集合.

- HTTPS 代理

  - [mitmproxy](https://mitmproxy.org/) - 允许拦截、检查、修改和重放流量.

- 系统仪表

  - [Sysdig](https://sysdig.com/opensource/) - 开源的系统级探索允许人们从正在运行的 GNU/Linux 实例捕获系统状态和活动，然后保存、过滤和分析结果.
  - [Fibratus](https://github.com/rabbitstack/fibratus) - 用于探索和跟踪 Windows 内核的工具.

- 用于 USB 传播恶意软件的蜜罐

  - [Ghost-usb](https://github.com/honeynet/ghost-usb-honeypot) - 针对通过 USB 存储设备传播的恶意软件的蜜罐.

- 数据采集

  - [Kippo2MySQL](https://bruteforcelab.com/kippo2mysql) - 从 Kippo 的基于文本的日志文件中提取一些非常基本的统计数据并将其插入 MySQL 数据库中.
  - [Kippo2ElasticSearch](https://bruteforcelab.com/kippo2elasticsearch) - 用于将数据从 Kippo SSH 蜜罐 MySQL 数据库传输到 ElasticSearch 实例（服务器或集群）的 Python 脚本.

- 被动网络审计框架解析器

  - [Passive Network Audit Framework (pnaf)](https://github.com/jusafing/pnaf) - 结合多种被动和自动分析技术的框架，以提供网络平台的安全评估.

- 虚拟机监控和工具

  - [Antivmdetect](https://github.com/nsmfoo/antivmdetection) - 用于创建与 VirtualBox 一起使用的模板的脚本，以使 VM 检测更加困难.
  - [VMCloak](https://github.com/hatching/vmcloak) - Cuckoo Sandbox 的自动虚拟机生成和伪装.
  - [vmitools](http://libvmi.com/) - 具有 Python 绑定的 C 库，可以轻松监控正在运行的虚拟机的低级详细信息.

- 二进制调试器

  - [Hexgolems - Pint Debugger Backend](https://github.com/hexgolems/pint) - 调试器后端和 PIN 的 LUA 包装器.
  - [Hexgolems - Schem Debugger Frontend](https://github.com/hexgolems/schem) - 调试器前端.

- 移动分析工具

  - [Androguard](https://github.com/androguard/androguard) - Android 应用程序的逆向工程、恶意软件和良好软件分析等.
  - [APKinspector](https://github.com/honeynet/apkinspector/) - 强大的 GUI 工具，可供分析师分析 Android 应用程序.

- 低交互蜜罐

  - [Honeyperl](https://sourceforge.net/projects/honeyperl/) - 基于 Perl 的蜜罐软件，带有为许多功能开发的插件，如：wingates、telnet、squid、smtp 等.
  - [T-Pot](https://github.com/dtag-dev-sec/tpotce) - 来自电信提供商 T-Mobile 的多合一蜜罐设备
  - [beelzebub](https://github.com/mariocandela/beelzebub) - 一个安全的蜜罐框架，非常容易通过yaml配置

- 蜜网数据融合

  - [HFlow2](https://projects.honeynet.org/hflow) - 用于蜜网/网络分析的数据合并工具.

- 服务器

  - [Amun](http://amunhoney.sourceforge.net) - 漏洞模拟蜜罐.
  - [Artillery](https://github.com/trustedsec/artillery/) - Open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods.
  - [Bait and Switch](http://baitnswitch.sourceforge.net) - 将所有恶意流量重定向到部分镜像您的生产系统的蜜罐.
  - [Bifrozt](https://github.com/Ziemeck/bifrozt-ansible) - 使用ansible自动部署bifrozt.
  - [Conpot](http://conpot.org/) - 低交互服务器端工业控制系统蜜罐.
  - [Heralding](https://github.com/johnnykv/heralding) - 捕获蜜罐的凭据.
  - [HoneyWRT](https://github.com/CanadianJeff/honeywrt) - 低交互 Python 蜜罐，旨在模仿可能成为攻击者目标的服务或端口.
  - [Honeyd](https://github.com/provos/honeyd) - 看 [honeyd tools](#honeyd-tools).
  - [Honeysink](http://www.honeynet.org/node/773) - 开源网络污水坑，提供检测和预防给定网络上恶意流量的机制.
  - [Hontel](https://github.com/stamparm/hontel) - Telnet 蜜罐.
  - [KFSensor](http://www.keyfocus.net/kfsensor/) - 基于 Windows 的蜜罐入侵检测系统 (IDS).
  - [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - 接管未使用的 IP 地址，并创建对蠕虫、黑客和其他互联网用户有吸引力的虚拟服务器.
  - [MTPot](https://github.com/Cymmetria/MTPot) - 开源 Telnet 蜜罐，专注于 Mirai 恶意软件.
  - [SIREN](https://github.com/blaverick62/SIREN) - 半智能蜜罐网络 - HoneyNet 智能虚拟环境.
  - [TelnetHoney](https://github.com/balte/TelnetHoney) - 简单的远程登录蜜罐.
  - [UDPot Honeypot](https://github.com/jekil/UDPot) - 简单的 UDP/DNS 蜜罐脚本.
  - [Yet Another Fake Honeypot (YAFH)](https://github.com/fnzv/YAFH) - Simple honeypot written in Go.
  - [arctic-swallow](https://github.com/ajackal/arctic-swallow) - 低交互蜜罐.
  - [fapro](https://github.com/fofapro/fapro) - 假协议服务器.
  - [glutton](https://github.com/mushorg/glutton) - All eating honeypot.
  - [go-HoneyPot](https://github.com/Mojachieee/go-HoneyPot) - 用 Go 编写的蜜罐服务器.
  - [go-emulators](https://github.com/kingtuna/go-emulators) - 蜜罐 Golang 模拟器.
  - [honeymail](https://github.com/sec51/honeymail) - 用 Golang 编写的 SMTP 蜜罐.
  - [honeytrap](https://github.com/tillmannw/honeytrap) - 低交互蜜罐和网络安全工具，旨在捕获针对 TCP 和 UDP 服务的攻击.
  - [imap-honey](https://github.com/yvesago/imap-honey) - 用 Golang 编写的 IMAP 蜜罐.
  - [mwcollectd](https://www.openhub.net/p/mwcollectd) - 多功能恶意软件收集守护进程，结合了猪笼草和蜜罐的最佳功能.
  - [potd](https://github.com/lnslbrty/potd) - 高度可扩展的低到中交互 SSH/TCP 蜜罐，专为 OpenWrt/IoT 设备而设计，利用多种 Linux 内核功能，例如命名空间、seccomp 和线程功能.
  - [portlurker](https://github.com/bartnv/portlurker) - Rust 中的端口侦听器，具有协议猜测和安全字符串显示功能.
  - [slipm-honeypot](https://github.com/rshipp/slipm-honeypot) - 简单的低交互端口监控蜜罐.
  - [telnet-iot-honeypot](https://github.com/Phype/telnet-iot-honeypot) - 用于捕获僵尸网络二进制文件的 Python telnet 蜜罐.
  - [telnetlogger](https://github.com/robertdavidgraham/telnetlogger) - Telnet 蜜罐旨在跟踪 Mirai 僵尸网络.
  - [vnclowpot](https://github.com/magisterquis/vnclowpot) - 低交互VNC蜜罐.

- IDS签名生成

  - [Honeycomb](http://www.icir.org/christian/honeycomb/) - 使用蜜罐自动创建签名.

- AS 编号和前缀的查找服务

  - [CC2ASN](http://www.cc2asn.com/) - 属于世界上任何给定国家的 AS 号码和前缀的简单查找服务.

- 数据收集/数据共享

  - [HPfriends](http://hpfriends.honeycloud.net/#/home) - 蜜罐数据共享平台.
    - [hpfriends - real-time social data-sharing](https://heipei.io/sigint-hpfriends/) - 关于HPFriends feed系统的介绍
  - [HPFeeds](https://github.com/rep/hpfeeds/) - 轻量级认证发布-订阅协议.

- 中央管理工具

  - [PHARM](http://www.nepenthespharm.com/) - 管理、报告和分析您的分布式 Nepenthes 实例.

- 网络连接分析器

  - [Impost](http://impost.sourceforge.net/) - 网络安全审计工具，旨在分析受损和/或易受攻击的守护程序背后的取证.

- 蜜罐部署

  - [Modern Honeynet Network](http://threatstream.github.io/mhn/) - 简化安全蜜罐的部署和管理.

- Wireshark 的蜜罐扩展

  - [Wireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) - 使用 Wireshark 对数据包捕获文件应用 Snort IDS 规则和签名.

- 客户

  - [CWSandbox / GFI Sandbox](https://www.gfi.com/products-and-solutions/all-products)
  - [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
  - [Capture-HPC-NG](https://github.com/CERT-Polska/HSN-Capture-HPC-NG)
  - [Capture-HPC](https://projects.honeynet.org/capture-hpc) - 高交互客户端蜜罐（也称为 honeyclient）.
  - [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
  - [HoneyC](https://projects.honeynet.org/honeyc)
  - [HoneySpider Network](https://github.com/CERT-Polska/hsn2-bundle) - 高度可扩展的系统集成多个客户端蜜罐来检测恶意网站.
  - [HoneyWeb](https://code.google.com/archive/p/gsoc-honeyweb/) - 创建 Web 界面来管理和远程共享 Honeyclients 资源.
  - [Jsunpack-n](https://github.com/urule99/jsunpack-n)
  - [MonkeySpider](http://monkeyspider.sourceforge.net)
  - [PhoneyC](https://github.com/honeynet/phoneyc) - Python honeyclient（后来被Thug取代）.
  - [Pwnypot](https://github.com/shjalayeri/pwnypot) - 高交互客户端蜜罐.
  - [Rumal](https://github.com/thugs-rumal/) - 暴徒的鲁马尔：暴徒的衣服和武器.
  - [Shelia](https://www.cs.vu.nl/~herbertb/misc/shelia/) - 用于攻击检测的客户端蜜罐.
  - [Thug](https://buffer.github.io/thug/) - 基于Python的低交互honeyclient.
  - [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.io/en/latest/index.html)
  - [Trigona](https://www.honeynet.org/project/Trigona)
  - [URLQuery](https://urlquery.net/)
  - [YALIH (Yet Another Low Interaction Honeyclient)](https://github.com/Masood-M/yalih) - 低交互客户端蜜罐，旨在通过签名、异常和模式匹配技术检测恶意网站.

- 蜜罐

  - [Deception Toolkit](http://www.all.net/dtk/dtk.html)
  - [IMHoneypot](https://github.com/mushorg/imhoneypot)

- PDF文档检查器

  - [peepdf](https://github.com/jesparza/peepdf) - 强大的Python工具来分析PDF文档.

- 混合低/高交互蜜罐

  - [HoneyBrid](http://honeybrid.sourceforge.net)

- SSH 蜜罐

  - [Blacknet](https://github.com/morian/blacknet) - 多头SSH蜜罐系统.
  - [Cowrie](https://github.com/cowrie/cowrie) - Cowrie SSH 蜜罐（基于 kippo）.
  - [DShield docker](https://github.com/xme/dshield-docker) - 运行 cowrie 并启用 DShield 输出的 Docker 容器.
  - [endlessh](https://github.com/skeeto/endlessh)  - SSH tarpit 缓慢发送无尽的横幅.  （[docker image](https://hub.docker.com/r/linuxserver/endlessh))
  - [HonSSH](https://github.com/tnich/honssh) - 记录客户端和服务器之间的所有 SSH 通信.
  - [HUDINX](https://github.com/Cryptix720/HUDINX) - 用 Python 设计的微型交互 SSH 蜜罐，用于记录暴力攻击，最重要的是，记录攻击者执行的整个 shell 交互.
  - [Kippo](https://github.com/desaster/kippo) - 中等交互的 SSH 蜜罐.
  - [Kippo_JunOS](https://github.com/gregcmartin/Kippo_JunOS) - Kippo 配置为后门网络屏幕.
  - [Kojoney2](https://github.com/madirish/kojoney2) - 用 Python 编写的低交互 SSH 蜜罐，基于 Jose Antonio Coret 的 Kojoney.
  - [Kojoney](http://kojoney.sourceforge.net/) - 基于 Python 的低交互蜜罐，模拟使用 Twisted Conch 实现的 SSH 服务器.
  - [Longitudinal Analysis of SSH Cowrie Honeypot Logs](https://github.com/deroux/longitudinal-analysis-cowrie) - 基于Python的命令行工具，用于分析cowrie日志随时间的变化.
  - [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) - 分析 SSH 蜜罐日志.
  - [Malbait](https://github.com/batchmcnulty/Malbait) - 用 Perl 实现的简单 TCP/UDP 蜜罐.
  - [MockSSH](https://github.com/ncouture/MockSSH) - 模拟 SSH 服务器并定义它​​支持的所有命令（Python、Twisted）.
  - [cowrie2neo](https://github.com/xlfe/cowrie2neo) - 将cowrie蜜罐日志解析到neo4j数据库中.
  - [go-sshoney](https://github.com/ashmckenzie/go-sshoney) - SSH 蜜罐.
  - [go0r](https://github.com/fzerorubigd/go0r) - Golang 中的简单 ssh 蜜罐.
  - [gohoney](https://github.com/PaulMaddox/gohoney) - 用 Go 编写的 SSH 蜜罐.
  - [hived](https://github.com/sahilm/hived) - 基于 Golang 的蜜罐.
  - [hnypots-agent)](https://github.com/joshrendek/hnypots-agent) - Go 中的 SSH 服务器记录用户名和密码组合.
  - [honeypot.go](https://github.com/mdp/honeypot.go) - 用 Go 编写的 SSH 蜜罐.
  - [honeyssh](https://github.com/ppacher/honeyssh) - 带有统计信息的凭证转储 SSH 蜜罐.
  - [hornet](https://github.com/czardoz/hornet) - 支持多个虚拟主机的中等交互 SSH 蜜罐.
  - [ssh-auth-logger](https://github.com/JustinAzoff/ssh-auth-logger) - 低/零交互 SSH 身份验证日志记录蜜罐.
  - [ssh-honeypot](https://github.com/droberson/ssh-honeypot) - 记录 IP 地址、用户名和密码的假 sshd.
  - [ssh-honeypot](https://github.com/amv42/sshd-honeypot) - OpenSSH 守护程序的修改版本，将命令转发到 Cowrie，所有命令都在其中解释并返回.
  - [ssh-honeypotd](https://github.com/sjinks/ssh-honeypotd) - 用 C 语言编写的低交互 SSH 蜜罐.
  - [sshForShits](https://github.com/traetox/sshForShits) - 高交互 SSH 蜜罐的框架.
  - [sshesame](https://github.com/jaksi/sshesame) - 假的 SSH 服务器，让每个人都可以登录并记录他们的活动.
  - [sshhipot](https://github.com/magisterquis/sshhipot) - 高交互 MitM SSH 蜜罐.
  - [sshlowpot](https://github.com/magisterquis/sshlowpot) - Go 中的另一个简洁的低交互 SSH 蜜罐.
  - [sshsyrup](https://github.com/mkishere/sshsyrup) - 简单的 SSH 蜜罐，具有捕获终端活动并上传到 asciinema.org 的功能.
  - [twisted-honeypots](https://github.com/lanjelot/twisted-honeypots) - 基于 Twisted 的 SSH、FTP 和 Telnet 蜜罐.

- 分布式传感器项目

  - [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)

- pcap分析仪

  - [Honeysnap](https://projects.honeynet.org/honeysnap/)

- 网络流量重定向器

  - [Honeywall](https://projects.honeynet.org/honeywall/)

- 混合内容的蜜罐分发

  - [HoneyDrive](https://bruteforcelab.com/honeydrive)

- 蜜罐传感器

  - [Honeeepi](https://redmine.honeynet.org/projects/honeeepi/wiki) - Raspberry Pi 上的蜜罐传感器基于定制的 Raspbian 操作系统.

- 文件雕刻

  - [TestDisk & PhotoRec](https://www.cgsecurity.org/)

- win32行为分析工具

  - [Capture BAT](https://www.honeynet.org/node/315)

- 现场CD

  - [DAVIX](https://www.secviz.org/node/89) - DAVIX 现场 CD.

- 垃圾邮件陷阱

  - [Mail::SMTP::Honeypot](https://metacpan.org/pod/release/MIKER/Mail-SMTP-Honeypot-0.11/Honeypot.pm) - Perl 模块似乎提供标准 SMTP 服务器的功能.
  - [Mailoney](https://github.com/awhitehatter/mailoney) - 用 python 编写的 SMTP 蜜罐、Open Relay、Cred Harvester.
  - [SendMeSpamIDS.py](https://github.com/johestephan/VerySimpleHoneypot) - 简单的 SMTP 获取所有 IDS 和分析器.
  - [Shiva](https://github.com/shiva-spampot/shiva) - 带有智能虚拟分析器的垃圾邮件蜜罐.
    - [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/security-blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)
  - [SpamHAT](https://github.com/miguelraulb/spamhat) - 垃圾邮件蜜罐工具.
  - [Spamhole](http://www.spamhole.net/)
  - [honeypot](https://github.com/jadb/honeypot) - 蜜罐项目非官方 PHP SDK.
  - [spamd](http://man.openbsd.org/cgi-bin/man.cgi?query=spamd%26apropos=0%26sektion=0%26manpath=OpenBSD+Current%26arch=i386%26format=html)

- 商业蜜网

  - [Cymmetria Mazerunner](https://github.com/paralax/awesome-honeypots/blob/master/ttps://cymmetria.com/products/mazerunner/) - 引导攻击者远离真实目标并创建攻击足迹.

- 服务器（蓝牙）

  - [Bluepot](https://github.com/andrewmichaelsmith/bluepot)

- Android应用程序的动态分析

  - [Droidbox](https://code.google.com/archive/p/droidbox/)

- Docker化的低交互包装

  - [Docker honeynet](https://github.com/sreinhardt/Docker-Honeynet) - 为 Docker 容器设置的几个 Honeynet 工具.
  - [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/) - Docker化 [Thug](https://github.com/buffer/thug) 分析恶意网页内容.
  - [Dockerpot](https://github.com/mrschyte/dockerpot) - 基于 Docker 的蜜罐.
  - [Manuka](https://github.com/andrewmichaelsmith/manuka) - 基于 Docker 的蜜罐（Dionaea 和 Kippo）.
  - [honey_ports](https://github.com/run41/honey_ports) - 非常简单但有效的 docker 部署蜜罐来检测您环境中的端口扫描.
  - [mhn-core-docker](https://github.com/MattCarothers/mhn-core-docker) - 在 Docker 中实现的现代蜂蜜网络的核心元素.

- 网络分析

  - [Quechua](https://bitbucket.org/zaccone/quechua)

- SIP服务器

  - [Artemnesia VoIP](http://artemisa.sourceforge.net)

- 啜

  - [SentryPeer](https://github.com/SentryPeer/SentryPeer) - 保护您的 SIP 服务器免受不良行为者的侵害.

- 物联网蜜罐

  - [HoneyThing](https://github.com/omererdem/honeything) - TR-069 蜜罐.
  - [Kako](https://github.com/darkarnium/kako) - 针对许多众所周知和已部署的嵌入式设备漏洞的蜜罐.

- 蜜币
  - [CanaryTokens](https://github.com/thinkst/canarytokens)  - 自托管蜜币生成器和报告仪表板； 演示版本可在 [CanaryTokens.org](https://canarytokens.org/generate).
  - [Honeybits](https://github.com/0x4D31/honeybits) - 简单的工具，旨在通过在生产服务器和工作站上传播面包屑和蜜币来引诱攻击者进入您的蜜罐，从而提高陷阱的有效性.
  - [Honeyλ (HoneyLambda)](https://github.com/0x4D31/honeylambda) - 简单的无服务器应用程序，旨在在 AWS Lambda 和 Amazon API Gateway 之上创建和监控 URL honeytoken.
  - [dcept](https://github.com/secureworks/dcept) - 用于部署和检测 Active Directory honeytoken 的使用的工具.
  - [honeyku](https://github.com/0x4D31/honeyku) - 基于 Heroku 的 Web 蜜罐，可用于创建和监控虚假 HTTP 端点（即蜜币）.

## Honeyd Tools

- Honeyd插件

  - [Honeycomb](http://www.honeyd.org/tools.php)

- 霍尼德查看器

  - [Honeyview](http://honeyview.sourceforge.net/)

- Honeyd 到 MySQL 连接器

  - [Honeyd2MySQL](https://bruteforcelab.com/honeyd2mysql)

- 一个脚本来可视化来自 honeyd 的统计数据

  - [Honeyd-Viz](https://bruteforcelab.com/honeyd-viz)

- 霍尼德统计
  - [Honeydsum.pl](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl)

## Network and Artifact Analysis

- 沙盒

  - [Argos](http://www.few.vu.nl/argos/) - 用于捕获零日攻击的模拟器.
  - [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
  - [Cuckoo](https://cuckoosandbox.org/) - 领先的开源自动化恶意软件分析系统.
  - [Pylibemu](https://github.com/buffer/pylibemu) - Libemu Cython 包装器.
  - [RFISandbox](https://monkey.org/~jose/software/rfi-sandbox/) - PHP 5.x 脚本沙箱构建于 [funcall](https://pecl.php.net/package/funcall).
  - [dorothy2](https://github.com/m4rco-/dorothy2) - 用 Ruby 编写的恶意软件/僵尸网络分析框架.
  - [imalse](https://github.com/hbhzwj/imalse) - 集成恶意软件模拟器和仿真器.
  - [libemu](https://github.com/buffer/libemu) - Shellcode 模拟库，对于 shellcode 检测很有用.

- 沙盒即服务

  - [Hybrid Analysis](https://www.hybrid-analysis.com) - 由 Payload Security 提供支持的免费恶意软件分析服务，使用独特的混合分析技术检测和分析未知威胁.
  - [Joebox Cloud](https://jbxcloud.joesecurity.org/login) - 分析 Windows、Android 和 Mac OS X 上恶意文件的行为，包括 PE、PDF、DOC、PPT、XLS、APK、URL 和 MachO，以发现可疑活动.
  - [VirusTotal](https://www.virustotal.com/) - 分析可疑文件和 URL 以检测恶意软件类型，并自动与安全社区共享.
  - [malwr.com](https://malwr.com/) - 免费恶意软件分析服务和社区.

## Data Tools

- 前端

  - [DionaeaFR](https://github.com/rubenespadas/DionaeaFR) - Front Web 到 Dionaea 低交互蜜罐.
  - [Django-kippo](https://github.com/jedie/django-kippo) - kippo SSH 蜜罐的 Django 应用程序.
  - [Shockpot-Frontend](https://github.com/GovCERT-CZ/Shockpot-Frontend) - 全功能脚本，用于可视化 Shockpot 蜜罐的统计数据.
  - [Tango](https://github.com/aplura/Tango) - Splunk 的蜜罐智能.
  - [Wordpot-Frontend](https://github.com/GovCERT-CZ/Wordpot-Frontend) - 全功能脚本，用于可视化来自 Wordpot 蜜罐的统计数据.
  - [honeyalarmg2](https://github.com/schmalle/honeyalarmg2) - 用于显示蜜罐警报的简化用户界面.
  - [honeypotDisplay](https://github.com/Joss-Steward/honeypotDisplay) - Flask 网站，显示从 SSH 蜜罐收集的数据.

- 可视化

  - [Acapulco](https://github.com/hgascon/acapulco) - 自动攻击社区图构建.
  - [Afterglow Cloud](https://github.com/ayrus/afterglow-cloud)
  - [Afterglow](http://afterglow.sourceforge.net/)
  - [Glastopf Analytics](https://github.com/katkad/Glastopf-Analytics) - 简单的蜜罐统计.
  - [HoneyMalt](https://github.com/SneakersInc/HoneyMalt) - Maltego 进行改造以映射蜜罐系统.
  - [HoneyMap](https://github.com/fw42/honeymap) - 精美的 SVG 世界地图上的 GPS 事件的实时 Websocket 流.
  - [HoneyStats](https://sourceforge.net/projects/honeystats/) - 蜜网上记录的活动的统计视图.
  - [HpfeedsHoneyGraph](https://github.com/yuchincheng/HpfeedsHoneyGraph) - 用于可视化 hpfeeds 日志的可视化应用程序.
  - [IVRE](https://github.com/ivre/ivre)  - 网络侦察框架，由 @cea-sec 和 @ANSSI-FR 发布. 构建您自己的、自托管且完全受控的 Crimeip / Shodan / ZoomEye / Censys 和 GreyNoise 的替代方案，运行您的被动 DNS 服务，从传感器收集和分析网络情报等等！
  - [Kippo stats](https://github.com/mfontani/kippo-stats) - Mojolicious 应用程序可显示 kippo SSH 蜜罐的统计信息.
  - [Kippo-Graph](https://bruteforcelab.com/kippo-graph) - 全功能脚本，用于可视化 Kippo SSH 蜜罐的统计数据.
  - [The Intelligent HoneyNet](https://github.com/jpyorre/IntelligentHoneyNet) - 从蜜罐创建可操作的信息.
  - [ovizart](https://github.com/oguzy/ovizart) - 网络流量的可视化分析.

## Guides

- [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)
- [Honeypot (Dionaea and kippo) setup script](https://github.com/andrewmichaelsmith/honeypot-setup-script/)

- 部署

  - [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) - 有关在 EC2 实例上设置 Dionaea 的教程.
  - [Using a Raspberry Pi honeypot to contribute data to DShield/ISC](https://isc.sans.edu/diary/22680) - 基于 Raspberry Pi 的系统将允许我们维护一个代码库，从而更轻松地收集防火墙日志之外的丰富日志.
  - [honeypotpi](https://github.com/free5ty1e/honeypotpi) - 将 Raspberry Pi 变成 HoneyPot Pi 的脚本.

- 调查报告

  - [Honeypot research papers](https://github.com/shbhmsingh72/Honeypot-Research-Papers) - 关于蜜罐的研究论文的 PDF.
  - [vEYE](https://link.springer.com/article/10.1007%2Fs10115-008-0137-3) - 用于自我传播蠕虫检测和分析的行为足迹.
