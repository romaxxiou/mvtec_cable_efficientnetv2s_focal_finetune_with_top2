# mvtec_cable_efficientnetv2s_focal_finetune_with_top2
# Industrial Surface Defect Detection - Cable Defect Classification

This project implements an automated defect detection system for industrial cables using **EfficientNetV2-S**. It focuses on classifying 9 different types of cable conditions (1 good + 8 defects) from the [MVTec AD Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad).

## 🚀 Key Features
* **Model:** EfficientNetV2-S (Pre-trained on ImageNet)
* **Strategy:** 5-Fold Cross Validation for robust evaluation.
* **Imbalance Handling:** Implemented **Focal Loss** to handle class imbalance.
* **Performance:** Achieved **94.92%** Top-1 Accuracy.

## 📂 Project Structure
* `MVTec_Cable_Defect_Detection.ipynb`: The main notebook containing data loading, training, evaluation, and visualization code.
* `deep_learning_project_topics-2.pptx`: Project presentation slides.

## 🛠️ Requirements
* Python 3.8+
* PyTorch
* Scikit-learn
* Matplotlib & Seaborn

## 📊 Results
The model effectively classifies subtle defects. Below is the summary of performance:
* **Accuracy:** 94.92%
* **Key Challenge:** Distinguishing between visually similar classes like `combined` and `cable_swap`.
