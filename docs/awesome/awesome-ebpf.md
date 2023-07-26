<div class="github-widget" data-repo="zoidbergwill/awesome-ebpf"></div>
## Awesome eBPF [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

&gt; 与 eBPF 相关的精彩项目的精选列表.

 BPF，如_Berkeley Packet Filter_中所示，是一个内核虚拟机，运行从用户空间传递的程序. 最初在 BSD 上实现，然后在 Linux 上实现，（现在是遗留的）“经典 BPF”或 cBPF 机器将与 tcpdump 等工具一起使用，用于过滤内核中的数据包，以避免无用的复制到用户空间. 最近，Linux 中的 BPF 基础设施已经完全重新设计，并为“扩展 BPF”或 eBPF 赋予了生命，它获得了新功能（安全和终止检查、程序的 JIT 编译、持久映射、标准库、硬件卸载）支持等），现在用于许多任务. 在极低级别处理数据包 (XDP)、跟踪和监视系统上的事件或对 cgroup 实施访问控制只是 eBPF 带来性能、可编程性和灵活性的几个示例.

Recently [Cilium](https://cilium.io) 推出了一个关于 eBPF 的优秀网站，名为 [ebpf.io](https://ebpf.io/) . 它的用途与此列表类似，其中 [an introduction to eBPF](https://ebpf.io/what-is-ebpf) 并链接到 [related projects](https://ebpf.io/projects).

 &gt; 注意：eBPF 是一项令人兴奋的技术，其生态系统正在不断发展. 我们希望得到_you_的帮助，使这个很棒的列表保持最新状态，并尽我们所能提高其信噪比. 请随意离开 [any feedback](https://github.com/zoidbergwill/awesome-ebpf/issues).



## Reference Documentation

### eBPF Essentials

- [ebpf.io](https://ebpf.io/) - 发现 eBPF 所有基础知识的门户，包括主要相关项目和社区资源的列表.
- [Cilium's BPF and XDP Reference Guide](http://docs.cilium.io/en/latest/bpf/) - 有关 eBPF 的大多数功能和方面的深入文档.

### Kernel Documentation

- [BPF Documentation](https://www.kernel.org/doc/html/latest/bpf/index.html) - Linux 内核附带的 BPF 相关文档索引.
- [linux/Documentation/networking/filter.rst](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/networking/filter.rst) - eBPF 规范（有些过时；信息应该仍然有效，但不详尽）.
- [BPF Design Q&A](https://www.kernel.org/doc/html/latest/bpf/bpf_design_QA.html) - 有关 BPF 基础设施背后决策的常见问题.
- [HOWTO interact with BPF subsystem](https://www.kernel.org/doc/html/latest/bpf/bpf_devel_QA.html) - 有关为 eBPF 开发做出贡献的常见问题.

### Manual Pages

- [`bpf(2)`](http://man7.org/linux/man-pages/man2/bpf.2.html) - 有关“bpf()”系统调用的手册页，用于管理用户空间中的 BPF 程序和映射.
- [`tc-bpf(8)`](http://man7.org/linux/man-pages/man8/tc-bpf.8.html) - 有关将 BPF 与 tc 结合使用的手册页，包括示例命令和代码示例.
- [`bpf-helpers(7)` man page](http://man7.org/linux/man-pages/man7/bpf-helpers.7.html) - 构成 BPF 标准库的内核辅助函数的描述.

### Other

- [IO Visor's Unofficial eBPF spec](https://github.com/iovisor/bpf-docs/blob/master/eBPF.md) - eBPF语法和操作代码总结.
- [Jesper Dangaard Brouer's documentation](https://prototype-kernel.readthedocs.io/en/latest/bpf/index.html) - 工作正在进行中，欢迎贡献.
- 大卫·米勒 (David Miller) 发给 [xdp-newbies](http://vger.kernel.org/vger-lists.html#xdp-newbies) 邮件列表：

  - [bpf.h and you...](https://www.spinics.net/lists/xdp-newbies/msg00179.html)
  - [Contextually speaking...](https://www.spinics.net/lists/xdp-newbies/msg00181.html)
  - [BPF Verifier Overview](https://www.spinics.net/lists/xdp-newbies/msg00185.html)

- [List of BPF features per kernel version](https://github.com/iovisor/bcc/blob/master/docs/kernel-versions.md)

## Articles and Presentations

### Generic eBPF Presentations and Articles

如果您是 eBPF 的新手，您可能想尝试本节中描述为“简介”的链接.

- [A brief introduction to XDP and eBPF](https://blogs.igalia.com/dpino/2019/01/07/introduction-to-xdp-and-ebpf/) - 易于理解的介绍，提供有关 eBPF 功能的背景、历史和详细信息.
- eBPF 概述 - Adrian Ratiu 的博客系列，涵盖了 eBPF 基础设施的许多方面：

  - [Part 1: Introduction](https://www.collabora.com/news-and-blog/blog/2019/04/05/an-ebpf-overview-part-1-introduction/)
  - [Part 2: Machine & Bytecode](https://www.collabora.com/news-and-blog/blog/2019/04/15/an-ebpf-overview-part-2-machine-and-bytecode/)

- [Ferris Ellis's blog posts about eBPF](https://ferrisellis.com/tags/ebpf/) - They have a few posts about eBPF:
  - [Part 1: Past, Present, and Future](https://ferrisellis.com/content/ebpf_past_present_future/)
  - [Part 2: Syscall and Map Types](https://ferrisellis.com/content/ebpf_syscall_and_maps/)
- [A BPF reference guide](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md) - 关于 BPF C 和 bcc Python 帮助程序，来自 bcc 存储库.
- [Making the Kernel's Networking Data Path Programmable with BPF and XDP](http://schd.ws/hosted_files/ossna2017/da/BPFandXDP.pdf) - 一组幻灯片，涵盖有关 eBPF 和 XDP 的所有基础知识（主要用于网络处理）.
- [The BSD Packet Filter](https://speakerdeck.com/tuxology/the-bsd-packet-filter) - 主要涵盖跟踪方面的介绍.
- [BPF: tracing and more](http://www.slideshare.net/brendangregg/bpf-tracing-and-more) - 主要涵盖跟踪方面的介绍.
- [Linux BPF Superpowers](http://www.slideshare.net/brendangregg/linux-bpf-superpowers) - 介绍主要涵盖跟踪方面，第一部分是火焰图.
- [IO Visor](https://www.socallinuxexpo.org/sites/default/files/presentations/Room%20211%20-%20IOVisor%20-%20SCaLE%2014x.pdf) - 还介绍了 [IO Visor project](https://www.iovisor.org/).
- [BPF -- in-kernel virtual machine](http://vger.kernel.org/netconf2015Starovoitov-bpf_collabsummit_2015feb20.pdf) - eBPF 作者的演示.
- [Extending extended BPF](https://lwn.net/Articles/603983/) - A blog post from 2014 on the development of BPF and demonstrating what can be done with it, using an example of stateful socket filtering by attaching an eBPF program to a socket.
- Greg Marsden 制作了一些关于 eBPF 的文档：
  - [A Tour of Program Types](https://blogs.oracle.com/linux/notes-on-bpf-1) - BPF 程序类型的所有现有挂钩及其兴趣的描述.
  - [BPF helper functions](https://blogs.oracle.com/linux/notes-on-bpf-2) - 回顾可以从 eBPF 程序中调用的内核函数.
  - [Communicating with Userspace](https://blogs.oracle.com/linux/notes-on-bpf-3) - BPF 如何与用户空间通信 - BPF 映射、性能事件、bpf_trace_printk.
  - [Building BPF Programs](https://blogs.oracle.com/linux/notes-on-bpf-4) - 设置环境来构建 BPF 程序.
  - [The BPF Bytecode and the BPF Verifier](https://blogs.oracle.com/linux/notes-on-bpf-5) - BPF如何保证程序安全？
  - [Using BPF to do Packet Transformation](https://blogs.oracle.com/linux/notes-on-bpf-6) - 一种有关数据包转换的 eBPF 用法.
- [Linux Kernel Observability through eBPF](https://sematext.com/blog/linux-kernel-observability-ebpf/) - 一篇博客文章，介绍了 eBPF 的基础知识以及 Go 中的代码示例，介绍了如何构建最小的 eBPF 程序并将其加载到内核中.
- [eBPF - From a Programmer's Perspective](https://www.researchgate.net/publication/349173667_eBPF_-_From_a_Programmer's_Perspective) - 一篇简短的论文，描述了 eBPF 的基础知识以及如何开始编写 eBPF 程序.
- [Cloudflare's blog posts on eBPF](https://blog.cloudflare.com/tag/ebpf/) - 有关网络用例和 eBPF 底层方面的不同博客文章.
- [Linux Extended BPF (eBPF) Tracing Tools](https://www.brendangregg.com/ebpf.html)  - 围绕使用 eBPF 的性能分析工具示例的深入信息收集. 页面末尾还包含有关其他资源的部分.
- [Beginner's guide to eBPF](https://github.com/lizrice/ebpf-beginners) - 一组实时编码讲座和随附的代码示例，介绍使用各种库和程序类型的 eBPF 编程.

### BPF Internals

- Daniel Borkmann 做了一些介绍 eBPF 内部结构的演讲和论文，特别是关于它与 tc 的使用.

  - [eBPF and XDP walkthrough and recent (2017) updates](https://fosdem.org/2017/schedule/event/ebpf_xdp/)
  - [Advanced programmability and recent updates with tc's cls_bpf](http://netdevconf.org/1.2/session.html?daniel-borkmann) - 有关 eBPF、其用于隧道和封装、直接数据包访问等的详细信息.
  - [cls_bpf/eBPF updates since netdev 1.1](http://netdevconf.org/1.2/slides/oct5/07_tcws_daniel_borkmann_2016_tcws.pdf) - 部分 [this tc workshop](http://netdevconf.org/1.2/session.html?jamal-tc-workshop).
  - [On getting tc classifier fully programmable with cls_bpf](http://www.netdevconf.org/1.1/proceedings/slides/borkmann-tc-classifier-cls-bpf.pdf)  - eBPF 简介，包括几个功能（映射管理、尾部调用、验证器）. 全文 [is also available here](http://www.netdevconf.org/1.1/proceedings/papers/On-getting-tc-classifier-fully-programmable-with-cls-bpf.pdf).
  - [Linux tc and eBPF](https://archive.fosdem.org/2016/schedule/event/ebpf/attachments/slides/1159/export/events/attachments/ebpf/slides/1159/ebpf.pdf)

- [IO Visor blog](https://www.iovisor.org/resources/blog)
- [Linux Networking Explained](http://www.slideshare.net/ThomasGraf5/linux-networking-explained) - Linux 网络内部结构，其中一部分是关于 eBPF 的.

### Kernel Tracing

- [Full-system dynamic tracing on Linux using eBPF and bpftrace](https://www.joyfulbikeshedding.com/blog/2019-01-31-full-system-dynamic-tracing-on-linux-using-ebpf-and-bpftrace.html) - 详细介绍了使用 eBPF 进行跟踪，从列出可用的跟踪点到运行 bpftrace 程序.
- [Meet-cute between eBPF and Kernel Tracing](http://www.slideshare.net/vh21/meet-cutebetweenebpfandtracing) - Kprobes、uprobes、ftrace.
- [Linux Kernel Tracing](http://www.slideshare.net/vh21/linux-kernel-tracing) - Systemtap、Kernelshark、trace-cmd、LTTng、perf-tool、ftrace、hist-trigger、perf、函数跟踪器、tracepoint、kprobe/uprobe 等.
- Brendan Gregg 的博客，特别是 [Linux BPF Superpowers](http://www.brendangregg.com/blog/2016-03-05/linux-bpf-superpowers.html) 文章.

### XDP

- [The eXpress Data Path](https://blogs.igalia.com/dpino/2019/01/10/the-express-data-path/) - 非常容易理解的 XDP 介绍，提供示例代码来展示如何处理数据包.
- 技术论文中的所有 XDP 详细信息： [The eXpress Data Path: Fast Programmable Packet Processing in the Operating System Kernel](https://github.com/tohojo/xdp-paper)，作者：Toke Høiland-Jørgensen、Jesper Dangaard Brouer、Daniel Borkmann、John Fastabend、Tom Herbert、David Ahern 和 David Miller，他们都是 eBPF 和 XDP 的重要贡献者.
- [Work-in-progress documentation for XDP](https://prototype-kernel.readthedocs.io/en/latest/networking/XDP/index.html)
- [BPF and XDP Reference Guide](http://docs.cilium.io/en/latest/bpf/) - 来自 Cilium 项目的指南.
- [XDP Project overview](https://www.iovisor.org/technology/xdp)
- [eXpress Data Path (XDP)](https://github.com/iovisor/bpf-docs/raw/master/Express_Data_Path.pdf) - 关于 XDP 的第一个演示.
- [BoF - What Can BPF Do For You?](https://events.linuxfoundation.org/sites/events/files/slides/iovisor-lc-bof-2016.pdf)
- [eXpress Data Path](http://www.slideshare.net/IOVisor/express-data-path-linux-meetup-santa-clara-july-2016) - 包含使用 mlx4 驱动程序获得的一些基准测试结果.
- Jesper Dangaard Brouer 有几组幻灯片描述了 XDP 的内部结构：

  - [XDP − eXpress Data Path, Intro and future use-cases](http://people.netfilter.org/hawk/presentations/xdp2016/xdp_intro_and_use_cases_sep2016.pdf)  - Linux 内核与 DPDK 的斗争.  XDP 的未来计划（截至撰写本文时）以及与 DPDK 的比较.
  - [Network Performance Workshop](http://netdevconf.org/1.2/session.html?jesper-performance-workshop) - 有关 XDP 内部结构和预期演变的其他提示.
  - [XDP – eXpress Data Path, Used for DDoS protection](http://people.netfilter.org/hawk/presentations/OpenSourceDays2017/XDP_DDoS_protecting_osd2017.pdf) - 有关 XDP 的详细信息和用例，包括基准测试结果、基准测试代码片段以及使用 eBPF/XDP 进行基本 DDoS 保护（基于 IP 黑名单方案）.
  - [Memory vs. Networking, Provoking and fixing memory bottlenecks](http://people.netfilter.org/hawk/presentations/MM-summit2017/MM-summit2017-JesperBrouer.pdf) - 有关 XDP 开发人员当前面临的内存问题的高级详细信息.
  - [XDP for the Rest of Us](http://netdevconf.org/2.1/session.html?gospodarek)  - 如何为普通人开始使用 eBPF 和 XDP. 朱莉娅·埃文斯 (Julia Evans) 也总结了 [her blog](http://jvns.ca/blog/2017/04/07/xdp-bpf-tutorial/).
  - [XDP now with REDIRECT](http://people.netfilter.org/hawk/presentations/LLC2018/XDP_LLC2018_redirect.pdf) - XDP 更新，特别是重定向操作.

- [XDP workshop -- Introduction, experience, and future development (Video)](http://netdevconf.org/1.2/session.html?herbert-xdp-workshop)
- [High Speed Packet Filtering on Linux](https://cdn.shopify.com/s/files/1/0177/9886/files/phv2017-gbertin.pdf) - 关于Linux上的数据包过滤、DDoS防护、内核中的数据包处理、内核旁路、XDP和eBPF.
- [How to drop 10 million packets per second](https://blog.cloudflare.com/how-to-drop-10-million-packets/) - Cloudflare 的博客文章谈论他们转向使用 XDP 进行数据包过滤.

### AF_XDP

- [AF_XDP](https://www.kernel.org/doc/html/latest/networking/af_xdp.html) - AF_XDP 地址族的内核文档.
- [Fast Packet Processing in Linux with AF_XDP](https://archive.fosdem.org/2018/schedule/event/af_xdp/)

### bpfilter

- [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/) - Cilium 发表的一篇关于 eBPF 和 bpfilter 背后动机的博客文章，其中包含几个示例以及使用 eBPF 和 bpfilter 的其他项目的链接.
- [bpfilter: Linux firewall with eBPF sauce](https://qmo.fr/docs/talk_20180316_frnog_bpfilter.pdf) - 幻灯片来自 Quentin Monnet 的演讲，内容涉及 eBPF 背景并将 bpfilter 与 iptables 进行比较.

### BTF

- [BPF Type Format (BTF)](https://www.kernel.org/doc/html/latest/bpf/btf.html) - 关于 BTF 的内核文档，解释如何使用它.
- [Enhancing the Linux kernel with BTF type information](https://facebookmicrosites.github.io/bpf/blog/2018/11/14/btf-enhancement.html) - 描述使用 BTF 为 BPF 程序提供调试信息所做的工作.

### cBPF

- [The BSD Packet Filter: A New Architecture for User-level Packet Capture](http://www.tcpdump.org/papers/bpf-usenix93.pdf) - 关于（经典）BPF 的原始论文.
- [The FreeBSD manual page about BPF](https://www.freebsd.org/cgi/man.cgi?query=bpf&sektion=4)
- [Linux' packet mmap(2), BPF, and Netsniff-NG](http://borkmann.ch/talks/2013_devconf.pdf)
- [tc and cls bpf: lightweight packet classifying with BPF](http://borkmann.ch/talks/2014_devconf.pdf)
- [Introducing Cloudflare's BPF Tools](https://blog.cloudflare.com/introducing-the-bpf-tools/) - 将 BPF 字节码与 iptables 的“xt_bpf”模块一起使用.
- [Libpcap filters syntax](http://biot.com/capstats/bpf.html)

### Hardware Offload

- [eBPF/XDP hardware offload to SmartNICs](http://netdevconf.org/1.2/session.html?jakub-kicinski) - 由 Netronome 引入的带有 TC 或 XDP（Linux 内核 4.9+）的 eBPF 硬件卸载.
- [Comprehensive XDP offload---Handling the edge cases](https://www.netdevconf.org/2.2/session.html?viljoen-xdpoffload-talk) - 上述主题的更新.
- [hBPF - eBPF in hardware](https://github.com/rprinz08/hBPF) - 为 FPGA 编写的 eBPF CPU.
- [OpenCSD eBPF SSD offloading](https://github.com/Dantali0n/qemu-csd) - 计算存储模拟 (QEMU) 平台，具有适用于分区命名空间 NVMe SSD 的 FUSE LFS 文件系统，使用 uBPF 进行计算内核卸载，全部在用户空间中.

## Tutorials

- [bcc Reference Guide](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md) - 开始使用密件抄送和 eBPF 的许多增量步骤，主要集中在跟踪和监控上.
- [bcc Python Developer Tutorial](https://github.com/iovisor/bcc/blob/master/docs/tutorial_bcc_python_developer.md) - 附带密件抄送，但针对十七个“课程”中的 Python 部分.
- [Building BPF applications with libbpf-bootstrap](https://nakryiko.com/posts/libbpf-bootstrap/) - 帮助生成最小或高级模板来引导您自己的应用程序（地图和程序的内核端和用户空间管理），具有 CO-RE、全局变量和环形缓冲区等功能.
- [How I ended up writing opensnoop in pure C using eBPF](https://bolinfest.github.io/opensnoop-native/) - 全面介绍如何编写 eBPF 程序，首先仅使用 bpf() 系统调用，然后使用 libbpf 库，并提供可重现的代码示例.
- [Linux Tracing Workshops Materials](https://github.com/goldshtn/linux-tracing-workshop) - 涉及使用多个 BPF 工具进行跟踪.
- [Tracing a packet journey using Linux tracepoints, perf and eBPF](https://blog.yadutaf.fr/2017/07/28/tracing-a-packet-journey-using-linux-tracepoints-perf-ebpf/) - 使用 perf 和 bcc 程序对 ping 请求和回复进行故障排除.
- [Open NFP platform](https://open-nfp.org/dataplanes-ebpf/technical-papers/) - 由 Netronome 运营：一些与网络相关的 eBPF 使用案例的教程，包括 eBPF 卸载入门指南.
- [XDP for the Rest of Us](http://netdevconf.org/2.1/session.html?gospodarek) - 第一版 XDP 入门研讨会.
- [XDP for the Rest of Us](https://www.netdevconf.org/2.2/session.html?gospodarek-xdp-workshop) - 第二版，有新内容.
- [Load XDP programs using the ip (iproute2) command](https://medium.com/@fntlnz/load-xdp-programs-using-the-ip-iproute2-command-502043898263)
- [XDP Hands-On Tutorial](https://github.com/xdp-project/xdp-tutorial) - A progressive (three levels of difficulty) tutorial to learn how to process packets with XDP.
- [All your tracing are belong to BPF](https://blog.trailofbits.com/2021/11/09/all-your-tracing-are-belong-to-bpf/) - 将 C++ 应用程序中的跟踪功能与 LLVM 库集成的分步演练.
- [Firewalling with BPF/XDP: Examples and Deep Dive](https://arthurchiao.art/blog/firewalling-with-bpf-xdp/) - 使用 TC 和 XDP 构建基本防火墙的简单指南.
- [A Deep Dive into eBPF: Writing an Efficient DNS Monitoring.](https://medium.com/@nurkholish.halim/a-deep-dive-into-ebpf-writing-an-efficient-dns-monitoring-2c9dea92abdf) - 详细解释了用于在套接字过滤层捕获 DNS 请求的方法.

## Examples

- [linux/samples/bpf/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/samples/bpf) - 在内核树中：一些示例 eBPF 程序.
- [linux/tools/testing/selftests/bpf](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/testing/selftests/bpf) - 在内核树中：Linux BPF 自测试，包含许多 eBPF 程序.
- [prototype-kernel/kernel/samples/bpf](https://github.com/netoptimizer/prototype-kernel/tree/master/kernel/samples/bpf) - Jesper Dangaard Brouer 的原型内核存储库包含一些可以在内核基础结构之外进行编译的其他示例.
- [iproute2/examples/bpf/](https://git.kernel.org/pub/scm/network/iproute2/iproute2-next.git/tree/examples/bpf) - 一些连接到 TC 接口的网络程序.
- [Netronome sample network applications](https://github.com/Netronome/bpf-samples/) - 提供基本但完整的 eBPF 应用程序示例，也与硬件卸载兼容.
- [bcc/examples](https://github.com/iovisor/bcc/tree/master/examples) - 密件抄送工具附带的示例，主要是关于跟踪.
- [bcc/tools](https://github.com/iovisor/bcc/tree/master/tools)  - 这些工具本身可以被视为 BPF 程序的示例用例，主要用于跟踪和监控.  bcc 工具已针对某些 Linux 发行版进行了打包.
- [MPLSinIP sample](https://github.com/fzakaria/eBPF-mpls-encap-decap)  - 一个广受好评的示例，演示如何在 IP 内封装和解封装 MPLS. 该代码为 BPF 开发新手提供了注释.
- [ebpf-samples](https://github.com/vbpf/ebpf-samples) - 从多个项目收集的已编译（作为 ELF 目标文件）样本的集合，主要用作用户空间验证程序的测试用例.
- [ebpf-kill-example](https://github.com/niclashedam/ebpf-kill-example) - eBPF 探针的完整记录和测试示例，记录所有强制终止并将其打印在用户空间中.
- [redbpf examples](https://github.com/foniod/redbpf/tree/main/examples) - 使用 RedBPF 在 Rust 中编写 eBPF 程序的示例程序.

## eBPF Workflow: Tools and Utilities

### bcc

- [bcc](https://github.com/iovisor/bcc/)  - 框架和工具集 - 处理 BPF 程序的一种方法，特别是用于跟踪和监视. 还包括一些可以帮助检查系统上的地图或程序的实用程序.
- [Lua front-end for BCC](https://github.com/iovisor/bcc/tree/master/src/lua) - C 的另一种替代方案，甚至是 bcc 中使用的大多数 Python 代码的另一种替代方案.

### iproute2

- [iproute2](https://git.kernel.org/pub/scm/network/iproute2/iproute2.git)  - 包含 Linux 上网络管理工具的软件包. 特别是，它包含用于管理 eBPF 过滤器和操作的“tc”，以及用于管理 XDP 程序的“ip”. 大部分与BPF相关的代码都在lib/bpf.c中.
- [iproute2-next](https://git.kernel.org/pub/scm/network/iproute2/iproute2-next.git) - 开发树，与net-next同步.

### LLVM

- [LLVM](https://llvm.org/)  - 包含 eBPF 工作流程中使用的多个工具. 可以从以下位置检索 Ubuntu/Debian 最新版本的快照 [here](http://apt.llvm.org/).

   - clang 用于将 C 编译为 ELF 格式的 eBPF 目标文件（clang v3.7.1+）.  BPF 后端添加了 [this commit](https://reviews.llvm.org/D6494).
  - llvm-objdump 用于以人类可读的格式转储目标文件的内容，可能带有初始 C 源代码 (llvm-objdump v4.0+).
  - llvm-mc 用于从 LLVM 中间表示编译为 eBPF 目标文件，以便可以从 C 编译为 eBPF 程序集，修补程序集，然后编译为 ELF 文件.

### libbpf

- [libbpf](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/tools/lib/bpf)  - AC 库用于处理 BPF 对象（程序和映射），并操作包含它们的 ELF 对象文件. 它随内核一起提供，并且 [mirrored on GitHub](https://github.com/libbpf/libbpf).
- [libbpf-bootstrap](https://github.com/libbpf/libbpf-bootstrap) - 使用 libbpf 和 BPF CO-RE 进行 BPF 应用程序开发的脚手架.

### Go libraries

- [cilium/ebpf](https://github.com/cilium/ebpf) - Pure-Go 库，用于读取、修改和加载 eBPF 程序并将它们附加到 Linux 内核中的各种挂钩.
- [libbpfgo](https://github.com/aquasecurity/libbpfgo) - Go 的 eBPF 库，由 libbpf 提供支持.
- [gobpf](https://github.com/iovisor/gobpf) - 用于 BCC 的 Go 绑定，用于创建 eBPF 程序.

### Aya

- [aya](https://github.com/aya-rs/aya)  - 一个纯 Rust 库，用于编写、加载和管理 eBPF 对象，重点关注开发人员体验和可操作性. 它支持用 Rust 编写 eBPF 程序，并通过 crates.io 分发库代码以在 eBPF 程序之间共享.  Aya 不依赖于 libbpf.
- [aya-template](https://github.com/aya-rs/aya-template) - 在 Aya 中编写 BPF 应用程序的模板，可与 [`cargo generate`](https://github.com/cargo-generate/cargo-generate).

### zbpf

- [zbpf](https://github.com/tw4452852/zbpf) - 用于编写跨平台 eBPF 程序的纯 Zig 框架，由 libbpf 和 Zig 工具链提供支持.

### eunomia-bpf

- [eunomia-bpf](https://github.com/eunomia-bpf/eunomia-bpf)  - 编译框架和运行时库，用于以多种语言和 WebAssembly 构建、分发、动态加载和运行 CO-RE eBPF 应用程序. 它支持仅编写 eBPF 内核代码（构建简单的 CO-RE libbpf eBPF 应用程序），以 BCC 和 libbpf 风格编写内核部分，以及在 WASM 模块中以多种语言编写用户空间并使用简单的 JSON 数据或 WASM OCI 进行分发图片. 运行时仅基于libbpf，为BCC风格的eBPF程序提供CO-RE，而不依赖于LLVM库.

### oxidebpf

- [oxidebpf](https://github.com/redcanaryco/oxidebpf)  - 用于管理 eBPF 程序的纯 Rust 库，专为安全用例而设计. 该功能集比其他库更受限制，但强调在各种内核和向后兼容的一次编译、运行最多的地方的稳定性.

### bpftool and Other Tools from the Kernel Tree

- [bpftool](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpftool) - 还有内核树中的一些其他工具，位于 [linux/tools/net/](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/net?h=v4.14) 对于 4.15 之前的版本，或者 [linux/tools/bpf/](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/tools/bpf) 在那之后：

  - [`bpftool`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpftool) - 一个通用实用程序，可用于与用户空间中的 eBPF 程序和映射进行交互，例如显示、转储、加载、反汇编、固定程序，或显示、创建、固定、更新、删除映射，或附加和分离到 cgroup 的程序.
  - [`bpf_asm`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_asm.c) - 一个最小的 cBPF 汇编器.
  - [`bpf_dbg`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_dbg.c) - cBPF 程序的小型调试器.
  - [`bpf_jit_disasm`](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/tree/tools/bpf/bpf_jit_disasm.c) - 两种 BPF 风格的反汇编器，对于 JIT 调试非常有用.

### User Space eBPF

- [uBPF](https://github.com/iovisor/ubpf/) - 用 C 语言编写.包含一个解释器、一个用于 x86_64 架构的 JIT 编译器、一个汇编器和一个反汇编器.
- [A generic implementation](https://github.com/YutaroHayakawa/generic-ebpf)  - 支持 FreeBSD 内核、FreeBSD 用户空间、Linux 内核、Linux 用户空间和 macOS 用户空间. 用于 [VALE software switch](https://www.unix.com/man-page/freebsd/4/vale/)'s [BPF extension module](https://github.com/YutaroHayakawa/vale-bpf).
- [rbpf](https://github.com/qmonnet/rbpf)  - 用 Rust 编写. 适用于 Linux、macOS 和 Windows 的解释器，以及适用于 Linux 下 x86_64 的 JIT 编译器.
- [PREVAIL](https://github.com/vbpf/ebpf-verifier) - eBPF 的用户空间验证器 [using an abstract interpretation layer](https://elazarg.github.io/pldi19main-final.pdf)，支持循环.
- [oster](https://github.com/grantseltzer/oster)  - 用 Go 编写. 一种通过将 eBPF 附加到 uprobes 来跟踪 Go 程序执行的工具.
- [wachy](https://rubrikinc.github.io/wachy/)  - 跟踪分析器，旨在使基于 eBPF uprobe 的调试更易于使用. 这是通过在源代码旁边的 UI 中显示跟踪并允许交互式深入分析来完成的.

### eBPF on Other Platforms

- [eBPF for Windows](https://github.com/microsoft/ebpf-for-windows) - 该项目是一个正在进行的工作，允许在 Windows 之上使用 Linux 生态系统中熟悉的现有 eBPF 工具链和 API.

### Testing in Virtual Environments

- [A Vagrant setup](https://github.com/iovisor/xdp-vagrant)  - 轻松测试XDP. 现在通用 XDP（独立于驱动程序，主要用于测试）存在，用处不大.
- [bcc in a Docker container](https://github.com/zlim/bcc-docker)

## Projects Related to eBPF

### Networking

- P4与eBPF有一些交互：

  - [P4 on the Edge](https://schd.ws/hosted_files/2016p4workshop/1d/Intel%20Fastabend-P4%20on%20the%20Edge.pdf) - P4 与 eBPF 一起创建高性能可编程交换机.
  - [OvS Orbit episode (#11), called P4 on the Edge](https://ovsorbit.org/#e11)  - 与前一项相关.  Open vSwitch 核心维护者之一 Ben Pfaff 对 John Fastabend 的音频采访.
  - [P4, EBPF and Linux TC Offload](https://open-nfp.org/m/documents/Open_NFP_P4_EBPF_Linux_TC_Offload_FINAL_5JHLETS.pdf) - P4 具有一些与 Netronome 的 NFP（网络流处理器）架构上的 eBPF 硬件卸载相关的元素.
  - [Old documentation for P4 usage with eBPF](https://github.com/iovisor/bcc/tree/master/src/cc/frontends/p4)  - 来自密件抄送存储库； 已被下面链接的 P4_16 后端弃用.
  - [P4_16 backend for eBPF](https://github.com/p4lang/p4c/blob/master/backends/ebpf/README.md)

- [Cilium](https://cilium.io/) 项目 （[GitHub repository](https://github.com/cilium/cilium) ）是一项依赖 BPF 和 XDP 的技术，为基于动态生成的 eBPF 程序的容器提供“快速的内核网络和安全策略实施”. 许多演示文稿可用（有重叠）：

  - [Cilium: Networking & Security for Containers with BPF & XDP](http://www.slideshare.net/ThomasGraf5/clium-container-networking-with-bpf-xdp) - 还具有负载均衡器用例
  - [Cilium: Networking & Security for Containers with BPF & XDP](http://www.slideshare.net/Docker/cilium-bpf-xdp-for-containers-66969823) - [video](https://www.youtube.com/watch?v=TnJF7ht3ZYc&list=PLkA60AVN3hh8oPas3cq2VA9xB7WazcIgs)
  - [Cilium: Fast IPv6 container Networking with BPF and XDP](http://www.slideshare.net/ThomasGraf5/cilium-fast-ipv6-container-networking-with-bpf-and-xdp)
  - [Cilium: BPF & XDP for containers](https://fosdem.org/2017/schedule/event/cilium/)
  - [OvS Orbit episode (#4)](https://ovsorbit.benpfaff.org/) - 本·普法夫 (Ben Pfaff) 对托马斯·格拉夫 (Thomas Graf) 的采访.
  - [A generic introduction to Cilium](https://opensource.googleblog.com/2016/11/cilium-networking-and-security.html)
  - [A podcast interviewing Thomas Graf](http://blog.ipspace.net/2016/10/fast-linux-packet-forwarding-with.html) - Ivan Pepelnjak 于 2016 年 10 月就 eBPF、P4、XDP 和 Cilium 采访 Thomas.

- Open vSwitch (OvS) 及其相关项目开放虚拟网络（OVN，一种开源网络虚拟化解决方案）正在考虑在各个级别使用 eBPF：

  - [Offloading OVS Flow Processing using eBPF](http://openvswitch.org/support/ovscon2016/7/1120-tu.pdf)
  - [Coupling the Flexibility of OVN with the Efficiency of IOVisor](http://openvswitch.org/support/ovscon2016/7/1245-bertrone.pdf)

- [Katran](https://code.fb.com/open-source/open-sourcing-katran-a-scalable-network-load-balancer/) - 基于 XDP 的第 4 层负载均衡器，由 Facebook 开源.
- [XDP in practice: integrating XDP in our DDoS mitigation pipeline](http://netdevconf.org/2.1/session.html?bertin) - Cloudflare 中使用 XDP 防御 DDoS.
- [Droplet: DDoS countermeasures powered by BPF + XDP](http://netdevconf.org/2.1/session.html?zhou) - 在 Facebook 上使用 XDP 防御 DDoS.
- [DPDK has a poll-mode driver (PMD) based on AF_XDP](https://dpdkuserspace2018.sched.com/event/G45Z/dpdk-pmd-for-afxdp)
- [CETH for XDP](http://www.slideshare.net/IOVisor/ceth-for-xdp-linux-meetup-santa-clara-july-2016) - 用于更快网络 I/O 的通用以太网驱动程序框架，这是由 Mellanox 发起的技术.
- Suricata，一个开源入侵检测系统， [relies on eBPF components](https://www.stamus-networks.com/2016/09/28/suricata-bypass-feature/) 其“捕获旁路”功能：

  - ["eBPF and XDP" section of Suricata documentation](http://suricata.readthedocs.io/en/latest/capture-hardware/ebpf-xdp.html?highlight=XDP#ebpf-and-xdp)
  - [SEPTun-Mark-II](https://github.com/pevma/SEPTun-Mark-II) - 极限性能调优指南 - Mark II.
  - [A blog post introducing the feature](https://www.stamus-networks.com/2016/09/28/suricata-bypass-feature/)
  - [The adventures of a Suricate in eBPF land](http://netdevconf.org/1.2/slides/oct6/10_suricata_ebpf.pdf)
  - [eBPF and XDP seen from the eyes of a meerkat](https://www.slideshare.net/ennael/kernel-recipes-2017-ebpf-and-xdp-eric-leblond)

- [Project Calico](https://projectcalico.docs.tigera.io/about/about-calico)  - Calico 是一个开源网络和网络安全解决方案，适用于容器、虚拟机和基于本机主机的工作负载.  Calico 的 eBPF 数据平面提供低延迟、高吞吐量的数据平面以及丰富的网络安全策略模型.
  - [Enabling eBPF data plane with Calico](https://projectcalico.docs.tigera.io/maintenance/ebpf/enabling-bpf)
- [merbridge](https://github.com/merbridge/merbridge/)  - 使用 eBPF 来加速您的服务网格.  Merbridge 用 eBPF 替换 iptables 规则来拦截流量. 它还结合了 msg_redirect，通过缩短 sidecar 和服务之间的数据路径来减少延迟.

### Observability

- [InKeV: In-Kernel Distributed Network Virtualization for DCN](https://github.com/iovisor/bpf-docs/blob/master/university/sigcomm-ccr-InKev-2016.pdf)
- [DEEP-mon](https://www.slideshare.net/necstlab/deepmon-dynamic-and-energy-efficient-power-monitoring-for-containerbased-infrastructures) - 帮助测量服务器的功耗并使用 eBPF 程序进行内核内数据聚合.
- [pixie](https://github.com/pixie-io/pixie)  - 使用 eBPF 的 Kubernetes 的可观察性. 功能包括协议跟踪、应用程序分析以及对分布式 bpftrace 部署的支持.
- [SkyWalking Rover](https://github.com/apache/skywalking-rover) - [Apache SkyWalking](https://skywalking.apache.org/) 是一个开源应用程序性能监控（APM）平台，专为具有微服务、云原生和基于容器（Kubernetes）架构的分布式系统而设计.  SkyWalking Rover 是一个基于 eBPF 的分析器和指标收集器，适用于 C、C++、Golang 和 Rust 应用程序.
- [parca-agent](https://github.com/parca-dev/parca-agent) - 基于 eBPF 的始终在线连续分析器，用于分析 CPU 和内存使用情况，精确到行数和整个时间.
- [rbperf](https://github.com/javierhonduco/rbperf) - Ruby 的采样分析器和跟踪器.
- [Hubble](https://github.com/cilium/hubble) - Network, service and security observability for Kubernetes using eBPF.
- [Caretta](https://github.com/groundcover-com/caretta) - 由 eBPF 生成的即时 Kubernetes 服务依赖关系图，直接指向 Grafana 实例.

### Security

- [Falco](https://falco.org/) - 用作 Kubernetes 威胁检测引擎的云原生运行时安全项目.
- [Sysmon for Linux](https://github.com/Sysinternals/SysmonForLinux)  - 安全监控工具. 这取决于 [SysinternalsEBPF](https://github.com/Sysinternals/SysinternalsEBPF).
- [Red Canary Linux Agent](https://redcanary.com/blog/ebpf-for-security) - Red Canary 已开始将 eBPF 合并到他们的 Linux 安全传感器中. 
- [Tracee](https://github.com/aquasecurity/tracee) - 适用于 Linux 的运行时安全和取证工具，它使用 eBPF 技术在运行时跟踪系统和应用程序，并分析收集的事件以检测可疑的行为模式.
- [redcanary-ebpf-sensor](https://github.com/redcanaryco/redcanary-ebpf-sensor)  - 一组 BPF 程序，用于从 Linux 内核收集安全相关事件数据.  BPF 程序被组合成一个 ELF 文件，根据运行的操作系统和内核版本，可以有选择地加载各个探针.
- [bpflock - Lock Linux machines](https://github.com/linux-lock/bpflock) - eBPF 驱动的安全工具，用于锁定和审核 Linux 机器.
- [Tetragon](https://github.com/cilium/tetragon) - Kubernetes 感知、基于 eBPF 的安全可观察性和运行时执行.

### Tools

- [ply](https://wkz.github.io/ply/) - 一个小型但灵活的 Linux 开源动态跟踪器，具有与 bcc 工具类似的功能，但采用受 awk 和 DTrace 启发的更简单的语言.
- [bpftrace](https://bpftrace.org/)  - 使用自己的高级跟踪语言进行跟踪的工具. 它足够灵活，可以设想作为 DTrace 和 SystemTap 的 Linux 替代品.
  - [bpftrace Cheat Sheet](https://www.brendangregg.com/BPF/bpftrace-cheat-sheet.html)  - bpftrace 编程的摘要和备忘单. 包含有关语法、探测类型、变量和函数的信息.
- [kubectl trace](https://github.com/iovisor/kubectl-trace) - 用于在 Kubernetes 集群中执行 bpftrace 程序的 kubectl 插件.
- [inspektor-gadget](https://github.com/inspektor-gadget/inspektor-gadget) - 一系列基于 eBPF 的工具，用于调试和检查 Kubernetes 资源和应用程序.
- [bpfd](https://github.com/genuinetools/bpfd)  - 用于在 Linux 上作为守护进程运行具有规则的 BPF 程序的框架. 容器感知.
- [BPFd](https://github.com/joelagnel/bpfd) - 一个独特的 BPF 守护进程，试图利用 bcc 工具的灵活性来跟踪和调试远程目标，特别是运行 Android 的设备.
- [adeb](https://github.com/joelagnel/adeb) - 用于通过 BPFd 在 Android 上使用跟踪工具的 Linux shell 环境.
- [greggd](https://github.com/olcf/greggd) - 系统守护进程，用于编译 eBPF 程序并将其加载到内核中，并将程序输出转发到套接字以进行度量聚合.
- [FUSE](https://events.linuxfoundation.org/wp-content/uploads/2017/11/When-eBPF-Meets-FUSE-Improving-Performance-of-User-File-Systems-Ashish-Bijlani-Georgia-Tech.pdf) - 考虑使用 eBPF.
- [upf-bpf](https://github.com/navarrothiago/upf-bpf) - 基于 XDP 的 5G UPF 内核内解决方案.
- [redbpf](https://github.com/foniod/redbpf) - 使用 Rust 高效编写 eBPF 代码的工具和框架.
- [ebpf-explorer](https://github.com/ebpfdev/explorer) - 用于探索系统地图和程序的网络界面.
- [ebpfmon](https://github.com/redcanaryco/ebpfmon) - 用于实时监控 eBPF 程序的 TUI（终端用户界面）应用程序.

## eBPF in Security

- [Embrace The Red: Offensive BPF!](https://embracethered.com/blog/tags/ebpf)  - 围绕 BPF 介绍的一系列帖子，重点关注攻击性环境，以及如何检测其滥用. 帖子包括有关 eBPF 的 rootkit 功能的讨论，或者不同用例需要哪种跟踪类型的讨论.
- [eBPF: Block Linux Fileless Payload "Malware" Execution with BPF LSM](https://djalal.opendz.org/post/ebpf-block-linux-fileless-payload-execution-with-bpf-lsm/) - 有关 BPF 如何帮助检测和阻止无文件恶意软件的博客文章.
- [Blackhat 2021: With Friends Like eBPF, Who Needs Enemies?](https://www.blackhat.com/us-21/briefings/schedule/#with-friends-like-ebpf-who-needs-enemies-23619)  - 讨论 eBPF rootkit 以及 eBPF 的功能如何被滥用.  Rootkit 也是 Defcon 上的演讲对象， [eBPF, I thought we were friends !](https://defcon.org/html/defcon-29/dc-29-speakers.html#fournier).
- [ebpfkit](https://github.com/Gui774ume/ebpfkit) - 利用多个 eBPF 功能来实施攻击性安全技术的 rootkit.
- [ebpfkit-monitor](https://github.com/Gui774ume/ebpfkit-monitor)  - 用于静态分析 eBPF 字节码或在运行时监视可疑 eBPF 活动的实用程序. 它是专门为检测 ebpfkit 而设计的.
- [Bad BPF](https://github.com/pathtofile/bad-bpf) - 恶意 eBPF 程序的集合，它们利用 eBPF 的能力在用户模式程序和内核之间读取和写入用户数据.
- [TripleCross](https://github.com/h3xduck/TripleCross) - 具有后门、C2、库注入、执行劫持、持久性和隐形功能的 Linux eBPF rootkit. 

## The Code

- [linux/include/linux/bpf.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/linux/bpf.h) - 和 [linux/include/uapi/bpf.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/bpf.h)：与eBPF相关的定义，分别用于内核和与用户空间程序的接口.
- [linux/include/linux/filter.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/linux/filter.h) - 和 [linux/include/uapi/filter.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/include/uapi/linux/filter.h)：用于运行 BPF 程序本身的信息.
- [linux/kernel/bpf/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf)  - 该目录包含大部分 BPF 相关代码. 特别是，这些文件值得关注：

  - [`syscall.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/syscall.c) - 系统调用允许的不同操作，例如程序加载或地图管理.
  - [`core.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/core.c) - BPF 解释器.
  - [`verifier.c`](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/kernel/bpf/verifier.c) - BPF 验证器.

- [linux/net/core/filter.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/core/filter.c)  - 与网络相关的功能和 eBPF 助手（TC、XDP 等）； 还包含将 cBPF 字节码迁移到 eBPF 的代码（所有 cBPF 程序在最近的内核中都转换为 eBPF）.
- [linux/kernel/trace/bpf_trace.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/trace/bpf_trace.c) - 与跟踪和监控相关的函数和 eBPF 助手（kprobes、跟踪点等）.
- JIT编译器位于各自架构的目录下，例如文件 [linux/arch/x86/net/bpf_jit_comp.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/arch/x86/net/bpf_jit_comp.c) 对于 x86\. 用于硬件卸载的 JIT 编译器例外，位于其驱动程序中，例如 [linux/drivers/net/ethernet/netronome/nfp/bpf/jit.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/drivers/net/ethernet/netronome/nfp/bpf/jit.c) Netronome NFP.
- [linux/net/sched/](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/sched) - 特别是在文件“act_bpf.c”（操作）和“cls_bpf.c”（过滤器）中：与 TC 的 BPF 操作和过滤器相关的代码.
- [linux/kernel/seccomp.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/kernel/seccomp.c)
- [linux/net/core/dev.c](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/tree/net/core/dev.c)  - 包含函数“dev_change_xdp_fd()”，在从用户空间加载到内核后，通过 Netlink 命令调用该函数以将 XDP 程序挂钩到设备. 该函数依次使用来自相关驱动程序的回调.

## Development and Community

- [The bpf-next tree](https://git.kernel.org/pub/scm/linux/kernel/git/bpf/bpf-next.git/)  - BPF 补丁落在这棵树上. 它定期合并到 [net-next](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git)，它本身会在每次发布时合并到 Linus 树中.
- [Kernel documentation](https://git.kernel.org/pub/scm/linux/kernel/git/davem/net-next.git/tree/Documentation/bpf/bpf_devel_QA.rst) - 关于对 BPF 的贡献.
- [The netdev mailing list](http://lists.openwall.net/netdev/)  - Linux 内核网络堆栈开发的邮件列表. 所有补丁都会发送到那里进行审查和包含.
- [XDP-newbies](http://vger.kernel.org/vger-lists.html#xdp-newbies) - 专门用于 XDP 编程的邮件列表（用于架构或寻求帮助）.
- [IO Visor mailing list](http://lists.iovisor.org/pipermail/iovisor-dev/) - BPF 是该项目的核心，并定期在邮件列表上进行讨论.
- [@IOVisor Twitter account](https://twitter.com/IOVisor)
- [The XDP Collaboration Project](https://github.com/xdp-project/xdp-project) - GitHub 存储库，其中包含有关 XDP 未来发展的注释和想法.

## Other Lists of Resources on eBPF

- [IO Visor's bcc documentation](https://github.com/iovisor/bcc/tree/master/docs)
- [IO Visor's bpf-docs repository](https://github.com/iovisor/bpf-docs/)
- [Dive into BPF: A List of Reading Material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/)

## Acknowledgement

感谢 Quentin Monnet 和 Daniel Borkmann 的原创作品 [Dive into BPF: A List of Reading Material](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/) 这成为了这份清单的基础.

## Contributing

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/zoidbergwill/awesome-ebpf/blob/master/contributing.md) 第一的.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，zoidbergwill 放弃了本作品的所有版权以及相关或邻接权.
