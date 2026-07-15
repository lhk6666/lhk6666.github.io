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
| 头像 | 替换 `assets/media/authors/me.jpg` |
| 发表论文 | 在 `content/publications/<论文名>/index.md` 新建（可用 `hugo new` 或参考 [文档](https://docs.hugoblox.com/)）|
| 论文演示动图 | 放 `content/publications/<论文名>/featured.gif`（≤5MB，800×450 为宜；GIF 不会被压缩，中英文共用）|
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

- [ ] `data/authors/me.yaml`：Google Scholar / ORCID / LinkedIn 链接（取消注释填入）

注：本站有意不提供 CV 下载。若日后想加，在 `content/_index.md` 的 `resume-biography-3`
板块下加回 `button:` 字段，并把 PDF 放到 `static/uploads/`。
