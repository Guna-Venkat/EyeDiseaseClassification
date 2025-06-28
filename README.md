# 🧠 Eye Disease Classification Using Deep Learning

This project focuses on classifying common eye diseases from retinal images using Convolutional Neural Networks (CNNs) with Transfer Learning. It is backed by a peer-reviewed publication and trained on publicly available datasets. The goal is to assist early diagnosis and decision-making for ophthalmologists using automated image analysis.

---

## 📄 Publication

📘 _EYE DISEASE CLASSIFICATION USING DEEP LEARNING TECHNIQUES_  
📍 *Industrial Engineering Journal*  
🗓️ Volume 51, Issue 11, No. 1, November 2022  
📚 ISSN: 0970-2555  

---

## 🧬 Problem Statement

Given a retinal image, the model predicts whether the patient is diagnosed with one of the following conditions:

- **Normal (Healthy)**
- **Diabetic Retinopathy**
- **Cataract**
- **Glaucoma**

---

## 📂 Dataset

- 🔗 [Kaggle Dataset: Eye Disease Classification](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification)
- Total of **4000 images**, with approximately 1000 images per class
- Collected from public datasets: **Ocular Recognition**, **HRF**, **DRIVE**, and **IDRiD**
- Images are pre-labeled and suitable for supervised learning

---

## 🛠️ Model & Methodology

- **Transfer Learning** using pretrained CNN architectures:
  - ✅ **ResNet50**
  - ✅ **VGG16**
- Image augmentation applied:
  - 🔁 Rotation
  - 🔍 Zoom
  - 📏 Scaling
- Fine-tuned using:
  - **SGD** and **Adam** optimizers
  - Learning rate adjustments
  - Early stopping for regularization

---

## 🧪 Performance

- **Validation set**: 400 images (100 per class)
- **Achieved Accuracy**: **92%**
- Trained using **GPU acceleration** on Kaggle
- Fine-tuning and hyperparameter optimization took ~1 week, with best training run completing in ~3 hours

---

## 🔧 How to Use

- 🔗 [Model Training & Evaluation Notebook (Kaggle)](https://www.kaggle.com/code/gunavenkatdoddi/final-model-build2)
- The notebook contains all training, validation, and performance tracking steps
- Trained weights available (contact or download from Kaggle kernel output if published)

> *Note: This GitHub repository is under development and mirrors the Kaggle implementation.*

---

## 📱 Future Work

We plan to develop a **mobile application** where:
- Users can upload a retinal image
- The app will predict the disease using the trained model
- Results can be used for clinical pre-screening

---

## 📃 License

*To be added*

---

## 👨‍💻 Author

Made with ❤️ by [Gunavenkat Doddi](https://www.kaggle.com/gunavenkatdoddi)  
For academic inquiries or collaborations, feel free to reach out!

---

## 📌 Acknowledgements

Thanks to the creators of the public datasets and the Kaggle community. Special appreciation to the co-authors and reviewers of the published paper.
