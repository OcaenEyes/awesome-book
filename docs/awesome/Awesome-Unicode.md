<div class="github-widget" data-repo="jagracey/Awesome-Unicode"></div>
![](https://raw.githubusercontent.com/jagracey/Awesome-Unicode/58f28d08aef7f36eb6cdca22d25e7654cd8de5ae/resources/banner.jpg)


## Awesome Unicode [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)



&gt; 令人愉快的 Unicode 花絮、包和资源的精选列表.

*请阅读 [contribution guidelines](https://github.com/jagracey/Awesome-Unicode/blob/master/CONTRIBUTING.md) 在贡献之前.*
*关键的 Unicode 术语在 [glossary](https://github.com/jagracey/Awesome-Unicode/blob/master/GLOSSARY.md).*

*交叉张贴到 [Wisdom's Dev Blog](https://wisdom.engineering/awesome-unicode/)*

<br><br>

## Foreword

 Unicode 很棒！ 在 Unicode 出现之前，国际通信非常费力——每个人都在 ASCII 的上半部分定义了他们单独的扩展字符集（称为代码页），这会发生冲突——想想看，讲德语的人与讲韩语的人协调使用哪个 127 个字符的代码页. 值得庆幸的是，Unicode 标准流行起来并统一通信.  Unicode 8.0 标准化了来自超过 129 个文字的超过 120,000 个字符 - 一些是现代的，一些是古代的，还有一些仍未破译.  Unicode 处理从左到右和从右到左的文本，组合标记，并包括不同的文化、政治、宗教字符和表情符号.  Unicode 非常人性化——但最终却被低估了.

<br>




## Quick Unicode Background

## What Characters Does the Unicode Standard Include?

 Unicode 标准定义了当今所有主要语言中使用的字符代码. 文字包括欧洲字母文字、中东从右到左的文字和许多亚洲文字.

 Unicode 标准还包括标点符号、变音符号、数学符号、技术符号、箭头、装饰符号、表情符号等.它为变音符号提供了代码，这些变音符号修饰字符标记，例如波浪号 (~)，与 base 结合使用表示重音字母的字符（例如ñ）. 总之，Unicode 标准 9.0 版提供了来自世界字母表、表意文字集和符号集合的 128,172 个字符的代码.

大多数常用字符适合前 64K 个代码点，代码空间的一个区域称为基本多语言平面，简称 BMP. 还有 16 个其他补充平面可用于编码其他字符，目前有超过 850,000 个未使用的代码点. 正在考虑将更多字符添加到标准的未来版本中.

 Unicode 标准还保留代码点供私人使用. 供应商或最终用户可以在内部为他们自己的字符和符号分配这些，或者将它们与专门的字体一起使用.  BMP 上有 6,400 个私人使用代码点和另外 131,068 个补充私人使用代码点，如果 6,400 个不足以满足特定应用.



## Unicode Character Encodings

字符编码标准不仅定义了每个字符的标识及其数值或代码点，还定义了该值如何以位表示.

 Unicode 标准定义了三种编码形式，允许以字节、字或双字为导向的格式（即每个代码单元 8、16 或 32 位）传输相同的数据. 所有三种编码形式都对相同的通用字符库进行编码，并且可以在不丢失数据的情况下有效地相互转换.  Unicode 联盟完全认可使用这些编码形式中的任何一种作为实现 Unicode 标准的一致方式.

 UTF-8 在 HTML 和类似协议中很流行.  UTF-8 是一种将所有 Unicode 字符转换为可变长度字节编码的方法. 它的优点是与熟悉的 ASCII 集对应的 Unicode 字符具有与 ASCII 相同的字节值，并且 Unicode 字符转换为 UTF-8 可以与许多现有软件一起使用，而无需大量的软件重写.  

 UTF-16 在许多需要平衡有效访问字符和经济使用存储的环境中很流行. 它相当紧凑，所有频繁使用的字符都适合一个 16 位代码单元，而所有其他字符都可以通过成对的 16 位代码单元访问.

 UTF-32 在不关心内存空间但需要固定宽度、单个代码单元访问字符的情况下很有用. 使用 UTF-32 时，每个 Unicode 字符都编码在一个 32 位代码单元中.

所有三种编码形式的每个字符最多需要 4 个字节（或 32 位）的数据.




## Lets talk Numbers


The Unicode characterset is divided into 17 core segments called "planes", which are further divided into blocks. Each plane has space for 65,536 (2¹⁶) codepoints, supporting a grand total of 1,114,112 codepoints. There are two "Private Use Area" planes (#16 & #17) that are allocated to be used however one wishes. These two Private Use planes account for 131,072 codepoints.

| \#  | Name                                    | Range                  |
|-----|-----------------------------------------|------------------------|
 |  1. |  **基本多语言平面** |  (U+0000 到 U+FFFF) |
 |  2. |  **补充多语言平面** |  (U+10000 到 U+1FFFF) |
 |  3. |  **补充表意平面** |  (U+20000 到 U+2FFFF) |
 |  4. | 第三表意平面 |  (U+30000 到 U+3FFFF) |
 |  5. | 平面 5（未分配）|  (U+40000 到 U+4FFFF) |
 |  6. | 平面 6（未分配）|  (U+50000 到 U+5FFFF) |
 |  7. | 平面 7（未分配）|  (U+60000 到 U+6FFFF) |
 |  8. | 平面 8（未分配）|  (U+70000 到 U+7FFFF) |
 |  9. | 平面 9（未分配）|  (U+80000 到 U+8FFFF) |
 |  10. | 平面 10（未分配）|  (U+90000 到 U+9FFFF) |
 |  11. | 平面 11（未分配）|  (U+A0000 到 U+AFFFF) |
 |  12. | 平面 12（未分配）|  (U+B0000 到 U+BFFFF) |
 |  13. | 平面 13（未分配）|  (U+C0000 到 U+CFFFF) |
 |  14. | 平面 14（未分配）|  (U+D0000 到 U+DFFFF) |
 |  15. |  **增补专机** |  (U+E0000 到 U+EFFFF) |
 |  16. |  **补充私人使用区 - A** |  (U+F0000 到 U+FFFFF) |
 |  17. |  **补充私人使用区 - B** |  (U+100000 到 U+10FFFF) |


第一个平面称为基本多语言平面或 BMP. 它包含从 U+0000 到 U+FFFF 的代码点，这些是最常用的字符. 其他十六个位面 (U+010000 → U+10FFFF) 称为补充位面或星体位面.




## UTF-16 Surrogate Pairs
 &gt; BMP 之外的字符，例如 U+1D306 tetragram for center ()，只能使用两个 16 位代码单元以 UTF-16 编码：0xD834 0xDF06. 这称为代理对. 请注意，代理对仅表示单个字符.
代理对的第一个代码单元始终在 0xD800 到 0xDBFF 的范围内，称为高代理或前导代理.
代理对的第二个代码单元总是在 0xDC00 到 0xDFFF 的范围内，称为低代理或尾代理.

-- [Mathias Bynens](https://mathiasbynens.be/notes/javascript-encoding#surrogate-pairs)

&gt; 代理对：单个抽象字符的表示，由
两个 16 位代码单元的序列，其中该对的第一个值是高代理项
代码单元，第二个值是低代理代码单元. 代理对仅在 UTF-16 中使用.  （参见第 3.9 节，Unicode 编码
形式.）  -  [Unicode 8.0.0 Chapter 3 - Surrogates](http://unicode.org/versions/Unicode8.0.0/ch03.pdf#page=47)


## Calculating Surrogate Pairs

 UTF-16 中的Unicode 字符** Pile of Poo (U+1F4A9)** 必须编码为代理对，即两个代理. 要将任何代码点转换为代理项对，请使用以下算法（在 JavaScript 中）. 请记住，我们使用的是十六进制表示法.

```javascript
 var High_Surrogate = function(Code_Point){ return Math.floor((Code_Point - 0x10000) / 0x400) + 0xD800 };
 var Low_Surrogate = function(Code_Point){ return (Code_Point - 0x10000) % 0x400 + 0xDC00 };

 // 反转转换
 var Code_Point = function(High_Surrogate, Low_Surrogate){
	返回 (High_Surrogate - 0xD800) * 0x400 + Low_Surrogate - 0xDC00 + 0x10000；
 };
```

```javascript
  &gt; var 代码点 = 0x1F4A9;  // 0x1F4A9 == 128169
 &gt; High_Surrogate(代码点).toString(16)
 “d83d” // 0xD83D == 55357
 &gt; Low_Surrogate(代码点).toString(16)
 “dca9” // 0xDCA9 == 56489

 &gt; String.fromCharCode( High_Surrogate(codepoint) , Low_Surrogate(codepoint) );
  ""
&gt; 字符串.fromCodePoint(0x1F4A9)
  ""
 &gt; &#39;\ud83d\udca9&#39;
  ""
```



## Composing & Decomposing
 Unicode 包括一种修改字符形状的机制，它极大地扩展了支持的字形库. 这涵盖了组合变音标记的使用. 它们被插入到主角之后. 多个组合变音符号可以叠加在同一个字符上.  Unicode 还包含大多数正常使用的字母/变音符号组合的预组合版本.



某些字符序列也可以表示为单个字符，称为预组合字符（或复合字符或可分解字符）. 例如，字符“ü”可以编码为单个代码点 U+00FC“ü”或基本字符 U+0075“u”后跟非空格字符 U+0308“¨”.  Unicode 标准对预组合字符进行编码以与已建立的标准（例如 Latin 1）兼容，其中包括许多预组合字符，例如“ü”和“ñ”.

为了一致性或分析，可以分解预组合字符. 例如，在按字母顺序排列（整理）名称列表时，字符“ü”可能会分解为“u”后跟非空格字符“¨”. 字符分解后，归类可能更容易处理字符，因为它可以作为“u”进行修改处理. 这使得字符修饰符不影响字母顺序的语言更容易按字母顺序排序.  Unicode 标准定义了 [decompositions](http://unicode.org/versions/Unicode8.0.0/ch03.pdf#page=44) 对于所有预组合字符. 它还定义了规范化形式以提供字符的唯一表示.


## Myths of Unicode
*来自马克·戴维斯 [Unicode Myths](http://macchiato.com/slides/UnicodeMyths.pdf) 幻灯片.*
- **Unicode is simply a 16-bit code** - Some people are under the misconception that Unicode is simply a 16-bit code where each character takes 16 bits and therefore there are 65,536 possible characters. This is not, actually, correct. It is the single most common myth about Unicode, so if you thought that, don't feel bad.

 - **您可以使用任何未分配的代码点供内部使用** - 不.最终那个洞将被不同的字符填充. 而是使用私人使用或非字符.

- **每个 Unicode 代码点代表一个字符** - 不，有很多非字符（FFFE、FFFF、1FFFE，……）
还有代理代码点、私有和未分配的代码点以及控制/格式“字符”（RLM、ZWNJ 等）

 - **Unicode 将用完空间** - 如果它是线性的，我们将在公元 2140 年用完. 但它不是线性的. 请参阅 http://www.unicode.org/roadmaps/

- **大小写映射为 1-1** - 不.它们也可以是：
  - 一对多：(ß → SS )
  - 上下文：(…Σ ↔ …σ AND …Σ… ↔ …σ… )
  - 语言环境敏感：（ I ↔ ı 和 İ ↔ i ）




## Applied Unicode Encodings


 | 编码类型 | 原始编码 |
|---------------------------|---------------------------------------|
|HTML Entity (Decimal) 		| &#128406;								|
|HTML Entity (Hexadecimal)  | &#x1F596;								|
 |网址转义码|  %F0%9F%96%96 |
 |UTF-8（十六进制）|  0xF0 0x9F 0x96 0x96 (f09f9696) |
 |UTF-8（二进制）|  11110000:10011111:10010110:10010110 |
 |UTF-16/UTF-16BE（十六进制）|  0xD83D 0xDD96 (d83ddd96) |
 |UTF-16LE（十六进制）|  0x3DD8 0x96DD (3dd896dd) |
 |UTF-32/UTF-32BE（十六进制）|  0x0001F596 (0001f596) |
 |UTF-32LE（十六进制）|  0x96F50100 (96f50100) |
 |八进制转义序列|  \360\237\226\226 |


## Source Code
 |编码类型| 原始编码|
|-------------|-------------|
 |  JavaScript |  \u1F596 |
 |  JSON |  \u1F596 |
 | 丙 |  \u1F596 |
 |  C++ |  \u1F596 |
 | 爪哇 |  \u1F596 |
 | 蟒蛇 |  \u1F596 |
 | 佩尔 |  \x{1F596} |
 | 红宝石 |  \u{1F596} |
 |  CSS |  \01F596 |






## Awesome Characters List




<center>
[![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)
</center>

## Special Characters

Unicode 联盟发布了一个 [general punctuation chart](http://www.unicode.org/charts/PDF/U2000.pdf) 您可以在哪里找到更多详细信息.


 | 字符 | 名称 | 说明 |
|----------|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
 |  `&#39; &#39;` |  U+FEFF（字节顺序标记 - BOM）| 具有字节重新排序明确的重要特性. 它也是零宽度的，并且是不可见的. 在不兼容的软件（如 PHP 解释器）中，这会导致各种有趣的行为.  |
 |  `&#39;￯&#39;` |  &#39;\\uFFEF&#39; 反转字节顺序标记 (BOM) | 不等同于合法字符，除了文本的开头.  |
 |  `&#39; &#39;` |  &#39;\\u200B&#39; 零宽度不间断空格 |  （一个没有外观的字符，除了防止连字的形成之外没有任何作用）.  |
 |  `&#39; &#39;` |  U+00A0 不间断空间 | 强制相邻的字符粘在一起. 在 HTML 中称为 ` .  |
 |  ```  U+00AD 软连字符 |  （在 HTML 中：）类似于零宽度空间，但如果（且仅当）发生中断时显示连字符.  |
 |  `&#39;‍&#39;` |  U+200D 零宽度连接器 | 强制相邻字符连接在一起（例如，阿拉伯字符或支持的表情符号）. 可以用它来组合顺序组合的表情符号.  |
 |  `&#39;⁠&#39;` |  U+2060 字连接器 | 与 U+00A0 相同，但完全不可见. 适合在 Twitter 上写@font-face.  |
 |  `&#39; &#39;` |  U+1680 OGHAM 空间标记 | 一个看起来像破折号的空间. 伟大的让程序员接近疯狂：1 + 2 === 3.
 |  `&#39;;&#39;` |  U+037E 希腊问号 | 与分号相似. 这也是惹恼开发人员的一种有趣方式.  |
 |  ```  U+202D | 将文本方向更改为从左到右.  |
 |  ```  U+202E | 将文本方向更改为从右到左：|
 |  `&#39;ꓸ&#39;` |  U+A4F8 傈僳语 LETTER TONE MYA TI | 与古文字相似.  |
 |  `&#39;ꓹ&#39;` |  U+A4F9 LISU LETTER TONE NA PO |与逗号字符相似.|
| `'ꓼ'` | U+A4FC LISU LETTER TONE MYA NA |A lookalike for the semi-colon character.|
 |  `&#39;ꓽ&#39;` |  U+A4FD LISU LETTER TONE MYA JEU|冒号字符相似.|
 |  `&#39;︀&#39;` |  **变体选择器**（U+FE00 到 U+FE0F 和 U+E0100 到 U+E01EF）| 具有 ID_Continue 属性的 256 个零宽度字符块 - 这意味着它们可以用于变量名称（不是第一个字母）. 这些特别之处在于鼠标光标在它们组合字符时经过它们 - 与大多数其他零宽度字符不同.
 |  `&#39;ᅟ&#39;` |  **U+115F 韩文初音填料** | 一般来说，它会产生一个空间. 如果在渲染中未明确支持，则渲染为零宽度（不可见）. 指定ID_Start|
 |  `&#39;ᅠ&#39;` |  **U+1160 HANGUL JUNGSEONG 填料** | 也许它产生了一个空间？ 如果在渲染中未明确支持，则渲染为零宽度（不可见）. 指定ID_Start|
 |  `&#39;ㅤ&#39;` |  **U+3164 韩文填充符** | 一般来说，它会产生一个空间. 如果在渲染中未明确支持，则渲染为零宽度（不可见）. 指定ID_Start |
<br><br>
#### Wait a second... what did I just read?


<br><br>
## Variable identifiers can effectively include whitespace!

 **U+3164 HANGUL FILLER** 字符显示为前进空白字符. 字符呈现为完全不可见（并且不前进，即“零宽度”），如果没有明确 [supported in rendering](http://unicode.org/faq/unsup_char.html) . 这意味着不应该显示丑陋的字符替换 (�) 符号.

我还不确定为什么 U+3164 被指定为这种行为. 有趣的是，U+3164 是在 1.1 版（1993 年）中添加到 Unicode 中的——所以联盟一定有很多时间来考虑它. 无论如何，这里有几个例子.

```javascript
&gt; var ᅟ = &#39;foo&#39;;
undefined
&gt;ᅟ
'foo'


&gt; 是 ᅠ= 警报；
undefined
&gt; var foo = &#39;酒吧&#39;
undefined
&gt; if ( foo ===`baz` ){} // 警报
undefined


&gt; var varᅠfooᅠ\u{A60C}ᅠπ = &#39;bar&#39;;
undefined
&gt; var ᅠ foo ꘌ ᅠ π
'bar'

```
<br>
 **注意：**我已经在 Ubuntu 和 OS X 上使用以下测试了 U+3164 渲染：`node`、`php`、`ruby`、`python3.5`、`scala`、`vim`、` cat`、`chrome`+`github gist`.  Atom 是唯一一个因（错误地）显示空框而失败的系统. 我还没有在 Emacs 和 Sublime 上测试它. 据我了解，Unicode 联盟不会重新分配或重命名字符或代码点，但可能会被说服更改 ID_Start/ID_Continue 等字符属性.


<br>



## Modifiers

零宽度连接符 (ZWJ) 是一种非印刷字符，用于某些复杂文字（例如阿拉伯文字或任何印度文字）的计算机排版. 当放置在两个原本不会连接的字符之间时，ZWJ 会使它们以连接的形式打印.

零宽度非连接符 (ZWNJ) 是一种非打印字符，用于使用连字的书写系统的计算机化. 当放置在两个原本会连接成连字的字符之间时，ZWNJ 会导致它们分别以最终形式和初始形式打印. 这也是空格字符的效果，但是当希望将单词靠得更近或将单词与其词素连接时，会使用 ZWNJ.



```javascript
&gt; &#39;一个&#39;
 “A”

&gt; &#39;a\u{0308}&#39;
 “A”

> 'a\u{20DE}\u{0308}'
 “a⃞̈”

&gt; &#39;a\u{20DE}\u{0308}\u{20DD}&#39;
 “a⃞̈⃝”

// 修改不可见字符
&gt; &#39;\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{ 200E}&#39;
 "‎‎‎‎‎‎‎‎‎‎"

&gt; &#39;\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{200E}\u{ 200E}&#39;.长度
 10
```


## :collision: Uppercase Transformation Collisions

 | 字符 | 代码点 | 输出字符 |
|------|------------|-------------|
 |  ß |  0x00DF |  `SS` |
 | 我 |  0x0131 |  `我` |
 |  ſ |  0x017F |  `S` |
 |  ﬁ |  0xFB00 |  `FF` |
 | 网络 |  0xFB01 |  `FI` |
 |  |  0xFB02 |  ``在&#39;&#39; |
 |  ﬃ |  0xFB03 |  ``费用&#39;&#39;|
 |  ﬄ |  0xFB04 |  `FFL`|
 |  ﬅ |  0xFB05 |  `ST` |
 |  ﬆ |  0xFB06 |  `ST` |

## :collision: Lowercase Transformation Collisions
 | 字符 | 代码点 | 输出字符 |
|------|------------|-------------|
 |  K |  0x212A |  `k` |



## Quirks and Troubleshooting

 - **字符串长度通常由计算代码点来确定.**这意味着代理项对将计为两个字符. 组合多个变音符号可以叠加在同一个字符上.  `a + ̈ == ̈a `，增加长度，同时只产生一个字符.

- **同样，反转字符串通常是一项非常重要的任务.**同样，代理对和变音符号必须一起反转. [ES Reverser](https://github.com/mathiasbynens/esrever) provides a pretty good solution.

- **大写和小写映射并不总是一对一的.**它们也可以是：
  - 一对多：(ß → SS )
  - 上下文：(…Σ ↔ …σ AND …Σ… ↔ …σ… )
  - 语言环境敏感：（ I ↔ ı 和 İ ↔ i ）



### One-To-Many Case Mappings
 *以下大多数字符在大写时表示它们的一对多大小写映射，而其他字符应小写. 这个列表应该分开*





 | 代码点 | 人物 | 名称 | 映射字符 | 映射代码点 |
|-------------------------------------------------|-----------|--------------------------------------------------------------------------|------------------|------------------------|
| [U+00DF](https://codepoints.net/U+00DF?lang=en)  |  `ß` | 拉丁文小写字母升号 S |  `s`, `s` |  U+0073, U+0073 |
| [U+0130](https://codepoints.net/U+0130?lang=en)  |  `İ` | 带点的拉丁文大写字母 I |  `i`, `̇` |  U+0069, U+0307 |
| [U+0149](https://codepoints.net/U+0149?lang=en)  |  `ŉ` | 带撇号的拉丁文小写字母 N |  ```, `n` |  U+02BC, U+006E |
| [U+01F0](https://codepoints.net/U+01F0?lang=en)  |  `ǰ` | 带 CARON 的拉丁文小写字母 J |  `j`, `̌` |  U+006A, U+030C |
| [U+0390](https://codepoints.net/U+0390?lang=en)  |  `α` | 带有 DIALYTIKA 和 TONOS 的希腊小写字母 IOTA |  `ι`, `̈`, `́` |  U+03B9、U+0308、U+0301 |
| [U+03B0](https://codepoints.net/U+03B0?lang=en)  |  `ð` | 带有 DIALYTIKA 和 TONOS 的希腊小写字母 UPSILON |  `υ`, `̈`, `́` |  U+03C5、U+0308、U+0301 |
| [U+0587](https://codepoints.net/U+0587?lang=en)  |: 和亚美尼亚小连字 ECH YIWN |:  ``e&#39;&#39;, ``u&#39;&#39; |  U+0565, U+0582 |:
| [U+1E96](https://codepoints.net/U+1E96?lang=en)  |  `ẖ` | 带下划线的拉丁文小写字母 H |  `h`, `̱` |  U+0068, U+0331 |
| [U+1E97](https://codepoints.net/U+1E97?lang=en)  |  `ẗ` | 带分音符的拉丁文小写字母 T |  `t`, `̈` |  U+0074, U+0308 |
| [U+1E98](https://codepoints.net/U+1E98?lang=en)  |  `ẘ` | 带圆环的拉丁文小写字母 W |  `w`, `̊` |  U+0077、U+030A |
| [U+1E99](https://codepoints.net/U+1E99?lang=en)  |  `ẙ` | 带上环的拉丁文小写字母 Y |  `y`, `̊` |  U+0079, U+030A |
| [U+1E9A](https://codepoints.net/U+1E9A?lang=en)  |  `ẚ` | 带右半环的拉丁文小写字母 A |  `a`, `ʾ` |  U+0061, U+02BE |
| [U+1E9E](https://codepoints.net/U+1E9E?lang=en)  |  `ẞ` | 拉丁文大写字母 SHARP S |  `s`, `s` |  U+0073, U+0073 |
| [U+1F50](https://codepoints.net/U+1F50?lang=en)  |  `ὐ` | 带有 PSILI 的希腊小写字母 UPSILON |  `υ`, `̓` |  U+03C5, U+0313 |
| [U+1F52](https://codepoints.net/U+1F52?lang=en)  |  `ὒ` | 带 PSILI 和 VARIA 的希腊小写字母 UPSILON |  `υ`, `̓`, `̀` |  U+03C5、U+0313、U+0300 |
| [U+1F54](https://codepoints.net/U+1F54?lang=en)  |  `ὔ` | 带有 PSILI 和 OXIA 的希腊小写字母 UPSILON |  `υ`, `̓`, `́` |  U+03C5、U+0313、U+0301 |
| [U+1F56](https://codepoints.net/U+1F56?lang=en)  |  `ὖ` | 带有 PSILI 和 PERISPOMENI 的希腊小写字母 UPSILON |  `υ`, `̓`, `͂` |  U+03C5、U+0313、U+0342 |
| [U+1F80](https://codepoints.net/U+1F80?lang=en)  |  `ᾀ` | 带 PSILI 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἀ`, `i` |  U+1F00, U+03B9 |
| [U+1F81](https://codepoints.net/U+1F81?lang=en)  |  `ᾁ` | 带 DASIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἁ`, `i` |  U+1F01, U+03B9 |
| [U+1F82](https://codepoints.net/U+1F82?lang=en)  |  `ᾂ` | 带 PSILI、VARIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἂ`, `ι` |  U+1F02, U+03B9 |
| [U+1F83](https://codepoints.net/U+1F83?lang=en)  |  `ᾃ` | 带 DASIA 和 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἃ`, `ι` |  U+1F03, U+03B9 |
| [U+1F84](https://codepoints.net/U+1F84?lang=en)  |  `ᾄ` | 带 PSILI、OXIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `是`，`ι` |  U+1F04, U+03B9 |
| [U+1F85](https://codepoints.net/U+1F85?lang=en)  |  `ᾅ` | 带 DASIA 和 OXIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἅ`, `ι` |  U+1F05, U+03B9 |
| [U+1F86](https://codepoints.net/U+1F86?lang=en)  |  `ᾆ` | 带 PSILI 和 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἆ`, `ι` |  U+1F06, U+03B9 |
| [U+1F87](https://codepoints.net/U+1F87?lang=en)  |  `ᾇ` | 带 DASIA 和 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ἇ`, `ι` |  U+1F07, U+03B9 |
| [U+1F88](https://codepoints.net/U+1F88?lang=en)  |  `ᾈ` | 带有 PSILI 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `ἀ`, `i` |  U+1F00, U+03B9 |
| [U+1F89](https://codepoints.net/U+1F89?lang=en)  |  `ᾉ` | 带 DASIA 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `ἁ`, `i` |  U+1F01, U+03B9 |
| [U+1F8A](https://codepoints.net/U+1F8A?lang=en)  |  `ᾊ` | 带有 PSILI 和 VARIA 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `ἂ`, `ι` |  U+1F02, U+03B9 |
| [U+1F8B](https://codepoints.net/U+1F8B?lang=en)  |  `ᾋ` | 带 DASIA 和 VARIA 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `ἃ`, `ι` |  U+1F03, U+03B9 |
| [U+1F8C](https://codepoints.net/U+1F8C?lang=en)  |  `ᾌ` | 带有 PSILI 和 OXIA 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `是`，`ι` |  U+1F04, U+03B9 |
| [U+1F8D](https://codepoints.net/U+1F8D?lang=en)  |  `ᾍ` | 带有 DASIA 和 OXIA 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `ἅ`, `ι` |  U+1F05, U+03B9 |
| [U+1F8E](https://codepoints.net/U+1F8E?lang=en) | `ᾎ`       | GREEK CAPITAL LETTER ALPHA WITH PSILI AND PERISPOMENI AND PROSGEGRAMMENI | `ἆ`, `ι`         | U+1F06, U+03B9         |
| [U+1F8F](https://codepoints.net/U+1F8F?lang=en)  |  `ᾏ` | 带 DASIA 和 PERISPOMENI 和 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `ἇ`, `ι` |  U+1F07, U+03B9 |
| [U+1F90](https://codepoints.net/U+1F90?lang=en)  |  `ᾐ` | 带 PSILI 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἠ`, `i` |  U+1F20, U+03B9 |
| [U+1F91](https://codepoints.net/U+1F91?lang=en)  |  `ᾑ` | 带有 DASIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἡ`, `i` |  U+1F21, U+03B9 |
| [U+1F92](https://codepoints.net/U+1F92?lang=en)  |  `ᾒ` | 带 PSILI、VARIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἢ`, `i` |  U+1F22, U+03B9 |
| [U+1F93](https://codepoints.net/U+1F93?lang=en)  |  `ᾓ` | 带 DASIA 和 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἣ`, `i` |  U+1F23, U+03B9 |
| [U+1F94](https://codepoints.net/U+1F94?lang=en)  |  `ᾔ` | 带 PSILI、OXIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἤ`, `i` |  U+1F24, U+03B9 |
| [U+1F95](https://codepoints.net/U+1F95?lang=en)  |  `ᾕ` | 带 DASIA 和 OXIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἥ`, `i` |  U+1F25, U+03B9 |
| [U+1F96](https://codepoints.net/U+1F96?lang=en)  |  `ᾖ` | 带 PSILI 和 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἦ&#39;, `i&#39; |  U+1F26, U+03B9 |
| [U+1F97](https://codepoints.net/U+1F97?lang=en)  |  `ᾗ` | 带有 DASIA 和 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ἧ`, `i` |  U+1F27, U+03B9 |
| [U+1F98](https://codepoints.net/U+1F98?lang=en)  |  `ᾘ` | 带有 PSILI 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἠ`, `i` |  U+1F20, U+03B9 |
| [U+1F99](https://codepoints.net/U+1F99?lang=en)  |  `ᾙ` | 带 DASIA 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἡ`, `i` |  U+1F21, U+03B9 |
| [U+1F9A](https://codepoints.net/U+1F9A?lang=en)  |  `ᾚ` | 带有 PSILI 和 VARIA 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἢ`, `i` |  U+1F22, U+03B9 |
| [U+1F9B](https://codepoints.net/U+1F9B?lang=en)  |  `ᾛ` | 带 DASIA 和 VARIA 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἣ`, `i` |  U+1F23, U+03B9 |
| [U+1F9C](https://codepoints.net/U+1F9C?lang=en)  |  `ᾜ` | 带 PSILI 和 OXIA 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἤ`, `i` |  U+1F24, U+03B9 |
| [U+1F9D](https://codepoints.net/U+1F9D?lang=en)  |  `ᾝ` | 带有 DASIA 和 OXIA 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἥ`, `i` |  U+1F25, U+03B9 |
| [U+1F9E](https://codepoints.net/U+1F9E?lang=en)  |  `ᾞ` | 带 PSILI 和 PERISPOMENI 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἦ&#39;, `i&#39; |  U+1F26, U+03B9 |
| [U+1F9F](https://codepoints.net/U+1F9F?lang=en)  |  `ᾟ` | 带 DASIA 和 PERISPOMENI 和 PROSGEGRAMMENI 的希腊大写字母 ETA |  `ἧ`, `i` |  U+1F27, U+03B9 |
| [U+1FA0](https://codepoints.net/U+1FA0?lang=en)  |  `ᾠ` | 带 PSILI 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὠ`, `ι` |  U+1F60, U+03B9 |
| [U+1FA1](https://codepoints.net/U+1FA1?lang=en)  |  `ᾡ` | 带 DASIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `c&#39;, `i&#39; |  U+1F61, U+03B9 |
| [U+1FA2](https://codepoints.net/U+1FA2?lang=en)  |  `ᾢ` | 带 PSILI 和 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὢ`, `ι` |  U+1F62, U+03B9 |
| [U+1FA3](https://codepoints.net/U+1FA3?lang=en)  |  `ᾣ` | 带 DASIA 和 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὣ`, `ι` |  U+1F63, U+03B9 |
| [U+1FA4](https://codepoints.net/U+1FA4?lang=en)  |  `ᾤ` | 带 PSILI、OXIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὤ`, `ι` |  U+1F64, U+03B9 |
| [U+1FA5](https://codepoints.net/U+1FA5?lang=en)  |  `ᾥ` | 带 DASIA 和 OXIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὥ`, `ι` |  U+1F65, U+03B9 |
| [U+1FA6](https://codepoints.net/U+1FA6?lang=en)  |  `ᾦ` | 带 PSILI 和 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὦ`, `ι` |  U+1F66, U+03B9 |
| [U+1FA7](https://codepoints.net/U+1FA7?lang=en)  |  `ᾧ` | 带 DASIA 和 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὧ`, `i` |  U+1F67, U+03B9 |
| [U+1FA8](https://codepoints.net/U+1FA8?lang=en)  |  `ᾨ` | 带 PSILI 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὠ`, `ι` |  U+1F60, U+03B9 |
| [U+1FA9](https://codepoints.net/U+1FA9?lang=en)  |  `ᾩ` | 带有 DASIA 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὡ`, `ι` |  U+1F61, U+03B9 |
| [U+1FAA](https://codepoints.net/U+1FAA?lang=en)  |  `ᾪ` | 带 PSILI 和 VARIA 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὢ`, `ι` |  U+1F62, U+03B9 |
| [U+1FAB](https://codepoints.net/U+1FAB?lang=en)  |  `ᾫ` | 带 DASIA 和 VARIA 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὣ`, `ι` |  U+1F63, U+03B9 |
| [U+1FAC](https://codepoints.net/U+1FAC?lang=en)  |  `ᾬ` | 带 PSILI 和 OXIA 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὤ`, `i` |  U+1F64, U+03B9 |
| [U+1FAD](https://codepoints.net/U+1FAD?lang=en)  |  `ᾭ` | 带 DASIA 和 OXIA 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὥ`, `ι` |  U+1F65, U+03B9 |
| [U+1FAE](https://codepoints.net/U+1FAE?lang=en)  |  `ᾮ` | 带 PSILI 和 PERISPOMENI 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὦ`, `ι` |  U+1F66, U+03B9 |
| [U+1FAF](https://codepoints.net/U+1FAF?lang=en)  |  `ᾯ` | 带 DASIA 和 PERISPOMENI 和 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  `ὧ`, `i` |  U+1F67, U+03B9 |
| [U+1FB2](https://codepoints.net/U+1FB2?lang=en)  |  `ᾲ` | 带有 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `ὰ`, `i` |  U+1F70, U+03B9 |
| [U+1FB3](https://codepoints.net/U+1FB3?lang=en)  |  `ᾳ` | 带 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `a&#39;, `i&#39; |  U+03B1, U+03B9 |
| [U+1FB4](https://codepoints.net/U+1FB4?lang=en)  |  `ᾴ` | 带 OXIA 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `a&#39;, `i&#39; |  U+03AC, U+03B9 |
| [U+1FB6](https://codepoints.net/U+1FB6?lang=en)  |  `ᾶ` | 带 PERISPOMENI 的希腊小写字母 ALPHA |  `a`，`͂` |  U+03B1、U+0342 |
| [U+1FB7](https://codepoints.net/U+1FB7?lang=en)  |  `ᾷ` | 带 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 ALPHA |  `a`，`͂`，`i` |  U+03B1、U+0342、U+03B9 |
| [U+1FBC](https://codepoints.net/U+1FBC?lang=en)  |  `ᾼ` | 带有 PROSGEGRAMMENI 的希腊大写字母 ALPHA |  `a&#39;, `i&#39; |  U+03B1, U+03B9 |
| [U+1FC2](https://codepoints.net/U+1FC2?lang=en)  |  `ῂ` | 带有 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `ὴ`, `i` |  U+1F74, U+03B9 |
| [U+1FC3](https://codepoints.net/U+1FC3?lang=en)  |  `ῃ` | 带 YPOGEGRAMMENI 的希腊小写字母 ETA |  `h&#39;, `i&#39; |  U+03B7, U+03B9 |
| [U+1FC4](https://codepoints.net/U+1FC4?lang=en)  |  `ῄ` | 带 OXIA 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `或&#39;, `我&#39; |  U+03AE, U+03B9 |
| [U+1FC6](https://codepoints.net/U+1FC6?lang=en)  |  `ῆ` | 带 PERISPOMENI 的希腊小写字母 ETA |  `η`, `͂` |  U+03B7, U+0342 |
| [U+1FC7](https://codepoints.net/U+1FC7?lang=en)  |  `ῇ` | 带 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 ETA |  `h`, ͂`, `i` |  U+03B7、U+0342、U+03B9 |
| [U+1FCC](https://codepoints.net/U+1FCC?lang=en)  |  `ῌ` | 带有 PROSGEGRAMMENI 的希腊大写字母 ETA |  `h&#39;, `i&#39; |  U+03B7, U+03B9 |
| [U+1FD2](https://codepoints.net/U+1FD2?lang=en)  |  `ῒ` | 带有 DIALYTIKA 和 VARIA 的希腊小写字母 IOTA |  `ι`, `̈`, `̀` |  U+03B9、U+0308、U+0300 |
| [U+1FD3](https://codepoints.net/U+1FD3?lang=en)  |  `我` | 带有 DIALYTIKA 和 OXIA 的希腊小写字母 IOTA |  `i`, `̈`, `́` |  U+03B9、U+0308、U+0301 |
| [U+1FD6](https://codepoints.net/U+1FD6?lang=en)  |  `ῖ` | 带 PERISPOMENI 的希腊小写字母 IOTA |  `i`, `͂` |  U+03B9，U+0342 |
| [U+1FD7](https://codepoints.net/U+1FD7?lang=en)  |  `ῗ` | 带有 DIALYTIKA 和 PERISPOMENI 的希腊小写字母 IOTA |  `ι`, `̈`, `͂` |  U+03B9、U+0308、U+0342 |
| [U+1FE2](https://codepoints.net/U+1FE2?lang=en)  |  `ῢ` | 带有 DIALYTIKA 和 VARIA 的希腊小写字母 UPSILON |  `υ`, `̈`, `̀` |  U+03C5、U+0308、U+0300 |
| [U+1FE3](https://codepoints.net/U+1FE3?lang=en)  |  ‘冰’ | 带 DIALYTIKA 和 OXIA 的希腊小写字母 UPSILON |  `y`, `̈`, `́` |  U+03C5、U+0308、U+0301 |
| [U+1FE4](https://codepoints.net/U+1FE4?lang=en)  |  `ῤ` | 带有 PSILI 的希腊小写字母 RHO |  `ρ`, `̓` |  U+03C1, U+0313 |
| [U+1FE6](https://codepoints.net/U+1FE6?lang=en)  |  `ῦ` | 带 PERISPOMENI 的希腊小写字母 UPSILON |  `υ`, `͂` |  U+03C5、U+0342 |
| [U+1FE7](https://codepoints.net/U+1FE7?lang=en)  |  `ῧ` | 带有 DIALYTIKA 和 PERISPOMENI 的希腊小写字母 UPSILON |  `υ`, `̈`, `͂` |  U+03C5、U+0308、U+0342 |
| [U+1FF2](https://codepoints.net/U+1FF2?lang=en)  |  `ῲ` | 带有 VARIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ὼ`, `i` |  U+1F7C, U+03B9 |
| [U+1FF3](https://codepoints.net/U+1FF3?lang=en)  |  `ῳ` | 带 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  ‘哦’，‘我’ |  U+03C9, U+03B9 |
| [U+1FF4](https://codepoints.net/U+1FF4?lang=en)  |  `ῴ` | 带 OXIA 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ώ`, `ι` |  U+03CE, U+03B9 |
| [U+1FF6](https://codepoints.net/U+1FF6?lang=en)  |  `ῶ` | 带 PERISPOMENI 的希腊小写字母 OMEGA |  `ω`, `͂` |  U+03C9, U+0342 |
| [U+1FF7](https://codepoints.net/U+1FF7?lang=en)  |  `ῷ` | 带 PERISPOMENI 和 YPOGEGRAMMENI 的希腊小写字母 OMEGA |  `ω`, ͂`, `i` |  U+03C9、U+0342、U+03B9 |
| [U+1FFC](https://codepoints.net/U+1FFC?lang=en)  |  `ῼ` | 带有 PROSGEGRAMMENI 的希腊大写字母 OMEGA |  ‘哦’，‘我’ |  U+03C9, U+03B9 |
| [U+FB00](https://codepoints.net/U+FB00?lang=en)  |  `` | 拉丁文小号连字 FF |  `f`, `f` |  U+0066, U+0066 |
| [U+FB01](https://codepoints.net/U+FB01?lang=en)  |  `fi` | 拉丁小连字 FI |  `f`, `i` |  U+0066, U+0069 |
| [U+FB02](https://codepoints.net/U+FB02?lang=en)  |  `fl` | 拉丁小连字 FL |  `f`, `l` |  U+0066、U+006C |
| [U+FB03](https://codepoints.net/U+FB03?lang=en)  |  `ﬃ` | 拉丁文小写连字 FFI |  `f`, `f`, `i` |  U+0066、U+0066、U+0069 |
| [U+FB04](https://codepoints.net/U+FB04?lang=en)  |  `ﬄ` | 拉丁小连字 FFL |  `f`, `f`, `l` |  U+0066、U+0066、U+006C |
| [U+FB05](https://codepoints.net/U+FB05?lang=en)  |  `ﬅ` | 拉丁文小号连字长 ST |  `s`, `t` |  U+0073, U+0074 |
| [U+FB06](https://codepoints.net/U+FB06?lang=en)  |  `ﬆ` | 拉丁小连字 ST |  `s`, `t` |  U+0073, U+0074 |
| [U+FB13](https://codepoints.net/U+FB13?lang=en)  |:  |: 亚美尼亚小连字男士现在 |:  ``m&#39;&#39;, ``n&#39;&#39; |  U+0574, U+0576 |:
| [U+FB14](https://codepoints.net/U+FB14?lang=en)  |:  ``我&#39;&#39; | 亚美尼亚小连字男士 ECH |：  ``m&#39;&#39;, ``e&#39;&#39; |  U+0574, U+0565 |:
| [U+FB15](https://codepoints.net/U+FB15?lang=en)  |:  ``米&#39;&#39; |: 亚美尼亚小连字男士 INI |:  ``m&#39;&#39;, ``i&#39;&#39; |  U+0574, U+056B |:
| [U+FB16](https://codepoints.net/U+FB16?lang=en)  |:  `ﬖ` |: 亚美尼亚小连字现在查看|：  ``v&#39;&#39;, ``n&#39;&#39; |:  U+057E, U+0576 |:
| [U+FB17](https://codepoints.net/U+FB17?lang=en)  |:  `ﬗ` |: 亚美尼亚小连字男 XEH |:  ``m&#39;&#39;, ``kh&#39;&#39; |:  U+0574, U+056D |:





## Awesome Packages & Libraries
- [PhantomScript](https://github.com/jagracey/PhantomScript) - :ghost: :flashlight: 不可见的 JavaScript 代码执行和社会工程
- [ESReverser](https://github.com/mathiasbynens/esrever) - 用 Ja​​vaScript 编写的可识别 Unicode 的字符串反向器.
- [mimic](https://github.com/reinderien/mimic) - [滥用]使用 Unicode 制造悲剧
- [python-ftfy](https://github.com/LuminosoInsight/python-ftfy) - 给定 Unicode 文本，使其表示一致并且可能更少损坏.
- [vim-troll-stopper](https://github.com/vim-utils/vim-troll-stopper) - 阻止 Unicode trolls 弄乱您的代码.


## Emojis
* [Unicode Consortium's Emoji Chart](http://www.unicode.org/emoji/charts/full-emoji-list.html)
* [Emojipedia](http://emojipedia.org/) - Information about specific emoji, news blog.
* [emojitracker](http://emojitracker.com/) - 在 Twitter 上使用实时表情符号.
* [World Translation Foundation](http://www.emojifoundation.com/) - 一种推广、探索书面文字并将其翻译成表情符号图形字母表的方法.
* [Can I Emoji?](http://caniemoji.com/android-2/) - 显示 iOS、Android 和 Windows 原生表情符号支持的当前状态.
* [How to register an emoji URL](http://www.name.com/blog/how-tos/2015/12/want-an-emoji-url-this-is-how-you-register-one/)


## Diversity

 Unicode 联盟做出了巨大努力，以更好地反映和融合人类多样性，包括文化习俗. 这是财团 [diversity report](http://unicode.org/reports/tr51/#Diversity).

同性家庭、牵手、接吻等混合性别表情现已上线. 真正的踢球者是 [Emoji combined sequences](http://www.unicode.org/emoji/charts/emoji-zwj-sequences.html) . 基本上：


 | 代码点 | 食谱 | 合并 |
|-------------|----------|----------|
 |  U+1F469 U+200D U+2764 U+FE0F U+200D U+1F469 | <img height="36" width="auto" alt="👩" src="http://unicode.org/reports/tr51/images/apple/apple_1f469.png"> <img height="36" width="auto" alt="❤️‍" src="http://unicode.org/reports/tr51/images/other/zwj.png"> <img height="36" width="auto" alt="❤️‍" src="http://unicode.org/reports/tr51/images/apple/apple_2764.png"> <img height="36" width="auto" alt="❤️‍" src="http://unicode.org/reports/tr51/images/other/zwj.png"> <img height="36" width="auto" alt="👩" src="http://unicode.org/reports/tr51/images/apple/apple_1f469.png"> | <img height="36" width="auto" alt="couple with heart: woman, woman" src="http://unicode.org/reports/tr51/images/apple/apple_1f469_200d_2764_fe0f_200d_1f469.png"> |
|U+1F468 U+200D U+1F468 U+200D U+1F467 U+200D U+1F466|<img height="36" width="auto" src="https://raw.githubusercontent.com/jagracey/Awesome-Unicode/c575db618a89c88624a8c3bdfe57eada064cbf14/resources/family%3B%20man%2C%20man%2C%20girl%2C%20boy%20-%20fallback%20-%20ZWJ.jpg">|<img height="36" width="auto" src="https://raw.githubusercontent.com/jagracey/Awesome-Unicode/58f28d08aef7f36eb6cdca22d25e7654cd8de5ae/resources/family%3B%20man%2C%20man%2C%20girl%2C%20boy.png">|

此外，表情符号现在支持肤色修饰符.

 &gt; 在 Unicode 版本 8.0（2015 年年中）中发布了五个符号修饰字符，为人类表情符号提供一系列肤色. 这些字符基于 Fitzpatrick 量表的六种音调，这是皮肤病学公认的标准（网上有很多这种量表的示例，例如 FitzpatrickSkinType.pdf）. 确切的阴影可能因实现而异.  -- [Unicode Consortium's Diversity report](http://unicode.org/reports/tr51/#Diversity)




 | 代码 | 名称 | 样品 |
|---------|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
 |  U+1F3FB | 表情符号修饰符 FITZPATRICK TYPE-1-2 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2.png" height="20" width="20"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2-bw.png" height="20" width="20"> |
 |  U+1F3FC | 表情符号修饰符 FITZPATRICK TYPE-3 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3.png"   height="20" width="20"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3-bw.png"   height="20" width="20"> |
 |  U+1F3FD | 表情符号修改器 FITZPATRICK TYPE-4 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4.png"   height="20" width="20"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4-bw.png"   height="20" width="20"> |
 |  U+1F3FE | 表情符号修改器 FITZPATRICK TYPE-5 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5.png"   height="20" width="20"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5-bw.png"   height="20" width="20"> |
 |  U+1F3FF | 表情符号修饰符 FITZPATRICK TYPE-6 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6.png"   height="20" width="20"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6-bw.png"   height="20" width="20"> |



只需使用一种肤色修饰符“\u{1F466}\u{1F3FE}”跟随所需的表情符号.

<p align="center">
	<img src="http://unicode.org/reports/tr51/images/other/person.png" height="36" width="auto" alt="">
	<font size="36">+</font>
	<img src="http://unicode.org/reports/tr51/images/other/swatch-type-5.png" height="36" width="auto" alt="">
	<font size="36">→</font>
	<img src="http://unicode.org/reports/tr51/images/other/person-5.png" height="36" width="auto" alt="">
</p>



<p align="center">
	<img src="http://unicode.org/reports/tr51/images/other/palette-with-gray.png" alt="" height="48" width="auto">
</p>




## Creatively Naming Variables and Methods
*示例是用 JavaScript (ES6) 编写的*

一般来说，字符指定 [ID_START](https://codepoints.net/search?IDS=1)  property 可以用在变量名的开头. 指定的字符 [ID_CONTINUE](https://codepoints.net/search?IDC=1) 属性可以用在变量的第一个字符之后.


```javascript

功能兰德（米，小号）{ ... };

String.prototype.reverseⵑ = function(){..};

Number.prototype.isTrueɁ = function(){..};

其中 WhatDoesThisDoɁɁɁɁ = 42
```



这里有一些非常有创意的变量名来自 [Mathias Bynes](https://mathiasbynens.be/notes/javascript-identifiers#examples)

```javascript
// 多么方便！
var π = Math.PI;

// 有时，您只需要使用 JavaScript 的错误部分：
varಠ_ಠ=评估；

// 代码，你没有工作？！
var l_ಠ益ಠ_l = 42;

// 用于函数式编程的 JavaScript 库怎么样？
var λ = function() {};

// 混淆枯燥的变量名以获得伟大的正义
var \u006C\u006F\u006C\u0077\u0061\u0074 = &#39;嘿&#39;;

// …或者只是随机组成
是Ꙭלↈⴱ = &#39;嗯&#39;;

// 虽然完全有效，但在大多数浏览器中不起作用：
var foo\u200Cbar = 42;

// 这*不是*按位左移 (`&lt;&lt;`):
var 〱〱 = 2;
// 不过，这是：
〱〱 << 〱〱; // 8

// 给自己一个折扣：
var price_9̶9̶_89 = &#39;便宜&#39;;

// 有趣的罗马数字
Ⅳ = 4;
Ⅴ = 5;
Ⅳ + Ⅴ; // 9

//克苏鲁在这里
var hͫ̆̒̐ͣ̊̄ͯ͗͏̵̗̻̰̠̬͝ͅe̴̷̬͎̱̘͇͍̾ͦ͊͒͊̓̓̐_̫̠̱̩̭̤͈̑̎̋ͮͩ̒͑̾͋͘ç̳͕̯̭̱̲̣̠̜͋̍o̴̦̗̯̹̼ͭ̐ͨ̊̈͘͠m̶̝̠̭̭̤̻͓͑̓̊ͣͤ̎͟͠e̢̞̮̹͍̞̳̣ͣͪ͐̈t̡̯̳̭̜̠͕͌̈́̽̿ͤ̿̅̑ẖ̱̺̰̳̹̘̰̈́̏ͪ̂̽͂̀͠ =&#39;zalgo&#39;;
```


这是一些 [Unicode CSS Classes](https://davidwalsh.name/unicode-css-classes) 来自大卫·沃尔什
```html
<!-- place this within the document head -->
<meta charset="UTF-8" />

<!-- error message -->
<div class="ಠ_ಠ">您无权访问此页面.</div>

<!-- success message -->
<div class="❤">您的更改已成功保存！</div>
```

```css
.ठ_ठ{
	border: 1px solid #f00;
}

.❤ {
	背景：浅绿色；
}
```

## Recursive HTML Tag Renaming Script
如果您想将所有 HTML 标签重命名为什么都没有，下面的脚本正是您要找的.

*但请注意，HTML 不支持所有 unicode 字符.*
```javascript
// U+1160 HANGUL JUNGSEONG FILLER
transformAllTags('ᅠ');

// 一个实际的 HTML 元素节点，看起来像一个注释节点，使用 U+01C3 拉丁字母 RETROFLEX CLICK 
//	<ǃ-- name="viewport" content="width=device-width"></ǃ-->
transformAllTags('ǃ--');

// 甚至 &lt;ᅠ⃝
transformAllTags('\u{1160}\u{20dd}');

 // 作为奖励，所有现有的标签名称都将包含每个字符.  h⃞t⃞m⃞l⃞
transformAllTags();


函数 transformAllTags (newName){
   // querySelectorAll 实际上并不返回一个数组.
   Array.from(document.querySelectorAll(&#39;*&#39;))
     .forEach(函数(x){
         转换标签（x，新名称）；
   });
}

功能不稳定（str）{
  返回 str.split(&#39;&#39;).join(&#39;\u{20de}&#39;) + &#39;\u{20de}&#39;;
}

函数 transformTag(tagIdOrElem, tagType){
     var elem = (tagIdOrElem instanceof HTMLElement) ?  tagIdOrElem : document.getElementById(tagIdOrElem);
    如果(!elem || !(elem instanceof HTMLElement))返回；
    var children = elem.childNodes;
    var parent = elem.parentNode;
    var newNode = document.createElement(tagType||wonky(elem.tagName));
    对于（var a=0；a
        newNode.setAttribute(elem.attributes[a].nodeName, elem.attributes[a].value);
    }
    对于 (var i= 0,clen=children.length;i
         newNode.appendChild(children[0]);  //0...总是指向第一个未移动的元素
    }
    newNode.style.cssText = elem.style.cssText;
    parent.replaceChild(newNode,elem);
}
```
这是它支持的内容：

```javascript
功能测试开始（海峡）{
 尝试{
    eval(`document.createElement(&#39;${str}&#39;);`)
    返回真；
 }
 抓住（e）{ 返回假；  }
}

功能测试继续（海峡）{
 尝试{
    eval(`document.createElement(&#39;a${str}&#39;);`)
    返回真；
 }
 抓住（e）{ 返回假；  }
}
```

这是一些基本结果
```javascript
// 测试破折号是否可以开始一个 HTML 标签
&gt; 正文开始（&#39;-&#39;）
< false

&gt; 测试继续（&#39;-&#39;）
< true

&gt; testBegin(&#39;ᅠ-&#39;) // 使用 U+1160 HANGUL JUNGSEONG FILLER 前置破折号
< true
```


## Unicode Fonts
 *单一的 TrueType / OpenType 字体格式无法涵盖所有​​ UTF-8 字符，因为字体中存在 65535 个字形的硬性限制. 由于有超过 110 万个 UTF-8 字形，您需要使用一个字体系列来覆盖它们.*
- https://en.wikipedia.org/wiki/Unicode_font#List_of_Unicode_fonts
- http://www.unifont.org/fontguide/


## More Reading
* [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](http://www.joelonsoftware.com/articles/Unicode.html) - 乔尔·斯波尔斯基
* [What Every Programmer Absolutely, Positively Needs To Know About Encodings And Character Sets To Work With Text](http://kunststube.net/encoding/)
* [The Unicode Consortium's Recommended Reading List](http://www.unicode.org/resources/readinglist.html)
* [Space Yourself](https://www.smashingmagazine.com/2015/10/space-yourself/) - Smashing Magazine 的间距指南
* [JavaScript has a Unicode Problem](https://mathiasbynens.be/notes/javascript-unicode)
* [Creative usernames and Spotify account hijacking](https://labs.spotify.com/2013/06/18/creative-usernames/)


## Exploring Deeper into Unicode Yourself
- [Shapecatcher](http://shapecatcher.com/) - 画出你要找的角色.
- [Confusable Unicode Characters](http://unicode.org/cldr/utility/confusables.jsp?r=None)
- [Unicode Character Database](http://www.unicode.org/ucd/)
- [Database Dumps of Codepoints.net](https://dumps.codepoints.net/)
- [Unicode Blocks List](http://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt)
- [Unicode Character Code Charts](http://www.unicode.org/charts/index.html)
- [Unicode Case Charts](http://www.unicode.org/charts/case/)
- [Unicode Normalization Chart](http://www.unicode.org/charts/normalization/)
- [Unicode FAQ](http://www.unicode.org/faq/)




## Overview Map
## A map of the Basic Multilingual Plane
**每个带编号的框代表 256 个代码点.**
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Roadmap_to_Unicode_BMP.svg/750px-Roadmap_to_Unicode_BMP.svg.png" alt="A map of the Basic Multilingual Plane. Each numbered box represents 256 code points."/>
</p>

 *中文、日文和韩文 (CJK) 文字具有共同的背景，统称为 CJK 字符. 在称为汉统一的过程中，通用（共享）字符被识别并命名为“CJK Unified Ideographs”.*


## Unicode Blocks
 *Unicode 标准以块的形式将字符组排列在一起. 这是所有 17 个平面的完整块列表. *

| Name                                                                                                                         | From     | To       | \# Codepoints |
|------------------------------------------------------------------------------------------------------------------------------|----------|----------|---------------|
| [Basic Latin](https://wikipedia.org/wiki/Basic_Latin)                                                                       |  U+0000 |  U+007F |  (128) |
| [Latin-1 Supplement](https://wikipedia.org/wiki/Latin-1_Supplement)                                                         |  U+0080 |  U+00FF |  (128) |
| [Latin Extended-A](https://wikipedia.org/wiki/Latin_Extended-A)                                                             |  U+0100 |  U+017F |  (128) |
| [Latin Extended-B](https://wikipedia.org/wiki/Latin_Extended-B)                                                             |  U+0180 |  U+024F |  (208) |
| [IPA Extensions](https://wikipedia.org/wiki/IPA_Extensions)                                                                 |  U+0250 |  U+02AF |  (96) |
| [Spacing Modifier Letters](https://wikipedia.org/wiki/Spacing_Modifier_Letters)                                             |  U+02B0 |  U+02FF |  (80) |
| [Combining Diacritical Marks](https://wikipedia.org/wiki/Combining_Diacritical_Marks)                                       |  U+0300 |  U+036F |  (112) |
| [Greek and Coptic](https://wikipedia.org/wiki/Greek_and_Coptic)                                                             |  U+0370 |  U+03FF |  (135) |
| [Cyrillic](https://wikipedia.org/wiki/Cyrillic)                                                                             |  U+0400 |  U+04FF |  (256) |
| [Cyrillic Supplement](https://wikipedia.org/wiki/Cyrillic_Supplement)                                                       |  U+0500 |  U+052F |  (48) |
| [Armenian](https://wikipedia.org/wiki/Armenian)                                                                             |  U+0530 |  U+058F |  (89) |
| [Hebrew](https://wikipedia.org/wiki/Hebrew)                                                                                 |  U+0590 |  U+05FF |  (87) |
| [Arabic](https://wikipedia.org/wiki/Arabic)                                                                                 |  U+0600 |  U+06FF |  (255) |
| [Syriac](https://wikipedia.org/wiki/Syriac)                                                                                 |  U+0700 |  U+074F |  (77) |
| [Arabic Supplement](https://wikipedia.org/wiki/Arabic_Supplement)                                                           |  U+0750 |  U+077F |  (48) |
| [Thaana](https://wikipedia.org/wiki/Thaana)                                                                                 |  U+0780 |  U+07BF |  (50) |
| [NKo](https://wikipedia.org/wiki/NKo)                                                                                       |  U+07C0 |  U+07FF |  (59) |
| [Samaritan](https://wikipedia.org/wiki/Samaritan)                                                                           |  U+0800 |  U+083F |  (61) |
| [Mandaic](https://wikipedia.org/wiki/Mandaic)                                                                               |  U+0840 |  U+085F |  (29) |
| [Arabic Extended-A](https://wikipedia.org/wiki/Arabic_Extended-A)                                                           |  U+08A0 |  U+08FF |  (50) |
| [Devanagari](https://wikipedia.org/wiki/Devanagari)                                                                         |  U+0900 |  U+097F |  (128) |
| [Bengali](https://wikipedia.org/wiki/Bengali)                                                                               |  U+0980 |  U+09FF |  (93) |
| [Gurmukhi](https://wikipedia.org/wiki/Gurmukhi)                                                                             |  U+0A00 |  U+0A7F |  (79) |
| [Gujarati](https://wikipedia.org/wiki/Gujarati)                                                                             |  U+0A80 |  U+0AFF |  (85) |
| [Oriya](https://wikipedia.org/wiki/Oriya)                                                                                   |  U+0B00 |  U+0B7F |  (90) |
| [Tamil](https://wikipedia.org/wiki/Tamil)                                                                                   |  U+0B80 |  U+0BFF |  (72) |
| [Telugu](https://wikipedia.org/wiki/Telugu)                                                                                 |  U+0C00 |  U+0C7F |  (96) |
| [Kannada](https://wikipedia.org/wiki/Kannada)                                                                               |  U+0C80 |  U+0CFF |  (87) |
| [Malayalam](https://wikipedia.org/wiki/Malayalam)                                                                           |  U+0D00 |  U+0D7F |  (100) |
| [Sinhala](https://wikipedia.org/wiki/Sinhala)                                                                               |  U+0D80 |  U+0DFF |  (90) |
| [Thai](https://wikipedia.org/wiki/Thai)                                                                                     |  U+0E00 |  U+0E7F |  (87) |
| [Lao](https://wikipedia.org/wiki/Lao)                                                                                       |  U+0E80 |  U+0EFF |  (67) |
| [Tibetan](https://wikipedia.org/wiki/Tibetan)                                                                               |  U+0F00 |  U+0FFF |  (211) |
| [Myanmar](https://wikipedia.org/wiki/Myanmar)                                                                               |  U+1000 |  U+109F |  (160) |
| [Georgian](https://wikipedia.org/wiki/Georgian)                                                                             |  U+10A0 |  U+10FF |  (88) |
| [Hangul Jamo](https://wikipedia.org/wiki/Hangul_Jamo)                                                                       |  U+1100 |  U+11FF |  (256) |
| [Ethiopic](https://wikipedia.org/wiki/Ethiopic)                                                                             |  U+1200 |  U+137F |  (358) |
| [Ethiopic Supplement](https://wikipedia.org/wiki/Ethiopic_Supplement)                                                       |  U+1380 |  U+139F |  (26) |
| [Cherokee](https://wikipedia.org/wiki/Cherokee)                                                                             |  U+13A0 |  U+13FF |  (92) |
| [Unified Canadian Aboriginal Syllabics](https://wikipedia.org/wiki/Unified_Canadian_Aboriginal_Syllabics)                   |  U+1400 |  U+167F |  （640）|
| [Ogham](https://wikipedia.org/wiki/Ogham)                                                                                   |  U+1680 |  U+169F |  (29) |
| [Runic](https://wikipedia.org/wiki/Runic)                                                                                   |  U+16A0 |  U+16FF |  (89) |
| [Tagalog](https://wikipedia.org/wiki/Tagalog)                                                                               |  U+1700 |  U+171F |  (20) |
| [Hanunoo](https://wikipedia.org/wiki/Hanunoo)                                                                               |  U+1720 |  U+173F |  (23) |
| [Buhid](https://wikipedia.org/wiki/Buhid)                                                                                   |  U+1740 |  U+175F |  (20) |
| [Tagbanwa](https://wikipedia.org/wiki/Tagbanwa)                                                                             |  U+1760 |  U+177F |  (18) |
| [Khmer](https://wikipedia.org/wiki/Khmer)                                                                                   |  U+1780 |  U+17FF |  (114) |
| [Mongolian](https://wikipedia.org/wiki/Mongolian)                                                                           |  U+1800 |  U+18AF |  (156) |
| [Unified Canadian Aboriginal Syllabics Extended](https://wikipedia.org/wiki/Unified_Canadian_Aboriginal_Syllabics_Extended) |  U+18B0 |  U+18FF |  (70) |
| [Limbu](https://wikipedia.org/wiki/Limbu)                                                                                   |  U+1900 |  U+194F |  (68) |
| [Tai Le](https://wikipedia.org/wiki/Tai_Le)                                                                                 |  U+1950 |  U+197F |  (35) |
| [New Tai Lue](https://wikipedia.org/wiki/New_Tai_Lue)                                                                       |  U+1980 |  U+19DF |  (83) |
| [Khmer Symbols](https://wikipedia.org/wiki/Khmer_Symbols)                                                                   |  U+19E0 |  U+19FF |  (32) |
| [Buginese](https://wikipedia.org/wiki/Buginese)                                                                             |  U+1A00 |  U+1A1F |  (30) |
| [Tai Tham](https://wikipedia.org/wiki/Tai_Tham)                                                                             |  U+1A20 |  U+1AAF |  (127) |
| [Combining Diacritical Marks Extended](https://wikipedia.org/wiki/Combining_Diacritical_Marks_Extended)                     |  U+1AB0 |  U+1AFF |  (15) |
| [Balinese](https://wikipedia.org/wiki/Balinese)                                                                             |  U+1B00 |  U+1B7F |  (121) |
| [Sundanese](https://wikipedia.org/wiki/Sundanese)                                                                           |  U+1B80 |  U+1BBF |  (64) |
| [Batak](https://wikipedia.org/wiki/Batak)                                                                                   |  U+1BC0 |  U+1BFF |  (56) |
| [Lepcha](https://wikipedia.org/wiki/Lepcha)                                                                                 |  U+1C00 |  U+1C4F |  (74) |
| [Ol Chiki](https://wikipedia.org/wiki/Ol_Chiki)                                                                             |  U+1C50 |  U+1C7F |  (48) |
| [Sundanese Supplement](https://wikipedia.org/wiki/Sundanese_Supplement)                                                     |  U+1CC0 |  U+1CCF |  (8) |
| [Vedic Extensions](https://wikipedia.org/wiki/Vedic_Extensions)                                                             |  U+1CD0 |  U+1CFF |  (41) |
| [Phonetic Extensions](https://wikipedia.org/wiki/Phonetic_Extensions)                                                       |  U+1D00 |  U+1D7F |  (128) |
| [Phonetic Extensions Supplement](https://wikipedia.org/wiki/Phonetic_Extensions_Supplement)                                 |  U+1D80 |  U+1DBF |  (64) |
| [Combining Diacritical Marks Supplement](https://wikipedia.org/wiki/Combining_Diacritical_Marks_Supplement)                 |  U+1DC0 |  U+1DFF |  (58) |
| [Latin Extended Additional](https://wikipedia.org/wiki/Latin_Extended_Additional)                                           |  U+1E00 |  U+1FF |  (256) |
| [Greek Extended](https://wikipedia.org/wiki/Greek_Extended)                                                                 |  U+1F00 |  U+1FFF |  (233) |
| [General Punctuation](https://wikipedia.org/wiki/General_Punctuation)                                                       |  U+2000 |  U+206F |  (111) |
| [Superscripts and Subscripts](https://wikipedia.org/wiki/Superscripts_and_Subscripts)                                       |  U+2070 |  U+209F |  (42) |
| [Currency Symbols](https://wikipedia.org/wiki/Currency_Symbols)                                                             |  U+20A0 |  U+20CF |  (31) |
| [Combining Diacritical Marks for Symbols](https://wikipedia.org/wiki/Combining_Diacritical_Marks_for_Symbols)               |  U+20D0 |  U+20FF |  (33) |
| [Letterlike Symbols](https://wikipedia.org/wiki/Letterlike_Symbols)                                                         |  U+2100 |  U+214F |  (80) |
| [Number Forms](https://wikipedia.org/wiki/Number_Forms)                                                                     |  U+2150 |  U+218F |  (60) |
| [Arrows](https://wikipedia.org/wiki/Arrows)                                                                                 |  U+2190 |  U+21FF |  (112) |
| [Mathematical Operators](https://wikipedia.org/wiki/Mathematical_Operators)                                                 |  U+2200 |  U+22FF |  (256) |
| [Miscellaneous Technical](https://wikipedia.org/wiki/Miscellaneous_Technical)                                               |  U+2300 |  U+23FF |  (251) |
| [Control Pictures](https://wikipedia.org/wiki/Control_Pictures)                                                             |  U+2400 |  U+243F |  (39) |
| [Optical Character Recognition](https://wikipedia.org/wiki/Optical_Character_Recognition)                                   |  U+2440 |  U+245F |  (11) |
| [Enclosed Alphanumerics](https://wikipedia.org/wiki/Enclosed_Alphanumerics)                                                 |  U+2460 |  U+24FF |  (160) |
| [Box Drawing](https://wikipedia.org/wiki/Box_Drawing)                                                                       |  U+2500 |  U+257F |  (128) |
| [Block Elements](https://wikipedia.org/wiki/Block_Elements)                                                                 |  U+2580 |  U+259F |  (32) |
| [Geometric Shapes](https://wikipedia.org/wiki/Geometric_Shapes)                                                             |  U+25A0 |  U+25FF |  (96) |
| [Miscellaneous Symbols](https://wikipedia.org/wiki/Miscellaneous_Symbols)                                                   |  U+2600 |  U+26FF |  (256) |
| [Dingbats](https://wikipedia.org/wiki/Dingbats)                                                                             |  U+2700 |  U+27BF |  (192) |
| [Miscellaneous Mathematical Symbols-A](https://wikipedia.org/wiki/Miscellaneous_Mathematical_Symbols-A)                     |  U+27C0 |  U+27EF |  (48) |
| [Supplemental Arrows-A](https://wikipedia.org/wiki/Supplemental_Arrows-A)                                                   |  U+27F0 |  U+27FF |  (16) |
| [Braille Patterns](https://wikipedia.org/wiki/Braille_Patterns)                                                             |  U+2800 |  U+28FF |  (256) |
| [Supplemental Arrows-B](https://wikipedia.org/wiki/Supplemental_Arrows-B)                                                   |  U+2900 |  U+297F |  (128) |
| [Miscellaneous Mathematical Symbols-B](https://wikipedia.org/wiki/Miscellaneous_Mathematical_Symbols-B)                     |  U+2980 |  U+29FF |  (128) |
| [Supplemental Mathematical Operators](https://wikipedia.org/wiki/Supplemental_Mathematical_Operators)                       |  U+2A00 |  U+2AFF |  (256) |
| [Miscellaneous Symbols and Arrows](https://wikipedia.org/wiki/Miscellaneous_Symbols_and_Arrows)                             |  U+2B00 |  U+2BFF |  (206) |
| [Glagolitic](https://wikipedia.org/wiki/Glagolitic)                                                                         |  U+2C00 |  U+2C5F |  (94) |
| [Latin Extended-C](https://wikipedia.org/wiki/Latin_Extended-C)                                                             |  U+2C60 |  U+2C7F |  (32) |
| [Coptic](https://wikipedia.org/wiki/Coptic)                                                                                 |  U+2C80 |  U+2CFF |  (123) |
| [Georgian Supplement](https://wikipedia.org/wiki/Georgian_Supplement)                                                       |  U+2D00 |  U+2D2F |  (40) |
| [Tifinagh](https://wikipedia.org/wiki/Tifinagh)                                                                             |  U+2D30 |  U+2D7F |  (59) |
| [Ethiopic Extended](https://wikipedia.org/wiki/Ethiopic_Extended)                                                          | U+2D80   | U+2DDF   | (79)          |
| [Cyrillic Extended-A](https://wikipedia.org/wiki/Cyrillic_Extended-A)                                                       |  U+2DE0 |  U+2DFF |  (32) |
| [Supplemental Punctuation](https://wikipedia.org/wiki/Supplemental_Punctuation)                                             |  U+2E00 |  U+2E7F |  (67) |
| [CJK Radicals Supplement](https://wikipedia.org/wiki/CJK_Radicals_Supplement)                                               |  U+2E80 |  U+2EFF |  (115) |
| [Kangxi Radicals](https://wikipedia.org/wiki/Kangxi_Radicals)                                                               |  U+2F00 |  U+2FDF |  (214) |
| [Ideographic Description Characters](https://wikipedia.org/wiki/Ideographic_Description_Characters)                         |  U+2FF0 |  U+2FFF |  (12) |
| [CJK Symbols and Punctuation](https://wikipedia.org/wiki/CJK_Symbols_and_Punctuation)                                       |  U+3000 |  U+303F |  (64) |
| [Hiragana](https://wikipedia.org/wiki/Hiragana)                                                                             |  U+3040 |  U+309F |  (93) |
| [Katakana](https://wikipedia.org/wiki/Katakana)                                                                             |  U+30A0 |  U+30FF |  (96) |
| [Bopomofo](https://wikipedia.org/wiki/Bopomofo)                                                                             |  U+3100 |  U+312F |  (41) |
| [Hangul Compatibility Jamo](https://wikipedia.org/wiki/Hangul_Compatibility_Jamo)                                           |  U+3130 |  U+318F |  (94) |
| [Kanbun](https://wikipedia.org/wiki/Kanbun)                                                                                 |  U+3190 |  U+319F |  (16) |
| [Bopomofo Extended](https://wikipedia.org/wiki/Bopomofo_Extended)                                                           |  U+31A0 |  U+31BF |  (27) |
| [CJK Strokes](https://wikipedia.org/wiki/CJK_Strokes)                                                                       |  U+31C0 |  U+31EF |  (36) |
| [Katakana Phonetic Extensions](https://wikipedia.org/wiki/Katakana_Phonetic_Extensions)                                     |  U+31F0 |  U+31FF |  (16) |
| [Enclosed CJK Letters and Months](https://wikipedia.org/wiki/Enclosed_CJK_Letters_and_Months)                               |  U+3200 |  U+32FF |  (254) |
| [CJK Compatibility](https://wikipedia.org/wiki/CJK_Compatibility)                                                           |  U+3300 |  U+33FF |  (256) |
| [CJK Unified Ideographs Extension A](https://wikipedia.org/wiki/CJK_Unified_Ideographs_Extension_A)                         |  U+3400 |  U+4DBF |  (6191) |
| [Yijing Hexagram Symbols](https://wikipedia.org/wiki/Yijing_Hexagram_Symbols)                                               |  U+4DC0 |  U+4FF |  (64) |
| [CJK Unified Ideographs](https://wikipedia.org/wiki/CJK_Unified_Ideographs)                                                 |  U+4E00 |  U+9FF |  (20941) |
| [Yi Syllables](https://wikipedia.org/wiki/Yi_Syllables)                                                                     |  U+A000 |  U+A48F |  （1165）|
| [Yi Radicals](https://wikipedia.org/wiki/Yi_Radicals)                                                                       |  U+A490 |  U+A4CF |  (55) |
| [Lisu](https://wikipedia.org/wiki/Lisu)                                                                                     |  U+A4D0 |  U+A4FF |  (48) |
| [Vai](https://wikipedia.org/wiki/Vai)                                                                                       |  U+A500 |  U+A63F |  （300）|
| [Cyrillic Extended-B](https://wikipedia.org/wiki/Cyrillic_Extended-B)                                                       |  U+A640 |  U+A69F |  (96) |
| [Bamum](https://wikipedia.org/wiki/Bamum)                                                                                   |  U+A6A0 |  U+A6FF |  (88) |
| [Modifier Tone Letters](https://wikipedia.org/wiki/Modifier_Tone_Letters)                                                   |  U+A700 |  U+A71F |  (32) |
| [Latin Extended-D](https://wikipedia.org/wiki/Latin_Extended-D)                                                             |  U+A720 |  U+A7FF |  (159) |
| [Syloti Nagri](https://wikipedia.org/wiki/Syloti_Nagri)                                                                     |  U+A800 |  U+A82F |  (44) |
| [Common Indic Number Forms](https://wikipedia.org/wiki/Common_Indic_Number_Forms)                                           |  U+A830 |  U+A83F |  (10) |
| [Phags-pa](https://wikipedia.org/wiki/Phags-pa)                                                                             |  U+A840 |  U+A87F |  (56) |
| [Saurashtra](https://wikipedia.org/wiki/Saurashtra)                                                                         |  U+A880 |  U+A8DF |  (81) |
| [Devanagari Extended](https://wikipedia.org/wiki/Devanagari_Extended)                                                       |  U+A8E0 |  U+A8FF |  (30) |
| [Kayah Li](https://wikipedia.org/wiki/Kayah_Li)                                                                             |  U+A900 |  U+A92F |  (48) |
| [Rejang](https://wikipedia.org/wiki/Rejang)                                                                                 |  U+A930 |  U+A95F |  (37) |
| [Hangul Jamo Extended-A](https://wikipedia.org/wiki/Hangul_Jamo_Extended-A)                                                 |  U+A960 |  U+A97F |  (29) |
| [Javanese](https://wikipedia.org/wiki/Javanese)                                                                             |  U+A980 |  U+A9DF |  (91) |
| [Myanmar Extended-B](https://wikipedia.org/wiki/Myanmar_Extended-B)                                                         |  U+A9E0 |  U+A9FF |  (31) |
| [Cham](https://wikipedia.org/wiki/Cham)                                                                                     |  U+AA00 |  U+AA5F |  (83) |
| [Myanmar Extended-A](https://wikipedia.org/wiki/Myanmar_Extended-A)                                                         |  U+AA60 |  U+AA7F |  (32) |
| [Tai Viet](https://wikipedia.org/wiki/Tai_Viet)                                                                             |  U+AA80 |  U+AADF |  (72) |
| [Meetei Mayek Extensions](https://wikipedia.org/wiki/Meetei_Mayek_Extensions)                                               |  U+AAE0 | 你+AAFF |  (23) |
| [Ethiopic Extended-A](https://wikipedia.org/wiki/Ethiopic_Extended-A)                                                       |  U+AB00 |  U+AB2F |  (32) |
| [Latin Extended-E](https://wikipedia.org/wiki/Latin_Extended-E)                                                             |  U+AB30 |  U+AB6F |  (54) |
| [Cherokee Supplement](https://wikipedia.org/wiki/Cherokee_Supplement)                                                       |  U+AB70 |  U+ABBF|  (80) |
| [Meetei Mayek](https://wikipedia.org/wiki/Meetei_Mayek)                                                                     |  U+ABC0 |  U+ABFF |  (56) |
| [Hangul Syllables](https://wikipedia.org/wiki/Hangul_Syllables)                                                            | U+AC00   | U+D7AF   | (2)           |
| [Hangul Jamo Extended-B](https://wikipedia.org/wiki/Hangul_Jamo_Extended-B)                                                 |  U+D7B0 |  U+D7FF |  (72) |
| [High Surrogates](https://wikipedia.org/wiki/High_Surrogates)                                                               |  U+D800 |  U+DB7F |  (2) |
| [High Private Use Surrogates](https://wikipedia.org/wiki/High_Private_Use_Surrogates)                                       |  U+DB80 |  U+DBFF |  (2) |
| [Low Surrogates](https://wikipedia.org/wiki/Low_Surrogates)                                                                 |  U+DC00 |  U+DFFF |  (2) |
| [Private Use Area](https://wikipedia.org/wiki/Private_Use_Area)                                                             |  U+E000 |  U+F8FF |  (2) |
| [CJK Compatibility Ideographs](https://wikipedia.org/wiki/CJK_Compatibility_Ideographs)                                     |  U+F900 | 优+发|  （472）|
| [Alphabetic Presentation Forms](https://wikipedia.org/wiki/Alphabetic_Presentation_Forms)                                   |  U+FB00 |  U+FB4F |  (58) |
| [Arabic Presentation Forms-A](https://wikipedia.org/wiki/Arabic_Presentation_Forms-A)                                       |  U+FB50 |  U+FDFF |  （643）|
| [Variation Selectors](https://wikipedia.org/wiki/Variation_Selectors)                                                       |  U+FE00 |  U+FE0F |  (16) |
| [Vertical Forms](https://wikipedia.org/wiki/Vertical_Forms)                                                                 |  U+FE10 |  U+FE1F |  (10) |
| [Combining Half Marks](https://wikipedia.org/wiki/Combining_Half_Marks)                                                     |  U+FE20 |  U+FE2F |  (16) |
| [CJK Compatibility Forms](https://wikipedia.org/wiki/CJK_Compatibility_Forms)                                               |  U+FE30 |  U+FE4F |  (32) |
| [Small Form Variants](https://wikipedia.org/wiki/Small_Form_Variants)                                                       |  U+FE50 |  U+FE6F |  (26) |
| [Arabic Presentation Forms-B](https://wikipedia.org/wiki/Arabic_Presentation_Forms-B)                                       |  U+FE70 | 你+FEFF |  (141) |
| [Halfwidth and Fullwidth Forms](https://wikipedia.org/wiki/Halfwidth_and_Fullwidth_Forms)                                   |  U+FF00 | 你+FFEF |  (225) |
| [Specials](https://wikipedia.org/wiki/Specials)                                                                             |  U+FFF0 | 你+FFFF |  (7) |
| [Linear B Syllabary](https://wikipedia.org/wiki/Linear_B_Syllabary)                                                         |  U+10000 |  U+1007F |  (88) |
| [Linear B Ideograms](https://wikipedia.org/wiki/Linear_B_Ideograms)                                                         |  U+10080 |  U+100FF |  (123) |
| [Aegean Numbers](https://wikipedia.org/wiki/Aegean_Numbers)                                                                 |  U+10100 |  U+1013F |  (57) |
| [Ancient Greek Numbers](https://wikipedia.org/wiki/Ancient_Greek_Numbers)                                                  | U+10140  | U+1018F  | (77)          |
| [Ancient Symbols](https://wikipedia.org/wiki/Ancient_Symbols)                                                               |  U+10190 |  U+101CF |  (13) |
| [Phaistos Disc](https://wikipedia.org/wiki/Phaistos_Disc)                                                                   |  U+101D0 |  U+101FF |  (46) |
| [Lycian](https://wikipedia.org/wiki/Lycian)                                                                                 |  U+10280 |  U+1029F |  (29) |
| [Carian](https://wikipedia.org/wiki/Carian)                                                                                 |  U+102A0 |  U+102DF |  (49) |
| [Coptic Epact Numbers](https://wikipedia.org/wiki/Coptic_Epact_Numbers)                                                     |  U+102E0 |  U+102FF |  (28) |
| [Old Italic](https://wikipedia.org/wiki/Old_Italic)                                                                         |  U+10300 |  U+1032F |  (36) |
| [Gothic](https://wikipedia.org/wiki/Gothic)                                                                                 |  U+10330 |  U+1034F |  (27) |
| [Old Permic](https://wikipedia.org/wiki/Old_Permic)                                                                         |  U+10350 |  U+1037F |  (43) |
| [Ugaritic](https://wikipedia.org/wiki/Ugaritic)                                                                             |  U+10380 |  U+1039F |  (31) |
| [Old Persian](https://wikipedia.org/wiki/Old_Persian)                                                                       |  U+103A0 |  U+103DF |  (50) |
| [Deseret](https://wikipedia.org/wiki/Deseret)                                                                               |  U+10400 |  U+1044F |  (80) |
| [Shavian](https://wikipedia.org/wiki/Shavian)                                                                               |  U+10450 |  U+1047F |  (48) |
| [Osmanya](https://wikipedia.org/wiki/Osmanya)                                                                               |  U+10480 |  U+104AF |  (40) |
| [Elbasan](https://wikipedia.org/wiki/Elbasan)                                                                               |  U+10500 |  U+1052F |  (40) |
| [Caucasian Albanian](https://wikipedia.org/wiki/Caucasian_Albanian)                                                         |  U+10530 |  U+1056F |  (53) |
| [Linear A](https://wikipedia.org/wiki/Linear_A)                                                                             |  U+10600 |  U+1077F |  (341) |
| [Cypriot Syllabary](https://wikipedia.org/wiki/Cypriot_Syllabary)                                                           |  U+10800 |  U+1083F |  (55) |
| [Imperial Aramaic](https://wikipedia.org/wiki/Imperial_Aramaic)                                                             |  U+10840 |  U+1085F |  (31) |
| [Palmyrene](https://wikipedia.org/wiki/Palmyrene)                                                                           |  U+10860 |  U+1087F |  (32) |
| [Nabataean](https://wikipedia.org/wiki/Nabataean)                                                                           |  U+10880 |  U+108AF |  (40) |
| [Hatran](https://wikipedia.org/wiki/Hatran)                                                                                 |  U+108E0 |  U+108FF |  (26) |
| [Phoenician](https://wikipedia.org/wiki/Phoenician)                                                                         |  U+10900 |  U+1091F |  (29) |
| [Lydian](https://wikipedia.org/wiki/Lydian)                                                                                 |  U+10920 |  U+1093F |  (27) |
| [Meroitic Hieroglyphs](https://wikipedia.org/wiki/Meroitic_Hieroglyphs)                                                     |  U+10980 |  U+1099F |  (32) |
| [Meroitic Cursive](https://wikipedia.org/wiki/Meroitic_Cursive)                                                             |  U+109A0 |  U+109FF |  (90) |
| [Kharoshthi](https://wikipedia.org/wiki/Kharoshthi)                                                                         |  U+10A00 |  U+10A5F |  (65) |
| [Old South Arabian](https://wikipedia.org/wiki/Old_South_Arabian)                                                           |  U+10A60 |  U+10A7F |  (32) |
| [Old North Arabian](https://wikipedia.org/wiki/Old_North_Arabian)                                                           |  U+10A80 |  U+10A9F |  (32) |
| [Manichaean](https://wikipedia.org/wiki/Manichaean)                                                                         |  U+10AC0 |  U+10AFF |  (51) |
| [Avestan](https://wikipedia.org/wiki/Avestan)                                                                               |  U+10B00 |  U+10B3F |  (61) |
| [Inscriptional Parthian](https://wikipedia.org/wiki/Inscriptional_Parthian)                                                 |  U+10B40 |  U+10B5F |  (30) |
| [Inscriptional Pahlavi](https://wikipedia.org/wiki/Inscriptional_Pahlavi)                                                   |  U+10B60 |  U+10B7F |  (27) |
| [Psalter Pahlavi](https://wikipedia.org/wiki/Psalter_Pahlavi)                                                               |  U+10B80 |  U+10BAF |  (29) |
| [Old Turkic](https://wikipedia.org/wiki/Old_Turkic)                                                                         |  U+10C00 |  U+10C4F |  (73) |
| [Old Hungarian](https://wikipedia.org/wiki/Old_Hungarian)                                                                   |  U+10C80 |  U+10CFF |  (108) |
| [Rumi Numeral Symbols](https://wikipedia.org/wiki/Rumi_Numeral_Symbols)                                                     |  U+10E60 |  U+10E7F |  (31) |
| [Brahmi](https://wikipedia.org/wiki/Brahmi)                                                                                 |  U+11000 |  U+1107F |  (109) |
| [Kaithi](https://wikipedia.org/wiki/Kaithi)                                                                                 |  U+11080 |  U+110CF |  (66) |
| [Sora Sompeng](https://wikipedia.org/wiki/Sora_Sompeng)                                                                     |  U+110D0 |  U+110FF |  (35) |
| [Chakma](https://wikipedia.org/wiki/Chakma)                                                                                 |  U+11100 |  U+1114F |  (67) |
| [Mahajani](https://wikipedia.org/wiki/Mahajani)                                                                             |  U+11150 |  U+1117F |  (39) |
| [Sharada](https://wikipedia.org/wiki/Sharada)                                                                               |  U+11180 |  U+111DF |  (94) |
| [Sinhala Archaic Numbers](https://wikipedia.org/wiki/Sinhala_Archaic_Numbers)                                               |  U+111E0 |  U+111FF |  (20) |
| [Khojki](https://wikipedia.org/wiki/Khojki)                                                                                 |  U+11200 |  U+1124F |  (61) |
| [Multani](https://wikipedia.org/wiki/Multani)                                                                               |  U+11280 |  U+112AF |  (38) |
| [Khudawadi](https://wikipedia.org/wiki/Khudawadi)                                                                           |  U+112B0 |  U+112FF |  (69) |
| [Grantha](https://wikipedia.org/wiki/Grantha)                                                                               |  U+11300 |  U+1137F |  (85) |
| [Tirhuta](https://wikipedia.org/wiki/Tirhuta)                                                                               |  U+11480 |  U+114DF |  (82) |
| [Siddham](https://wikipedia.org/wiki/Siddham)                                                                               |  U+11580 |  U+115FF |  (92) |
| [Modi](https://wikipedia.org/wiki/Modi)                                                                                     |  U+11600 |  U+1165F |  (79) |
| [Takri](https://wikipedia.org/wiki/Takri)                                                                                   |  U+11680 |  U+116CF |  (66) |
| [Ahom](https://wikipedia.org/wiki/Ahom)                                                                                     |  U+11700 |  U+1173F |  (57) |
| [Warang Citi](https://wikipedia.org/wiki/Warang_Citi)                                                                       |  U+118A0 |  U+118FF |  (84) |
| [Pau Cin Hau](https://wikipedia.org/wiki/Pau_Cin_Hau)                                                                       |  U+11AC0 |  U+11AFF |  (57) |
| [Cuneiform](https://wikipedia.org/wiki/Cuneiform)                                                                           |  U+12000 |  U+123FF |  （922）|
| [Cuneiform Numbers and Punctuation](https://wikipedia.org/wiki/Cuneiform_Numbers_and_Punctuation)                           |  U+12400 |  U+1247F |  (116) |
| [Early Dynastic Cuneiform](https://wikipedia.org/wiki/Early_Dynastic_Cuneiform)                                             |  U+12480 |  U+1254F |  (196) |
| [Egyptian Hieroglyphs](https://wikipedia.org/wiki/Egyptian_Hieroglyphs)                                                     |  U+13000 |  U+1342F |  （1071）|
| [Anatolian Hieroglyphs](https://wikipedia.org/wiki/Anatolian_Hieroglyphs)                                                   |  U+14400 |  U+1467F |  （583）|
| [Bamum Supplement](https://wikipedia.org/wiki/Bamum_Supplement)                                                             |  U+16800 |  U+16A3F |  （569）|
| [Mro](https://wikipedia.org/wiki/Mro)                                                                                       |  U+16A40 |  U+16A6F |  (43) |
| [Bassa Vah](https://wikipedia.org/wiki/Bassa_Vah)                                                                           |  U+16AD0 |  U+16AFF |  (36) |
| [Pahawh Hmong](https://wikipedia.org/wiki/Pahawh_Hmong)                                                                     |  U+16B00 |  U+16B8F |  (127) |
| [Miao](https://wikipedia.org/wiki/Miao)                                                                                     |  U+16F00 |  U+16F9F |  (133) |
| [Kana Supplement](https://wikipedia.org/wiki/Kana_Supplement)                                                               |  U+1B000 |  U+1B0FF |  (2) |
| [Duployan](https://wikipedia.org/wiki/Duployan)                                                                             |  U+1BC00 |  U+1BC9F |  (143) |
| [Shorthand Format Controls](https://wikipedia.org/wiki/Shorthand_Format_Controls)                                           |  U+1BCA0 |  U+1BCAF |  (4) |
| [Byzantine Musical Symbols](https://wikipedia.org/wiki/Byzantine_Musical_Symbols)                                           |  U+1D000 |  U+1D0FF |  (246) |
| [Musical Symbols](https://wikipedia.org/wiki/Musical_Symbols)                                                               |  U+1D100 |  U+1D1FF |  (231) |
| [Ancient Greek Musical Notation](https://wikipedia.org/wiki/Ancient_Greek_Musical_Notation)                                 |  U+1D200 |  U+1D24F |  (70) |
| [Tai Xuan Jing Symbols](https://wikipedia.org/wiki/Tai_Xuan_Jing_Symbols)                                                   |  U+1D300 |  U+1D35F |  (87) |
| [Counting Rod Numerals](https://wikipedia.org/wiki/Counting_Rod_Numerals)                                                   |  U+1D360 |  U+1D37F |  (18) |
| [Mathematical Alphanumeric Symbols](https://wikipedia.org/wiki/Mathematical_Alphanumeric_Symbols)                           |  U+1D400 |  U+1D7FF |  (996) |
| [Sutton SignWriting](https://wikipedia.org/wiki/Sutton_SignWriting)                                                         |  U+1D800 |  U+1DAAF |  （672）|
| [Mende Kikakui](https://wikipedia.org/wiki/Mende_Kikakui)                                                                   |  U+1E800 |  U+1E8DF |  (213) |
| [Arabic Mathematical Alphabetic Symbols](https://wikipedia.org/wiki/Arabic_Mathematical_Alphabetic_Symbols)                 |  U+1EE00 |  U+1EEFF |  (143) |
| [Mahjong Tiles](https://wikipedia.org/wiki/Mahjong_Tiles)                                                                   |  U+1F000 |  U+1F02F |  (44) |
| [Domino Tiles](https://wikipedia.org/wiki/Domino_Tiles)                                                                     |  U+1F030 |  U+1F09F |  (100) |
| [Playing Cards](https://wikipedia.org/wiki/Playing_Cards)                                                                   |  U+1F0A0 |  U+1F0FF |  (82) |
| [Enclosed Alphanumeric Supplement](https://wikipedia.org/wiki/Enclosed_Alphanumeric_Supplement)                             |  U+1F100 |  U+1F1FF |  (173) |
| [Enclosed Ideographic Supplement](https://wikipedia.org/wiki/Enclosed_Ideographic_Supplement)                               |  U+1F200 |  U+1F2FF |  (57) |
| [Miscellaneous Symbols and Pictographs](https://wikipedia.org/wiki/Miscellaneous_Symbols_and_Pictographs)                   |  U+1F300 |  U+1F5FF |  （766）|
| [Emoticons](https://wikipedia.org/wiki/Emoticons)                                                                           |  U+1F600 |  U+1F64F |  (80) |
| [Ornamental Dingbats](https://wikipedia.org/wiki/Ornamental_Dingbats)                                                       |  U+1F650 |  U+1F67F |  (48) |
| [Transport and Map Symbols](https://wikipedia.org/wiki/Transport_and_Map_Symbols)                                           |  U+1F680 |  U+1F6FF |  (98) |
| [Alchemical Symbols](https://wikipedia.org/wiki/Alchemical_Symbols)                                                         |  U+1F700 |  U+1F77F |  (116) |
| [Geometric Shapes Extended](https://wikipedia.org/wiki/Geometric_Shapes_Extended)                                           |  U+1F780 |  U+1F7FF |  (85) |
| [Supplemental Arrows-C](https://wikipedia.org/wiki/Supplemental_Arrows-C)                                                   |  U+1F800 |  U+1F8FF |  (148) |
| [Supplemental Symbols and Pictographs](https://wikipedia.org/wiki/Supplemental_Symbols_and_Pictographs)                     |  U+1F900 |  U+1F9FF |  (15) |
| [CJK Unified Ideographs Extension B](https://wikipedia.org/wiki/CJK_Unified_Ideographs_Extension_B)                         |  U+20000 |  U+2A6DF |  (42676) |
| [CJK Unified Ideographs Extension C](https://wikipedia.org/wiki/CJK_Unified_Ideographs_Extension_C)                         |  U+2A700 |  U+2B73F |  (60) |
| [CJK Unified Ideographs Extension D](https://wikipedia.org/wiki/CJK_Unified_Ideographs_Extension_D)                         |  U+2B740 |  U+2B81F |  (27) |
| [CJK Unified Ideographs Extension E](https://wikipedia.org/wiki/CJK_Unified_Ideographs_Extension_E)                         |  U+2B820 |  U+2CEAF |  (2) |
| [CJK Compatibility Ideographs Supplement](https://wikipedia.org/wiki/CJK_Compatibility_Ideographs_Supplement)               |  U+2F800 |  U+2FA1F |  （542）|
| [Tags](https://wikipedia.org/wiki/Tags)                                                                                     |  U+E0000 |  U+E007F |  (97) |
| [Variation Selectors Supplement](https://wikipedia.org/wiki/Variation_Selectors_Supplement)                                 |  U+E0100 |  U+E01EF |  （240）|
| [Supplementary Private Use Area-A](https://wikipedia.org/wiki/Supplementary_Private_Use_Area-A)                             |  U+F0000 |  U + FFFFF |  (4) |
| [Supplementary Private Use Area-B](https://wikipedia.org/wiki/Supplementary_Private_Use_Area-B)                             |  U+100000 |  U+10FFFF |  (4) |



## [Principles of the Unicode Standard](http://www.unicode.org/standard/principles.html)


Unicode 标准规定了以下基本原则：

* **Universal repertoire** 	 - Every writing system ever used shall be respected and represented in the standard
* **逻辑顺序** - 在双向文本中，字符按逻辑顺序存储，而不是表示形式
* **效率** - 文档必须高效且完整.
 * **统一** - 如果不同的文化或语言使用相同的字符，则只能包含一次. 这一点是
 * **Characters, not glyphs** - 只对字符而不是字形进行编码. 简而言之，字形是实际的图形
 * **动态组合** - 新字符可以由其他已经标准化的字符组成. 例如，字符“Ä”可以由“A”和分音符号（“¨”）组成.
* **语义** - 包含的字符必须明确定义并与其他字符区分开来.
 * **稳定性** - 一旦定义的字符将永远不会被删除或重新分配它们的代码点. 在错误的情况下，代码点应被弃用.
* **纯文本** - 标准中的字符是文本，绝不是标记或元字符.
* **可转换性**——所有其他使用的编码都应以 Unicode 编码表示.

注：原理说明来自 [codepoints.net](https://codepoints.net/about#unicode)



## Unicode Versions

* [Version 9.0.0](http://www.unicode.org/versions/Unicode9.0.0/) （最新版本，2016 年 8 月 - 恰好添加了 7,500 个字符）
* [Version 8.0.0](http://www.unicode.org/versions/Unicode8.0.0/)
* [Version 7.0.0](http://www.unicode.org/versions/Unicode7.0.0/)
* [Version 6.3.0](http://www.unicode.org/versions/Unicode6.3.0/)
* [Version 6.2.0](http://www.unicode.org/versions/Unicode6.2.0/)
* [Version 6.1.0](http://www.unicode.org/versions/Unicode6.1.0/)
* [Version 6.0.0](http://www.unicode.org/versions/Unicode6.0.0/)
* [Version 5.2.0](http://www.unicode.org/versions/Unicode5.2.0/)
* [Version 5.1.0](http://www.unicode.org/versions/Unicode5.1.0/)
* 版本 5.0.0（不可用）
* [Version 4.0.1](http://www.unicode.org/versions/Unicode4.0.1/)
* [Version 4.0.0](http://www.unicode.org/versions/corrigendum5.html)




<br><br>


## Contributing

请参阅 *Awesome Unicode* [contribution guide](https://github.com/jagracey/Awesome-Unicode/blob/master/CONTRIBUTING.md) 有关如何贡献的详细信息.


## Code of Conduct

见 [Code of Conduct](https://github.com/jagracey/Awesome-Unicode/blob/master/CODE-OF-CONDUCT.md) 了解详情. 基本上可以归结为：
&gt;为了营造一个开放和热情的环境，我们作为
贡献者和维护者承诺参与我们的项目，并且
我们的社区为每个人提供无骚扰的体验，无论年龄、身体如何
体型、残疾、种族、性别认同和表达、经验水平、
国籍、外貌、种族、宗教或性认同和性取向.


## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，[
contributors](https://github.com/jagracey/Awesome-Unicode/graphs/contributors)
已放弃该作品的所有版权和相关或邻接权. 见
[license file](https://github.com/jagracey/Awesome-Unicode/blob/master/LICENSE) 了解详情.
