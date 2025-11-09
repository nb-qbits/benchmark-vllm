# benchmark-vllm

# vLLM Benchmark Suite

This repository provides a reproducible benchmark setup for evaluating **inference performance of large language models (LLMs)** using the [vLLM](https://github.com/vllm-project/vllm) framework.  
It allows you to compare throughput, latency, and resource utilization across models under controlled conditions.

---

## 🚀 Overview

This notebook (`Benchmark.ipynb`) automates running vLLM's benchmark tool to:
- Launch benchmarks for one or more models.
- Collect latency, throughput, and memory usage metrics.
- Summarize and visualize results for comparison.
- Support configurable batch sizes, sequence lengths, and tensor parallelism.

The goal is to help researchers and engineers quickly **evaluate performance trade-offs** between models or hardware setups.

---
## Usage

1. Clone this repository

``` git clone https://github.com/<your-username>/<your-repo>.git```

2. Run the cells sequentially

The notebook will automatically:
Launch the vLLM benchmark,
Record performance metrics,
Generate comparative plots.
