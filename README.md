# WS-Mamba: Weak Signal Mamba Unmixing

A lightweight hyperspectral unmixing framework that leverages Mamba state-space models and simple spectral–spatial fusion to better identify **low-reflectance, sparse endmembers**. **Code coming soon.**

## Features

* Weak-signal–aware normalization and losses (RMSE/SAD).
* Mamba (SSM) + vision branch for long-range spectral–spatial dependencies.
* Plug-and-play feature branches (conv/wavelet/transformer-style).
* Compatible with common HSI datasets (e.g., Samson, APEX, synthetic).

## Roadmap

* [ ] Minimal reproducible training & eval
* [ ] Ablations + visualizations
* [ ] Pretrained weights & logs
* [ ] Tech report

## Acknowledgements

* Mamba Vision: [https://github.com/NVlabs/MambaVision](https://github.com/NVlabs/MambaVision)
* DeepTrans-HSU: [https://github.com/preetam22n/DeepTrans-HSU](https://github.com/preetam22n/DeepTrans-HSU)

