# AI Website Builder - Landing Page Template

> 使用 AI 人工智能打造的现代化单页落地页模板 / Modern landing page template powered by AI

[English](#english) | [中文](#中文)

---

## 🎯 Overview

AI 建站演示落地页，一个纯 HTML + Tailwind CSS 构建的现代化、高转化率单页网站模板。无需构建工具，直接在浏览器打开即可运行。

A pure HTML + Tailwind CSS (CDN) landing page template for AI-powered website building services. Zero build tools required — just open in browser.

## ✨ Features

- 🎨 **Modern Design** — 渐变 Hero、玻璃态效果、浮动动画、平滑滚动
- 📱 **Fully Responsive** — 完美适配手机、平板、桌面端
- 🌐 **Bilingual** — 中英双语支持，一键切换
- ⚡ **No Build Required** — 纯 HTML + Tailwind CSS CDN，无依赖
- 💫 **Smooth Animations** — 滚动渐入、悬停效果、脉冲动画
- 📊 **Pricing Tiers** — 3 个价格套餐卡片（免费/专业/企业）
- 📝 **Working Contact Form** — 带成功提示的完整联系表单
- 🔍 **SEO Ready** — 语义化 HTML、Meta 标签
- 🧭 **Sticky Nav** — 滚动时带模糊背景的固定导航栏
- 📱 **Mobile Menu** — 汉堡菜单，移动端全屏导航

## 📁 Project Structure

```
ai-website-builder/
├── index.html      # 完整的落地页（含所有 CSS/JS）
└── README.md        # 本说明文档
```

## 🚀 Quick Start

```bash
# 直接在浏览器打开
open index.html

# 或使用任意静态服务器
npx serve .
python -m http.server 8080
```

## 🗂️ Sections

| Section | Description |
|---------|-------------|
| **Hero** | 全屏渐变背景 + 数据统计 + CTA 按钮 |
| **Features** | 6 个功能卡片，网格布局 |
| **Pricing** | 3 套餐定价（免费/专业/企业） |
| **About** | 公司介绍 + 数据展示 |
| **Testimonials** | 3 条用户评价 |
| **Contact** | 玻璃态联系表单 + 成功提示 |
| **Footer** | 链接导航 + 社交媒体图标 |

## 🎨 Design System

- **Primary Color:** `#1079e0` (Brand Blue)
- **Gradient:** `#0f3458` → `#1079e0` → `#289df5`
- **Font:** Inter (Google Fonts)
- **Icons:** Inline SVG (无外部依赖)

## 🌐 Internationalization

页面内置中英双语支持。通过点击导航栏右上角的语言切换按钮实现切换，语言偏好会保存到 `localStorage`。

Switch language via the toggle in the top-right corner. Preference is saved to `localStorage`.

---

## English

### What is This?

This is the landing page template for the AI 建站 (AI Website Builder) product demo. Built as a standalone HTML file with Tailwind CSS via CDN.

### How to Customize

1. **Text Content** — 编辑 `index.html` 中的 `data-zh` 和 `data-en` 属性
2. **Colors** — 修改 `<script tailwind.config>` 中的 `theme.extend.colors`
3. **Images** — 替换 Hero 背景或 About 区域图片（使用 Unsplash 或本地图片）
4. **Pricing** — 编辑 Pricing 区域的套餐内容和价格
5. **Form** — 将 `handleSubmit` 函数接入真实后端 API

### Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

---

## 📄 License

MIT License — 可免费商用 / Free for commercial use
