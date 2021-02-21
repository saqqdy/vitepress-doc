---
home: true
heroImage: /images/gitmars.png
heroAlt: Logo image
heroText: vitepress-doc
tagline: 基于vitepress的组件文档库
actionText: 开始 →
actionLink: /idea/
features:
    - title: 简洁至上
      details: 以 Markdown 为中心的项目结构，以最少的配置帮助你专注于写作。
    - title: Vue驱动
      details: 享受 Vue + webpack 的开发体验，在 Markdown 中使用 Vue 组件，同时可以使用 Vue 来开发自定义主题。
    - title: 高性能
      details: VitePress 为每个页面预渲染生成静态的 HTML，同时在页面被加载的时候，将作为 SPA 运行。
footer: MIT Licensed | Copyright © 2018-present saqqdy
---

```shell
# 安装
yarn global add vitepress # 或者：npm install -g vitepress

# 新建一个 markdown 文件
echo '# Hello VitePress!' > README.md

# 开始写作
vitepress dev .

# 构建静态文件
vitepress build .
```
