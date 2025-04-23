# PyTorch Triton 3.3.0 (Custom Build)

This repository contains a custom wheel for `pytorch-triton` version **3.3.0**, built from source with compatibility for **CUDA 12.8** and tested with **vLLM**.

## Build Details

- **Version:** 3.3.0
- **Source Commit:** `git96316ce5`
- **CUDA Version:** 12.8
- **Platform:** Linux x86_64
- **Python Compatibility:** 3.8–3.12

## Installation

You can install the wheel directly using `pip`:

```bash
pip install pytorch_triton-3.3.0+git96316ce5-cp312-cp312-linux_x86_64.whl
```

> ⚠Make sure your environment uses the appropriate Python version and has compatible NVIDIA drivers.

## Related Projects

- [vLLM](https://github.com/vllm-project/vllm)
- [Triton by OpenAI](https://github.com/openai/triton)

## 📝otes

This build is provided as-is for convenience and testing. Built in a clean environment to isolate PyTorch and NVIDIA dependencies for reuse across multiple projects.
