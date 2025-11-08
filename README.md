# DKT + SMI: Self-Monitoring Index for Deep Knowledge Tracing

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)

**Self-Monitoring Index (SMI)**: A **parameter-free**, interpretable metacognitive feature that enhances Deep Knowledge Tracing by modeling students' self-monitoring behavior from behavioral logs.

> **+3.27% relative AUC improvement** on ASSISTment 2017 ($p < 0.001$)  
> **Zero trainable parameters added**  
> **Fully reproducible** on public datasets

---

## Paper
> **"Self-Monitoring Index: Enhancing Deep Knowledge Tracing with Metacognitive Behavioral Signals"**  
> Navid Rezaei Melal  
> *Under review*  
> [[PDF](https://arxiv.org/abs/XXXX.XXXXX)] (coming soon)

---

## Results

| Model | ASSISTment 2017 (Test AUC) | Δ vs Baseline |
|------|----------------------------|----------------|
| DKT (baseline) | 0.8187 | — |
| DKT + attempt/rt | 0.8381 | +2.37% |
| **DKT + SMI (ours)** | **0.8393** | **+3.27%** |

> Statistical significance: $p < 0.001$ (bootstrap, 1000 iterations)

---

## Installation

```bash
# Clone the repository
git clone https://github.com/NavidRezaei/dkt-smi.git
cd dkt-smi

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
