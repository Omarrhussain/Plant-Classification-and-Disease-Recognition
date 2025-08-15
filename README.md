# 🌿 Plant Classification & Disease Recognition

This **Computer Vision** project identifies plant species and detects diseases from images using deep learning techniques.  
The system first classifies the plant into its correct class using **MobileNet**, then recognizes plant diseases using a **Siamese Network** for similarity-based learning.  
The workflow includes image preprocessing, augmentation, and class weighting to improve model robustness and accuracy.

---

## 📌 Features
- **Two-stage approach:**
  - **Plant Classification** → Identify the plant species using MobileNet.
  - **Disease Recognition** → Detect plant diseases using a Siamese Network.
- **Image preprocessing** for noise reduction and consistency.
- **Data augmentation** (rotation, flipping, scaling) to enhance generalization.
- **Class weighting** to handle imbalanced datasets.
- Support for multiple plant classes and disease categories.

---

## 🛠️ Tech Stack
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**, **Pandas**
- **Matplotlib / Seaborn** for visualization

---

## ⚙️ Installation
1. Clone this repository:
   ```bash
   git clone (https://github.com/Omarrhussain/Plant-Classification-and-Disease-Recognition)
   cd Plant-Classification-and-Disease-Recognition
