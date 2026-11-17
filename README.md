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

## Publishing blog posts

Copy `src/content/post/_template.md` to a new Markdown or MDX file in the same directory. Its filename becomes the article URL, for example `my-post.md` → `/blog/my-post`. Keep the original template as a draft so the content loader can watch the directory before the first post is published.

```markdown
---
title: 'My post'
publishDate: 2026-11-17T00:00:00Z
author: 'xLLM Team'
type: 'blog' # blog (default) or news
excerpt: 'A short introduction for the article list.'
draft: true # Remove or set to false to publish
# image: '/images/blog/my-post.png' # Optional thumbnail and cover
---

Article content goes here.
```

Published posts appear newest first at `/blog` and `/zh/blog`, with search and Blog/News filters. Both language versions share article content and localize the surrounding interface. Drafts are excluded from the list and article routes. The blog displays an empty state until the first article is published.

## Developing in VS Code / Cursor

This is an Astro project. In VS Code or Cursor, you should install the Astro extension for proper `.astro` syntax highlighting, diagnostics, and editor support.

Recommended extension:

- [Astro VSCode Extension](https://open-vsx.org/extension/astro-build/astro-vscode)

If you use Cursor, this extension is still recommended.
