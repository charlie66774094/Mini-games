# 🌌 PolyVerse Arcade (多边形宇宙街机厅)

> **沉浸式 Web 3D 游戏体验中心 | 纯前端实现 | 移动端适配**

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Tech](https://img.shields.io/badge/Three.js-r160-black) ![AI](https://img.shields.io/badge/Co--Pilot-Gemini%203-4285F4)

## 💡 关于本项目 (About)

**PolyVerse Arcade** 是一个基于 WebGL 的高性能 3D 游戏合集网站。它打破了传统网页游戏的平面限制，采用了极具未来感的 **Cyberpunk (赛博朋克)** 视觉风格，并实现了从 3D 选单大厅到游戏场景的无缝交互。

本项目探索了现代浏览器在无需安装任何插件的情况下，如何通过代码生成高精度模型（Procedural Generation）与实时物理交互。

### 🤖 AI 驱动开发
本项目由 **Google Gemini 3** 担任核心架构师与代码生成引擎。
从视觉概念设计、技术选型、物理逻辑编写到响应式 UI 布局，均由 Gemini 3 在与开发者的对话中实时构建完成。这是 **AI 结对编程 (AI Pair Programming)** 的一次完美实践。

---

## ✨ 核心特性 (Features)

* **🪐 沉浸式 3D 大厅**：
    * 基于 Three.js 的动态线框球体核心，带有呼吸动效。
    * 响应鼠标与触摸的 3D 视差背景（Parallax Effect）。
    * 粒子流体背景，营造深空氛围。
* **🎮 精品小游戏：Zen Stack (禅意堆叠)**：
    * **PBR 材质**：模拟磨砂玻璃与自发光霓虹质感。
    * **动态难度**：随着堆叠高度增加，镜头自动跟随，颜色动态变化。
    * **移动端适配**：支持触摸操作，随时随地可玩。
* **📱 全响应式设计**：
    * 完美适配 Desktop、Tablet 与 Mobile 设备。
    * 移动端自动切换为“纵向卡片流”布局，优化触控体验。
* **⚡ 轻量化架构**：
    * **零依赖构建**：无需 Webpack/Vite 打包，纯 HTML/JS 即可运行。
    * **CDN 加载**：通过 ES Modules 直接引用 Three.js 与 GSAP。

---

## 🛠 技术栈 (Tech Stack)

* **渲染引擎**: [Three.js](https://threejs.org/) (r160) - 处理所有 3D 场景与光照。
* **动画引擎**: [GSAP](https://greensock.com/gsap/) - 处理 UI 切换与丝滑的转场动画。
* **开发语言**: HTML5, CSS3 (Glassmorphism UI), Vanilla JavaScript (ES6+).
* **物理逻辑**: Custom Lightweight Physics (自定义轻量级碰撞检测).

---

## 📂 目录结构 (File Structure)

```text
PolyVerse-Arcade/
├── index.html      # 3D 主页 (入口)
│                   # 包含全息地球背景、游戏选单、GSAP 转场逻辑
├── game1.html      # 游戏 01: Zen Stack
│                   # 包含堆叠玩法核心逻辑、物理计算、PBR 材质渲染
└── README.md       # 项目说明文档
