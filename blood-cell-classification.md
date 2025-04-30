---
layout: single
title: "Blood Cell Image Classification with Deep Learning"
permalink: /projects/blood-cell-classification/
---

## 🧠 Summary
This research introduces a deep learning-based framework for the accurate classification of blood cell images, significantly enhancing diagnostic precision in healthcare. The study evaluated a wide range of state-of-the-art CNN architectures—including a novel hybrid model combining InceptionV3 and Xception—achieving a peak test accuracy of 98.51%. The work contributes scalable, reliable, and cost-effective solutions for improving medical diagnostics in resource-constrained settings.

## 🔍 Technical Highlights
	• Created a full deep learning classification pipeline using a curated dataset of 17,000+ annotated blood cell images.
	• Developed and compared models using:
		○ CNN, U-Net, ResNet-50, VGG-16, DenseNet-201
		○ Supervised Contrastive Learning
		○ MobileNet-V2, InceptionV3, Xception
		○ Hybrid model (InceptionV3 + Xception) – Best performing model
	• Conducted 5-fold cross-validation and applied SMOTE to address class imbalance.
	• Top-performing hybrid model achieved 98.51% test accuracy, 98.53% precision, and 98.52% F1-score.

## 🧰 Tools & Methods Used
	• Deep Learning Architectures: CNN, U-Net, ResNet-50, InceptionV3, Xception, DenseNet-201, MobileNetV2
	• Techniques: Supervised Contrastive Learning, Ensemble Learning, Transfer Learning
	• Data Preprocessing: OpenCV, Image resizing (224x224), Stratified splitting
	• Performance Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
	• Optimization: SMOTE for class imbalance, shuffling strategies to enhance generalization
	• Frameworks: TensorFlow / Keras, NumPy, Scikit-learn

## ✨ Key Contributions
	• Introduced a novel hybrid deep learning model combining InceptionV3 and Xception with state-of-the-art accuracy (98.51%).
	• Provided in-depth evaluation of how data shuffling affects model robustness and generalization.
	• Demonstrated scalable blood cell classification that can assist clinical diagnostics, especially in low-resource settings.
	• Offered comparative analysis across multiple architectures—serving as a benchmark for future research.

## 🌍 Why This Research Matters
	• Manual blood smear analysis is slow, subjective, and error-prone.
	• Your framework enables automated, high-accuracy diagnostics using deep learning, reducing reliance on expensive equipment.
	• The model can be integrated into real-time systems for early detection of diseases like leukemia and autoimmune disorders.
	• It bridges a critical gap between AI and healthcare accessibility—paving the way for affordable diagnostic tools.
![image](https://github.com/user-attachments/assets/b39fd01e-971b-4ab6-9d9c-715b0a651b16)


## 🔗 [View Code on GitHub](https://github.com/sh1vb/Blood_Cell_Classifier)
