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
  <div><a href="https://www.nustarnuclear.com/about/our-team/yjin" target="_blank" class="border-none! font-300">yjin</a></div>
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

# 主要框架

<div flex="~" justify-evenly items-center h-90>
<v-clicks>

<div flex="~ col" items-center>
<!-- <img w-20 mb6 src="/vite.svg"> -->
<logos-vitejs text-4.6rem mb6 />
<div text-2xl>Vite</div>
<div text-base op50>Next Generation Frontend Tooling</div>
</div>

<div flex="~ col" items-center>
<!-- <img w-20 mb6 src="/vite-node.svg"> -->
<logos-vue text-4.6rem mb6 />
<div text-2xl>Vue</div>
<div text-base op50>Progressive JavaScript Framework</div>
</div>

<div flex="~ col" items-center>
<!-- <div text-4.6rem>⚗️</div> -->
<logos-vuetifyjs text-4.6rem mb6 />
<div text-2xl>Vuetify</div>
<div text-base op50>Material Design UI Library</div>
</div>

</v-clicks>
</div>

<!--
 
-->

---
growX: 60
growY: 60
---

# 核领域前端解决方案

<v-clicks>

- 可交互的组件功率分布图

- 象限功率倾斜
- 运行梯形图
- 自研脚手架

</v-clicks>

<!--
提炼了许多常用的组件供不同项目复用。
-->

---
growX: 85
growY: 40
---

# Vitify Admin

核星自研 开箱即用的企业级前端模板

<v-clicks>

- 🌍 **I18n** - 国际化开箱即用
- 🧪 **愿检尽检** - Vitest 单元/组件测试 + Cypress E2E 测试
- 💩 **PostCSS + Babel** - 旧浏览器兼容
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
在github上很多前端领域的大佬也给我们的项目打了星，对其中的一些优秀的工程实践和微创新给出了他们的赞誉。我可以说有这个信心，我们的脚手架是放眼整个社区同类项目里是最好的。
-->

---
growX: 50
growY: 80
---

# <img src="/vtk.svg" h-10 class="-mt-2" inline /> - The Visualization Toolkit

Core Visualizer

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
---

# <img src="/vtk.svg" h-10 class="-mt-2" inline /> - The Visualization Toolkit

3D数据可视化

<div absolute right-15 bottom-40 style="height:260px; border-radius:30px" overflow-hidden>
<iframe src="https://kitware.github.io/vtk-js/examples/SimpleCone/index.html" allowvr="yes" allow="xr-spatial-tracking" scrolling="no" class="-m-3" h-xs style="mix-blend-mode: lighten; filter: contrast(1.7)"/>
</div>

<v-clicks>

- VTK C++

- vtk.js
- ParaView-Web / VTK-Web Python
- trame

</v-clicks>

<!--
 
-->

---
growX: 0
growY: 50
---

# 桌面客户端 <span v-click="2"> - 基于Web技术</span>

<v-clicks at="1">

- Qt Widgets

- Electron / Tauri

</v-clicks>

<div v-click="3" flex="~ wrap" justify-evenly items-center w-80 h-70>
<logos-notion-icon />
<logos-whatsapp-icon />
<logos-discord-icon />
<logos-figma />
<logos-skype style="margin-left: 40px" />
<logos-visual-studio-code />
<logos-microsoft-teams />
<logos-twitch />
<logos-dropbox />
<img src="/github-desktop.svg" alt="GitHub Desktop" />
<img h-10 src="https://cdn.worldvectorlogo.com/logos/tencent-qq.svg" alt="Tencent QQ">
</div>


<style>
  img, svg{
    width: 50px;
    height: 50px;
    margin-left: 30px;
  }
</style>

<!--
 近10年来，即便是Qt也在往web前端上靠，推出了QML这样类似于CSS和JSON的声明式语言，并可以内联JavaScript代码。
-->

---
growX: 40
growY: 10
---
# KeyCloak

单点登录，用户统一管理及鉴权

<div flex="~">

<img v-click src="/keycloak-login.jpg" rounded-5 min-w-0>

<img v-click src="/keycloak-console.jpg" rounded-5 min-w-0 ml-4>

</div>

<!--
随着产品数量的增加，我们为核星的产品整合了单点登录功能。
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

<v-click>

[nustarnuclear.com](https://www.nustarnuclear.com)

</v-click>

<!--
包括我们的公司官网，也是我们自己写的。基于现代前端技术栈打造，也是多年以前我们试水新的前端框架顺便写的一个小项目。我们公司呢在未来会继续专注于核工业软件前端产品开发上。如果说广核有什么网页app开发的需要，我们可以一起探讨合作的可能。
-->

---
layout: intro
class: text-center pb-5
growX: 50
growY: 120
---

# Thank You!

Slides on [docs.nustarnuclear.com](https://nustarnuclear.com)

<!--
这是我所有要分享的内容，谢谢各位的聆听。
-->
