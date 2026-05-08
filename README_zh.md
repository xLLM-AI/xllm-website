# xLLM Website

[English](./README.md) | [中文](./README_zh.md)

本仓库包含 `xLLM` 官网的前端代码。

它基于 [AstroWind](https://github.com/arthelokyo/astrowind) 模板构建，并已裁剪为一个专注于展示 `xLLM` 的网站。本仓库主要用于：

- 维护 xLLM 官网首页和视觉风格
- 管理导航、SEO 设置、文案和静态资源
- 支持本地开发、预览和生产构建

## 技术栈

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)

## 开发

在 macOS 上安装依赖环境：

```bash
# 安装 Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 安装 Node.js 和 npm
brew install node

# 验证 npm 是否安装成功
node -v
npm -v
```

开发网站：

```bash
git clone https://github.com/xLLM-AI/website.git
cd website

# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

默认本地访问地址：

```text
http://localhost:4321
```

## 在 VS Code / Cursor 中开发

这是一个 Astro 项目。在 VS Code 或 Cursor 中开发时，建议安装 Astro 扩展，以获得正确的 `.astro` 语法高亮、诊断和编辑器支持。

推荐扩展：

- [Astro VSCode Extension](https://open-vsx.org/extension/astro-build/astro-vscode)

如果你使用 Cursor，也同样建议安装该扩展。
