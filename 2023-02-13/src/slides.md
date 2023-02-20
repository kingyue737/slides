---
layout: cover
highlighter: shiki
css: unocss
colorSchema: dark
transition: fade-out
title: 核星产品部技术交流
info: |
  ### 核星广核产品交流
  金越
---

<h1 flex="~ col">
<div>核星科技产品部技术交流</div>
<div flex="~ gap3" items-center> <Nustar filled inline-block h-21 mb-2/> <b font-bold text-blue>NuStar</b></div>
</h1>

<div uppercase text-sm tracking-widest>
金 越
</div>

<div abs-br mx-10 my-12 flex="~ col" text-sm text-right>
  <div>上海 ↔️ 深圳</div>
  <div text-sm opacity-50>Feb. 14th 2023</div>
</div>

---
layout: intro
growX: 10
growY: 90
style: 'padding-left: 8rem;'
---

# 金 越

<div class="leading-10 opacity-80">
复旦大学 核工程与核技术学士<br>
巴黎高科国立高等先进技术学院ENSTA 工程师学位<br>
法国CEA国立核科技学院INSTN Génie Atomique<br>
核星科技 全栈工程师<br>
</div>

<div my-10 w-min flex="~ gap-1" items-center justify-center whitespace-nowrap>
  <mdi-user-circle op50 ma text-xl/>
  <div><a href="https://www.nustarnuclear.com/about/our-team" target="_blank" class="border-none! font-300">yjin</a></div>
  <mdi-github op50 ma text-xl ml4/>
  <div><a href="https://github.com/kingyue737" target="_blank" class="border-none! font-300">kingyue737</a></div>
  <mdi-stackoverflow op50 ma text-xl ml4/>
  <div><a href="https://stackoverflow.com/users/13326361/yue-jin" target="_blank" class="border-none! font-300">Yue JIN</a></div>
</div>

<img src="/avatar.jfif" rounded-full w-35 abs-tr mt-32 mr-40/>

<div flex="~ gap2">

</div>

<!--

-->

---
layout: center
growX: 20
growY: 0
---

# 核星前端产品 

<!--
首先我来带大家速览一下核星的前端产品
-->

---

# 我们的Web前端产品

数十款基于现代前端技术开发的产品

<v-click>

- 在线监测系统

- AXIOM-P
- 压水堆换料安全分析平台
- 环保部安审中心AI审评系统
- ORIENT 2<sup text-blue> new</sup>
- 重水堆换料设计支持系统<sup text-purple> WIP</sup>
- ...

</v-click>

<!--
 
-->

---
growX: 100
growY: 0
---

# 在线监测系统

<span>ECharts 数据可视化</span>
<span ml-3>自定义网格布局</span>
<span ml-3>响应式设计</span>

<img v-click-hide absolute rounded-2 h-sm src="/online-monitor.gif">
<img v-after absolute rounded-2 h-sm src="/online-monitor.jpg">


<!--
我们的客户需要在不同的显示屏上使用我们的网页客户端，有高分辨率也有低分辨率的，宽屏、方屏等等。我们的响应式设计可以适配不同分辨率的电脑，根据窗口宽度改变成不同的布局，甚至手机上也能正常使用我们在线监测的大部分功能。
-->

---
growX: 100
growY: 0
clicks: 2
---

# 压水堆换料安全分析平台

<v-clicks>

- 数据表格增删改查，结果展示
- 表单校验

</v-clicks>

<div flex="~" mt-4>

<img v-click="1" src="/refueling-safety.jpg" rounded-3 min-w-0>

<img v-click="2" src="/refueling-safety.gif" rounded-3 min-w-0 ml-4>

</div>

<!---->

---
growX: 100
growY: 0
---

# 环保部安审中心AI审评系统

- UI多样化交互模式
- `pdfjs` 实现报告渲染和数据操作

<div flex="~" mt-4>

<img v-click src="/safety-report.jpg" rounded-3 min-w-0>

<img v-click src="/safety-report2.jpg" rounded-3 min-w-0 ml-4>

</div>

---
growX: 100
growY: 0
---

# ORIENT 2

---
layout: center
growX: 50
growY: 120
growSize: 1.5
---

# 前端产品技术栈

<!--
 
-->

---
growX: 50
growY: 0
---

# 主要技术栈

<div flex="~" justify-evenly items-center h-90>
<v-clicks>

<div flex="~ col" items-center>
<logos-vitejs text-4.6rem mb6 />
<div text-2xl>Vite</div>
<div text-base op50>Next Generation Frontend Tooling</div>
<div text-xs>极速启动；超快热重载；丰富的插件</div>
</div>

<div flex="~ col" items-center>
<logos-vue text-4.6rem mb6 />
<div text-2xl>Vue</div>
<div text-base op50>Progressive JavaScript Framework</div>
<div text-xs>性能出色，适用场景广泛的 Web 前端框架</div>
</div>

<div flex="~ col" items-center>
<logos-vuetifyjs text-4.6rem mb6 />
<div text-2xl>Vuetify</div>
<div text-base op50>Material Design UI Library</div>
<div text-xs>组件功能丰富；谷歌设计，简洁美观</div>
</div>

</v-clicks>
</div>

<!--
 
-->

---
growX: 60
growY: 60
layout: two-cols
clicks: 8
---

# 堆芯领域前端解决方案

<v-clicks>

- 可交互的组件功率分布图 (方形、六角形)

- 象限功率倾斜
- 运行梯形图
- 轴向分布、历史趋势图
- 建模材料成分图
- 表单表格
- ...
- 自研模板

</v-clicks>

::right::

<img v-click="1" src="/section.jpg" class="rounded-md ml-15 h-15rem">
<img v-click="2" src="/qptr.png" class="rounded-md mt-2 ml-20 h-15rem">

<!--
提炼了许多常用的组件供不同项目复用。

 JavaScript拥有整个编程领域最庞大的生态。雷打不动，多年来稳坐第一的宝座。
- ECharts 数据可视化
- Grid Layout 自定义网格布局
- VeeValidate 表单校验 规避人因失误
- pdfjs 前端界面和pdf交互
不用重复造轮子，可以直接整合社区中最好的解决方案。
-->

---
growX: 85
growY: 40
---

# Vitify Admin

核星自研 开箱即用的企业级前端模板

<v-clicks>

- 🌍 **I18n** - 国际化
- 🧪 **应测尽测** - Vitest 单元/组件测试 + Cypress E2E 测试
- ⚖️ **PostCSS + Babel** - 旧浏览器兼容
- 🪟 **后台管理系统布局** - 内置应用栏、状态栏和自动生成的导航栏
- 🖼️ **风格清新简洁** - Material Design, 自定义主题色
- 🤡 **Mock Service Worker** - 开发与测试环境下模拟后端数据
- 🔔 **全局通知**

</v-clicks>

<v-click>

- ⚡️ **Vite 4, pnpm, ESBuild** - 快速安装、重载、打包
- 🦾 **TypeScript** - 支持 Vuetify2 模板 intelisense, Powered by Volar
- 🍍 **状态管理** - Pinia
- 🗂️ **Pages** - 基于文件的路由
- 📑 **布局系统** - 零配置布局
- 📦 **自动 import** - 组件自动化加载，API 自动导入

</v-click>

<img src="/vitify.svg" absolute top-30 right-30 h-40>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
在github上很多前端领域的大佬也给我们的项目打了星，对其中的一些优秀的工程实践和微创新给出了他们的赞誉。我可以说有这个信心，我们的脚手架是放眼整个社区同类项目里是最好的。紧跟潮流，最新技术栈，大厂用什么我们也用什么。
-->

---
growX: 50
growY: 80
---

# <img src="/vtk.svg" h-10 class="-mt-2" inline /> - The Visualization Toolkit

- 基于VTK进行3D数据可视化开发

- 针对堆芯物理计算模型深度定制
- 丰富的视图模式，呈现更全面的数据可视化
- 标准化数据格式，便于与后台专业程序集成

---
layout: image
growFollow: false
image: /core-visualizer.gif
class: important-bg-contain
---

<!--
-->

---
growX: 80
growY: 80
preload: false
---

# <img src="/vtk.svg" h-10 class="-mt-2" inline /> - The Visualization Toolkit

3D数据可视化

<div absolute right-15 bottom-40 style="height:260px; border-radius:30px" overflow-hidden>
<iframe id="cone-example" src="https://kitware.github.io/vtk-js/examples/SimpleCone/index.html" allowvr="yes" allow="xr-spatial-tracking" scrolling="no" allowtransparency="true" class="-m-3" h-xs style="mix-blend-mode: lighten; filter: contrast(1.7); background:transparent"
/>
</div>

<v-clicks>

- VTK C++

- vtk.js - 在浏览器中展示科学数据3D模型
- ParaView-Web / VTK-Web Python - 服务端渲染
- trame - 前后端一体化

</v-clicks>

<!--
 
-->

---
growX: 0
growY: 90
---

# 全面前端化

<iframe v-click src="https://kingyue737.github.io/vitify-docs/" 
  onload="this.style.visibility = 'visible';" 
  scale-50 origin-top-right absolute right-0 top-0 bottom-0 w="140%" h="200%" 
  style="mix-blend-mode: lighten;filter:contrast(1.5);visibility:hidden;"
/>


<v-clicks>

- 开发文档

- 用户手册
- 幻灯片
- 门户网站

</v-clicks>

<!--
包括我们的公司官网，也是我们自己写的。基于现代前端技术栈打造，也是多年以前我们试水新的前端框架顺便写的一个小项目。我们公司呢在未来会继续专注于核工业软件前端产品开发上。如果说广核有什么网页app开发的需要，我们可以一起探讨合作的可能。
-->

---
growX: 100
growY: 50
---

# 核星的优势

承接堆工软件计算平台Web前端开发

<v-clicks>

- **全面的交付能力：** 前后端分离，浏览器兼容性良好，兼顾设计与开发

- **合理的技术选型：** 先进且成熟稳定，开源可控，关键模块自研
- **极致的开发效率：** 基于核星自研的 Vitify Admin 企业级前端模板，未来也将持续升级
- **强大的数据可视化：** 全面的堆芯数据可视化（包括3D）开发能力
- **丰富的开发经验：** 双方团队专业软件产品类型相似，核星前端团队已有丰富的经验积累
- **良好的业务对接：** 团队自身有堆工专业基础，且与专业软件开发人员有充分的沟通经验

</v-clicks>

---
layout: intro
class: text-center pb-5
growX: 50
growY: 120
---

# Thank You!

Slides on [nustarnuclear.com](https://yjin.nustarnuclear.com/2023/cgn-exchange/)

<!--
这是我所有要分享的内容，谢谢各位的聆听。
-->
