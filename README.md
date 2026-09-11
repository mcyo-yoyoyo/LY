# 数智·变革 | Mcyo

个人站：[mcyo-yoyoyo.github.io/LY](https://mcyo-yoyoyo.github.io/LY/)

Mercy · 包容 / Courage · 勇敢 / Yearning · 热忱 / Onward · 前行。

深色单页。首页一排 4 张卡片，点开就是可运行的产品现场；Blogs 写文章；About 是自我介绍。上一版白底站点在 `archive/index.v1.html`。

## 页面

- **Home**：Work / Family / Life。封面在 `covers/`，条目在 `site/projects.json`
- **Blogs**：文章在 `notes/`，目录是 `notes/manifest.json`
- **About**：理念、数据、擅长、行业经历，数据在 `site/about.json`
- **Studio**：管理员后台，标签与顶部一致（Home / Blogs / About）。卡片可拖动改位置，点击弹出配置（名称、分类、简介、链接、换图、上移 / 下移 / 置顶 / 置底 / 隐藏 / 删除）。About 按前台版式所见即所得编辑

浏览读本仓库。Studio 保存时用本机 GitHub Token 写回上述文件，换电脑也能看到同一份数据。

整站是仓库根目录的 `index.html`（React 18 + Babel + Tailwind CDN）。本地预览在根目录起一个静态服务即可。
