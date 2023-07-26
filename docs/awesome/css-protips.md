<div class="github-widget" data-repo="AllThingsSmitty/css-protips"></div>
<p align="center">
  <img src="https://raw.githubusercontent.com/AllThingsSmitty/css-protips/master/./assets/img/bulb.svg?sanitize=true" width="200" alt="light bulb icon">
</p>

## CSS Protips [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

一系列技巧可帮助您提高 CSS 技能.

&gt; 如需其他精彩列表，请查看 [@sindresorhus](https://github.com/sindresorhus/)的精选清单 [awesome lists](https://github.com/sindresorhus/awesome/).



* [Contribution Guidelines](https://github.com/AllThingsSmitty/css-protips/blob/master/CONTRIBUTING.md)


## Protips



### Use a CSS Reset

 CSS 重置有助于在不同浏览器之间强制执行样式一致性，并为样式元素提供干净的状态. 您可以使用 CSS 重置库，例如 [Normalize](http://necolas.github.io/normalize.css/)，_et al._，或者您可以使用更简化的重置方法：

```css
*,
*::before,
*：：后 {
  框大小：边框框；
  保证金：0；
  填充：0；
}
```

现在，元素将被去除边距和填充，并且“box-sizing”可让您使用 CSS 盒模型管理布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/kkrkLL)

**注意：** 如果您遵循 [Inherit `box-sizing`](#inherit-box-sizing) 下面的提示您可能会选择在 CSS 重置中不包含“box-sizing”属性.

<sup>[back to table of contents](#table-of-contents)</sup>


### Inherit `box-sizing`

让 `box-sizing` 继承自 `html`：

```css
html{
  框大小：边框框；
}

*,
*::before,
*：：后 {
  盒子大小：继承；
}
```

这使得在插件或利用其他行为的其他组件中更改“盒子大小”变得更容易.

#### [Demo](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `unset` Instead of Resetting All Properties

重置元素的属性时，无需重置每个单独的属性：

```css
按钮 {
  背景：无；
  边框：无；
  颜色：继承；
  字体：继承；
  概要：无；
  填充：0；
}
```

您可以使用“all”简写来指定元素的所有属性. 将值设置为“unset”会将元素的属性更改为其初始值：

```css
按钮 {
  全部：未设置；
}
```

**注意：** IE11 不支持 `all` 和 `unset` 简写.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:not()` to Apply/Unapply Borders on Navigation

而不是把边界...

```css
/* 添加边框 */
.name in {
  border-right: 1px solid #666;
}
```

...然后把它从最后一个元素上取下来...

```css
/* 去除边框 */
.nav li:最后一个子项 {
  右边界：无；
}
```

...使用 `:not()` 伪类仅应用于您想要的元素：

```css
.nav li:not(:最后一个孩子) {
  border-right: 1px solid #666;
}
```

在这里，CSS 选择器被解读为人类对它的描述.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/LkymvO)

<sup>[back to table of contents](#table-of-contents)</sup>


### Check If Font Is Installed Locally

您可以在远程获取字体之前检查本地是否安装了字体，这也是一个很好的性能提示.

```css
@font-face {
  字体系列：“Dank Mono”；
  源代码：
    /* 全名 */
    本地（“丹克单声道”），
    /* 后记名称 */
    本地（“丹克单声道”），
     /* 否则，下载它！  */
    url(&quot;//...a.server/fonts/DankMono.woff&quot;);
}

代码 {
  字体系列：“Dank Mono”，system-ui-monospace；
}
```

感谢 Adam Argyle 分享此专业提示并 [demo](https://codepen.io/argyleink/pen/VwYJpgR).

<sup>[back to table of contents](#table-of-contents)</sup>


### Add `line-height` to `body`

您不需要为每个`添加`line-height`<p>  `,`<h*>  `，_et al_. 分别地. 相反，将其添加到“body”中：

```css
身体 {
  行高：1.5；
}
```

这样文本元素就可以轻松地从“body”继承.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/VjbdYd)

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `:focus` for Form Elements

有视力的键盘用户依靠焦点来确定键盘事件在页面中的位置. 使表单元素的焦点比浏览器的默认实现更加突出和一致：

```css
a:focus,
button:focus,
input:focus,
select:focus,
文本区域：焦点{
  盒子阴影：无；
  outline: #000 dotted 2px;
  轮廓偏移：0.05em；
}
```

#### [Demo](https://codepen.io/AllThingsSmitty/pen/ePzoOP/)

<sup>[back to table of contents](#table-of-contents)</sup>


### Vertically-Center Anything

不，这不是黑魔法，你确实可以将元素垂直居中. 你可以用 Flexbox 来做到这一点......

```css
html,
身体 {
  高度：100%；
  保证金：0；
}

身体 {
  -webkit-align-items：居中；
  -ms-flex-align：居中；
  对齐项目：居中；
  显示：-webkit-flex；
  显示：柔性；
}
```

...还有 CSS 网格：

```css
身体 {
  显示：网格；
  高度：100vh；
  保证金：0；
  地点项目：中心中心；
}
```


想要集中其他东西吗？ 垂直、水平……任何时间、任何地点？  CSS-Tricks 有 [a nice write-up](https://css-tricks.com/centering-css-complete-guide/) 做这一切.

**注意：** 注意一些 [buggy behavior](https://github.com/philipwalton/flexbugs#3-min-height-on-a-flex-container-wont-apply-to-its-flex-items) 在 IE11 中使用 Flexbox.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/GqmGqZ)

<sup>[back to table of contents](#table-of-contents)</sup>


### Comma-Separated Lists

使列表项看起来像一个真实的、以逗号分隔的列表：

```css
ul &gt; li:not(:last-child)::after {
  内容： ”，”;
}
```

使用 `:not()` 伪类，最后一项不会添加逗号.


<sup>[back to table of contents](#table-of-contents)</sup>


### Select Items Using Negative `nth-child`

在 CSS 中使用负数“nth-child”来选择项目 1 到 n.

```css
那 {
  显示：无；
}

/* 选择项目 1 到 3 并显示它们 */
li:第n个孩子(-n+3) {
  显示：块；
}
```

或者，既然你已经了解了一些 [using `:not()`](#use-not-to-applyunapply-borders-on-navigation)， 尝试：

```css
/* 选择除前 3 项之外的所有项并显示它们 */
li:not(:第n个孩子(-n+3)) {
  显示：块；
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/WxjKZp)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use SVG for Icons

没有理由不使用 SVG 来制作图标：

```css
.标识 {
  背景： url(&quot;logo.svg&quot;);
}
```

SVG 可以很好地适应所有分辨率类型，并且在所有浏览器中都受支持 [back to IE9](http://caniuse.com/#search=svg) . 放弃 .png、.jpg 或 .gif-jif-whatev 文件.

**Note:** If you have SVG icon-only buttons for sighted users and the SVG fails to load, this will help maintain accessibility:

```css
.no-svg .icon-only::after {
  内容：attr(aria-label);
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use the "Lobotomized Owl" Selector

它可能有一个奇怪的名字，但使用通用选择器（“*”）和相邻的同级选择器（“+”）可以提供强大的 CSS 功能：

```css
* + * {
  顶部边距：1.5em；
}
```

在此示例中，文档流中其他元素后面的所有元素都将接收“margin-top: 1.5em”.

有关“脑白质切除猫头鹰”选择器的更多信息，请阅读 [Heydon Pickering's post](http://alistapart.com/article/axiomatic-css-and-lobotomized-owls) 在*A List Apart*上.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/grRvWq)

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `max-height` for Pure CSS Sliders

使用隐藏溢出的“max-height”实现纯 CSS 滑块：

```css
.滑块{
  最大高度：200px；
  溢出-y：隐藏；
  宽度：300px；
}

.slider:悬停{
  最大高度：600px；
  溢出-y：滚动；
}
```

元素在悬停时扩展到“最大高度”值，并且滑块由于溢出而显示.

<sup>[back to table of contents](#table-of-contents)</sup>


### Equal-Width Table Cells

使用表格可能会很痛苦. 尝试使用“table-layout:fixed”来保持单元格宽度相等：

```css
.日历 {
  表格布局：固定；
}
```

无痛的表格布局.

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALALm)

<sup>[back to table of contents](#table-of-contents)</sup>


### Get Rid of Margin Hacks With Flexbox

使用列装订线时，您可以通过使用 Flexbox 的“space- Between”属性来摆脱“nth-”、“first-”和“last-child”黑客行为：

```css
.列表 {
  显示：柔性；
  justify-content：空间之间；
}

.列表.人{
  弹性基础：23%；
}
```

现在，列装订线总是显示均匀间隔.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Attribute Selectors with Empty Links

当 ` <a>` 元素没有文本值但 `href` 属性有链接时显示链接：</a>

```css
a[href^=&quot;http&quot;]:empty::before {
  内容：attr(href)；
}
```

那是相当方便的.


#### [Demo](http://codepen.io/AllThingsSmitty/pen/zBzXRx)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style "Default" Links

添加“默认”链接的样式：

```css
a[href]:not([class]) {
  color: #008000;
  文本装饰：下划线；
}
```

现在，通过 CMS 插入的链接（通常没有“class”属性）将具有区别，而不会普遍影响级联.

<sup>[back to table of contents](#table-of-contents)</sup>


### Intrinsic Ratio Boxes

要创建具有固有比例的框，您所需要做的就是将顶部或底部填充应用于 div：

```css
.容器 {
  高度：0；
  底部填充：20%；
  位置：相对；
}

.容器div {
  border: 2px dashed #ddd;
  高度：100%；
  左：0；
  位置：绝对；
  顶部：0；
  宽度：100%；
}
```

使用 20% 进行填充会使框的高度等于其宽度的 20%. 无论视口的宽度如何，子 div 都将保持其纵横比 (100% / 20% = 5:1).

#### [Demo](http://codepen.io/AllThingsSmitty/pen/jALZvE)

<sup>[back to table of contents](#table-of-contents)</sup>


### Style Broken Images

使用一点 CSS 让破碎的图像更加美观：

```css
图像{
  显示：块；
  字体系列：无衬线字体；
  字体粗细：300；
  高度：自动；
  行高：2；
  位置：相对；
  文本对齐：居中；
  宽度：100%；
}
```

现在添加伪元素规则来显示用户消息和损坏图像的 URL 引用：

```css
img::之前{
  content: &quot;很抱歉，下面的图片已损坏:(&quot;;
  显示：块；
  底部边距：10px；
}

图像::之后{
  内容：“（url：“attr（src）”）”；
  显示：块；
  字体大小：12px；
}
```

了解有关此模式样式的更多信息 [Ire Aderinokun](https://github.com/ireade/)'s [original post](http://bitsofco.de/styling-broken-images/).

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `rem` for Global Sizing; Use `em` for Local Sizing

在根部设置基本字体大小（`html { font-size: 100%; }`）后，将文本元素的字体大小设置为 `em`：

```css
h2 {
  字体大小：2em；
}

p {
  字体大小：1em；
}
```

然后将模块的字体大小设置为“rem”：

```css
文章 {
  字体大小：1.25rem；
}

放在一边.module {
  字体大小：.9rem；
}
```

现在，每个模块都变得分区化，更容易设计样式、更易于维护且更灵活.

<sup>[back to table of contents](#table-of-contents)</sup>


### Hide Autoplay Videos That Aren't Muted

对于自定义用户样式表来说，这是一个很棒的技巧. 避免页面加载时自动播放的视频声音给用户造成负担. 如果声音未静音，则不显示视频：

```css
视频[自动播放]:not([静音]) {
  显示：无；
}
```

我们再次利用 [`:not()`](#use-not-to-applyunapply-borders-on-navigation) 伪类.

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:root` for Flexible Type

响应式布局中的字体大小应该能够根据每个视口进行调整. 您可以使用`:root`根据视口高度和宽度计算字体大小：

```css
：根 {
  字体大小： calc(1vw + 1vh + .5vmin);
}
```

现在您可以根据 `:root` 计算的值使用 `root em` 单位：

```css
身体 {
  字体：1rem/1.6 无衬线；
}
```

#### [Demo](http://codepen.io/AllThingsSmitty/pen/XKgOkR)

<sup>[back to table of contents](#table-of-contents)</sup>


### Inherit `font` on Form Elements for a Better Mobile Experience

默认情况下，某些表单控件不继承印刷样式. 避免移动浏览器（iOS Safari 等）在“”时放大 HTML 表单元素<select>点击`下拉菜单，为了减少浏览器之间样式不一致的情况，请将`font`规则设置为`inherit`：

```css
input,
button,
select,
文本区域{
  字体：继承；
}
```

了解更多信息 [MDN's guide to styling web forms](https://developer.mozilla.org/en-US/docs/Learn/Forms/Styling_web_forms).

<sup>[back to table of contents](#table-of-contents)</sup>


### Use Pointer Events to Control Mouse Events

[Pointer events](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events) 允许您指定鼠标如何与其所触摸的元素交互. 要禁用按钮上的默认指针事件，例如：

```css
按钮：禁用{
  不透明度：.5；
  指针事件：无；
}
```

就是这么简单.

<sup>[back to table of contents](#table-of-contents)</sup>


### Set `display: none` on Line Breaks Used as Spacing

As [Harry Roberts pointed out](https://twitter.com/csswizardry/status/1170835532584235008)，这可以帮助防止 CMS 用户使用额外的换行符作为间距：

```css
br + br {
  显示：无；
}
```

<sup>[back to table of contents](#table-of-contents)</sup>


### Use `:empty` to Hide Empty HTML Elements

如果您有空的 HTML 元素，即内容尚未由 CMS 设置或动态注入（例如，`<p class="error-message"></p>  `) 并且它在布局上创建了不需要的空间，请使用 `:empty` 伪类隐藏布局上的元素. 

```css
：空的 {
  显示：无；
}
```

 **注意：** 请记住，带有空格的元素不被视为空，例如`<p class="error-message"></p>  `.

<sup>[back to table of contents](#table-of-contents)</sup>


## Support

Chrome、Firefox、Safari、Opera、Edge 和 IE11 的当前版本.

<sup>[back to table of contents](#table-of-contents)</sup>


## Translations

 **注意：** 我没有足够的时间来维护不断增长的翻译提示列表； 添加新的提示需要包含十几个翻译. 因此，翻译后的自述文件可能不包含主自述文件中列出的所有提示.

* [简体中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-CN)
* [正體中文](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/zh-TW)
* [Deutsch](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/de-DE)
* [Español](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/es-ES)
* [Français](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/fr-FR)
* [λληνικά](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/gr-GR)
* [ગુજરાતી](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/gu-IND)
* [Italiano](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/it-IT)
* [日本語](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ja-JP)
* [한국어](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ko-KR)
* [Polskie](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pl-PL)
* [Português do Brasil](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-BR)
* [Português do Europe](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/pt-PT)
* [Русский](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/ru-RU)
* [Tiếng Việt](https://github.com/AllThingsSmitty/css-protips/tree/master/translations/vn-VN)

<sup>[back to table of contents](#table-of-contents)</sup>
