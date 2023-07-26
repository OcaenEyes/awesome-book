<div class="github-widget" data-repo="ocaml-community/awesome-ocaml"></div>
很棒的 OCaml [![Build Status](https://travis-ci.org/ocaml-community/awesome-ocaml.svg?branch=master)](https://travis-ci.org/ocaml-community/awesome-ocaml)
=============

<img src="https://raw.githubusercontent.com/ocaml-community/awesome-ocaml/master/colour-logo.png" width="70%" />

&gt; _**你在掌握 OCaml 的道路上所需要的一切.**_

精选的 OCaml 工具、框架、库和文章的参考列表. 此外，还有一系列免费提供 [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books), [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) 和 [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations).

如果您正在寻找有关 OCaml 的综合社区驱动内容，请访问[OCamlverse](https://ocamlverse.github.io/)!

有关现代 OCaml 开发工作流程的快速介绍，请参阅 [**Up and Running with OCaml**](https://ocaml.org/learn/tutorials/up_and_running.html) 教程.

没有列出您喜欢的包？ 叉和 [create a Pull Request](https://github.com/rizo/awesome-ocaml/edit/master/README.md) 添加它！



* * *


## Community

- [Official OCaml Website](https://ocaml.org/)
- [OCaml Discourse Web Forum](https://discuss.ocaml.org/)
- [OCaml Discord Chat](https://discord.gg/ZBgYuvR)
- [Official OCaml Mailing List](https://inbox.ocaml.org/caml-list/)
- [OCaml Planet](https://ocaml.org/community/planet/)
- [OCaml SubReddit](https://www.reddit.com/r/ocaml/)


## Algorithms and Data Structures

- [Comparing a Machine Learning Algorithm Implemented in F# and OCaml](https://philtomson.github.io/blog/2014-05-29-comparing-a-machine-learning-algorithm-implemented-in-f-sharp-and-ocaml/)
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) – OCaml 的通用图形库.
- [ods](https://github.com/owainlewis/ods) – OCaml 的大量数据结构和算法.
- [combine](https://github.com/backtracking/combine)  – 用于组合学的 OCaml 库<https://www.lri.fr/~filliatr/combine/> .
- [Decompress](https://github.com/mirage/decompress) - Zlib 的纯 OCaml 实现.
- [Ke](https://github.com/mirage/ke) - 在 OCaml 中快速实现队列 (FIFO).
- [Duff](https://github.com/mirage/duff) - P. MacDonald 在 OCaml 中实现 Rabin 的指纹和增量压缩（与 [libXdiff](http://www.xmailserver.org/xdiff-lib.html)
- [ORaft](https://github.com/komamitsu/oraft) - 图书馆 [Raft consensus algorithm](https://raft.github.io/raft.pdf) 在 OCaml 中实现


## Application Libraries

- [Batteries Included](https://github.com/ocaml-batteries-team/batteries-included) – 用于 OCaml 项目的社区维护基础库.
- [Cmdliner](https://github.com/dbuenzli/cmdliner) – OCaml 命令行界面的声明性定义.
- [Core](https://github.com/janestreet/core)  – Jane Street Capital 成熟的标准库覆盖.  Core 的可移植子集也可用： [Core_kernel](https://github.com/janestreet/core_kernel).
- [Base](https://github.com/janestreet/base) - Jane Street Capital 的无依赖、快速编译、完全可移植的跨越任何可以运行 OCaml 代码的环境的标准库.
- [React](http://erratique.ch/software/react)  – React 是用于函数式反应式编程 (FRP) 的 OCaml 模块. 它为具有时变值的程序提供支持：声明性事件和信号.
- [Minicli](https://github.com/UnixJunkie/minicli) - 用于命令行解析的极简库.
- [easy-format](https://github.com/mjambon/easy-format) – OCaml 的漂亮打印库.
- [ocaml-rpc](https://github.com/mirage/ocaml-rpc) – 用于处理 OCaml 中的 RPC 的轻型库.
- [ocaml-containers](https://github.com/c-cube/ocaml-containers)  – 一个轻量级的、模块化的标准库扩展、字符串库和各种库的接口（bigarrays、unix 等）.  BSD 许可证.


## Benchmarking

- [core_bench](https://github.com/janestreet/core_bench) – Jane Street 的 OCaml 微基准测试库.
  - [Getting Started with Core_bench](https://github.com/janestreet/core_bench/wiki/Getting-Started-with-Core_bench)
- [benchmark](https://github.com/Chris00/ocaml-benchmark) – 用于使用延迟或吞吐量测量函数运行时间的基准函数.


## Blogs

- [Gagallium](http://gallium.inria.fr/blog/)
- [Type OCaml – Many things about OCaml](http://typeocaml.com/)
- [OCaml Platform](https://opam.ocaml.org/blog/)
- [Drup's Thingies](https://drup.github.io/)

## Books

- [More OCaml: Algorithms, Methods, and Diversions](https://www.amazon.com/More-OCaml-Algorithms-Methods-Diversions/dp/0957671113/)  – 在更多 OCaml 中 John Whitington 用 OCaml 进行了函数式编程的曲折之旅，介绍了各种语言特性并描述了一些经典算法. 本书以处理 PDF 文件生成的大型实例结尾. 每章都有问题以及有效的答案和提示.
- [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html) 作者：Allen Downey 和 Nicholas Monje – 如何像计算机科学家一样思考是一本基于 OCaml 语言的编程入门教科书. 它是 Allen Downey 的 Think Python 的修改版本. 它适用于编程新手，也适用于那些了解一些编程但想在面向函数范式中学习编程的人，或者那些只想学习 OCaml 的人.
- [OCaml from the Very Beginning](http://ocaml-book.com/) 作者：J. Whitington - OCaml from the Very Beginning 将吸引新程序员和渴望探索 OCaml 等函数式语言的经验丰富的程序员.
- [Pearls of Functional Algorithm Design](https://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383) 作者 Richard Bird - 它总结了函数编程世界中的 30 个硬算法问题. 虽然是Haskell，但是算法题很有意思，尝试用OCaml解决也有助于函数式编程的思考.  OCaml 中的部分解决方案是 [here](https://github.com/MassD/pearls).
- [Real World OCaml](https://realworldocaml.org/) Y. Minsky、A. Madhavapeddy 和 J. Hickey - 面向大众的函数式编程.
- [Unix System Programming in OCaml](https://ocaml.github.io/ocamlunix/) 作者：X. Leroy 和 D. Rémy – Unix 系统编程简介，重点是进程之间的通信.
- [Using, Understanding, and Unraveling OCaml](https://caml.inria.fr/pub/docs/u3-ocaml) – 本书描述了 OCaml 语言及其强大类型系统背后的理论基础.
- [Purely Functional Data Structures](https://www.amazon.co.uk/Purely-Functional-Structures-Chris-Okasaki/dp/0521631246/ref=sr_1_1?ie=UTF8&qid=1406279836&sr=8-1&keywords=functional+data+structures)  - 这是第一本也是唯一一本关注 FP 世界中各种数据结构的书. 必读之作.
- [OCaml for Scientists](http://www.ffconsultancy.com/products/ocaml_for_scientists/) - 乔恩哈罗普.
- [Functional Programming in OCaml: A Principled Approach](https://www.cs.cornell.edu/courses/cs3110/2021sp/textbook/) - 康奈尔大学 OCaml CS 3110 函数式编程教科书.



## Code Analysis and Linters

- [Mascot](http://mascot.x9c.fr/) - Mascot 是 OCaml 源代码的样式检查器
- [pfff](https://github.com/returntocorp/pfff) – pfff 是一组工具和 API，用于执行一些静态分析、动态分析、代码可视化、代码导航或保持样式的源到源转换，例如源代码重构.
- [Infer](https://github.com/facebook/infer) - Infer 是 Java、C 和 Objective-C 的静态分析器
- [Frama-C](http://frama-c.com) - Frama-C 是 C 和 C++ 的静态分析和形式证明框架
- [flow](https://github.com/facebook/flow) - flow 是 JavaScript 的静态类型检查器
- [SLAyer](https://github.com/Microsoft/SLAyer) - SLAyer 是一种自动形式化验证工具，它使用分离逻辑来验证C 程序的内存安全性.
- [MemCAD](https://github.com/Antique-team/memcad)  - MemCAD 是用于形状分析的抽象解释器.  MemCAD 可以验证处理复杂数据结构的 C 程序.
- [Camelot](https://github.com/upenn-cis1xx/camelot) - Camelot 是一个模块化且完全可配置的 OCaml linter 和 stylechecker.
- [coq-of-ocaml](https://github.com/formal-land/coq-of-ocaml) - 从 OCaml 到 Coq 的翻译器，以正式验证 OCaml 代码.

## Program analysis
- [BAP](https://github.com/BinaryAnalysisPlatform/bap) - BAP 是一个针对二进制程序的逆向工程和程序分析平台.
- [BinCat](https://github.com/airbus-seclab/bincat) - BinCat 是一个二进制代码静态分析工具包.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) - cwe_checker 在二进制可执行文件中发现易受攻击的模式.

## Compilers and Compiler Tools

- **语言和编译器**：
  - [Caramel](https://caramel.run/) - Caramel 是一种函数式语言，用于构建类型安全、可扩展和可维护的应用程序.
  - [cDuce](http://www.cduce.org/) - cDuce 是一种具有创新功能的现代面向 XML 的函数式语言.
  - [Compcert C Compiler](http://compcert.inria.fr/) - 它是一个支持大多数 ISO C90 和 C99 / ANSI C 特性的 C 编译器.
  - [Eff Programming Language](http://www.eff-lang.org/) - Eff 是一种函数式语言，不仅可以处理异常，还可以处理其他计算效果，例如状态或 I/O.
  - [Hack Programming Language](https://hacklang.org/)
  - [Haxe Programming Language](https://haxe.org/)
  - [Neko Programming Language](https://nekovm.org/) - 最初编译器是用 OCaml 编写的.
  - [Mezzo Programming Language](https://protz.github.io/mezzo/) - Mezzo 是 ML 传统中的一种编程语言，它非常强调对别名的控制和对可变内存的访问.
  - [OCaml-Java](http://www.ocamljava.org/) - OCaml 到 Java 字节码编译器.
  - [Opa Programming Language](http://opalang.org/)
  - [Rhine](https://github.com/artagnon/rhine-ml) – 用 OCaml 编写的 LLVM 上的 Lisp.
  - [Rust Programming Language](https://www.rust-lang.org/) - 最初在引导之前用 OCaml 编写.
  - [Quick C-- Target Language](http://www.cminusminus.org/) - 它现在是一个死项目. [Github Repo](https://github.com/nrnrnr/qc--). [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).
  - [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) - 用于查找用标准 C 编写的程序中的细微错误的解释器

  - [Reason](http://facebook.github.io/reason/) - Facebook 的 OCaml 友好语法和工具链.
  - [RaML](http://raml.co/index.html) - Resource Aware ML (RaML) 是一种自动和静态计算 OCaml 程序的资源使用范围的工具.

- **解析器和词法分析器生成器**：
  - [Opal](https://github.com/pyrocat101/opal) – 用于 OCaml 的独立单子解析器组合器.
  - [Sedlex](https://github.com/ocaml-community/sedlex) 是一个现代的、与编码无关的（阅读：支持 Unicode 的）词法分析器生成器（基于 ppx 的继任者 [ulex](http://www.cduce.org/download.html#side).)
  - [Menhir](http://gallium.inria.fr/~fpottier/menhir/) – Menhir 是 OCaml 的 LR(1) 解析器生成器.
    - 看 [ocaml-parsing](https://github.com/smolkaj/ocaml-parsing) for a clearer example of using Menhir and Sedlex to produce a useful parser,
    - ... 和 [Obelisk](https://github.com/Lelio-Brun/Obelisk)，一个简洁的项目，可以为您的语法生成可读的 LaTeX、HTML 或纯文本 EBNF 样式的文档.
  - [ocamllex/ocamlyacc](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) – OCaml 的 lex 和 yacc 实现.
  - [Angstrom](https://github.com/inhabitedtype/angstrom) - 为速度和内存效率而构建的解析器组合器
- **文章**：
  - [Kaleidoscope: Implementing a Language with LLVM in Objective Caml¶](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)


## Concurrency

 OCaml 中存在两个并发库：_Lwt_ 和 _Async_. 它们提供非常相似的功能，但在错误处理和内部实现细节方面做出截然不同的决定（有关更多详细信息，请参见下面的链接）. [Real World OCaml](https://realworldocaml.org/) 使用 Async 但一个版本 [code examples translated to Lwt](https://github.com/dkim/rwo-lwt) 也可用.

- **图书馆**：
  - [Lwt](http://ocsigen.org/lwt/) — OCaml 的协作线程库.
  - [Async](https://opensource.janestreet.com/async/) — 与核心库一起使用的单子并发库.
- **文章**：
  - [The blog post that introduced Async](https://blog.janestreet.com/announcing-async/)
  - [A user gives up on Async](http://rgrinberg.com/posts/abandoning-async/)
  - [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).

还有一个正在进行的实验项目，使 OCaml 多处理器和多核感知在 [OCaml multicore](https://github.com/ocamllabs/ocaml-multicore) 叉.

## Databases

- **绑定**
  - [Dbm](https://forge.ocamlcore.org/projects/camldbm/) — 绑定到 NDBM/GDBM Unix“数据库”.
  - [Mongo.ml](https://massd.github.io/mongo/) – Mongodb 的 OCaml 驱动程序
  - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) — 纯 OCaml 中 PostgreSQL 的类型安全接口.
    - [ppx_pgsql](https://github.com/tizoc/ppx_pgsql) – 使用 PG&#39;OCaml 的嵌入式 SQL 查询的语法扩展.
  - [PostgreSQL-OCaml](https://mmottl.github.io/postgresql-ocaml/) — 通过 C API (`libpq`) 到 PostgreSQL 的接口.
  - [SQLite3](https://github.com/mmottl/sqlite3-ocaml) — OCaml 绑定到 SQLite3 数据库.
  - [Sqlite3EZ](https://mlin.github.io/ocaml-sqlite3EZ/) — 具有简化界面的 SQLite3 的瘦包装器.
  - [ocaml-redis](https://github.com/0xffea/ocaml-redis) – OCaml 的 Redis 绑定.
  - [mysql](http://ygrek.org.ua/p/ocaml-mysql/) – 绑定到 libmysqlclient 以与 MySQL 数据库交互.
  - [pgx](https://github.com/arenadotio/pgx) – 纯 OCaml PostgreSQL 客户端库
.
  - [mysql_protocol](https://github.com/slegrand45/mysql_protocol) – 使用 Bitstring 库实施 MySQL 协议.
- **新实现**
  - [Irmin](https://github.com/mirage/irmin) — 遵循与 Git 相同设计原则的分布式数据库.
  - [Obigstore](http://obigstore.forge.ocamlcore.org/) — 在 LevelDB 之上具有类似 BigTable 数据模型的数据库.
  - [RunOrg](https://github.com/RunOrg/RunOrg) - 这是一个用 OCaml 编写的 WIP 数据库服务器.
  - [dokeysto](https://github.com/UnixJunkie/dokeysto) - 愚蠢的 OCaml 键值存储、字符串键和字符串
  值. 可选的动态 LZ4 值压缩或 tokyocabinet 后端.

- **叠加**
  - [Sequoia](https://github.com/andrenth/sequoia) - Sequoia 是用于 MySQL/MariaDB 和 PostgreSQL 的类型安全查询生成器
  - [Macaque](https://github.com/ocsigen/macaque) — Macaque 是一个在 PG&#39;OCaml 之上使用推导式进行安全灵活的数据库查询的库.
  - [ORM](https://github.com/mirage/orm) — SQLite 的 ORM.
  - [Caqti](https://github.com/paurkedal/ocaml-caqti) - 对关系数据的协作线程访问
- **文章**：
  - [Implementing the Binary Memcached Protocol with Ocaml and Bitstring](https://andreas.github.io/2014/08/22/implementing-the-binary-memcached-protocol-with-ocaml-and-bitstring/)
  - [Interfacing OCaml and PostgreSQL with Caqti](https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11)
  - [Caqti setence preparation, ppx_rapper](https://github.com/roddyyaga/ppx_rapper)


## Datetime

- [ISO8601](https://github.com/sagotch/ISO8601.ml)
- [calendar](http://calendar.forge.ocamlcore.org/)
- [odate](https://github.com/hhugo/odate)
- [ptime](http://erratique.ch/software/ptime)


## Developer Tools

- [Try OCaml](https://try.ocamlpro.com/) – 在您的网络浏览器中试用 OCaml.
- [BetterOCaml](https://betterocaml.ml) – 一个高效、直观和跨平台的 Web IDE，您的 OCaml 代码可以在浏览器中解释和运行！
- [codingground](https://www.tutorialspoint.com/compile_ocaml_online.php) – 在线编译和执行 OCaml 代码.
- [OCaml: Learn & Code iOS app](https://apps.apple.com/app/ocaml-learn-code/id1547506826) - 从您的 iPhone/iPad/Mac 学习和执行 OCaml 代码.
- [Jupyter](https://github.com/akabe/ocaml-jupyter) – 用于 Jupyter notebook 的 OCaml 内核.
- [utop](https://github.com/ocaml-community/utop) – OCaml 的通用顶层，支持多行版本、历史、实时和上下文敏感的完成、颜色等.
- [ocamlformat](https://github.com/ocaml-ppx/ocamlformat) - 用于格式化 OCaml 代码的命令行工具.
- [ocamlbrowser](http://caml.inria.fr/pub/docs/manual-ocaml/browser.html)  – 源代码和编译界面浏览器，使用 LablTk 编写. 包含在 ocaml &lt;= 4.01 的标准发行版中，以及 ocaml &gt;= 4.02 的 labltk 中.
- [ghim](https://github.com/samoht/ghim) – 管理 Github Issues 的命令行工具.
- [OCaml Yeoman Generator](https://github.com/mabrasil/generator-ocaml) – 用于构建 OCaml 模块的 Yeoman 生成器.

- **外部函数接口**：
  - [ctypes](https://github.com/ocamllabs/ocaml-ctypes) – 使用纯 OCaml 绑定到 C 库的库.
  - [ocaml-main-program-in-c](https://github.com/johnwhitington/ocaml-main-program-in-c) – 用于制作混合 C/Ocaml 二进制文件的示例构建系统，其中主程序在 C 中.
  - [Modular foreign function bindings](http://openmirage.org/blog/modular-foreign-function-bindings)
  - [Py.ml](https://github.com/thierry-martinez/pyml) - Python 的 OCaml 绑定.
- **编辑器集成**：
  - [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) - 用于 OCaml 的 LSP 语言服务器，可与任何理解 LSP 的编辑器集成，例如 [VSCode](https://github.com/microsoft/vscode)、Vim 和 Emacs.
  - [merlin](https://github.com/ocaml/merlin) – Vim 和 Emacs 中 Ocaml 的上下文敏感完成.
  - [tuareg](https://github.com/ocaml/tuareg) - Emacs 的 OCaml 模式，可以在 Emacs 中运行顶层和调试器.
  - [merlin-eldoc](https://github.com/Khady/merlin-eldoc) – Emacs 包通过 eldoc 提供 merlin 的功能.
  - [vscode-ocaml](https://github.com/hackwaly/vscode-ocaml) – 提供 OCaml 语言支持的扩展 [VSCode](https://github.com/microsoft/vscode)
  - [OCaml Debugger](https://github.com/hackwaly/ocamlearlybird) – 提供 OCaml 调试器的扩展 [VSCode](https://github.com/microsoft/vscode)
  - [Sublime better ocaml](https://github.com/whitequark/sublime-better-ocaml) – 用于 Sublime Text 的更好的 OCaml 模式.
    - [Sublime text package](https://github.com/def-lkb/sublime-text-merlin)
  - [ocp-index](http://www.typerex.org/ocp-index.html)  – 轻松访问已安装的 OCaml 库的接口信息. 提供诸如 ocp-browser 和 ocp-grep 之类的独立工具.
    - [ocp-browser](http://www.typerex.org/ocp-index.html#ocp-browser) – 基于 ncurses 的小型 API 和文档浏览器.
    - [ocp-index-top](https://github.com/reynir/ocp-index-top) – 使用 ocp-index 查找文档的顶级指令.
    - [Sublime text package](https://sublime.wbond.net/packages/OCaml%20Autocompletion)
  - [ocp-indent](http://www.typerex.org/ocp-indent.html) – OCaml 的缩进工具，可从 Emacs 和 Vim 等编辑器中使用.
    - [Vim plugin](https://github.com/def-lkb/ocp-indent-vim).
- **代码覆盖率**：
  - [Bisect_ppx](https://github.com/aantron/bisect_ppx)


## Exercises and Short Examples

- [99 problems](https://ocaml.org/learn/tutorials/99problems.html) .  99%的解决方案是 [here](https://github.com/MassD/99).
- [Rosetta Code](http://rosettacode.org/wiki/Category:OCaml)
- [OCaml at Exercism](http://exercism.io/languages/ocaml)  – Exercism 是您进行深思熟虑的代码对话的场所. 探索简单性、惯用的语言特性和富有表现力的可读代码. [Solutions](https://github.com/exercism/xocaml).
- [Programming Language Examples Alike Cookbook](http://pleac.sourceforge.net/pleac_ocaml/index.html) - 本书的 OCaml 部分是使用 OCaml 解决常见编程问题的免费参考.

## Formal Software Verification

- [Coq](https://coq.inria.fr/)  – Coq 是一个正式的证明管理系统. 它提供了一种形式化语言来编写数学定义、可执行算法和定理，以及用于机器检查证明的半交互式开发的环境.
- [Why3](http://why3.lri.fr/)  – Why3 是一个用于演绎程序验证的平台. 它为规范和编程提供了丰富的语言，称为 WhyML，并依赖于自动化和交互式的外部定理证明器来满足验证条件.
- [Alt-Ergo](http://alt-ergo.lri.fr/) – Alt-Ergo 是一个开源的 SMT 求解器，专门用于证明在程序验证的上下文中生成的数学公式.


## General

- [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
- [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
- [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
- [Why We Use OCaml](https://espertech.wordpress.com/2014/07/15/why-we-use-ocaml)
- [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
- [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
- [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)
- [Why OCaml, why now?](http://spyder.wordpress.com/2014/03/16/why-ocaml-why-now/)
- [A blog about game development in OCaml](http://cranialburnout.blogspot.ca/)
- [(Functional) Alternatives to inheritance](http://ocamltutorials.blogspot.se/2013/06/alternatives-to-subtyping.html)
- [camlPDF](https://github.com/johnwhitington/camlpdf) – 用于阅读、编写和修改 PDF 文件的 OCaml 库.
- [slacko](https://github.com/Leonidas-from-XIV/slacko) – OCaml 中 Slack 的简洁界面.
- [Learn X in Y minutes](https://learnxinyminutes.com/docs/ocaml/) - 其中 X=OCaml.


## Graphics

- **2D**
  - [archimedes](http://archimedes.forge.ocamlcore.org/) — 二维绘图库.
  - [cairo2](https://github.com/Chris00/ocaml-cairo)  — 绑定到开罗，一个二维矢量图形库. 与 lablgtk 很好地集成.
  - [Vg](https://github.com/dbuenzli/vg) – OCaml 的声明性二维矢量图形.
- **3D**
  - [glMLite](https://github.com/fccm/glMLite)  — OCaml 的 OpenGL 绑定. 提供一个（实验性的）功能 API.  ([homepage](http://decapode314.free.fr/ocaml/GL/))
  - [lablgl](https://forge.ocamlcore.org/projects/lablgl/)  — OpenGL 接口. 与 lablgtk 很好地集成.
  - [tgls](http://erratique.ch/software/tgls) — 精简绑定 OpenGL 3.{2,3},4.{0,1,2,3,4} 和 OpenGL ES {2,3}.


## Internationalization

- [Camomile](https://github.com/yoriyuki/Camomile/) — OCaml 的 Unicode 库.
- [ocaml-m17n](https://github.com/whitequark/ocaml-m17n)  — OCaml 源代码的多语言化. 允许在 OCaml 源代码中使用 Unicode 标识符.
- [Uucd](https://github.com/dbuenzli/uucd) — OCaml 的 Unicode 字符数据库解码器.
- [Uucp](https://github.com/dbuenzli/uucp) — OCaml 的 Unicode 字符属性.
- [Uunf](https://github.com/dbuenzli/uunf) — OCaml 的 Unicode 文本规范化.
- [Uuseg](https://github.com/dbuenzli/uuseg) — OCaml 的 Unicode 文本分割.
- [Uutf](https://github.com/dbuenzli/uutf) — OCaml 的非阻塞流式 Unicode 编解码器.


## User Interface

- [lablgtk](https://garrigue.github.io/lablgtk/) — OCaml 的 GTK2 和 GTK3 绑定以及用于定义 GUI 的各种高级工具.
- [lablqml](https://github.com/Kakadu/lablqml) – OCaml 的 QML Qt5 绑定.
- [labltk](https://forge.ocamlcore.org/projects/labltk/)  — Tcl/Tk GUI 框架的接口. 在 ocaml &lt;= 4.01 的标准分布中.
- [TSDL](http://erratique.ch/software/tsdl) – Tsdl 是一个 OCaml 模块，提供到跨平台 SDL 库的精简绑定.
- [Lambda-Term](https://github.com/ocaml-community/lambda-term)  – Lambda-Term 是一个用于操作终端的跨平台库. 它为键、鼠标事件、颜色以及一组小部件提供了抽象，以编写类似 curses 的应用程序.
- [Notty](https://github.com/pqwy/notty) - Notty 是 OCaml 的声明性终端库，围绕可组合图像的概念构建.
- [ocaml-linenoise](https://github.com/ocaml-community/ocaml-linenoise) - 独立的 OCaml 绑定到 linenoise，OCaml 中简单的高级 readline 功能.


## Language-related

- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) – 使用正则表达式扩展的 OCaml 模式匹配
- [Inlined records in constructors](https://www.lexifi.com/ocaml/inlined-records-constructors/)
- [Algebraic Data Types](https://espertech.wordpress.com/2014/07/30/algebraic-data-types/)
- [XEN – OCaml Best Practices for Developers](http://wiki.xen.org/wiki/OCaml_Best_Practices_for_Developers)
- [OCaml Style Guide (by Jane Street)](https://opensource.janestreet.com/standards/) - 另见：[[1]](https://www.seas.upenn.edu/~cis500/cis500-f06/resources/programming_style.html)，[[2]](http://www.cs. cornell.edu/Courses/cs312/2001sp/style.html)，[[3]](https://www.seas.upenn.edu/~cis120/20fa/ocaml_style/).
- [A safe but strange way of modifying OCaml compiler](https://camlspotter.blogspot.com/2012/09/a-safe-but-strange-way-of-modifying.html)
- [Fiddling with the OCaml Type System](https://technotroph.wordpress.com/2013/10/25/fiddling-with-the-ocaml-type-system/)


## Large Source Code Examples

- [Base](https://github.com/janestreet/base) - OCaml 的标准库
- [cil](https://github.com/cil-project/cil) - C 中间语言
- [coq](https://github.com/coq/coq) - 正式证明管理系统
- [Dark](https://github.com/darklang/dark) - 一种组合的语言、编辑器和基础架构，可以轻松构建后端
- [frama-c](https://git.frama-c.com/pub/frama-c) - 专门用于分析用 C 编写的源代码的平台
- [libguestfs](https://github.com/libguestfs/libguestfs) - 用于访问和修改虚拟机磁盘映像的库和工具
- [Liquidsoap](https://github.com/savonet/liquidsoap) - 用于多媒体流媒体的瑞士军刀，尤其适用于 netradios 和 webtv
- [mirage](https://github.com/mirage/mirage) - 为跨各种云计算和移动平台的安全、高性能网络应用构建 unikernel 的图书馆操作系统
- [MLDonkey](https://github.com/ygrek/mldonkey) - 跨平台多网络点对点守护进程
- [Oni2](https://github.com/onivim/oni2) - 本机、轻量级模态代码编辑器
- [pfff](https://github.com/returntocorp/pfff) - 一个 OCaml API，用于编写静态分析、动态分析、代码可视化、代码导航或保持样式的源到源转换，例如源代码重构.
- [WHY3](https://gitlab.inria.fr/why3/why3) - 演绎程序验证平台
- [xen-api](https://github.com/xapi-project/xen-api) - 配置和控制支持 Xen 的主机和资源池并协调池内资源的管理堆栈

## Logging

- [dolog](https://github.com/UnixJunkie/dolog) – 一个愚蠢的 OCaml 记录器.
- [Volt](https://github.com/codinuum/volt) – Bolt OCaml 日志记录工具的变体.
- [Logs](http://erratique.ch/software/logs) - Logs 为 OCaml 提供日志记录基础设施.

## Machine Learning

- **图书馆**
	- [Ocaml-sklearn](https://github.com/lehy/ocaml-sklearn) 用于 OCaml 的 scikit-learn.
	- [Owl](https://ocaml.xyz/) - 具有神经网络、算法微分和 ONNX 支持的科学图书馆.
	- [Object detection convolutional neural network with OCaml (based on Owl)](https://github.com/owlbarn/owl_mask_rcnn).
	- [PyTorch bindings](https://github.com/LaurentMazare/ocaml-torch) - PyTorch 的 OCaml 绑定.
- **文章**
	- [Deep Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/deep-learning-experiments-in-ocaml/).
	- [Transfer Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/of-pythons-and-camels/).
	- [Reinforcement Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/playing-atari-games-with-ocaml-and-deep-rl/).

## Messaging

- [ocaml-zmq](https://github.com/issuu/ocaml-zmq) – 带有异步和 Lwt 包装器的 OCaml 的 ZeroMQ 绑定.
- [onanomsg](https://github.com/rgrinberg/onanomsg) – OCaml 的 nanomsg 绑定.
- [Kafka](https://github.com/didier-wenzek/ocaml-kafka) – Apache Kafka 的 OCaml 绑定.
- [AMQP](https://github.com/andersfugmann/amqp-client) – 用于 Async 和 Lwt 的 AMQP 客户端库.
- [MPI](https://github.com/xavierleroy/ocamlmpi) – OCaml 的消息传递接口绑定.
- [MQTT](https://github.com/j0sh/ocaml-mqtt) – MQTT pubsub 协议的 OCaml 实现.
- [capnp-ocaml](https://github.com/capnproto/capnp-ocaml) – 用于 Cap&#39;n Proto 序列化框架的 OCaml 代码生成器插件.

## Metaprogramming

- **文章**：
  - [A Guide to Extension Points in OCaml](http://whitequark.org/blog/2014/04/16/a-guide-to-extension-points-in-ocaml/)
  - [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
  - [Syntax extensions without Camlp4: let's do it!](https://www.lexifi.com/ocaml/syntax-extensions-without-camlp4-lets-do-it/)
  - [Reading Camlp4 – Ambassador to the Computers](https://ambassadortothecomputers.blogspot.com/p/reading-camlp4.html)
- **语法扩展**：
  - [ppx_import](https://github.com/ocaml-ppx/ppx_import) – Import 是一种语法扩展，允许从其他已编译的接口文件中提取类型或签名.
  - [ppx_string_interpolate](https://github.com/sheijk/ppx_string_interpolate) – 一个简单的 ppx 过滤器，支持字符串插值，如 `[%str &quot;value of foo is $(foo)&quot;]`.
  - [ppx_monad](https://github.com/rizo/ppx_monad) – OCaml 的 Monad 语法扩展.
  - [ppx_deriving_yojson](https://github.com/whitequark/ppx_deriving_yojson) – 用于 OCaml 的 Yojson 编解码器生成器.
- **工具和语言扩展**：
  - [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) – 用于多阶段编程的 OCaml 方言.
  - [Fan](http://zhanghongbo.me/fan/)  – Fan 是 OCaml 的编译时元编程系统，最初受到 Camlp4 的启发. 它是 OCaml 和 Lispy 宏的组合. 它与 OCaml 共享相同的具体语法.
  - [camlp5](https://camlp5.github.io/) - Camlp5 是 OCaml 的预处理器漂亮打印机.
  - [camlp4](http://caml.inria.fr/pub/docs/manual-camlp4/manual002.html) - Camlp4 是标准 OCaml 发行版的一部分，与 Camlp5 不同.

## Metrics

- [prometheus](https://github.com/mirage/prometheus) – 用于 Prometheus 监控的 OCaml 客户端库.

## Mobile Applications

- **文章**：
  - [OCaml on iOS 7 Released](http://psellos.com/2014/08/2014.08.ocamlxarm-402.html)
  - [OCaml + Cordova = more secured, typed and hybrid mobile applications](https://dannywillems.github.io/2016/07/14/ocaml-cordova-secured-typed-hybrid-mobile-applications.html)
- **绑定**：
  - [Cordova plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list)  – 与 Cordova 插件的绑定列表. 在 OCaml 中访问本地设备组件，如加速度计、SMS、地理定位等.


## Networking

- **HTTP 工具**：
  - [ocaml-cohttp](https://github.com/mirage/ocaml-cohttp) – 使用 Lwt 或 Async 的非常轻量级的 HTTP 服务器.
  - [ocurl](https://github.com/ygrek/ocurl) – OCaml bindings to libcurl.
  - [httpaf](https://github.com/inhabitedtype/httpaf) – 用 OCaml 编写的高性能、内存高效且可扩展的 Web 服务器.
  - [piaf](https://github.com/anmonteiro/piaf) - 完全用 OCaml 编写的 HTTP/1.X / HTTP/2 的客户端/服务器库.
- [ocaml-dns](https://github.com/mirage/ocaml-dns) – DNS 协议的纯 OCaml 实现.
- [fluent-logger](https://github.com/fluent/fluent-logger-ocaml) – OCaml 的 Fluentd 记录器.
- [charrua-unix](https://github.com/haesbaert/charrua-unix) - charrua-unix 是一个基于 Unix DHCP 守护进程 [charrua-core](https://github.com/haesbaert/charrua-core).


## Online Courses

- [Introduction to Functional Programming in OCaml](https://www.fun-mooc.fr/courses/parisdiderot/56002S02/session02/about).
- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php).
- [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).
- [University of Illinois](https://courses.engr.illinois.edu/cs421/fa2014/) - 使用 OCaml 教授函数式编程和编程语言设计的课程


## Package Management
- **分配**：
  - [OPAM](http://opam.ocamlpro.com/) – 灵活的 Git 友好包管理器，支持多种编译器.
  - [ocamlfind](http://projects.camlcity.org/projects/findlib.html)  — 本地 OCaml 库管理器. 被大多数 OCaml 生态系统使用.
  - [OCaml for Windows](https://fdopen.github.io/opam-repository-mingw) - 适用于 Windows 的 opam 存储库和实验版本（自 2021 年起弃用）.
  - [Diskuv OCaml](https://github.com/diskuv/dkml-installer-ocaml#readme) - 适用于 Windows 的 Diskuv OCaml 发行版.
  - [makorel](https://github.com/sagotch/makorel) – 轻松发布 OPAM 包.
  - [esy](https://github.com/esy/esy) - 使用 Reason/OCaml 进行本机开发的 package.json 工作流.

- **构建工具**：
  - [dune](https://github.com/ocaml/dune) – 用于 OCaml（以前的 jbuilder）的可组合和自以为是的构建系统
  - [Oasis](http://oasis.forge.ocamlcore.org/)  - 在您的 OCaml 项目中集成配置、构建和安装系统的工具. 它有助于在您的构建系统中创建标准入口点，并允许外部工具轻松分析您的项目.
    - [oasis2opam](https://github.com/ocaml/oasis2opam) — 将 OASIS 元数据转换为 OPAM 包描述的工具.
  - [obuild](https://github.com/ocaml-obuild/obuild) – Simple package build system for ocaml.
  - [ocaml-makefile](https://github.com/mmottl/ocaml-makefile) — 易于使用的 Makefile 用于中小型 OCaml 项目.
  - [topkg](https://github.com/dbuenzli/topkg) — 使用 ocamlbuild 的 OPAM 感知打包系统.
  - [Bazel](https://github.com/jin/rules_ocaml) - OCaml 规则 [Bazel](https://bazel.build/)，谷歌的多语言和平台构建工具.

## Parallelism

（_注：从易用到灵活排序._）

- **图书馆**：
  - [Parmap](http://rdicosmo.github.io/parmap/) — 提供易于使用的平行映射和折叠功能.
  - [ForkWork](https://github.com/mlin/forkwork) — 一个简单的库，用于分叉子进程以在多个核心上执行工作.
  - [Functory](http://functory.lri.fr/About.html) — 一个分布式计算库，它有助于以无缝方式分布式执行可并行计算.
  - [Rpc.Parallel](https://github.com/janestreet/rpc_parallel) — 用于在机器集群上生成进程并在它们之间传递类型化消息的库.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)  — 增强的系统平台库. 包含“netmulticore”库以根据需要在尽可能多的机器内核上计算任务.
  - [Nproc](https://github.com/MyLifeLabs/nproc) – OCaml 的进程池实现.
  - [Parany](https://github.com/UnixJunkie/parany) – 对独立项目进行并行计算，即使它们的数量是无限的.
  - [Sklml](http://sklml.inria.fr) – 用于 OCaml 程序的功能性并行骨架编译器和编程系统.
  - [SPOC](https://github.com/mathiasbourgoin/SPOC) - 用于将密集计算卸载到并行加速器（多核 CPU、GPU 和其他与 GPGPU 框架兼容的加速器）的库和语法扩展.

- **文章**：
  - [What is the state of OCaml's parallelization abilities?](https://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)

## Printers helpers

- 理性的本机 [**Console.log**](https://github.com/reasonml/reason-native/tree/master/src/console#consoleloganything)
- [**Dum**](https://github.com/mjambon/dum#readme)
- [**Inspect**](https://github.com/krohrer/caml-inspect#readme)
- [**ppx_deriving** ](https://github.com/ocaml-ppx/ppx_deriving#usage)的`[@@deriving show]`.
- [**refl** ](https://github.com/thierry-martinez/refl#basic-usage), 类似 ppx_deriving 的.
- [**lrt** ](https://github.com/LexiFi/lrt#getting-started)，另一个类似 ppx_deriving 的.
- [**tpf** ](https://github.com/pqwy/tpf#readme)，又是类似 ppx_deriving 的.
- [**typerep** ](https://github.com/janestreet/typerep)，可能是 ppx_deriving-like 与 ppx_typerep_conv.
- [**repr**](https://mirage.github.io/repr/repr/Repr/index.html#val-pp_json)，除了让用户在需要的地方传递它之外，它似乎让用户从组合器手动构建类型表示.
- [**data-encoding**](https://gitlab.com/nomadic-labs/data-encoding/-/blob/master/src/tutorial.md#how-to-build-an-encoding)，也完全手动.
- [**cmon** ](https://github.com/let-def/cmon#documentation)，全手动.
- [**dyn** ](https://github.com/ocaml/dune/blob/4b95cd3d1b3a62e69a9a9db2bc4af2f9fd2e56d8/otherlibs/dyn/dyn.mli) 在沙丘. 似乎也是完全手动
- [**Genprint** ](https://github.com/progman1/genprintlib#readme)
- [**OCaml@p** ](https://github.com/tsubame-sp/ocaml_at_p#readme)


## Project Starter Templates

- [drom](https://github.com/OCamlPro/drom/) - drom 工具是 opam/dune 的包装器，旨在提供类似货物的用户体验.
- [spin](https://github.com/tmattio/spin) - Reason 和 Ocaml 项目生成器
- [modern-ocaml](https://github.com/Khady/modern-ocaml) - 使用现代工具的 ocaml 项目模板

## Questions

- [OCaml polymorphism example other than template function?](https://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [OCaml - polymorphic print and type losing](https://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)


## Science and Technical Computing

- [biocaml](https://github.com/biocaml/biocaml)  – OCaml 生物信息学库<http://biocaml.org> .
- [bistro](https://github.com/pveber/bistro) – 用于构建生物信息学管道的 OCaml 库.
- [lacaml](https://mmottl.github.io/lacaml/) - 用于 BLAS/LAPACK（高性能线性代数 Fortran 库）的 OCaml 绑定.
- [obandit](http://freux.fr/oss/obandit.html) - 用于多臂强盗的 OCaml 库.
- [onumerical](https://github.com/cheshire/onumerical) – OCaml 的数字库.
- [oml](https://github.com/hammerlab/oml) - 用于一般数值工作的 OCaml 库.
- [ocephes](https://github.com/rleonid/ocephes) - 绑定到常用的“C”特殊函数库.
- [slap](https://github.com/akabe/slap) - OCaml 中的线性代数库，具有针对矩阵运算的基于类型的静态大小检查.
- [tensorflow-ocaml](https://github.com/LaurentMazare/tensorflow-ocaml) – TensorFlow 的 OCaml 绑定.
- [owl](https://github.com/owlbarn/owl) - OCaml 数值库：密集和稀疏矩阵、线性代数、回归、数学和统计函数.


## Regular Expressions

- [Re](https://github.com/ocaml/ocaml-re) – 带有组合器的纯 OCaml 正则表达式库，支持多种格式（glob、posix、str ...）
- [ocaml-pcre](https://github.com/mmottl/pcre-ocaml) – 绑定到 PCRE 库（perl 兼容的正则表达式）
- [Humane-re](https://github.com/rgrinberg/humane-re) – Humane-re 试图为 90% 的正则表达式需求提供一个简单的界面，由 ocaml-re 提供
- [Tyre](https://github.com/Drup/tyre) - Tire 是一组组合器，用于构建类型安全的正则表达式，允许自动提取和修改匹配组.


## Security and Cryptography

- [ocaml-tls](https://github.com/mirleft/ocaml-tls) – 纯 OCaml 中的 TLS.
- [Digestif](https://github.com/mirage/digestif) - OCaml 和 C 中的哈希算法（如 SHA* 或 BLAKE2*）.
- [cryptokit](https://github.com/xavierleroy/cryptokit) – OCaml 的 Cryptokit 库提供了多种加密原语，可用于在安全敏感应用程序中实施加密协议.
- [nocoiner](https://github.com/marcoonroad/nocoiner) - 用于多方计算的承诺方案库，例如在线拍卖和赌博.
- [nocrypto](https://github.com/mirleft/ocaml-nocrypto)  – ocaml-tls 项目背后的小型加密库. 它被构建为易于使用，遵循函数式编程原则并能够在基于 Xen 的 unikernel 中运行.

&gt; 注意：`nocrypto` 和 `cryptokit` 加密库之间的区别在以下博客文章中进行了描述： [OCaml-TLS: building the nocrypto library core](https://mirage.io/blog/introducing-nocrypto).


## Semantic Technology

- [OCaml-RDF](https://framagit.org/zoggy/ocaml-rdf) – OCaml 库，用于操作 RDF 图和执行 Sparql 查询.


## Serialization

- [bencode](https://github.com/rgrinberg/bencode) — Bencode（.torrent 文件格式）读取器/写入器.
- [biniou](https://github.com/mjambon/biniou) – 可扩展的二进制数据格式，如 JSON 但速度更快.
- [cbor](https://github.com/ygrek/ocaml-cbor) — OCaml 本机 [CBOR](https://cbor.io/) 解码器/编码器.
- [jsonm](http://erratique.ch/software/jsonm) — OCaml 的非阻塞流式 JSON 编解码器.
- [xmlm](http://erratique.ch/software/xmlm) — 用于解码和编码 XML 数据格式的流式编解码器.
- [yojson](https://github.com/ocaml-community/yojson) — 针对 JSON 格式优化的解析和打印库.
- [sexplib](https://github.com/janestreet/sexplib) – S 表达式解析器和打印机


## System Programming

- [Mirage OS](https://github.com/mirage/mirage) – Mirage 是一种编程框架，用于跨各种云计算和移动平台构建安全、高性能的网络应用程序.
- [ocaml-fat](https://github.com/mirage/ocaml-fat) – 从 OCaml 读取和写入 FAT 格式的文件系统.
- [ocaml-git](https://github.com/mirage/ocaml-git) – 纯 OCaml 低级 git 绑定.
- [ocaml-vchan](https://github.com/mirage/ocaml-vchan) – “vchan”共享内存通信协议的纯 OCaml 实现.

- **嵌入式系统**
  - [OMicroB](https://github.com/stevenvar/omicrob) - 设计用于在 AVR（例如 Arduino）微控制器上运行 OCaml 字节码的虚拟机.
  - [OCaPIC](http://www.algo-prog.info/ocapic/web/index.php?id=OCAPIC:OCAPIC) - 用于 PIC18 微控制器的 OCaml 虚拟机.
  - [ocaml-esp32](https://github.com/sadiqj/ocaml-esp32) - ESP32 SoC 的编译器.


## Testing

- [Alcotest](https://github.com/mirage/alcotest) - 一个轻量级和丰富多彩的测试框架.
- [OUnit](http://ounit.forge.ocamlcore.org/)  – OUnit 是 OCaml 的单元测试框架. 它允许人们轻松地为 OCaml 代码创建单元测试. 它基于 HUnit，Haskell 的单元测试框架.
- [QCheck](https://github.com/c-cube/qcheck) — QCheck 是一个属性测试库，灵感来自 Haskell 的 QuickCheck
- [iTeML](https://github.com/vincent-hugot/iTeML) （原名 [qtest](http://batteries.vhugot.com/qtest/)) — 支持内联编译指示以生成测试.
- [Kaputt](http://kaputt.x9c.fr/) — 全面的测试框架.
- [Pa_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) — 通用内联测试宏.
- [TestSimple](https://github.com/hcarty/ocaml-testsimple) - 兼容的轻量级单元测试框架 [Test Anything Protocol](https://testanything.org/).
- [expect-test](https://github.com/janestreet/ppx_expect) — 在 OCaml 中编写测试的框架，类似于 [Cram](https://bitheap.org/cram/)， 由开发 [JaneStreet](https://blog.janestreet.com/testing-with-expectations/). 


## Utilities

- [ocaml-cuid](https://github.com/marcoonroad/ocaml-cuid) - 用于服务器可扩展性和数据库性能的抗冲突 ID.
- [Uuidm](https://erratique.ch/software/uuidm) - Uuidm 是一个 OCaml 模块，根据 RFC 4122 实现 128 位通用唯一标识符版本 3、5（基于 MD5、SHA-1 哈希的名称）和 4（基于随机）.


## Web Development

- **构架**：
  - [Opium](https://github.com/rgrinberg/opium) – 类似 Sinatra 的 OCaml 网络工具包.
  - [Ocsigen Eliom](http://ocsigen.org/eliom/)  – Eliom 是一个功能齐全的多层框架，用于将多平台 Web 和移动应用程序开发为 100% OCaml 分布式应用程序. 它还可以用于更传统的 Web 或移动应用程序：网站、单页应用程序、REST API 等.
  - [Dream](https://aantron.github.io/dream/) - OCaml 和 ReasonML 的 Tidy Web 框架
  - [webmachine](https://github.com/inhabitedtype/ocaml-webmachine)  – OCaml 的 REST 工具包.  OCaml webmachine 是 cohttp 之上的一个层，它实现了一个基于状态机的 HTTP 请求处理器. 它特别适合编写 RESTful API. 顾名思义，这是 webmachine 项目的 OCaml 端口.
  - [incr_dom](https://github.com/janestreet/incr_dom) - 使用 Js_of_ocaml 构建动态网络应用程序的库
  - [ocaml-vdom](https://github.com/LexiFi/ocaml-vdom) - OCaml 的 Elm 架构和 (V)DOM

- **工具**：
  - [COW](https://github.com/mirage/ocaml-cow) – Web 上的 Caml (COW) 是一组解析器和语法扩展，可让您直接从 OCaml 代码操作 HTML、CSS、XML、JSON 和 Markdown.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)
    有很多相关的网络图书馆——
    [Nethtml](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Nethtml.html)
    html解析器，
    [Netasn1](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netasn1.html)
    对于 ASN.1 解析，
    [Netencoding](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netencoding.html)
    对于 Base64、Quoted Printable、URL 编码和 HTML 转义，
    [Netmime](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netmime.html)
    用于 MIME 处理等.请参阅 [list of
    模块](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/index.html)
    在 Ocamlnet 的手册中.
  - [tyxml](http://ocsigen.org/tyxml) — 构建有效（根据 W3C 规范）Html 和 Svg 树的库.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml)  – Js_of_ocaml 是 OCaml 字节码到 Javascript 的编译器. 它使得在 Web 浏览器中运行 Ocaml 程序成为可能.
    - [commonjs_of_ocaml](https://github.com/AngryLawyer/commonjs_of_ocaml) - 从 js_of_ocaml 项目轻松导入和导出 CommonJS 模块.
  - [ReScript](https://rescript-lang.org/) - ReScript 是一种强类型语言，可编译为高效且人类可读的 JavaScript.
  - [ocaml-uri](https://github.com/mirage/ocaml-uri) – RFC3986 URI 解析库.
  - [Goji](https://github.com/klakplok/goji) – 用于 JavaScript 库的 OCaml 绑定生成器.
  - [Syndic](https://github.com/Cumulus/Syndic) – RSS 和 Atom 提要解析
  - [ocaml-mustache](https://github.com/rgrinberg/ocaml-mustache) – OCaml 中的 mustache.js 无逻辑模板.
  - [atdjs](https://github.com/barko/atdjs) – OCaml/js_of_ocaml 的 atd 代码生成器.
  - [jingoo](https://github.com/tategakibunko/jingoo) – OCaml 模板引擎几乎与 jinja2 兼容.
  - [dispatch](https://github.com/inhabitedtype/ocaml-dispatch) – 客户端和服务器端应用程序的基于路径的调度.
  - [Lambda Soup](https://github.com/aantron/lambda-soup) - 使用 CSS 选择器进行功能性 HTML 抓取和操作，就像 Python 的 Beautiful Soup.
  - [Markup.ml](https://github.com/aantron/markup.ml) - 错误恢复流式 HTML5 和 XML 解析器、序列化器.
  - [gen_js_api](https://github.com/LexiFi/gen_js_api) - gen_js_api 旨在简化为 Javascript 库创建 OCaml 绑定.
  - [routes](https://github.com/anuragsoni/routes) - OCaml/ReasonML 网络应用程序的类型化路由.

- **开源项目**：
  - [Cumulus](https://github.com/Cumulus/Cumulus) – 黑客新闻，例如使用 OCaml 框架 Ocsigen 的网站

* * *

 _受 awesome projects 系列的启发. 发现 [more awesomeness](https://github.com/bayandin/awesome-awesomeness) :sparkles:._
