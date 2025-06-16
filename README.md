This repository contains a curated collection of classic image classification projects developed as part of academic coursework at UMT. Each project demonstrates a unique approach to solving vision-related challenges — from heuristic-based decision rules to traditional machine learning classifiers like KNN, SVM, and SGD. The goal is to provide a comprehensive foundation in pattern recognition and image classification using raw pixel data.

---

## 📂 Projects Overview

### 1. 🔢 Heuristic-Based Digit Classifier (No ML)
**Assignment**: S-2025 No ML Digit Classification  
**Tools**: Pure Python, NumPy (no ML libraries)  
**Dataset**: Handwritten digits (CSV format)  
**Highlights**:
- Binary thresholding of grayscale images
- Manual feature extraction (mean, variance)
- Euclidean distance-based nearest neighbor matching

**Result**:  
✔️ Validation Accuracy: **86.27%**

**Files**:  
- `train.csv`  
- `validate.csv`  
- `test.csv`  
- `submission.csv`

---

### 2. 🧭 Image Classification with KNN (CIFAR-10)
**Assignment**: S-2025 KNN Classifier  
**Libraries**: NumPy, Pillow, scikit-learn  
**Dataset**: CIFAR-10 (image folders)  
**Highlights**:
- Grayscale conversion and flattening
- KNN classifier with `k=3`
- Manual feature processing

**Result**:  
✔️ Validation Accuracy: **31%**

**Structure**:
```

knn\_assignment/
├── train/
└── test/

````

---

### 3. ⚖️ Linear SVM from Scratch (CIFAR-10)
**Challenge**: Manual SVM implementation without ML libraries  
**Libraries**: NumPy, Pandas, Matplotlib (visuals only)  
**Dataset**: `cifar10_sampled.csv` (10-class subset)  
**Highlights**:
- Hinge loss calculation
- Gradient descent optimization
- Manual data split and validation

**Result**:
- ✅ Training Accuracy: **100%**
- ⚠️ Validation Accuracy: **30%**
- ❌ Testing Accuracy: **15%**

---

### 4. 💼 Digit Classification with SGD (Scikit-learn)
**Method**: Linear SVM using `SGDClassifier`  
**Libraries**: scikit-learn, pandas  
**Dataset**: MNIST-style digits in CSV  
**Highlights**:
- Data normalization and standardization
- Use of `partial_fit` for incremental learning
- Accuracy tracked over multiple epochs

**Output**:  
- `submission.csv` with predicted labels

---

## 🛠 Requirements

Install the necessary libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib pillow
````

---

## 🚀 How to Run

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/ashar-vision-baselines.git
   cd ashar-vision-baselines
   ```

2. **Add datasets**: Place `.csv` files or images into the corresponding folders.

3. **Open notebooks**:

   * Launch in Jupyter Lab, VS Code, or Google Colab.
   * Run all cells sequentially.

4. **Review outputs**:

   * Accuracy reports
   * Saved predictions in `submission.csv`

---

## 📌 Coming Soon

* ✅ CNN models built using Keras and TensorFlow
* ✅ Transfer learning with MobileNet/VGG
* ✅ Training visualizations and performance graphs
* ✅ Confusion matrices and per-class breakdowns

---

## 👨‍🎓 Author

**Syed Mohammad Ali Ashar**
Bachelor of Science in Artificial Intelligence
University of Management and Technology (UMT), Lahore

---

```

