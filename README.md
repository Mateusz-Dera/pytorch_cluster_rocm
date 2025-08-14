# PyTorch Cluster ROCm

[![Version](https://img.shields.io/badge/Version-1.6.3-orange.svg)](https://github.com/Mateusz-Dera/pytorch_cluster_rocm)

This is a fork of PyTorch Cluster adapted to work with ROCm and is used in https://github.com/Mateusz-Dera/ROCm-AI-Installer<br>
All code was generated automatically using hipify.<br>
Original repository: https://github.com/bachdj-px/pytorch_cluster<br>
Original README: https://github.com/Mateusz-Dera/pytorch_cluster_rocm/ORIGINAL_README.md

### Test platform:
|Name|Info|
|:---|:---|
|CPU|AMD Ryzen 9950X3D|
|GPU|AMD Radeon 7900XTX|
|RAM|64GB DDR5 6600MHz|
|Motherboard|ASRock B650E PG Riptide WiFi (BIOS 3.30)|
|OS|Debian 13|
|Kernel|6.14.0-27-generic|
|ROCm|6.4.2|

## Instalation:
```bash
git clone https://github.com/Mateusz-Dera/pytorch_cluster_rocm
cd pytorch_cluster_rocm
uv venv --python 3.12
source .venv/bin/activate
uv pip install torch==2.7.1 torchvision==0.22.1 pytorch-triton-rocm==3.3.1 triton==3.3.1 --index-url https://download.pytorch.org/whl/rocm6.4
uv pip install . # Ignore NVIDIA warnings
```
