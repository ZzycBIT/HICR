# HICR: Hierarchical Interaction with Cross-coordinate Representation for Trajectory Prediction

Official implementation of our paper:  
**HICR: Hierarchical Interaction with Cross-coordinate Representation for Multi-Agent Trajectory Prediction**  

---

## 🚀 Overview
HICR is an engineering-oriented framework for motion forecasting that supports both **single-agent** and **multi-agent** trajectory prediction tasks.  
It introduces a **Global–Local Fusion Block (GLFB)** to effectively exchange information across coordinate systems, reducing redundant computation while improving accuracy.  

HICR achieves state-of-the-art performance on **Argoverse1** and **Argoverse2** benchmarks, outperforming strong baselines such as **HiVT** and **QCNet**.  

---

## 📊 Results
| Dataset      | Metric   | HICR (ours) |
|--------------|----------|-------------|
| Argoverse1   | minADE6  | 0.59        |
| Argoverse2   | minADE6  | 0.55        |

For detailed comparisons, please refer to our paper.

---

## 📂 Code Release Plan
We are currently reorganizing the codebase and documentation to ensure clarity and ease of use.  
The complete implementation, pre-trained models, and training scripts will be released soon.  

- [x] Repository initialization  
- [x] Project description  
- [ ] Core implementation cleanup  
- [ ] Pre-trained models upload  
- [ ] Training & evaluation instructions  

Stay tuned! 🚧

---

## 📦 Requirements
- Python >= 3.8  
- PyTorch >= 1.10  
- CUDA 11.0+  
- Other dependencies will be listed upon release.  

---

## 📑 Citation
If you find this work useful, please cite our paper:
