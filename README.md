
## 📌 Project Overview
This project implements **Principal Component Analysis (PCA)** in Python with **dynamic eigenvalue selection**.  
The number of principal components is chosen automatically based on a variance threshold.  
The project also includes **benchmarking** to compare the performance of models before and after PCA.

---

## 🎯 Objectives
- Implement PCA for reducing dimensions
- Automatically select the optimal number of principal components
- Benchmark performance before and after applying PCA

---

## 📂 Project Structure
# PCA_Formative2_Assignment

---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/h-mutumwinka/PCA_Formative2_Assignment.git
cd PCA_Formative2_Assignment
pip install -r requirements.txt


from pca_lib.pca import PCA

pca = PCA(variance_threshold=0.95)
X_reduced = pca.fit_transform(X)

