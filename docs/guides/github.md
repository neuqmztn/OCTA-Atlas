---
title: GitHub 使用教程
---

<div class="content" markdown="1">

# GitHub 使用教程

## 适用场景

用于组内代码仓库、资料网站、论文附录代码和实验记录的版本管理。

## 推荐流程

1. 创建或 Fork 仓库。
2. 使用 `git clone` 拉取到本地。
3. 新建分支完成修改。
4. 使用 `git add`、`git commit`、`git push` 提交。
5. 通过 Pull Request 合并。

## 常用命令

```bash
git status
git add .
git commit -m "docs: update paper note"
git push origin main
```

## 组内约定

- 文档修改使用 `docs:` 前缀。
- 实验代码使用 `exp:` 前缀。
- 修复问题使用 `fix:` 前缀。
- 每次提交只解决一个明确问题。

</div>
