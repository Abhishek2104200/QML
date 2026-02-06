# 🧬 Quantum Machine Learning for SARS-CoV-2 Variant Classification

![Quantum Computing](https://img.shields.io/badge/Domain-Bioinformatics-blueviolet)
![PennyLane](https://img.shields.io/badge/Framework-PennyLane-blue)
![Python](https://img.shields.io/badge/Language-Python-yellow)

## 🌟 Overview
This repository explores the intersection of **Quantum Machine Learning (QML)** and **Bioinformatics**, specifically focusing on the classification of SARS-CoV-2 variants. By leveraging quantum circuits, we aim to process high-dimensional genomic data more efficiently than traditional classical models.

---

## 🚀 Main Implementation
### `qnn&vqc.ipynb` 
> **Note:** This is the **primary notebook** containing the core research, model architecture, and final results. All other files serve as exploratory or supporting works.

It contains the primary research and implementation of:
* **Variational Quantum Classifiers (VQC):** Utilizing parameterized quantum circuits for supervised learning.
* **Quantum Neural Networks (QNN):** Implementing layered quantum gates to capture complex patterns in variant data.

#### **Quantum Circuit Architecture**
The model utilizes an advanced multi-qubit architecture featuring **Angle Embedding** and nested entanglement layers to map genomic features into the Hilbert space.

![Quantum Circuit Diagram](07992372-eb01-4fc4-b384-13d4a4e30f65.png)
*Figure 1: The QNN REUPLOADING architecture used for feature processing.*

---

## 🛠 Supporting Works
While the main logic resides in the primary notebook, the following files provide critical supporting analysis:

| File | Description |
| :--- | :--- |
| **`Base_QSVM_QKNN.ipynb`** | Baseline implementations of Quantum SVM and Quantum KNN. |
| **`HCQNN.ipynb`** | Exploration of **Hybrid Classical-Quantum Neural Networks**. |
| **`datatset_details.ipynb`** | Data preprocessing and exploratory analysis of the SARS-CoV-2 dataset. |
| **`quantum_kernal.ipynb`** | Implementation of Quantum Kernel Estimation. |
| **`full_Quantum.ipynb`** | An end-to-end pipeline focused on purely quantum operations. |

---

## 📊 Visual Insights & Performance
We analyze the Hilbert space overlap and optimization landscapes to ensure model stability.

### **1. Quantum Fidelity Surface**
Analyzing the quantum embedding to ensure distinguishability between variants.
![Quantum Fidelity](f125aa94-68d4-48ba-8f2f-518dff47dd66.png)

### **2. Loss Landscape Analysis**
Visualizing the 3D loss landscape to understand the optimization "terrain."
![Loss Landscape](9313fdbf-a2e0-4ee6-b6e6-23ec8e7b0c6f.png)

### **3. Accuracy Progression**
This surface showcases how model accuracy evolves relative to weight optimization.
![Accuracy Progression](8016a0da-8ef4-4245-8a53-5d0354722717.png)

---

## 📦 Requirements
To run these notebooks, you will need:
* **PennyLane**
* **Scikit-Learn**
* **Pandas & NumPy**
* **Matplotlib**

```bash
pip install pennylane scikit-learn pandas matplotlib
