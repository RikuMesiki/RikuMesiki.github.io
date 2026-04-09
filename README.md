# Hexo + GitHub Pages Blog

This directory is ready to be used as your blog source repository.

## Local development

Install dependencies:

```bash
npm install
```

Start the local server:

```bash
npm run server
```

Default preview URL:

```text
http://localhost:4000
```

## Common commands

Create a new post:

```bash
npm run new:post -- "Post title"
```

Create a new page:

```bash
npm run new:page -- "about"
```

Build static files:

```bash
npm run build
```

Clean generated files:

```bash
npm run clean
```

## Deploy to GitHub Pages

1. Create a GitHub repository, preferably named `your-github-username.github.io`.
2. Push this directory to the `main` branch of that repository.
3. Open the repository `Settings` -> `Pages`.
4. Set `Build and deployment` to `GitHub Actions`.
5. Push again if needed. The workflow will build and publish your site automatically.

## Update before publishing

Edit `_config.yml` and replace:

```yml
title: Your Blog Name
author: Your Name
url: https://your-github-username.github.io
```
