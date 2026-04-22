# Claude Theme for Typora

[English](#english) | 中文

---

一款灵感源自 [Claude.ai](https://claude.ai) 的 Typora 主题。以温暖的纸质米白为底，珊瑚橙作点缀，**衬线标题 + 无衬线正文** 的编辑感排版，还原 Claude 文档的阅读气质。

## 📸 预览

![Claude 主题预览](claude/screenshot.png)

> 📄 想看**完整的排版效果**（所有 Markdown 元素：多级标题、代码块、表格、任务列表、引用等）？
> 查看完整预览 PDF：[`claude/Typora_Claude_theme_test.pdf`](claude/Typora_Claude_theme_test.pdf)

## 🆕 v2 更新

本次版本是一次彻底的设计语言对齐，不只是调色：

- 🔤 **衬线标题** — 标题全部改用 Source Serif 4 / Charter / Georgia 衬线字体栈，Claude.ai 最标志性的"编辑器"气质来源
- ✒️ **`<em>` 衬线斜体** — 正文中的 _斜体_ 自动切换为衬线斜体，细节见品位
- 📏 **780px 最佳阅读行宽** — 从原来的 80% 收窄至 70 字符黄金阅读宽度
- 🎭 **极简 Blockquote** — 去掉底色与斜体，只留一条珊瑚橙左边框
- 📐 **扁平化阴影** — 页面卡片阴影从 `0 10px 25px` 压薄为 1px 描边，更贴近 Claude.ai 的扁平感
- 🎨 **更暖的纸质配色** — 背景、文字、边框全部重新调校，整体更接近真 Claude UI
- ✅ **修复 Checkbox** — 对齐 Typora 内置选择器优先级，解决了 v1 对号不显示的问题
- 🔘 **已完成任务文字弱化** — 视觉上更清晰地区分「待办 / 已完成」
- 🧵 **h1/h2 细线下划线、h5/h6 小标签化** — 层次感更分明
- 📊 **表格圆角化、行悬停高亮** — 去内竖线，只保留横线分隔

## ✨ 特性

- 🎨 **温暖的纸质配色** — 米白底 `#FAF7F0`，搭配 Claude 标志性的珊瑚橙 `#C15F3C` 作为强调色
- 🔤 **衬线 + 无衬线混排** — 标题衬线、正文无衬线、`<em>` 衬线斜体，编辑感十足
- 📝 **全面覆盖 Markdown 元素** — 标题、引用、代码、表格、任务列表等均经过精心设计
- 🧭 **侧边栏美化** — 文件列表与大纲项圆角高亮，选中态使用品牌色填充
- 🖱️ **精致交互细节** — 链接悬浮、checkbox 勾选动画、滚动条悬浮感、选中高亮等
- 🔤 **完善的字体栈** — 中英文兼顾，无需额外安装也能优雅降级

## 📦 安装

1. 下载 `claude.css` 文件
2. 打开 Typora → **偏好设置** → **外观** → **打开主题文件夹**
3. 将 `claude.css` 复制到主题文件夹
4. **完全退出 Typora**（托盘图标也要退）后重新打开
5. 在 **主题** 菜单中选择 **Claude**

> ⚠️ Typora 对 CSS 有缓存，**按 F5 或切换主题不一定会重新加载**，建议彻底重启。

## 🔤 推荐字体（可选但强烈推荐）

为了完整还原 Claude.ai 的质感，建议安装这两款免费字体：

| 字体               | 用途                   | 下载                                                             |
| ------------------ | ---------------------- | ---------------------------------------------------------------- |
| **Source Serif 4** | 衬线标题 / `<em>` 斜体 | [Google Fonts](https://fonts.google.com/specimen/Source+Serif+4) |
| **Inter**          | 正文无衬线             | [rsms.me/inter](https://rsms.me/inter/)                          |

不安装也能正常使用——字体栈会优雅降级到 Georgia + 系统字体。

## 🎨 配色方案

| 用途           | 色值      |
| -------------- | --------- |
| 主色（珊瑚橙） | `#C15F3C` |
| 外层背景       | `#F0EBE1` |
| 写作卡片背景   | `#FAF7F0` |
| 侧边栏背景     | `#EBE6DB` |
| 代码块背景     | `#EEE7DA` |
| 正文色         | `#3D3929` |
| 标题色         | `#1F1B17` |
| 次要文字       | `#78726A` |
| 边框           | `#E0D9CA` |

## 🛠️ 自定义

修改 `claude.css` 顶部 `:root` 中的 CSS 变量即可微调：

```css
:root {
  --claude-primary: #c15f3c; /* 主色调 */
  --bg-color: #f0ebe1; /* 外层背景 */
  --page-bg: #faf7f0; /* 写作卡片背景 */
  --text-color: #3d3929; /* 正文颜色 */
  --heading-color: #1f1b17; /* 标题颜色 */

  /* 想换字体？改这里 */
  --font-serif: 'Source Serif 4', 'Georgia', serif;
  --font-sans: 'Inter', 'PingFang SC', sans-serif;
  --font-mono: 'JetBrains Mono', 'Consolas', monospace;
}
```

## 📄 许可

MIT License — 自由使用与修改。

---

<a name="english"></a>

# Claude Theme for Typora

[中文](#) | English

---

A Typora theme inspired by [Claude.ai](https://claude.ai). Warm paper off-white base, coral-orange accents, and **serif headings paired with sans-serif body** — a faithful recreation of Claude's editorial reading aesthetic.

## 📸 Preview

![Claude Theme Preview](claude/screenshot.png)

> 📄 Want to see **the full styling in action** (all Markdown elements: headings at every level, code blocks, tables, task lists, blockquotes)?
> Check out the complete preview PDF: [`claude/Typora_Claude_theme_test.pdf`](claude/Typora_Claude_theme_test.pdf)

## 🆕 What's New in v2

This is a full design-language realignment, not just a recolor:

- 🔤 **Serif headings** — Source Serif 4 / Charter / Georgia stack; the signature "editorial" feel of Claude.ai
- ✒️ **Serif italic `<em>`** — Inline emphasis automatically renders in serif italic
- 📏 **780px reading width** — Narrowed from 80% to the golden ~70-character measure
- 🎭 **Minimal blockquotes** — Background and italics removed; only a coral left border remains
- 📐 **Flattened shadows** — Page card shadow reduced from heavy `0 10px 25px` to a subtle 1px ring
- 🎨 **Warmer paper palette** — Background, text, and borders recalibrated to match Claude's UI
- ✅ **Checkbox fix** — Resolved Typora's built-in selector specificity issue from v1
- 🔘 **Completed tasks fade** — Finished todos get dimmed text for clearer state
- 🧵 **h1/h2 hairline underlines, h5/h6 as small-caps labels** — Clearer hierarchy
- 📊 **Rounded tables with row hover** — No inner vertical lines, cleaner grid

## ✨ Features

- 🎨 **Warm paper palette** — Off-white base `#FAF7F0` with Claude's signature coral `#C15F3C`
- 🔤 **Serif + sans mix** — Serif headings, sans body, serif italics — full editorial treatment
- 📝 **Comprehensive Markdown coverage** — Headings, blockquotes, code, tables, task lists, all polished
- 🧭 **Refined sidebar** — Rounded highlights and brand-filled active state
- 🖱️ **Thoughtful micro-interactions** — Link hover, checkbox animation, floating scrollbar, selection
- 🔤 **Graceful font fallbacks** — Works well across systems with or without optional fonts

## 📦 Installation

1. Download `claude.css`
2. Open Typora → **Preferences** → **Appearance** → **Open Theme Folder**
3. Copy `claude.css` into the theme folder
4. **Fully quit Typora** (including the tray icon) and relaunch
5. Select **Claude** from the **Themes** menu

> ⚠️ Typora caches CSS — pressing F5 or toggling themes may not reload it. A full restart is recommended.

## 🔤 Recommended Fonts (Optional but Highly Recommended)

To fully recreate the Claude.ai feel, install these two free fonts:

| Font               | Role                            | Download                                                         |
| ------------------ | ------------------------------- | ---------------------------------------------------------------- |
| **Source Serif 4** | Serif headings & `<em>` italics | [Google Fonts](https://fonts.google.com/specimen/Source+Serif+4) |
| **Inter**          | Sans-serif body                 | [rsms.me/inter](https://rsms.me/inter/)                          |

Skipping these is fine — the font stack gracefully falls back to Georgia + system fonts.

## 🎨 Color Scheme

| Purpose         | Value     |
| --------------- | --------- |
| Primary (Coral) | `#C15F3C` |
| Outer Canvas    | `#F0EBE1` |
| Writing Card    | `#FAF7F0` |
| Sidebar         | `#EBE6DB` |
| Code Background | `#EEE7DA` |
| Body Text       | `#3D3929` |
| Heading Text    | `#1F1B17` |
| Secondary Text  | `#78726A` |
| Border          | `#E0D9CA` |

## 🛠️ Customization

Edit the CSS variables in the `:root` block at the top of `claude.css`:

```css
:root {
  --claude-primary: #c15f3c; /* Accent color */
  --bg-color: #f0ebe1; /* Outer canvas */
  --page-bg: #faf7f0; /* Writing card */
  --text-color: #3d3929; /* Body text */
  --heading-color: #1f1b17; /* Heading text */

  /* Swap fonts here */
  --font-serif: 'Source Serif 4', 'Georgia', serif;
  --font-sans: 'Inter', 'PingFang SC', sans-serif;
  --font-mono: 'JetBrains Mono', 'Consolas', monospace;
}
```

## 📄 License

MIT License — free to use and modify.
