# PCsmiles.github.io

彭城的学术个人主页，基于 [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)（MIT License）搭建。

网址：https://pcsmiles.github.io

## 怎么改

| 想改什么 | 改哪个文件 |
|---|---|
| 头像 | `images/avatar.jpg`（换成同名的方图即可） |
| 姓名、简介、邮箱、GitHub 链接 | `_config.yml` 里的 `author:` 段 |
| 网页标题、搜索引擎描述 | `_config.yml` 里的 `title:` / `description:` |
| 正文（新闻 / 专利 / 获奖 / 教育 / 项目） | `_pages/about.md` |
| 左侧导航目录 | `_data/navigation.yml` |

改完保存 → 提交 → 推送，GitHub 会自动重新构建（约 1 分钟）：

```bash
git add -A && git commit -m "update" && git push
```

## 本地预览（可选，需要装 Ruby）

```bash
bundle install && bundle exec jekyll serve
```
然后浏览器打开 http://127.0.0.1:4000
