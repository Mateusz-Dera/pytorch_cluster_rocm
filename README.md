
# PyTorch Cluster ROCm

[![Version](https://img.shields.io/badge/version-1.6.3-orange.svg)](https://github.com/Mateusz-Dera/pytorch_cluster_rocm)

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
|OS|Ubuntu 24.04.2 LTS|
|Kernel|6.14.0-24-generic|
|ROCm|6.4.2|

## Instalation:
```bash
git clone https://github.com/Mateusz-Dera/pytorch_cluster_rocm
cd pytorch_cluster_rocm
pip install torch==2.7.1 torchvision==2.7.1 --index-url https://download.pytorch.org/whl/rocm6.3
pip install .
```
