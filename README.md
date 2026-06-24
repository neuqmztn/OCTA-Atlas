# OCTA-Atlas

OCTA-Atlas 是面向 OCTA、血管分析与医学影像智能分析的课题组知识库与研究导航平台。

## 网站结构

网站源码位于 `docs/` 目录，适合直接使用 GitHub Pages 发布。

```text
OCTA-Atlas/
├── docs/
│   ├── index.md
│   ├── guides/
│   ├── octa-basics/
│   ├── papers/
│   ├── ideas/
│   ├── projects/
│   ├── tools/
│   └── templates/
├── README.md
└── .gitignore
```

## GitHub Pages 发布方式

1. 将本目录推送到 GitHub 仓库。
2. 打开仓库 `Settings -> Pages`。
3. Source 选择 `Deploy from a branch`。
4. Branch 选择 `main`，Folder 选择 `/docs`。
5. 保存后等待 GitHub Pages 构建完成。

如果仓库名不是 `OCTA-Atlas`，请修改 `docs/_config.yml` 中的 `baseurl`。

## 内容维护建议

- 常用教程放在 `docs/guides/`。
- OCTA 与医学影像基础资料放在 `docs/octa-basics/`。
- 论文阅读笔记按研究方向放在 `docs/papers/`。
- 未完成但有潜力的想法放在 `docs/ideas/`。
- 统一模板放在 `docs/templates/`。
