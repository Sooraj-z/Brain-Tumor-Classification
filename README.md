# 🧠 Brain Tumor Classification using EfficientNet-B0

This project performs multi-class classification of brain tumor MRI scans using a fine-tuned EfficientNet-B0 model. The model distinguishes between four tumor types — glioma, meningioma, pituitary, and no tumor — with nearly 99% accuracy.

🔗 [Back to Main GitHub Profile](https://github.com/Sooraj-z)

---

## 📊 Performance Overview

| Metric         | Value     |
|----------------|-----------|
| **Accuracy**   | 98.93%    |
| **Precision**  | 0.989     |
| **Recall**     | 0.989     |
| **F1-Score**   | 0.989     |

---

## 🧠 Class-wise Metrics

| Class       | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| Glioma      | 0.9966    | 0.9867 | 0.9916   | 300     |
| Meningioma  | 0.9740    | 0.9804 | 0.9772   | 306     |
| No Tumor    | 0.9902    | 0.9951 | 0.9926   | 405     |
| Pituitary   | 0.9967    | 0.9933 | 0.9950   | 300     |

---

## 🧬 Dataset

This project uses the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) curated by **Masoud Nickparvar** on Kaggle.

> This dataset is a combination of three open datasets:
> - **Figshare**
> - **Br35H** (for “no tumor” class)
> - **SARTAJ** (partially used; glioma images were replaced due to mislabeling)

**Disclaimer:**  
All credit for dataset curation goes to the original author. This project does not redistribute the data, and respects the license terms as per Kaggle's usage policy. The dataset is intended for academic and experimental use.

📎 Kaggle: [Nickparvar Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)  
📄 License: As per original dataset sources (Figshare, Br35H, SARTAJ)

## 🧪 Tools Used
- **Model:** EfficientNet-B0 (transfer learning)
- **Frameworks:** PyTorch, Torchvision, matplotlib, seaborn
- **Explainability:** Grad-CAM
- **Evaluation:** Confusion matrix, ROC curve, classification report
