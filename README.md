# 🪖 HelmNet – Computer Vision Project  

## 📌 Overview  
Workplace safety in hazardous environments requires strict compliance with protective equipment usage. This project, **HelmNet**, applies **deep learning and computer vision** to detect whether workers are wearing safety helmets. Using transfer learning with **VGG16**, the model achieved **100% accuracy** on training and validation data, supporting SafeGuard Corp’s mission of enhancing workplace safety compliance.  

---

## 🎯 Objectives  
- Build an image classification model for helmet detection  
- Classify images into **With Helmet** and **Without Helmet** categories  
- Support real-time safety monitoring in industrial and construction environments  

---

## 📂 Dataset  
⚠️ *Dataset not included due to university policy*  
- 631 images (311 with helmets, 320 without helmets)  
- Covers diverse environments, lighting, angles, and worker activities  

---

## 🛠️ Tech Stack / Libraries  
- **Python**  
- **TensorFlow / Keras** – deep learning models  
- **OpenCV** – image preprocessing  
- **NumPy / Pandas** – data handling  
- **Matplotlib / Seaborn** – visualization  

---

## 📊 Key Steps  
1. **Baseline CNN Model** – initial architecture, moderate accuracy  
2. **Transfer Learning with VGG16** – improved performance  
3. **Fine-Tuning with Data Augmentation** – achieved 100% accuracy, strong generalization  
4. **Evaluation** – precision, recall, F1-score, confusion matrices  
5. **Insights** – strong performance but occasional false positives on lookalike objects (e.g., caps, pets)  

---

## 🔍 Actionable Insights  
- **High Accuracy & Generalization** – VGG16 fine-tuned model delivered 100% recall and precision  
- **Effective Regularization** – augmentation eliminated overfitting despite small dataset size  
- **Strong Visual Predictions** – robust under varying lighting, angles, and occlusions  
- **Transfer Learning Advantage** – outperformed custom CNN, proving value in limited-data scenarios  

---

## 💼 Business Recommendations  
1. **Deploy Model 4 (VGG16 Fine-Tuned)** for helmet compliance monitoring  
2. **Expand Dataset** with diverse examples and negative samples to reduce false positives  
3. **Extend PPE Detection** to vests, goggles, and gloves for holistic compliance  
4. **Integrate Real-Time Alerts** for immediate supervisor notifications  
5. **Retrain Periodically** with field data to maintain long-term accuracy  
6. **Upgrade to Multi-Class Classification** (Helmet On / Helmet Off / No Helmet)  

