<div class="github-widget" data-repo="sjfricke/awesome-webgl"></div>
## Awesome WebGL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://raw.githubusercontent.com/sjfricke/awesome-webgl/master/webgl_logo.png" align="right" width="175">](https://www.khronos.org/webgl/)

这是一个很棒的 WebGL 库、资源等的精选列表.

## What is WebGL

WebGL（Web 图形库）是一种 JavaScript API，用于在内部渲染交互式 3D 计算机图形和 2D 图形
任何不使用插件的兼容网络浏览器.  WebGL 已完全集成到所有 Web 标准中
浏览器允许 GPU 加速使用物理和图像处理以及作为网页画布一部分的效果.

WebGL 元素可以与其他 HTML 元素混合，并与页面或页面背景的其他部分合成.
WebGL 程序由用 JavaScript 编写的控制代码和在计算机图形上执行的着色器代码组成
处理单元 (GPU).


## WebGL

&gt; 所有与 WebGL 打交道的事情

### WebGL sub-categories

### Articles

&gt; WebGL 文章和/或博客文章（非教程）

* [Context Loss & Preloading](https://medium.com/@mattdesl/non-intrusive-webgl-cebd176c281d#.gyc6h9mr5) - 当您遇到可怕的上下文丢失时如何管理 WebGL.
* [WebGL Off the Main Thread](https://hacks.mozilla.org/2016/01/webgl-off-the-main-thread/) - 如何在 WebGL 中使用网络工作者.
* [Optimizing Scenes for Better WebGL Performance](https://www.soft8soft.com/docs/manual/en/introduction/Optimizing-WebGL-performance.html) - 经证明可以很好地创建基于 WebGL 的交互的优化技术.
* [First steps in WebGL](https://dev.to/aralroca/first-steps-in-webgl-385c) - 通过绘制三角形了解什么是 WebGL 及其工作原理. 

### Blog Series

&gt; WebGL 主题博客系列

* [Codeflow](http://codeflow.org/tags/webgl.html) - 许多关于不同技巧和技术的博客.
* [Real-Time Rendering](http://www.realtimerendering.com/blog/tag/webgl/) - 这是《实时渲染》一书的博客.
* [WebGL Best Practices](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/WebGL_best_practices) - Mozilla 的官方最佳实践集.
* [WebGL Insights](http://webglinsights.blogspot.com/) - 这是 _WebGL Insights_ 一书的博客.
* [WebGL Month](https://github.com/lesnitsky/webgl-month) – 一个月的每日 WebGL 教程.

### Books

&gt; 关于 WebGL 的热门书籍

* [Interactive Computer Graphics: A Top-Down Approach with WebGL](https://www.amazon.com/Interactive-Computer-Graphics-Top-Down-Approach/dp/0133574849) 由 **Edward Angel** 和 **Dave Shreiner** - 适用于计算机科学与工程专业的本科生、具有良好编程技能的其他学科的学生，以及对使用最新版本的计算机动画和图形感兴趣的专业人士WebGL.
* [Professional WebGL Programming](https://www.amazon.com/Professional-WebGL-Programming-Developing-Graphics/dp/1119968860) 作者 **Andreas Anyuru** - 关于使用 WebGL 开发硬件加速 3D 图形你需要知道的一切.
* [Programming 3D Applications with HTML5 and WebGL](https://www.amazon.com/Programming-Applications-HTML5-WebGL-Visualization/dp/1449362966) 作者 **Tony Parisi** - 使用 HTML5 和相关技术（如 CSS3 和 WebGL——新兴的 Web 图形标准）为 Web 创建高性能、视觉效果惊人的 3D 应用程序.
* [WebGL Beginner's guide](https://www.amazon.com/WebGL-Beginners-Guide-Diego-Cantor/dp/184969172X) 作者 **Diego Cantor** 和 **Brandon Jones** - 适用于想要通过 WebGL 投入 3D 网络开发的 JavaScript 开发人员.
* [WebGL Hotshot](https://www.amazon.com/WebGL-Hotshot-Mitch-Williams-ebook/dp/B00KLAJ65Y) 作者 **Mitch Williams** - 适用于希望扩展 3D 图形概念知识并拓宽现有技能的网页设计师.
* [WebGL Insights](https://github.com/WebGLInsights/WebGLInsights.github.io/releases/download/v1.0/WebGL.Insights.-.Patrick.Cozzi.pdf) 作者 **Patrick Cozzi** - 通过汇集经验丰富的 WebGL 引擎和应用程序开发人员、GPU 供应商、浏览器开发人员、研究人员和教育工作者的贡献，为中级和高级 WebGL 开发人员展示真实世界的技术.
  * [Book's Personal Site](http://www.webglinsights.com/)
* [WebGL Programming Guide: Interactive 3D Graphics Programming with WebGL](https://www.amazon.com/WebGL-Programming-Guide-Interactive-Graphics/dp/0321902920) 由 **Kouichi Matsuda** 和 **Rodger Lea** - WebGL 编程指南将帮助您快速开始交互式 WebGL 3D 编程，即使您之前没有 HTML5、JavaScript、3D 图形、数学或 OpenGL 的知识.

### Bug Reporting

&gt; 从长远来看，报告错误对每个人都有帮助

* [Chrome Bug Report](https://bugs.chromium.org/p/chromium/issues/list) - Chrome 相关错误
* [Khronos Github Issue Page](https://github.com/KhronosGroup/WebGL/issues) - 规范或一致性相关的错误
* [Mozilla BugZilla](https://bugzilla.mozilla.org) - Firefox 相关错误

### GLSL Editors

&gt; 在线 GLSL 编辑器
>
&gt; 注意： [WebGL must conform to The OpenGL ES Shading Language, Version 1.00](https://www.khronos.org/registry/webgl/specs/1.0.3/#4.3)
> 
> [Official Specs for GLSL Version 1.00](https://www.khronos.org/registry/OpenGL/specs/es/2.0/GLSL_ES_Specification_1.00.pdf)
>
> [Official Specs for Open ES Version 2.0.25](https://www.khronos.org/registry/OpenGL/specs/es/2.0/es_full_spec_2.0.pdf)

* [Fractal Lab](http://hirnsohle.de/test/fractalLab/) - 在线分形浏览器，让您探索 2D 和 2D 分形.
* [GLSL Sandbox](http://glslsandbox.com) - 片段着色器的在线实时编辑器.
* [GLSLbin](http://glslb.in) - 片段着色器沙箱支持 [glslify](https://github.com/glslify/glslify).
* [Shader Toy](https://www.shadertoy.com) - 最流行的片段着色器实时编辑器.
* [ShaderFrog](https://shaderfrog.com/) - WebGL 着色器编辑器和作曲家.
* [SHDR Editor](http://shdr.bkcore.com) - 实时 GLSL 着色器编辑器、查看器和验证器.
* [ShaderExpo](https://anuraghazra.github.io/ShaderExpo/) - 具有内联错误日志、自动完成、模型和纹理加载的无依赖性着色器编辑器. 

### References

&gt; WebGL 参考资料

* [Google Project ANGLE](https://github.com/google/angle) - Windows 平台上 Google Chrome 和 Mozilla Firefox 的默认 WebGL 后端.
* [Khronos Official Wiki](https://www.khronos.org/webgl/wiki/) - WebGL 的官方 wiki.
* [WebVR Community Group](https://www.w3.org/community/immersive-web/) - 目标是帮助将高性能虚拟现实带入开放网络的组织.
* [WebGL Errata](https://www.khronos.org/webgl/wiki/Errata_to_the_WebGL_Specification) - 图形驱动程序中的已知错误会影响一致性套件，从而影响代码的可移植性.
* [WebGL Extensions](https://www.khronos.org/registry/webgl/extensions/) - WebGL 的扩展列表
* [WebGL Reference Card](https://www.khronos.org/files/webgl/webgl-reference-card-1_0.pdf) - 用于打印的 WebGL 1.0 API 快速参考卡.
* [WebGL Source Code](https://github.com/KhronosGroup/WebGL) - 查看和贡献的源代码.
* [WebGL Spec Sheet](https://www.khronos.org/registry/webgl/specs/1.0/) - 有关 WebGL 的所有详细信息.


### Talks

&gt; WebGL 相关讲座

* [List of Presentations](https://www.khronos.org/webgl/wiki/Presentations) - 由 Khronos 提供的各种 WebGL 相关演示文稿的列表.
* [Next-Generation 3D Graphics on the Web](https://www.youtube.com/watch?v=K2JzIUIHIhc) - 来自 Ricardo Cabello (MrDoob) 的 Google I/O 19 演讲.

### Tools/Debugging

&gt; 用于开发和调试 WebGL 的工具

* [Khronos Dev Tools](https://github.com/KhronosGroup/WebGLDeveloperTools) - 有用的 WebGL 开发工具，旨在用作 ES6 模块.
* [Spector.js](https://spector.babylonjs.com/) - Agnostic JavaScript framework for exploring and troubleshooting your WebGL scenes.
* [WebGL Inspector](http://benvanik.github.io/WebGL-Inspector/) - 受 gDEBugger 和 PIX 启发的工具，旨在简化高级 WebGL 应用程序的开发.
* [WebGl Playground](http://jessevdk.github.io/webgl-play/)  - 编辑器允许您以方便的方式同时处理 JavaScript 代码和 GLSL 顶点/片段着色器（如果有的话）. 一切都按照您的意愿进行了组织、格式化和突出显示.
* [WebGL Report](http://webglreport.com/?v=1) - 查看浏览器支持 WebGL 的详细信息的方法.
* [WebGL Support Stats](http://webglstats.com/) - 交互式仪表板显示不同浏览器和设备对 WebGL 功能的支持.
* [WebGL Texture Tester](http://toji.github.io/texture-tester/) - 尝试加载 WebGL 支持的每种纹理格式之一，旨在快速显示您的浏览器/设备支持的格式.
* [Web Tracing Framework](http://google.github.io/tracing-framework/index.html) - 用于跟踪和调查复杂 Web 应用程序的库、工具和可视化工具集.

#### Chrome Specific Tools/Debugger

* [GLSL Shader Editor Extension](https://github.com/spite/ShaderEditorExtension) - Chrome DevTools 扩展，可帮助您在浏览器中实时编辑着色器.
* [Spector.js Extension](https://chrome.google.com/webstore/detail/spectorjs/denbgaamihkadbghdceggmchnflmhpmk) - 轻松探索 WebGL 和 WebGL2 场景并排除故障.
* [Webgl Insight](https://github.com/3Dparallax/insight) - 提供多种功能的 Chrome 扩展 WebGL 调试工具包.

#### Firefox Specific Tools/Debugger

* [Canvas Debugger](https://hacks.mozilla.org/2014/03/introducing-the-canvas-debugger-in-firefox-developer-tools/) - 快速教程如何使用 Firefox 的开发者工具来调试 WebGL 着色器.
* [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools) - 所有 Firefox 调试器工具的官方列表.
* [Shader Editor](https://hacks.mozilla.org/2013/11/live-editing-webgl-shaders-with-firefox-developer-tools/) - 快速教程如何使用 Firefox 的开发者工具来调试 WebGL 着色器.

### Tutorials

&gt; 在线 WebGL 教程（非视频）

* [Directional Shadow Mapping](http://chinedufn.com/webgl-shadow-mapping-tutorial/) - 实时定向光影映射背后的概念.
* [Get Started Tutorial](https://www.khronos.org/webgl/wiki/Tutorial) - Khronos 的教程如何启动和运行 WebGL.
* [Getting Started with WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL) - Mozilla 基金会 WebGL 入门指南.
* [Learn WebGL](https://www.tutorialspoint.com/webgl/index.htm) - Tutorials Point 系列文章让您熟悉 WebGL 术语.
* [Learning WebGL](http://learningwebgl.com/blog/?page_id=1217) - 来自_WebGL Up and Running_作者的教程.
* [Multitexturing using a Blendmap](http://chinedufn.com/webgl-multitexture-blend-map-tutorial/) - 如何使用混合贴图对地形进行多重纹理处理.
* [Particle Effects via Billboards](http://chinedufn.com/webgl-particle-effect-billboard-tutorial/) - 通过应用称为广告牌的技术来创建粒子效果.
* [The Book of Shaders](https://thebookofshaders.com/) - 通过片段着色器的抽象和复杂世界的温和的分步指南.
* [WebGL Academy](http://www.webglacademy.com/)  - 简化的在线 IDE，具有自动缩进、HTML、Javascript、GLSL 和 Python 语法突出显示. 您可以运行您的代码并下载您的项目.
* [WebGL Fundamentals](https://webglfundamentals.org/) - 包含代码示例和现场演示的在线教程系列.
* [WebGL Workshop](http://webgl-workshop.com/) - 让您开始使用 WebGL 并运行的交互式研讨会.

### Videos

&gt; WebGL 相关视频

* [An Introduction to WebGL Programming](https://www.youtube.com/watch?v=tgVLb6fOVVc&feature=youtu.be) - SIGGRAPH 大学对 WebGL 的 3 小时概述.
* [WebGL Tutorials - YouTube](https://www.youtube.com/playlist?list=PLjcVFFANLS5zH_PeKC6I8p0Pt1hzph_rt) - 来自 YouTube 上 Indigo Code 的一系列讲座式视频教程.

## WebGL 2

&gt; 有关即将推出的 WebGL 2 规范的信息
>
&gt; 一般与 WebGL 有关的任何内容都可以在 [WebGL](#WebGL) 部分

### WebGL 2 sub-categories

### Articles

&gt; WebGL 2 文章和/或博客文章（非教程）

* [WebGL 2 What's New](https://webgl2fundamentals.org/webgl/lessons/webgl2-whats-new.html) - 查看 WebGL 2 中添加的新功能.
* [What's Coming in WebGL 2.0](https://blog.tojicode.com/2013/09/whats-coming-in-webgl-20.html) - 查看即将推出的 WebGL 2 功能.
* [WebGL 2 SIGGRAPH Asia 2015](https://docs.google.com/presentation/d/1Orx0GB0cQcYhHkYsaEcoo5js3c5-pv7ahPniIRIzzfg/edit#slide=id.p) - Zhenyao Mo 和 Google 的 Ken Russell 在 SIGGRAPH Asia 2015 期间的演讲.
* [WebGL 2 Lands in Firefox](https://hacks.mozilla.org/2017/01/webgl-2-lands-in-firefox/) - 从 Firefox 51 开始支持 WebGL 2 的信息.
* [WebGL 2 Basics](http://www.realtimerendering.com/blog/webgl-2-basics/) - 关于开始使用 WebGL 2 的博客文章.
* [WebGL 2 New Features](http://www.realtimerendering.com/blog/webgl-2-new-features/) - 关于 WebGl 2 的新功能和酷炫功能的博客文章.

### References

&gt; WebGL 2 参考资料

* [WebGL 2 Spec Sheet (Editor Draft)](https://www.khronos.org/registry/webgl/specs/latest/2.0/) - 有关 WebGL 2 的所有详细信息.
* [WebGL 2 Reference Card](https://www.khronos.org/files/webgl20-reference-guide.pdf) - 用于打印的 WebGL 2.0 API 快速参考卡.
* [WebGL 2 Compatible Chart](https://caniuse.com/#feat=webgl2) - 显示当前支持 WebGL 2 的浏览器的图表

### Tutorials
* [WebGL 2 Fundamentals](https://webgl2fundamentals.org/)- 包含代码示例和现场演示的在线教程系列.
* [WebGL 2 Samples](http://webglsamples.org/WebGL2Samples/) - 许多不同的 WebGL 2 工作的重要来源以及非常好的评论.
* [WebGL 2 Examples](https://github.com/tsherif/webgl2examples) - 在原始 WebGL 2 中实现的渲染算法.

### Videos

&gt; WebGL 相关视频

* [Fun with WebGL 2.0](https://www.youtube.com/playlist?list=PLMinhigDWz6emRKVkVIEAaePW7vtIkaIF) - WebGL 2 入门视频教程系列，仍在积极添加视频.
* [WebGL 2.0 is Here: What You Need To Know](https://www.youtube.com/watch?v=Xf65duJ_QFs) - 2017 年 4 月 Khronos 网络研讨会.
    * [Slides](https://www.khronos.org/assets/uploads/developers/library/2017-webgl-webinar/Khronos-Webinar-WebGL-20-is-here_What-you-need-to-know_Apr17.pdf)

## WebVR

&gt; 关于新的和即将到来的 WebVR 生态系统的不同部分的信息
>
&gt; 所有项目都与更多的开发人员相关，而较少涉及在哪里可以找到 WebVR 内容作为娱乐

### WebVR sub-categories


### Articles

&gt; WebVR 文章和/或博客文章（非教程）

### Blog Series

&gt; 维护了以 WebVR 为重点的主题的博客系列

* [Mozilla VR Blog](https://blog.mozvr.com/) - 来自 Firefox 制造商的专注于 WebVR 的博客.

### Platforms

&gt; WebVR 设计的平台来体验

* [JanusVR](https://janusvr.com/) - 网页作为通过门户互连的协作 3D 网络空间.

### References

&gt; WebVR 参考资料

* [Browser Support](https://webvr.rocks/) - 显示浏览器、耳机和操作系统的支持.
* [Mozilla VR](https://mixedreality.mozilla.org/) - Mozilla 的官方 WebVR 页面.
* [UX of VR](https://www.uxofvr.com/) - 有助于在 WebVR 中创建良好 UX 的精选资源列表.
* [WebXR Device API](https://immersive-web.github.io/webxr/) - WebXR 的 W3C 草案 API.
* [WebVR Spec](https://w3c.github.io/webvr/) - 官方 W3C WebVR 规范（遗留）.
  * [How to read WebVR Specs](https://dassur.ma/things/reading-specs/)

## Libraries

> [More detailed information about the different libraries can be found in the Libraries directory.](https://github.com/sjfricke/awesome-webgl/tree/master/Libraries)

### 2D
* [p2.js](https://github.com/schteppe/p2.js) - 用 Ja​​vaScript 编写的 2D 刚体物理引擎.
* [Phaser](https://phaser.io/) - 用于 Canvas 和 WebGL 的开源 HTML5 2D 游戏框架，支持移动网络浏览器.
* [PixiJS](http://www.pixijs.com/) - 基于 WebGL 的强大 2D Javascript 渲染器.
* [Planck.js](https://github.com/shakiba/planck.js) - 用于跨平台 HTML5 游戏开发的 2D 物理引擎.
* [Stage.js](https://github.com/shakiba/stage.js) - 用于跨平台 HTML5 游戏开发的 2D 库.

### Compute (GPGPU)

#### Computer Vision
* [GammaCV](https://gammacv.com) - 用于浏览器的 WebGL 加速计算机视觉库.

#### Particles
* [Phenomenon](https://github.com/vaneenige/phenomenon) - 非常小的低级 WebGL 库，提供提供高性能体验的要素.

### Maps and Visualizations
* [Cesium](https://cesiumjs.org/) - Open-source library for world-class 3D globes and maps.
* [Deck.gl](http://deck.gl/) - 用于 React 的 WebGL 覆盖套件提供了一组高性能的数据可视化覆盖.
* [Luma.gl](https://luma.gl/) - 用于 GPU 驱动的数据可视化和计算的 WebGL2 驱动框架.
* [xeogl](http://xeogl.org/) - WebGL 上的数据驱动 3D 可视化引擎.

### Math
* [glMatrix](http://glmatrix.net/) - 用于高性能 WebGL 应用程序的 Javascript 矩阵和矢量库.
* [Sylvester](http://sylvester.jcoglan.com/) - Sylvester 是一个用于 JavaScript 的矢量、矩阵和几何库.
* [TWGL](http://twgljs.org/) - 唯一的目的是使 WebGL API 的使用不那么冗长.

### Rendering
* [GLBoost](https://github.com/emadurandal/GLBoost) - 3D 图形极客的渲染库.
* [GrimoireGL](https://grimoire.gl/) - Web 工程师和 CG 工程师之间的桥梁.
* [Hilo3d](https://github.com/hiloteam/Hilo3d) - 用于 3D 游戏的 WebGL 渲染引擎.

### Physics
* [Ammo.js](https://github.com/kripken/ammo.js/) - 使用 Emscripten 将 Bullet 物理引擎直接移植到 JavaScript.
* [Cannon.js](http://schteppe.github.io/cannon.js/) - 用于网络的轻量级和简单的 3D 物理引擎.

### WebGL 2
* [PicoGL.js](https://tsherif.github.io/picogl.js/) - 最小的 WebGL 2-only 渲染库.

### WebVR
* [A-Frame](https://aframe.io/) - 用于构建虚拟现实体验的 Web 框架.
  * [Awesome-AFrame](https://github.com/aframevr/awesome-aframe)
* [Hologram](https://hologram.cool/) - 桌面应用程序，让您无需先前的编码知识即可以交互方式创建和原型化 WebVR.
* [LÖVR](https://lovr.org/) - 使用 Lua 创建 VR 的简单框架.
* [React 360](https://facebook.github.io/react-360/) - 使用 React 构建 VR 网站和交互式 360 度体验.
* [Primrose](https://github.com/capnmidnight/Primrose/) - 在您的浏览器中快速制作 VR 应用程序原型.

### Others
* [Babylon.js](https://www.babylonjs.com/) - 用于使用 HTML5、WebGL 和 Web Audio 构建 3D 游戏的完整 JavaScript 框架.
* [Blend4Web](https://www.blend4web.com/en/) - 用于在 Internet 上进行交互式 3D 可视化的工具.
* [ClayGL](http://claygl.xyz/) - 用于构建可扩展的 Web3D 应用程序的 WebGL 图形库.
* [CopperLicht](https://www.ambiera.com/copperlicht/index.html) - 用于创建游戏和 3D 应用程序的 JavaScript 库和 WebGL 3D 引擎.
* [GLGE](http://www.glge.org/) - 旨在简化 WebGL 使用的 Javascript 库.
* [Lightgl.js](https://github.com/evanw/lightgl.js) - 轻量级和明确的库来帮助原型.
* [OSG.js](https://cedricpinson.github.io/osgjs-website/) - 基于 OpenSceneGraph 概念的 WebGL 框架与 WebGL 交互.
* [Pex-gl](http://vorg.github.io/pex/) - Plask/Node.js 和 WebGL 中用于计算思维的 JavaScript 库.
* [PlayCanvas](https://playcanvas.com/) - 构建互动体验的游戏引擎平台.
* [Pocket.gl](https://github.com/gportelli/pocket.gl) - 完全可定制的 webgl 着色器沙箱，可嵌入到您的页面中.
* [Regl](http://regl.party/) - 轻型声明和无状态库，WebGL 的功能抽象.
* [Scene.js](http://scenejs.org/) - 用于高细节 3D 可视化的可扩展的基于 WebGL 的引擎.
* [Three.js](https://threejs.org/) - 旨在创建一个易于使用、轻量级的 3D 库.
* [Turbulenz](https://github.com/turbulenz/turbulenz_engine) - 模块化 3D 和 2D 游戏框架，用于为浏览器、桌面和移动设备制作 HTML5 驱动的游戏.
* [Verge3D](https://www.soft8soft.com/verge3d/) - 一个艺术家友好的工具包，用于创建 3D 网络体验.
* [Whitestorm.js](https://whs.io/) - 用于开发具有物理特性的 3D 网络应用程序的框架.

## Community
* [Stack Overflow](https://stackoverflow.com/questions/tagged/webgl)
* [Reddit](https://www.reddit.com/r/webgl/)
* [Facebook](https://www.facebook.com/groups/webgl/about/)
* [Twitter](https://twitter.com/webgl)
* [Freenode IRC](http://webchat.freenode.net/?channels=webgl)
* [Khronos Forum](https://community.khronos.org/c/other-standards/webgl)
* [Google Group](https://groups.google.com/forum/#!forum/webgl-dev-list)
* [Google Plus](https://plus.google.com/communities/114915309361980512257)
* [Public Mailing List](https://www.khronos.org/webgl/public-mailing-list/)
* [WebVR Slack](http://webvr-slack.herokuapp.com/)
* [WebVR Public Mailing List](https://lists.w3.org/Archives/Public/public-webvr/)
* 活跃的聚会小组
  * [San Francisco, CA](https://www.meetup.com/WebGL-Developers-Meetup/)
  * [Mountain View, CA](https://www.meetup.com/Silicon-Valley-HTML5-WebGL-Meetup/)
  * [London, United Kingdom](https://www.meetup.com/WebGL-Workshop-London/)
  * [New York, NY](https://www.meetup.com/NYC-WebGL-Developers/)

## Related lists

&gt; 类似的很棒的列表

* [awesome](https://github.com/sindresorhus/awesome) - 精选清单.
* [awesome-opengl](https://github.com/eug/awesome-opengl)  - 很棒的 OpenGL 库、调试器和资源的精选列表. 灵感来自 awesome-... 东西.
* [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) - 很棒的 Vulkan 项目和生态系统的精选列表.
* [gamedev](https://github.com/ellisonleao/magictools) - 关于游戏开发的精彩列表.
* [glTF](https://github.com/KhronosGroup/glTF) - 专为网络设计的运行时 3D 资产交付.
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - 图形编程资源列表.

## Contributing
请参见 [CONTRIBUTING](https://github.com/sjfricke/awesome-webgl/blob/master/CONTRIBUTING.md) 了解详情.

## Testing
Travis CI 测试自动化感谢 [awesome_bot](https://github.com/dkhamsing/awesome_bot)!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Spencer Fricke](https://github.com/sjfricke) 已放弃该作品的所有版权和相关或邻接权.
