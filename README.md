# DKT + SMI: Self-Monitoring Index for Deep Knowledge Tracing

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)
)

> **A parameter-free metacognitive signal** that improves DKT by **+3.27% AUC** on ASSISTment 2017 ($p < 0.001$) — **without adding any trainable parameters**.

---

## Paper
**"Self-Monitoring Index: Enhancing Deep Knowledge Tracing with Metacognitive Behavioral Signals"**  
Navid Rezaei Melal  
*Under review*  
[[PDF](https://arxiv.org/abs/XXXX.XXXXX)] (coming soon)

---

## Key Results (ASSISTment 2017)

| Model                  | Test AUC | Δ vs Baseline |
|------------------------|---------:|---------------|
| DKT (baseline)         | 0.8187   | —             |
| DKT + attempt/rt       | 0.8381   | +2.37%        |
| **DKT + SMI (ours)**   | **0.8393** | **+3.27%**    |

> **Statistical significance:** $p < 0.001$ (bootstrap, 1000 iterations)

---

## Installation

```bash
git clone https://github.com/NavidRezaei/dkt-smi.git
cd dkt-smi
pip install -r requirements.txt
