# yangliu-cooper.github.io

Yang Liu's personal website, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, hosted by GitHub Pages.

## 常用修改位置

- 个人信息/域名:`_config.yml`
- 首页简介:`_pages/about.md`
- 社交链接:`_data/socials.yml`
- 新闻动态:`_news/`
- 论文列表:`_bibliography/papers.bib`
- CV 内容:`assets/json/resume.json`(或 `_data/cv.yml`)
- 头像:替换 `assets/img/prof_pic.jpg`

本地修改后 push 到 `main` 分支,GitHub Actions 会自动构建并发布。
