---
title: OCTA graph-to-token 接口
---

<div class="content" markdown="1">

# OCTA graph-to-token 接口

## 问题背景

OCTA 血管天然具有图结构，但 Transformer 通常处理规则 token 序列。如何把血管图结构转成可学习 token，是值得探索的接口问题。

## 初步想法

以血管分叉点、端点、局部骨架片段或区域图为基本单元，构建结构 token，并与图像 patch token 融合。

</div>
