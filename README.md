# ✂️ Data Pruning Algorithms for Gaudi Environment  

This repository provides an implementation of **Difficulty and Uncertainty-Aware Lightweight (DUAL)** data pruning. DUAL enables efficient dataset pruning without requiring full training on the original dataset, making it particularly suitable for the **Gaudi environment**.  



---
## 📄 Paper

For more details, check out our paper on Arxiv: 

[Lightweight Dataset Pruning without Full Training via
Example Difficulty and Prediction Uncertainty](https://arxiv.org/abs/2502.06905)
---

## 📌 Available Data Pruning Algorithms  
- **Forgetting**  [https://arxiv.org/abs/1812.05159](https://arxiv.org/abs/1812.05159)
- **EL2N**  [https://arxiv.org/abs/2107.07075](https://arxiv.org/abs/2107.07075)
- **AUM**  [https://arxiv.org/abs/2001.10528](https://arxiv.org/abs/2001.10528)
- **CCS**  [https://arxiv.org/abs/2210.15809](https://arxiv.org/abs/2210.15809)
- **Entropy**  [https://arxiv.org/abs/1906.11829](https://arxiv.org/abs/1906.11829)
- **Dyn-Unc**  [https://arxiv.org/abs/2306.05175](https://arxiv.org/abs/2306.05175)
- **TDDS**  [https://arxiv.org/abs/2311.13613](https://arxiv.org/abs/2311.13613)
- **DUAL** (**ours**)  

---
## 🚀 Usage  

Please refer to each folder for dataset-specific experiments:  
- **`exp_cifar`** for CIFAR experiments  
- **`exp_imagenet`** for ImageNet experiments  

---
## 📚 Citation
```bibtex
@article{cho2025lightweight,
  title={Lightweight Dataset Pruning without Full Training via Example Difficulty and Prediction Uncertainty},
  author={Cho, Yeseul and Shin, Baekrok and Kang, Changmin and Yun, Chulhee},
  journal={arXiv preprint arXiv:2502.06905},
  year={2025}
}
```

