---
title: Python 与 Conda 环境配置
---

<div class="content" markdown="1">

# Python 与 Conda 环境配置

## 推荐原则

- 一个项目对应一个 Conda 环境。
- 环境名尽量包含项目或任务信息。
- 重要实验保留 `environment.yml` 或 `requirements.txt`。

## 基础命令

```bash
conda create -n octa-ai python=3.10
conda activate octa-ai
conda install numpy scipy scikit-image matplotlib
pip install opencv-python tqdm
```

## 导出环境

```bash
conda env export > environment.yml
pip freeze > requirements.txt
```

</div>
