# lhk6666.github.io

Personal academic homepage of Haokun Liu, built with [Hugo Blox](https://hugoblox.com/) (Academic CV template), bilingual (English / 中文).

Live site: https://lhk6666.github.io/ (English) · https://lhk6666.github.io/zh/ (中文)

## 如何更新网站

推送到 `main` 分支后，GitHub Actions 会自动构建并部署，约 2 分钟后生效。

### 常用修改位置

| 想改什么 | 改哪个文件 |
|---|---|
| 个人信息、教育经历、链接（英文） | `data/authors/me.yaml` |
| 个人信息（中文覆盖） | `data/zh/authors/me.yaml` |
| 首页板块与文字（英文 / 中文） | `content/_index.md` / `content/_index.zh.md` |
| 头像 | 替换 `assets/media/authors/me.png` |
| 简历 PDF | 替换 `static/uploads/resume.pdf` |
| 发表论文 | 在 `content/publications/<论文名>/index.md` 新建（可用 `hugo new` 或参考 [文档](https://docs.hugoblox.com/)）|
| 新闻动态 | 在 `content/blog/<标题>/index.md` 新建，中文版为 `index.zh.md` |
| 学术报告 | `content/events/` |
| 项目 | `content/projects/` |
| 导航菜单（英文 / 中文） | `config/_default/menus.yaml` / `config/_default/languages.yaml` |
| 主题颜色、字体 | `config/_default/params.yaml` |

### 本地预览

需要 Hugo extended ≥ 0.164、Go、Node.js：

```bash
npm install        # 首次需要（安装 TailwindCSS 等）
hugo server        # 打开 http://localhost:1313 （中文 /zh/）
```

### 待完善（TODO）

- [ ] `data/authors/me.yaml`：真实的学位、教育经历、Google Scholar / ORCID 链接
- [ ] `data/zh/authors/me.yaml`：中文姓名
- [ ] 替换占位头像 `assets/media/authors/me.png` 和简历 `static/uploads/resume.pdf`
- [ ] 添加自己的论文到 `content/publications/`
