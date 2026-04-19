## 🧠 MRI Brain Tumor Classifier  

Developed a deep learning-based medical image classification system to detect brain tumors from MRI scans using a custom ResNet architecture built from scratch with PyTorch.

---

### 📌 Categories  
- No Tumor  
- Glioma  
- Meningioma  
- Pituitary  

---

### 🛠️ Tech Stack  
- Python  
- PyTorch  
- OpenCV  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

### 🏗️ Model Architecture  
Designed and implemented a custom ResNet architecture from scratch using residual blocks (BasicBlock), instead of relying on pretrained models. This approach provided full control over the network design and enabled adaptation to grayscale MRI images.

---

### 📂 Dataset  
Dataset obtained from Kaggle: **Brain Tumor MRI Dataset**

---

### 🚀 How to Run  
1. Open the notebook in Google Colab  
2. Download the dataset from Kaggle  
3. Place it in the `data/` folder  
4. Run all cells  

---

### 📊 Results  
- Test Accuracy: **95.35%**  
- Evaluated using: Accuracy, Precision, Recall, and F1-score  
- Generated a confusion matrix to analyze classification performance across tumor types  

---

### ⚠️ Limitations  
- Performance depends on dataset size and quality  
- Risk of overfitting due to limited medical data  
- Not intended for real-world medical diagnosis  
