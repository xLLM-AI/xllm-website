# xLLM Website

[English](./README.md) | [中文](./README_zh.md)

This repository contains the frontend code for the `xLLM` website.

It is based on the [AstroWind](https://github.com/arthelokyo/astrowind) template and has been trimmed down into a focused site for presenting `xLLM`. The repository is mainly used to:

- maintain the xLLM website homepage and visual style
- manage navigation, SEO settings, copywriting, and static assets
- support local development, preview, and production builds

## Tech Stack

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)

## Development

Install npm on macOS:

```bash
# install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# install Node.js and npm
brew install node

# verify npm is installed
node -v
npm -v
```

Develop website:

```bash
git clone https://github.com/xLLM-AI/website.git
cd website

# install dependencies
npm install

# start development server
npm run dev
```

Default local address:

```text
http://localhost:4321
```

## Developing in VS Code / Cursor

This is an Astro project. In VS Code or Cursor, you should install the Astro extension for proper `.astro` syntax highlighting, diagnostics, and editor support.

Recommended extension:

- [Astro VSCode Extension](https://open-vsx.org/extension/astro-build/astro-vscode)

If you use Cursor, this extension is still recommended.
