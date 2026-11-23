# 汉火 (Hanhuo Org)

> 中华古文字视觉识别、历史汉语三代拟音与古诗文唱吟开源工程 · Open-source AI tools for ancient Chinese scripts, historical phonology TTS, and classical chanting.

---

## 核心开源项目

| 项目 | 在线演示 | 简介 | 权重与数据集 |
| :--- | :---: | :--- | :--- |
| **[`hanhuo-dadian`](https://github.com/hanhuo-org/hanhuo-dadian)** | — | **汉火大典总仓**：以 Git Submodule 统一汇聚全部子项目，支持 `git clone --recursive` 一键拉取 | — |
| **[`shizi`](https://github.com/hanhuo-org/shizi)** | [xing.hanhuo.org](https://xing.hanhuo.org) | **汉火识字（Clean V10）**：甲骨文、西周金文、战国楚简、汉代玺印及历代碑帖书法浏览器端 100% 离线古文字识别与完整训练工程（21.7 万多原型 INT8 向量库 + Rust-WASM + CenterNet） | [Release `v10`](https://github.com/hanhuo-org/shizi/releases/tag/v10) · [HF Dataset](https://huggingface.co/datasets/hanhuo-org/hanhuo-shizi-dataset) |
| **[`niyin`](https://github.com/hanhuo-org/niyin)** | [yin.hanhuo.org](https://yin.hanhuo.org) | **汉火拟音（v1.0）**：上古 / 中古（切韵）/ 近古（中原音韵）三代历史汉语拟音 TTS（ZipVoice + QAT INT8 + WebGPU/WASM 离线工作台）与唐调《诗经》/古文/辞赋 44.1kHz 男女双声部唱吟引擎 | [Release `v1.0`](https://github.com/hanhuo-org/niyin/releases/tag/v1.0) · [HF Models](https://huggingface.co/hanhuo-org/hanhuo-niyin-models) · [HF Dataset](https://huggingface.co/datasets/hanhuo-org/hanhuo-niyin-dataset) |

---

## Hugging Face 开源模型与数据集

- **组织主页**：[huggingface.co/hanhuo-org](https://huggingface.co/hanhuo-org)
- **预训练模型**：[`hanhuo-org/hanhuo-niyin-models`](https://huggingface.co/hanhuo-org/hanhuo-niyin-models)
- **训练数据集**：[`hanhuo-org/hanhuo-shizi-dataset`](https://huggingface.co/datasets/hanhuo-org/hanhuo-shizi-dataset) · [`hanhuo-org/hanhuo-niyin-dataset`](https://huggingface.co/datasets/hanhuo-org/hanhuo-niyin-dataset)
