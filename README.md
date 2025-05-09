# 🧠 Brain Tumor Detection and Classification using GCN-RNN Hybrid Model

A Novel Approach Using GCN-RNN Hybrid Model for Enhanced Brain Tumor Detection and Classification.

## 📌 Project Overview

Brain tumors can be life-threatening if not detected and treated early. This project presents a novel deep learning pipeline that leverages the strengths of **Graph Convolutional Networks (GCN)** and **Recurrent Neural Networks (RNN)** to detect and classify brain tumors more accurately from MRI images.

By transforming MRI scans into graph representations and analyzing them with GCNs followed by RNNs, this model captures both **spatial dependencies** and **sequential relationships**, leading to more robust predictions.

---

## 🚀 Highlights

- 📈 **Hybrid Architecture:** Combines GCN and RNN for superior feature extraction and classification.
- 🧠 **Focus Area:** Early and accurate brain tumor diagnosis using deep learning.
- 🖼️ **Input:** Preprocessed MRI images of brain scans.
- ✅ **Output:** Tumor classification (e.g., Meningioma, Glioma, Pituitary).
- 🔬 **Application:** Can assist radiologists and medical professionals in diagnosis.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **TensorFlow / Keras / PyTorch**
- **OpenCV** – Image preprocessing
- **NetworkX** – Graph representation
- **NumPy, Pandas** – Data manipulation
- **Matplotlib, Seaborn** – Visualization

---


## 📊 Methodology

1. **Data Preprocessing**
   - MRI images are resized, normalized, and augmented.
   - Converted into graph-based structures using pixel neighborhood relationships.

2. **Graph Convolutional Network (GCN)**
   - Learns spatial features from graph-structured MRI data.
   - Captures relational patterns in tumor structure.

3. **Recurrent Neural Network (RNN)**
   - Captures temporal or sequential dependencies from GCN features.
   - Useful for context-aware classification.

4. **Output Layer**
   - Final classification into tumor categories using softmax activation.

---

## 📈 Results

- The GCN-RNN hybrid model significantly outperformed traditional CNN-based approaches in accuracy and robustness.
- **Accuracy Achieved:** _(1.00)_

---

## 🧪 Installation & Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/brain-tumor-detection-gcn-rnn.git
   cd brain-tumor-detection-gcn-rnn



