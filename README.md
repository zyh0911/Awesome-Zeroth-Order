<div align="center">
    <h1 style="display: inline-flex; align-items: center;">
        <img src="img/static/icon.png" alt="icon" style="width: 32px; height: 32px; margin-right: 8px;">
        Awesome Zeroth-Order
    </h1>
</div>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="https://github.com/yihangzu/Awesome-Zeroth-Order/stargazers"><img src="https://img.shields.io/github/stars/yihangzu/Awesome-Zeroth-Order?style=social" alt="GitHub stars"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
    <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
</p>

This repository manually collects works in **zeroth-order optimization**, which will be continuously updated.


## 📖 News
**[2025/12/18]** We release the initial version!

## 🌟 Overview
Here, we classify all the zeroth-order optimization based methods into three categories, and sort by date in ascending order:
- [📖 News](#-news)
- [🌟 Overview](#-overview)
- [🤝 Contributing](#-contributing)
- [🔥 Methods](#-methods)
  - [Algorithmic Improvement](#algorithmic-improvement)
  - [Hardware Acceleration](#hardware-acceleration)
  - [Application](#application)


## 🤝 Contributing
We warmly welcome contributions of excellent resources you find via **pull request**. Please follow the instruction in **CONTRIBUTING.md** if you want to make one.
Additionally, if you want to have any other issue, please add my wechat: Aquila-911.

## 🔥 Methods

### Algorithmic Improvement

| Year | Paper Title | Affiliation | Conference | Code |
|:---:|---|---|:---:|:---:|
| 2023 | [Fine-Tuning Language Models with Just Forward Passes](https://proceedings.neurips.cc/paper_files/paper/2023/file/a627810151be4d13f907ac898ff7e948-Paper-Conference.pdf) | Princeton | NIPS | [Github](https://github.com/princeton-nlp/MeZO) |
| 2024 | [AdaZeta: Adaptive Zeroth-Order Tensor-Train Adaption for Memory-Efficient Large Language Models Fine-Tuning](https://aclanthology.org/2024.emnlp-main.56.pdf) | UCSB/Amazon | EMNLP | [Github](https://github.com/yifanycc/AdaZeta) |
| 2024 | [Variance-reduced zeroth-order methods for fine-tuning language models](https://arxiv.org/pdf/2404.08080) | Amazon | ICML | [Github](https://github.com/amazon-science/mezo_svrg) |
| 2024 | [DeepZero: Scaling up Zeroth-Order Optimization for Deep Model Training](https://openreview.net/pdf?id=qBWhjsNPEY) | MSU | ICLR | [Github](https://github.com/OPTML-Group/DeepZero) |
| 2024 | [Revisiting Zeroth-Order Optimization for Memory-Efficient LLM Fine-Tuning: A Benchmark](https://arxiv.org/pdf/2402.11592) | UNC | ICML | [Github](https://github.com/ZO-Bench/ZO-LLM) |
| 2024 | [ReLIZO: Sample Reusable Linear Interpolation-based Zeroth-order Optimization](https://proceedings.neurips.cc/paper_files/paper/2024/file/1b3750390ca8b931fb9ca988647940cb-Paper-Conference.pdf) | SJTU | NIPS | [Github](https://github.com/Thinklab-SJTU/ReLIZO) |
| 2025 | [MaZO: Masked zeroth-order optimization for multi-task fine-tuning of large language models](https://arxiv.org/pdf/2502.11513?) | UCSB/Amazon | EMNLP |N/A |
| 2025 | [OAT-Rephrase: Optimization-Aware Training Data Rephrasing for Zeroth-Order LLM Fine-Tuning](https://arxiv.org/pdf/2506.17264) | Stevens Institute of Technology | Arxiv |N/A |
| 2025 | [HELENE: Hessian Layer-wise Clipping and Gradient Annealing for Accelerating Fine-Tuning LLM with Zeroth-Order Optimization](https://arxiv.org/pdf/2411.10696) | University of Georgia | EMNLP |N/A |
| 2025 | [Harmony in divergence: Towards fast, accurate, and memory-efficient zeroth-order llm fine-tuning](https://arxiv.org/pdf/2502.03304) | University of Georgia | NIPS |N/A |
| 2025 | [On the Optimal Construction of Unbiased Gradient Estimators for Zeroth-Order Optimization](https://arxiv.org/pdf/2510.19953) | UMD | NIPS | [Github](https://github.com/Skilteee/DiZO) |
| 2025 | [Second-Order Fine-Tuning without Pain for LLMs: a Hessian Informed Zeroth-Order Optimizer](https://arxiv.org/pdf/2402.15173) | A*star | ICLR | [Github](https://github.com/Yanjun-Zhao/HiZOO) |
| 2025 | [Enhancing Zeroth-order Fine-tuning for Language Models with Low-rank Structures](https://arxiv.org/pdf/2410.07698) | PKU | ICLR | [Github](https://github.com/optsuite/LOZO) |
| 2025 | [PaZO: Preconditioned Accelerated Zeroth-Order Optimization for Fine-Tuning LLMs](https://openreview.net/pdf?id=b2IU6QOOfo) | PKU | NIPS | [Github](https://github.com/thos314/PaZO-Preconditioned-Accelerated-Zeroth-Order-Optimization-for-Fine-Tuning-LLMs) |
| 2025 | [PseuZO: Pseudo-Zeroth-Order Algorithm for Training Deep Neural Networks](https://openreview.net/pdf?id=tM4cHBD7kD) | PKU | NIPS | [Github](https://github.com/YangBigMn/PseuZO) |
| 2025 | [MUZO: Leveraging Multiple Queries and Momentum for Zeroth-Order Fine-Tuning of Large Language Models](https://aclanthology.org/2025.emnlp-main.432.pdf) | SJTU | EMNLP |N/A |

### Hardware Acceleration

| Year | Paper Title | Affiliation | Conference | Code |
|:---:|---|---|:---:|:---:|
| 2025 | [QuZO: Quantized zeroth-order fine-tuning for large language models](https://arxiv.org/pdf/2502.12346) | UCSB/Amazon | EMNLP | N/A |
| 2025 | [MobiZO: Enabling Efficient LLM Fine-Tuning at the Edge via Inference Engines](https://arxiv.org/pdf/2409.15520?) | Amazon | EMNLP | [Github](https://github.com/leigao97/MobiZO) |
| 2025 | [Zeroth-Order Fine-Tuning of LLMs with Transferable Static Sparsity](https://openreview.net/pdf?id=myYzr50xBh) | Stevens Institute of Technology | ICLR | [Github](https://github.com/GarlGuo/SensZOQ)* |
| 2025 | [Perturbation-efficient zeroth-order optimization for hardware-friendly on-device training](https://arxiv.org/pdf/2504.20314) | University of Georgia | ICCAD |  N/A |
| 2025 | [Memory-Efficient Backpropagation for Fine-Tuning LLMs on Resource-Constrained Mobile Devices](https://aclanthology.org/2025.emnlp-industry.52.pdf) | Apple | EMNLP | [Github](https://github.com/apple/ml-mebp) |
| 2025 | [QZO: Fine-tuning Quantized Neural Networks with Zeroth-order Optimization](https://arxiv.org/pdf/2505.13430) | HKBU | arxiv | [Github](https://github.com/maifoundations/QZO) |
| 2025 | [Sparse MeZO: Less Parameters for Better Performance in Zeroth-Order LLM Fine-Tuning](https://arxiv.org/pdf/2402.15751) | NUS | ICLR | N/A |
| 2026 | [FZOO: Fast Zeroth-Order Optimizer for Fine-Tuning Large Language Models towards Adam-Scale Speed](https://arxiv.org/abs/2506.09034) | A*star | Arxiv | [Github](https://github.com/DKmiyan/FZOO) |

  *: Empty GitHub repository

### Application

| Year | Paper Title | Affiliation | Conference | Code |
|:---:|---|---|:---:|:---:|
| 2017 | [ZOO: Zeroth Order Optimization based Black-box Attacks to Deep Neural Networks without Training Substitute Models](https://arxiv.org/pdf/1708.03999) | IBM/UCD | AIsec | [Github](https://github.com/huanzhang12/ZOO-Attack) |
| 2025 | [Towards memory-efficient and sustainable machine unlearning on edge using zeroth-order optimizer](https://dl.acm.org/doi/pdf/10.1145/3716368.3735273) | University of Georgia | GLSVLSI |  N/A |
| 2025 | [Private Fine-tuning of Large Language Models with Zeroth-order Optimization](https://arxiv.org/pdf/2401.04343) | Apple | TMLR | N/A |
| 2025 | [ZO-ASR: Zeroth-Order Fine-Tuning of Speech Foundation Models without Back-Propagation](https://arxiv.org/pdf/2512.01267) | SJTU | ASRU | [Github](https://github.com/Gatsby-web/ZO-ASR) |
| 2026 | [Branch, or Layer? Zeroth-Order Optimization for Continual Learning of Vision-Language Models](https://arxiv.org/pdf/2506.12409) | NJU | AAAI | N/A |
| 2026 | [More Than Memory Savings: Zeroth-Order Optimization Mitigates Forgetting in Continual Learning](https://arxiv.org/pdf/2510.21019)| UNCC | WACV | [Github](https://arxiv.org/pdf/2510.21019)|
