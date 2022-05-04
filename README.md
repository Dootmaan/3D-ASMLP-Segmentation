# U-shaped 3D ASMLP for Medical Image Segmentation

This repo is mainly built on ICLR2022 paper [*ASMLP: An Axial Shifted MLP Architecture for Vision*](https://github.com/svip-lab/AS-MLP). Personally i think it is a very elegant pure-MLP framework (works in an "axial convolution" way) that worth an experiment.

I turned the AS-MLP into 3D version and built a U-shaped network based on it (with skip connection). You can directly copy the "model" folder to anywhere and perform segmentation with "from model.asmlp import Med_ASMLP". The network still cannot surpass ordinary CNNs or Vision Transformers, but remember it is a **PURE-MLP** network for **DENSE PREDICTION** that doesnt require too much GPU memory.