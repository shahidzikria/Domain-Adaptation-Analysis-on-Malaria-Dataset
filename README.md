# DAA-M5: Malaria Cell Detection Analysis via Domain Adaptation

## Overview

This project focuses on **Domain Adaptation (DA)** for malaria detection using microscopy images. It tackles key challenges in medical imaging, including:
- The high cost and time required for annotation.
- The performance degradation caused by domain shifts when applying models across datasets.

### Highlights:
- Evaluates **Unsupervised Domain Adaptation (UDA)** and **Source-Free Domain Adaptation (SFDA)** techniques.
- Uses the **M5-Malaria dataset**, which includes high-cost (HCM) and low-cost (LCM) microscopic images.
- **Results:** 
  - UDA methods, such as **ConfMix**, perform well for HCM to LCM adaptations.
  - SFDA methods show potential but face limitations, such as data imbalance and visual differences between image types.

This work emphasizes the potential of DA techniques in improving model generalization for medical imaging tasks.

---

## Authors and Supervisors

| Name                      | Role           | Links                                            |
|---------------------------|----------------|-------------------------------------------------|
| **Shahid Zikria**         | Researcher     | [GitHub](https://github.com/shahidzikria)       |
| **Waqas Sultani**         | Supervisor     | [Website](https://waqassultani.github.io/)      |
| **Mohsen Ali**            | Co-Supervisor  | [Website](https://mohsenali.github.io/)         |

---

## Project Resources

- 📜 **[Thesis](http://google.com)**  
- 💻 **[Code Repository](https://github.com/shahidzikria/Domain-Adaptation-Analysis-on-Malaria-Dataset)**  
- 📦 **[Model Weights](https://drive.google.com/drive/folders/1WJI39Ziuf0UcdqEaVl1q-qBeMe3gadBX?usp=sharing)**  

---

## Abstract

Deep Learning models have demonstrated exceptional success in medical image analysis tasks, such as segmentation and detection. However, these models face significant performance drops when applied to datasets from different domains due to domain shifts.

This thesis evaluates domain adaptation techniques for malaria detection using microscopy images. Experiments are conducted on the **M5-Malaria dataset**, comprising both **high-cost microscopy (HCM)** and **low-cost microscopy (LCM)** images. The study assesses **Unsupervised Domain Adaptation (UDA)** and **Source-Free Domain Adaptation (SFDA)** methods:

- **UDA Techniques:** Achieve strong performance, with methods like **ConfMix** excelling in HCM-to-LCM adaptations.  
- **SFDA Techniques:** Demonstrate poor performance than UDA.


