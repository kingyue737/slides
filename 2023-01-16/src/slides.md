---
theme: default
layout: cover
background: /cover.jpg
# https://sli.dev/custom/highlighters.html
highlighter: shiki
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ### 2022年度工作总结
  金越
# persist drawings in exports and build
drawings:
  persist: false
colorSchema: "dark"
---

# 2022 年度工作总结

<div class="uppercase text-sm tracking-widest">
金越
</div>

<div class="abs-bl mx-12 my-12 flex">
  <img src="/logo-dark.png" class="h-11">
</div>

---
layout: section

---

# 在线监测系统前端

全面升级，打造核星前端标杆

---
layout: two-cols

---

# 在线监测系统前端

- 新增功能
  - 动态通量图
  - 电厂历史数据详表
  - 燃耗可视化
  - 路由自动跳转
  - 表格读取，确认对话框，面包屑导航，状态栏 
  - ...

<v-click>

- 界面美化，部分页面重新设计

</v-click>

::right::

<img src="/online-monitor.jpg" class="rounded-md mt-14 ml-3 h-xs">

---
layout: two-cols

---

# 在线监测系统前端

- 大规模重构
  - 重写警报模块
  - 重写所有参数设置
  - `vue-echarts` 和 `composables` 重写所有图表
  - 重写前员工的遗留代码

<v-click>

- 技术栈替换
  - Vite 替换 Vue-CLI
  - Volar 替换 Vetur
  - 移除了过时的 Class API
  - 移除了过时的 Vue 2 filter 和 Mixin
  - 全部使用`<script setup>`+ Composition API
  - Pinia 替代 Vuex 和 `ref` 管理全局堆芯数据
  - ...

</v-click>

<v-click>

- 完善单元测试和集成测试

</v-click>

::right::

<img src="/section.jpg" class="rounded-md ml-15 h-15rem">
<img src="/qptr.jpg" class="rounded-md mt-2 ml-15 h-15rem">


---
layout: section

---

# Vitify Admin

用于快速创建 web 后台应用的起始模板。Vite + Vuetify = Vitify

---

# Vitify Admin

核星首个开箱即用的企业级前端模板

<v-clicks>

- ⚡️ **Vite 4, pnpm, ESBuild** - 快得一逼
- 🦾 **TypeScript** - 支持 Vuetify2 模板 intelisense, Powered by Volar
- 🍍 **状态管理** - Pinia
- 🌍 **I18n** - 国际化开箱即用
- 🧪 **愿检尽检** - Vitest 单元/组件测试 + Cypress E2E 测试
- 💩 **PostCSS + Babel** - 浏览器兼容
- 🖼️ **风格清新简洁** - 符合越哥的审美

</v-clicks>

<v-click>

- 🗂️ **Pages** - 基于文件的路由
- 📑 **布局系统** - 零配置布局
- 🔥 **`<script setup>`** - 使用 Vue3 语法
- 📦 **自动 import** - 组件自动化加载，API 自动导入
- 📉 **数据可视化** - Vue-ECharts
- 🤡 **Mock Service Worker** - 开发与测试环境下模拟后端数据

</v-click>

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

---

<div class="grid grid-cols-2 gap-x-4"><div>

# Before

```vue {all|3-6,11-16|all}
<script lang="ts">
import { reactive, defineComponent } from 'vue'
import BtnCount from './BtnCount.vue'
export default defineComponent({
  components: { BtnCount },
  setup() {
    const state = reactive({ count: 0 })
    function increment() {
      state.count++
    }
    return {
      state,
      increment
    }
  }
})
</script>
<template>
  <BtnCount @click="increment">
    {{ state.count }}
  </BtnCount>
</template>
```
</div>
<div v-after>

# With `<script setup>`

```vue {2-6}
<script setup lang="ts">
import BtnCount from './BtnCount.vue'
const state = reactive({ count: 0 })
function increment() {
  state.count++
}
</script>
<template>
  <BtnCount @click="increment">
    {{ state.count }}
  </BtnCount>
</template>
```

</div>
</div>

---

<img src="/demo.gif" class="rounded-md  h-xs">
<img v-click src="/volar-plugin.jpg" class="rounded-md mt-4">

---

<img src="/repros1.jpg" class="inline-block rounded-md h-xs">
<img src="/repros2.jpg" class="inline-block rounded-md h-xs ml-4">
<img v-click src="/kazupon.jpg" class="rounded-md mt-4 ">

---
layout: iframe
url: https://kingyue737.github.io/vitify-docs

---
# 文档

---

<img src="/andrew-henry.jpg" class="rounded-md h-xs">
<img v-click src="/hannoeru.jpg" class="inline-block rounded-md mt-4 h-8rem">
<img v-click src="/ilhammeidi.jpg" class="inline-block rounded-md mt-4 ml-4 h-8rem">
<img v-click src="/andrey-sitnik.jpg" class="inline-block rounded-md mt-4 ml-4 h-8rem">


---
layout: section

---

# 压水堆换料安全分析

入门后端，熟悉业务，向全栈迈进

---
layout: two-cols

---

# 压水堆换料安全分析 <Marker class="text-blue-400">New</Marker>

- 产品设计研讨
- 前端设计与开发
  - 包含增删改查，进度与结果显示的任务数据表
  - 计算结果高亮与格式化
  - 滑动式单页设置表单
  - 状态管理切换任务

<v-click>

- 学习 EGRET 使用和校算，使用 EGRET `h5` 实现：
  - 落棒事故
  - 提棒事故
  - 硼稀释事故
  - 卡轴事故
  - HZP EOL 停堆裕量计算

</v-click>

::right::

<img src="/refueling-safety.jpg" class="rounded-md mt-14 ml-3 h-xs">

---

# 压水堆换料安全分析 <Marker class="text-blue-400">New</Marker>

<div class="grid grid-cols-[2fr,1fr] gap-x-4">

- 入门后端开发，建立项目雏形，学习 Python 工程化
  - 后端框架：`FastAPI`
  - Formatter: `Black` + `AutoFlake` + `Flake8` +`isort`
  - Linter，类型检查： `Mypy` + `Pyright`
  - 包管理工具：`Poetry`
  - 数据库 ORM：`Postgresql` + `SQLModel` + `SQLAlchemy`
  - 任务队列：`Celery`, `Redis`, `Flower`

<img src="/fastapi.webp">

<v-clicks :every='2'>

- 学习容器开发与部署，自动化部署流程
  - CLI
  - Compose
  - Multi-stage build
  - Buildkit cache
  - 邮件部署

<img src="/docker.webp" class="w-12rem mt-4">

</v-clicks>

</div>

---
layout: section

---

# Miscellaneous

全干工程师，十八般武艺

---

# Figma UI原型设计 <Marker class="text-orange-400">Design</Marker>

<img src="/电子规程执行.png" class="rounded-md h-md">

---

# Figma UI原型设计 <Marker class="text-orange-400">Design</Marker>

<img src="/实时监控.png" class="rounded-md h-md">

---

# Figma UI原型设计 <Marker class="text-orange-400">Design</Marker>

<img src="/电子规程设计.png" class="rounded-md h-md">

---

# Figma UI原型设计 <Marker class="text-orange-400">Design</Marker>

<img src="/用户管理.png" class="rounded-md h-md">

---

# OpenMC 球床堆芯建模

- OpenMC 自带的 RSP+CRP 算法在容器中填充不重叠的弥散颗粒。
- 将燃料球模型和石墨球打乱，随机弥散分布于球床中，模拟双重异质性。
- 网格划分 TRISO 颗粒，大幅加快输运计算。

<img src="/triso-pebble-bed.png" class="rounded-md h-xs mb-2 inline-block">

---

# OpenMC 板状燃料堆屏蔽问题 <Marker class="text-blue-400">New</Marker>

<img src="/plate-core.png" class="rounded-md h-xs mb-2 inline-block">
<img src="/plate-core-whole.png" v-click class="rounded-md h-xs ml-5 mb-2 inline-block">

<div v-after>

| 吊篮 | 水  | 压力容器 | 水  | 保温层  | 钢  | 屏蔽水箱  | 钢  | 硼碳钢 | 铅硼聚乙烯 |
| ---- | --- | ---- | --- | --- | --- | --- | --- | ------ | ---------- |

</div>

<v-click>

- Weighted Windows 逐级增加光子数量

</v-click>


<style>
  .slidev-layout tr th{
      --tw-border-opacity: 1;
    border-color: rgba(156, 163, 175, var(--tw-border-opacity));
    --tw-border-opacity: 0.2;
    border-width: 1px;
  }
  </style>

---

# 提升工作效率 <Marker class="text-purple-400">WIP</Marker>

<img v-click src="/contribution-2021.jpg" class="rounded-md h-9rem mb-2">
<img v-click src="/contribution-2022.jpg" class="rounded-md h-9rem mb-2">

<v-click>

- Shell Tools and Scripting
- dotfiles
- Windows 沙盒
- ...

</v-click>

---
layout: two-cols

---

# dotfiles <Marker class="text-purple-400">WIP</Marker>

- npm 配置
- pip 源
- PowerShell 常用函数
- Git 配置
- Windows Terminal 配置
- Oh My Posh 配置
- wsl 配置
- docker daemon
- OpenMC 环境变量
- Conda 通道与源设置
- ssh 免密登录
- ...

::right::

<v-click>

```bash
~（用户目录）
├── .bashrc
├── .gitconfig          # Git 配置
├── .npmrc              # pnpm 配置
├── .yarnrc
├── .wslconfig          # WSL 配置
├── .config               
│   ├── clash           # VPN设置
│   │   ├─ config.yaml  # 内网绕过代理
│   │   └─ profiles
│   └── thefuck
├── .docker
│   ├── config.json
│   └── daemon.json
├── .matplotlib
├── .ssh
│   ├── authorized_keys
│   └── config
├── pip
│   └── pip.ini
├── Documents
│   └── PowerShell      # PowerShell 启动脚本
│       ├─ Microsoft.PowerShell_profile.ps1
│       └─ profile.ps1
└── .nuxtrc
```

</v-click>

---

# 2023 

- 重水堆换料
- Vuetify v3.3 前端的最后一波大升级
- 后端的技术栈的熟悉与探索
- 学习 Docker 集群部署
- EGRET Python API

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
