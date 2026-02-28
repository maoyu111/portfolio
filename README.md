# Fri.AI 个人作品集网站

一个基于 HTML/CSS/JavaScript 构建的现代化个人作品集网站，展示品牌运营、AI 实践和项目经验。

## ✨ 特性

- 🎨 **极简设计** - 遵循 Apple 设计语言，简洁优雅
- 📱 **响应式布局** - 完美适配桌面端和移动端
- ⚡ **轻量级** - 无需构建工具，纯 HTML/CSS/JS
- 🎭 **流畅动画** - 滚动入场动画、悬停效果
- 🔧 **易于定制** - CSS 变量管理配色和样式

## 📂 项目结构

```
portfolio/
├── demo-v4.html          # 主页面文件
├── 参考.html              # 设计参考
├── README.md              # 项目说明
├── logo images/           # Logo 图片
└── 项目images/            # 项目截图
```

## 🎨 页面板块

### 1. 简介 (Intro)
- 个人定位介绍
- 核心价值主张
- CTA 按钮

### 2. 核心能力 (Skills)
- 策略输出
- 账号操盘
- 数据分析
- 数据统计展示

### 3. AI Tools
展示 8 个常用 AI 工具：
- NotebookLM
- ChatGPT
- Gemini
- 即梦
- ClaudeCode
- N8N
- Podwise
- Lovart

### 4. Project Showcase
6 个项目展示，支持展开/收起：
- 微信读书笔记一键同步 Notion
- 英/法语精读精听练习 Web
- 东京旅行小助手
- 抖音文案一键改写
- 我和宠物的毛毡效果合照
- 手搓 AI 漫剧

### 5. 联系我 (Contact)
- 邮箱联系方式
- 社交链接

## 🎯 设计规范

### 配色方案
```css
--bg: #FBFBFD           /* 页面背景 */
--card-bg: #FFFFFF      /* 卡片背景 */
--accent: #0066FF       /* 主强调色 */
--xhs-red: #ff2442      /* 小红书红 */
--text-main: #1D1D1F    /* 主文字 */
--text-sub: #6E6E73     /* 次要文字 */
--border: #E5E5E7       /* 边框 */
--radius: 28px          /* 圆角 */
```

### 字号层级
- H1 (Hero): 54px
- H2 (板块标题): 36px
- H3 (卡片标题): 28px
- 正文: 16px
- 导航: 13px

### 间距系统
- Section 间距: 120px
- 卡片间距: 24px
- 导航高度: ~60px

## 🚀 使用方法

### 本地预览

1. 克隆或下载项目
```bash
git clone <repository-url>
cd portfolio
```

2. 直接用浏览器打开
```bash
# Windows
start demo-v4.html

# macOS
open demo-v4.html

# Linux
xdg-open demo-v4.html
```

或使用本地服务器：
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

然后访问 `http://localhost:8000/demo-v4.html`

### 自定义内容

#### 修改个人信息
编辑 HTML 中的以下部分：
- 标题：`<title>` 标签
- 导航栏：`.nav-content` 区域
- 简介部分：`#intro` section
- 联系方式：`#contact` section

#### 修改配色
在 `<style>` 标签内的 `:root` 中修改 CSS 变量：
```css
:root {
    --accent: #0066FF;     /* 修改为你喜欢的颜色 */
    /* ... 其他变量 */
}
```

#### 替换图片
- Logo: `logo images/` 目录
- 项目截图: `项目images/` 目录
- 个人照片: `images/me.jpeg`（如果需要）

## 🛠️ 技术栈

- **HTML5** - 语义化标签
- **CSS3** - Flexbox/Grid、CSS 变量、动画
- **JavaScript (ES6+)** - DOM 操作、事件处理
- **Tailwind CSS** - 通过 CDN 引入（备用样式）
- **Lucide Icons** - 图标库

## 📝 待办事项

- [ ] 添加深色模式切换
- [ ] 多语言支持（中/英）
- [ ] 博客板块
- [ ] 作品筛选功能
- [ ] SEO 优化

## 📄 许可证

MIT License - 可自由使用和修改

## 👤 作者

**Fri.AI**
- 邮箱: xzzilndk@foxmail.com
- 定位: 品牌运营 & AI 实践者

---

Built with Passion & AI © 2024 Fri.AI
