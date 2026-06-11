---
layout: page
title: nanoSGLang
description: Minimal high-performance LLM serving engine in Python and PyTorch.
importance: 1
category: open-source
github: https://github.com/xiehuanyi/nanoSGLang
---

**Minimal LLM Serving Engine**

Built a compact serving engine from scratch in Python/PyTorch for studying the systems behind production LLM inference.

- **Serving stack**: Implemented continuous batching, chunked prefill, paged KV cache, prefix-sharing radix cache, streaming API, and request-level metrics.
- **Kernel integration**: Integrated FlashInfer paged attention and fused operators for efficient inference.
- **Benchmark**: Reached 3469 tok/s on Qwen2.5-0.5B with an RTX A5000 in the referenced workload.
