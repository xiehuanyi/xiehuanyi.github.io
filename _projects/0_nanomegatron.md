---
layout: page
title: nanoMegatron
description: Minimal distributed training framework covering DDP, ZeRO, tensor, sequence, pipeline, and expert parallelism.
importance: 2
category: open-source
github: https://github.com/xiehuanyi/nanoMegatron
---

**Minimal Distributed Training Framework**

Implemented core distributed-training algorithms in a compact educational codebase.

- **Parallel training**: Built DDP, ZeRO-1/2/3, tensor parallelism, sequence parallelism, pipeline parallelism, and expert parallelism.
- **MoE pipeline**: Added a working SFT pipeline for Phi-tiny-MoE and GSM8K with MoE AllToAll dispatch.
- **Systems comparison**: Included benchmark logs against DeepSpeed and PyTorch FSDP-style sharding.
