# MeTU: MobileViT-based U-Net for Efficient Edge Segmentation

This repository hosts the official project page for **MeTU**, a lightweight semantic segmentation model optimized for resource-constrained edge devices. 



## 🚀 [View Live Project Page](https://eastlaw13.github.io/MeTU_project_page/)

---

## 📌 Project Summary
**MeTU** is a hybrid segmentation architecture that combines the global context representation of **MobileViT** with the high-resolution spatial recovery of a **U-Net** decoder. 

Key objectives of this project include:
* **High Efficiency:** Achieving real-time performance on ARM-based CPUs (Raspberry Pi 4B).
* **Robustness:** Maintaining segmentation stability under environmental noise and diverse weather conditions (Cityscapes-C).
* **Spatial Precision:** Enhancing boundary recovery for small objects through multi-scale feature fusion.

## 📊 Key Results at a Glance
* **Cityscapes:** 73.46% mIoU (with 45% fewer parameters than Segformer-b0).
* **PASCAL VOC 2012:** 70.31% mIoU (+9.23%p over pure Transformer baselines).
* **Edge Performance:** 12.17 FPS on Raspberry Pi 4B (ONNX Runtime).

## 🛠 Tech Stack
* **Framework:** PyTorch, ONNX Runtime
* **Backbone:** MobileViT (xxs, xs variants)
* **Environment:** Docker (Reproducible research)

---

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.