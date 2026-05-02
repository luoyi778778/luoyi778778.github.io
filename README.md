---
title: 落以个人主页项目
tags:
  - MOC
  - 网页开发
  - AI辅助开发
type: index
---

# 落以个人主页项目

> 单页响应式个人主页，玻璃拟态风格，部署于 GitHub Pages。全程 **AI 辅助开发**，人机协作完成。

**线上地址**：[https://luoyi778778.github.io/](https://luoyi778778.github.io/)

---

## 项目速览

| 项 | 内容 |
|----|------|
| 技术栈 | HTML5 + CSS3 + JavaScript（原生，无框架） |
| 设计风格 | Glassmorphism 玻璃拟态 + 气泡粒子动画 |
| 开发方式 | AI 辅助开发（见下方工具链） |
| 响应式断点 | 860px |
| 部署 | GitHub Pages（静态） |
| 状态 | 🟢 运行中 |

---

## AI 辅助开发工具链

本项目由 AI 深度参与设计与编码，采用**双 AI 工具协作**模式：

| 工具 | 用途 | 说明 |
|------|------|------|
| **Claude Code CLI** | 主力开发 | 接入 mimo2.5pro API，负责页面结构搭建、CSS 设计系统、动画实现等核心编码 |
| **Codex** | 代码优化 | 对生成代码进行重构、性能优化和细节打磨 |

**开发流程**：
1. Claude Code CLI（mimo2.5pro）根据需求描述生成完整页面框架与样式
2. Codex 对代码进行审阅优化，改进可读性与性能
3. 人工微调细节，迭代出最终版本

---

## 笔记导航

| 笔记 | 说明 |
|------|------|
| [[开发笔记]] | 完整开发记录：技术栈、页面结构、设计系统、动画实现、待优化项 |

---

## 核心特性

- **旋转开页动画** — 页面加载时从 -90° 旋转展开，配合 LOGO 遮罩淡出
- **气泡粒子背景** — Canvas 绘制 18 个漂浮气泡，淡蓝色调径向渐变
- **滚动触发动画** — IntersectionObserver 监听 4 种方向的入场动画
- **玻璃拟态卡片** — backdrop-filter 模糊 + 半透明背景 + 微边框
- **CSS 变量系统** — 颜色 / 阴影 / 圆角全部可配置，便于主题扩展

---

## 相关仓库

- 📦 [GitHub 仓库](https://github.com/luoyi778778/luoyi778778.github.io)
- 📍 [GPS 宠物定位器](https://github.com/luoyi778778/P_01_GPS_FreeRTOS_send)
- 📱 [Daily 学习打卡](https://github.com/luoyi778778/Daily)
