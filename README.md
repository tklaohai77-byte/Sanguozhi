# 《三国志》全本 · 全注 · 全译（免费在线阅读版）

西晋 陈寿 撰 · 南朝宋 裴松之 注 · 简体全本（65 卷）

- 每卷一个独立 HTML：`v01.html` ~ `v65.html`，含原文、裴注、现代注释、逐段白话翻译
- 首页 `index.html`（封面/凡例/简介/目录）、附录 `appendix.html`
- 保留全部阅读功能：卷内分页、页码跳转条、原文/裴注折叠、"仅原文"模式、键盘左右翻页、移动端自适应

## 部署到 GitHub Pages

1. 新建仓库（如 `sanguozhi`），把本目录下所有文件（index.html、appendix.html、v01~v65.html、sitemap.xml、robots.txt）上传到仓库根目录；
2. 仓库 Settings → Pages → Source 选 `main` 分支 / (root)，保存；
3. 发布后把 `build_ghpages.py` 里的 `SITE_BASE` 改成你的真实地址（如 `https://你的用户名.github.io/sanguozhi/`），重新运行 `python3 build_ghpages.py`，把更新后的文件再次上传——这样 canonical 与 sitemap 才是正确域名。

## 版权与授权

本书由「冷趣三国」运用豆包整理制作，免费分享，供学习交流；欢迎转载，请注明出处；未经许可不得用于商业用途。

《三国志》原文（陈寿撰、裴松之注）为公有领域；本书的白话翻译与现代注释由整理者享有权利，按上述授权条款免费分享。
