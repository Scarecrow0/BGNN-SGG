# BGNN-SGG
[![LICENSE](https://img.shields.io/badge/license-MIT-green)](https://github.com/KaihuaTang/Scene-Graph-Benchmark.pytorch/blob/master/LICENSE)
[![Python](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/)
![PyTorch](https://img.shields.io/badge/pytorch-1.4.0-%237732a8)

Our paper [Bipartite Graph Network with Adaptive Message Passing for Unbiased Scene Graph Generation](https://arxiv.org/abs/2104.00308) has been accepted by CVPR 2021.

We have release the related code in [PySGG project](https://github.com/SHTUPLUS/PySGG) with other SGG models. Feel free to play with the PySGG


### VG
| Model(SGGen) | mR@50 | mR@100 | R@50 | R@100 | head | body | tail |
|--------------|:-----:|:------:|:----:|:-----:|------|------|------|
| BGNN         |  10.9 |  13.55 | 29.8 |  34.6 | 33.4 | 13.4 | 6.4  |


### OIv6
| Model(SGGen) | mR@50 | R@50 | wmAP_rel | wmAP_phr | score_wtd |
|---|:---:|:---:|:---:|:---:|---|
| BGNN | 41.71 | 74.96 | 33.83 | 34.87 | 42.47 |
