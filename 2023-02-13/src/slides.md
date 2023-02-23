---
layout: cover
highlighter: shiki
presenter: dev
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
  <div text-sm opacity-50>Feb. 23rd 2023</div>
</div>

<!--中广核的各位大家好，由我来为大家分享以下我们核星的web前端产品以及交流一下我们所使用的技术栈。-->

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
首先自我介绍一下。我本科毕业于复旦大学，和在座的大多数人一样也是核工程专业的。研究生期间在巴黎高科ENSTA和CEA的INSTN各学习了一年拿到了工程师学位。在CEA的堆芯计算部门工作实习了半年之后回到国内，随后之后一直在核星产品部工作。
-->

---
layout: center
growX: 20
growY: 0
---

# 核星前端产品 

<!--
我先来带大家速览一下核星的前端产品
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
我们公司近几年带有用户界面的产品，客户端都是用现代前端技术开发的。例如在线监测系统，我们和瑞典 A.N.T.International 公司联合开发的燃料破损监测软件 AXIOM-P。最近我们正在将我们的ORIENT压水堆堆芯物理分析与燃料管理软件系统，以前用jquery开发的，从十多年前的技术栈升级到最新的技术栈。目前正在研发的重水堆换料设计支持系统也是基于现代前端技术栈来开发用户界面。在最近的三年间，核星已经积累了数十款基于web前端软件，在这一领域已经拥有丰富的经验。
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
在线监测系统用到了百度的开源图表库ECharts，提供直观，生动，可交互，可个性化定制的数据可视化图表。显示历史趋势用到的折线图，组件功率燃耗分布图，轴向分布图等都是通过ECharts实现的。不仅美观，像点击选中，拖拽，鼠标悬浮显示相应信息等，交互性也非常优秀。
自定义网格布局是在线监测系统的一大特色，能够让用户自主决定需要在屏幕上显示的内容，自行规划布局。
另外我们的客户需要在不同的显示屏上使用我们的网页客户端，有高分辨率也有低分辨率的，宽屏、方屏等等。我们的响应式设计可以适配不同分辨率的电脑，根据窗口宽度改变成不同的布局，甚至手机上也能正常使用我们在线监测的大部分功能。
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

<!--
压水堆换料安全分析平台的前端主要用于负责管理后台堆芯计算任务。我们通过数据表格的形式实现对任务的增删改查，同时这个数据表格是可折叠的，像手风琴一样，通过展开数据表，可以直接显示每个堆芯计算任务的后处理结果。
用户在使用软件的时候往往需要填写一些复杂的表单，对堆芯的各种参数进行设置。需要输入的参数越多，用户越容易犯错，数字多打了一个0啊，控制棒填的步数不小心超过了限值啊等等。用web前端开发的客户端，不仅能提供各种多样的表单输入方式，像输入框啊，滑动条啊，复选框啊，还能直接在图表上同步显示输入的值。最重要的是这些输入控件本身会提供校验，比如用户无法输入超过预设最大值的数，用户输入的数不满足一定规则时，会显示相应的警告，输入框也会变成红色。这在web前端都是容易实现的功能。校验功能能够有效减少人因失误，特别是对和使用和生产直接挂钩的软件，比如重水堆换料，是非常有必要集成的功能。
-->

---
growX: 100
growY: 0
---

# 环保部安审中心AI审评系统

- `pdfjs` 实现报告渲染和数据操作
- UI多样化交互模式

<div flex="~" mt-4>

<img v-click src="/safety-report.jpg" rounded-3 min-w-0>

<img v-click src="/safety-report2.jpg" rounded-3 min-w-0 ml-4>

</div>

<!--
审评系统是我们为环保部开发的，用于辅助审查核电厂安全分析报告的系统。在前端，我们通过firefox的开源库pdfjs将pdf文档内嵌在网页中。用户可以直接和文档交互，选中文档内容后可以传送至后端，由ai分析出关键词。点选相应的关键词可以在屏幕中显示关联的知识图谱，辅助工作人员学习相关知识以及根据过往的历史报告，审查当前报告。网页的底部还可以弹出表单，工作人员在一边阅读报告时，一边就可以填写问题单。
-->

---
growX: 100
growY: 0
---

# ORIENT 2

压水堆堆芯物理分析与燃料管理软件系统

<div flex="~" mt-4>

<img v-click src="/orient.jpg" rounded-3 min-w-0>

<img v-click src="/orient.gif" rounded-3 min-w-0 ml-4>

</div>

<!--这是我们正在开发的新一代ORIENT用户界面，同样使用了ECharts来实现了方形和六角形的组件布置图，确保用户友好。另外像是用户在定义材料时，我们使用了扇形图清晰地显示了材料的构成关系，直观而且美观。-->

---
layout: center
growX: 50
growY: 120
growSize: 1.5
---

# 前端产品技术栈

<!--
那开发这些产品我们具体用到了什么技术栈呢？
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
我们使用的最主要的技术栈归结为3V。Vite、Vue和Vuetify。Vite是一种新型前端构建工具，他有两大主要功能，一是提供了热重载功能的开发服务器，什么意思呢，当我在更改代码的时候，网页会实时反应这些更改，不需要刷新网页或者清除应用程序的状态。而且速度非常快，不管程序有多大，只需要不到0.1s,正如他的名字Vite，在法语里就是快的意思。第二个主要功能就是他可以打包代码，可输出用于生产环境的高度优化过的静态资源。打个比方，当我们通过浏览器打开网页，网页是从服务器经过网络传输过来的。经过Vite打包的代码体积会大大缩小，降低网络传输的耗时。
Vue 是一款用于构建用户界面的 JavaScript 框架。它基于标准 HTML、CSS 和 JavaScript 构建，并提供了一套声明式的、组件化的编程模型，帮助工程师高效地开发用户界面。无论是简单还是复杂的界面，Vue 都可以胜任。Vue 基于标准 HTML 拓展了一套模板语法，使得我们可以声明式地描述最终输出的 HTML 和 JavaScript 状态之间的关系，而且这种联系是响应性的。比如说我想把一个二维数组显示在界面上，当这个二维数组里的值变动时，Vue会自动更新HTML，更新界面上显示出来的值，不需要开发人员额外地再去写更改页面的代码。Vue的组件化功能可以帮助我们把某些界面及相关逻辑功能提出来作为一个组件在一个项目的多个地方，甚至跨项目地复用。比如我们的多个项目都引用了同一个堆芯分布图组件。
有了开发构建工具、JavaScript框架Vue，我们还需要基础的组件。像是按钮、表格、卡片、标签、工具栏、状态栏还有刚才看到的那些最基础的表单输入组件，我们不用自己造轮子。Vuetify提供了现成的UI组件，而且设计上遵循谷歌的material design，符合大众审美。
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
正如刚才提到的，还有我们在之前的产品介绍里看到的，我们的开发人员提炼了许多常用的组件供不同项目复用。

除此之外JavaScript拥有整个编程领域最庞大的生态。雷打不动，多年来稳坐第一的宝座。
很多功能上的需求，可以直接整合社区中最好的解决方案。

不仅如此，我们还有自研的项目模板，集成了常用的重要功能，可以让我们的开发人员快速启动项目开发。并提升开发体验和效率。
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
Vitify Admin是我们公司自研的，开箱即用的企业级前端模板，整合了大量常用功能。我们不仅为国内的客户开发软件，像是和瑞典、巴基斯坦等国家都有合作。国际化功能就可以让我们用一套代码来写不同语言的界面，并且随意切换。
模板中还集成了单元测试和E2E测试，做到应测尽测，减少错误，提高代码的健壮度。我们知道现在很多项目投标，甲方是直接把测试写进项目要求里的。
像我们为中核集团开发软件，他们的浏览器统一使用的是版本很老旧的360浏览器。这一功能就保证了我们能用最新的语法和语言特性开发程序，但是构建出来的程序，依然可以在旧版浏览器上正常使用。
模板中内置了后台管理系统通用的界面布局，而且支持换肤，主题色更改。
平时我们的开发是前后端分离的，前端在开发时使用mock service worker来模拟后端传过来的数据。并且能做到和后端API接口之间的无缝替换。
内置的全局通知功能为用户提供各种提示信息与警告。
还有大量提升开发者体验与工作效率的功能，保证项目的按时交付。
在github上很多前端领域的大佬也给我们的项目打了星，对其中的一些优秀的工程实践和微创新给出了他们的赞誉。我可以说有这个信心，我们的脚手架是放眼整个社区同类项目里是最好的。紧跟潮流，使用最新最稳定的技术栈，大厂用什么我们也用什么。将来也会持续地维护与升级
-->

---
growX: 50
growY: 80
---

# <img src="/vtk.svg" h-10 class="-mt-2" inline /> - The Visualization Toolkit

<v-click>

- 基于VTK进行3D数据可视化开发

- 针对堆芯物理计算模型深度定制
- 丰富的视图模式，呈现更全面的数据可视化
- 标准化数据格式，便于与后台专业程序集成

</v-click>

<!--除了传统的2D数据可视化，我们也将vtk的三维可视化能力集成到了前端产品中，为用户呈现三维的堆芯模型-->

---
layout: image
growFollow: false
image: /core-visualizer.gif
class: important-bg-contain
---

<!--这是我们多年以前基于vtk开发的可视化软件，可以清晰地显示物理量在整个三维堆芯中的分布情况-->

---
growX: 80
growY: 80
preload: false
---

# <img src="/vtk.svg" h-10 class="-mt-2" inline /> - The Visualization Toolkit

Web 3D数据可视化

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
之前我们是用c++来写的，随着近两年vtk.js的诞生和不断完善，我们能把vtk整合到前端产品中。
我们知道要呈现堆芯数据，如果网格划分得比较细，那数据量会非常庞大，要把数据通过网络传到前端会占用带宽并耗费大量的时间。并且由前端负责渲染，对硬件的要求也较高，只有集成显卡的笔记本电脑可能难以胜任。我们现在还可以通过vtk和paraview python后端，让服务器完成渲染，再把图片逐帧传给前端显示。完全解放前端的负担。就算是随便一台比较老旧的笔记本电脑上打开浏览器访问网页也没有问题。
我们可以看到右边我就放了一个可以交互的vtk模型
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
现在我们公司进入了一个全面前端化的进程，我们公司的内部项目，像刚才提到的模板Vitify Admin的文档就是使用前端技术栈生成。我们产品的用户手册，像交付给秦山在线监测系统的手册同样如此。用网站开发用户手册，可以把视频动图等多媒体资源嵌入进去，更直观地指导用户使用软件。
这个幻灯片也是如此，大家应该已经发现了，我们正在看的幻灯片不是powerpoint,是一个网站。
包括我们的公司官网，也是我们自己写的。是多年以前我们试水新的前端框架顺便写的一个小项目。
核星在未来会继续专注于核工业软件前端产品开发上。
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

<!--如果说中广核有什么网页app开发的需要，我们可以一起探讨合作的可能。-->

---
layout: intro
class: text-center pb-5
growX: 50
growY: 120
---

# Thank You!

Slides on [nustarnuclear.com](https://yjin.nustarnuclear.com/2023/cgn-exchange/)

<!--
这是我所有要分享的内容，感谢各位的聆听。
-->
