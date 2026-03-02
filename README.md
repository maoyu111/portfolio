# Fri.AI 个人作品集网站

一个基于 HTML/CSS/JavaScript 构建的现代化个人作品集网站，展示内容运营、AI 实践和项目经验。

## ✨ 特性

- 🎨 **极简设计** - 遵循 Apple 设计语言，简洁优雅
- 📱 **响应式布局** - 完美适配桌面端和移动端
- ⚡ **轻量级** - 无需构建工具，纯 HTML/CSS/JS
- 🎭 **流畅动画** - 滚动入场动画、悬停效果
- 🔧 **易于定制** - CSS 变量管理配色和样式

## 📂 项目结构

```
portfolio/
├── Frii.html              # 主页面文件
├── demo-v2.html           # 其他版本
├── demo-v2-浅色版.html     # 浅色版本
├── demo.html              # 演示版本
├── demo-v3.html           # 第三版
├── 参考.html              # 设计参考
├── README.md              # 项目说明
├── 链接.md                # 外部链接文档
├── CHANGELOG.md           # 更新日志
├── logo images/           # Logo 图片
└── 项目images/            # 项目截图
```

## 🎨 页面板块

### 1. 简介 (Intro)
- **个人定位**: 内容运营 · 策略策划 · AIGC创作者
- **核心价值**: 用内容连接情绪，用数据验证结果，用AI驱动效率
- **状态标签**: Learning • Building • Open to Work
- **CTA 按钮**: 查看简历（链接到飞书文档）

### 2. 核心能力 (Skills)
三大核心能力模块，每个都有对应的飞书详情链接：

#### 策略输出
- 擅长品牌IP化叙事与全链路营销转化
- 技能标签：短视频脚本、账号规划、品牌手册、产品方案
- [查看详情](https://my.feishu.cn/file/Kq0Ob87lsoxL63xoEqGcdf2CnTf)

#### 账号操盘
- 擅长 0-1 账号孵化与商业化闭环
- 技能标签：微信公众号、小红书、摩点、KOL投放
- [查看详情](https://my.feishu.cn/file/FmwEbO3A6ocs09xW3MSclmw4n9g)

#### 数据分析
- 全链路ROI追踪与链路优化
- 技能标签：Excel、Python、飞书多维表格
- [查看详情](https://my.feishu.cn/file/Jenxb3kolohYfnx4AETce5tqn3b)

**数据统计卡片**: 展示关键成果数据

### 3. AIGC 工具箱 (Tools & Creations)

展示 8 个常用 AI 工具及其应用场景：

| 工具 | 用途 |
|------|------|
| NotebookLM | 个人知识库，智能分析长文档与结构化研究 |
| ChatGPT | 全能助手，用于文案初稿生成与多维策略拆解 |
| Gemini | 原生多模态理解，快速处理视频与复杂表格数据 |
| 即梦 | 高质量视觉创作，从小红书配图到品牌海报生成 |
| ClaudeCode | 智能辅助编程，加速自动化脚本与工具原型开发 |
| N8N | 工作流自动化核心，连接不同应用的数据孤岛 |
| Podwise | AI 驱动的播客笔记工具，智能提取内容要点与知识管理 |
| Lovart | AI 艺术美学探索，为创意内容注入独特设计感 |

### 4. 项目展示 (Showcase)
6 个实战项目展示，支持展开/收起查看详情：

- **微信读书笔记一键同步 Notion** - 打破知识孤岛，使用 API 实现笔记结构化自动存储
- **英/法语精读精听练习 Web** - 外语学习辅助工具
- **东京旅行小助手** - AI 驱动的旅行规划工具
- **抖音文案一键改写** - 内容创作效率工具
- **我和宠物的毛毡效果合照** - 创意图像处理
- **手搓 AI 漫剧** - AIGC 创作实验

### 5. 联系我 (Contact)
- 邮箱: xzzilndk@foxmail.com
- Slogan: Let's build the future.

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
- Hero 主标题: 54px (桌面)
- Hero 副标题: 7.5vw → 5.8vw → 5.4vw (响应式)
- H2 (板块标题): 36px
- H3 (卡片标题): 28px
- 正文: 16px
- 导航: 13px

### 间距系统
- Section 间距: 120px
- Hero 顶部间距: 180px
- Hero 底部间距: 140px
- 卡片间距: 24px
- 导航高度: 60px

### 特殊样式
- Bento 卡片圆角: 28px
- 卡片悬停效果: translateY(-5px) + 阴影
- 滚动动画: reveal → active
- 强调文字: border-b border-orange-500

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
start Frii.html

# macOS
open Frii.html

# Linux
xdg-open Frii.html
```

或使用本地服务器：
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

然后访问 `http://localhost:8000/Frii.html`

### 自定义内容

#### 修改个人信息
编辑 HTML 中的以下部分：
- 标题：`<title>` 标签（Fri.AI | 内容运营 & AI 实践者）
- 导航栏：`.nav-content` 区域
- 简介部分：`#intro` section
- 核心价值主张：Hero 区域的 `<p>` 标签
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

#### 更新飞书链接
在 `链接.md` 文件中维护所有外部链接，同步更新到 HTML 中的对应位置：
- 查看简历: 链接.md 第1行
- 策略输出: 链接.md 第2行
- 账号操盘: 链接.md 第3行
- 数据分析: 链接.md 第4行

## 🛠️ 技术栈

- **HTML5** - 语义化标签
- **CSS3** - Flexbox/Grid、CSS 变量、动画
- **JavaScript (ES6+)** - DOM 操作、事件处理
- **Tailwind CSS** - 通过 CDN 引入（备用样式）
- **Lucide Icons** - 图标库

## 📝 核心功能实现

### 响应式导航
- 桌面端：水平导航菜单
- 移动端：汉堡菜单 + 下拉面板
- 点击链接后自动关闭移动端菜单

### 滚动动画
```javascript
// Intersection Observer 实现滚动入场动画
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) entry.target.classList.add('active');
    });
}, { threshold: 0.1 });
```

### Showcase 展开收起
- 点击卡片头部展开/收起详情
- 支持多个卡片独立展开
- 图标状态切换 (+ ↔ -)

## 📝 待办事项

- [ ] 添加深色模式切换
- [ ] 多语言支持（中/英）
- [ ] 博客板块
- [ ] 作品筛选功能
- [ ] SEO 优化
- [ ] 更多 AIGC 实验项目

## 📄 许可证

MIT License - 可自由使用和修改

## 👤 作者

**Fri.AI**
- 邮箱: xzzilndk@foxmail.com
- 定位: 内容运营 & AI 实践者
- 状态: Learning • Building • Open to Work

---

Built with Passion & AI © 2024 Fri.AI
