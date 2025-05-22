# 🧠 Brain Tumor Classification using EfficientNet-B0

This project performs multi-class classification of brain tumor MRI scans using a fine-tuned EfficientNet-B0 model. The model distinguishes between four tumor types — glioma, meningioma, pituitary, and no tumor — with nearly 99% accuracy. Built for real-world reliability and supported with explainability techniques like Grad-CAM.

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

## 🧪 Tools Used
- **Model:** EfficientNet-B0 (transfer learning)
- **Frameworks:** PyTorch, Torchvision, matplotlib, seaborn
- **Explainability:** Grad-CAM
- **Evaluation:** Confusion matrix, ROC curve, classification report
