# 🩺 Skin Cancer Detection using Machine Learning & Deep Learning  

Early detection of skin cancer can save lives. This project explores **state-of-the-art machine learning and deep learning models** for classifying skin cancer images into multiple categories with high accuracy. By leveraging CNN architectures, Vision Transformers, and optimized training strategies, we aim to create a reliable and efficient skin cancer prediction system.  

---

## 🚀 Problem Statement  
Skin cancer is one of the most common cancers worldwide, but **early diagnosis** can drastically improve treatment outcomes. Traditional methods are time-consuming and require expert dermatologists. This project addresses the challenge by using **AI-powered models** to detect skin cancer from images quickly and accurately.  

---

## 🧠 Models Implemented  

We trained **six powerful models** along with different optimizers to evaluate performance:  

1. **BizNet201**  
2. **EfficientNet B0**  
3. **InceptionNet B3**  
4. **MobileNet V3 (Large)**  
5. **Vision Transformer (ViT)** → optimized with **AdamW** (best performing)  
6. **ResNet50 + CBAM (Convolutional Block Attention Module)**  

📌 Optimizers used across experiments: **Adam, NAGs, AdamW, Madam, SGD**  

---

## 📊 Dataset  

We used two benchmark dermatology datasets:  

- **Dataset 1:** 3,297 images, 2 classes (binary classification)  
- **Dataset 2:** 12,400 images, 8 classes (multi-class classification)  

Images were preprocessed and augmented to ensure balanced training and robust results.  

---

## 🏆 Results  

✨ Our models achieved **world-class performance**, with validation accuracy ranging from **80% up to 97.73%**.  

- ViT (with AdamW optimizer) provided the **best accuracy**.  
- Traditional CNN-based approaches also performed strongly.  

---

## ⚙️ Tech Stack  

- **Language:** Python 🐍  
- **Frameworks & Libraries:** TensorFlow, PyTorch, Scikit-learn, OpenCV, NumPy, Matplotlib  
- **Optimization:** Adam, NAGs, AdamW, Madam, SGD  

---

## 📂 Project Structure  
 -  data/ # Dataset (images)
 - notebooks/ # Colab notebooks for model training & evaluation
 -  models/ # Saved trained models
 - results/ # Accuracy plots, confusion matrices
 - src/ # Core training & preprocessing scripts
 - requirements.txt # Dependencies
 - README.md # Project documentation

## 🔧 Installation & Usage  

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/SkinCancerDetection.git
   cd SkinCancerDetection

📌 Key Features

✔️ Multiple state-of-the-art ML/DL architectures tested
✔️ Attention-enhanced ResNet50 with CBAM
✔️ Vision Transformer optimized with AdamW
✔️ High accuracy up to 97.73%
✔️ Supports binary and multi-class skin cancer classification

📈 Sample Results

<p align="center">
  <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0ebf8dd2-040c-41da-af57-99a960cbab22" />
</p>

👨‍💻 Contributors

Gagandeep Singh – Project Lead & Researcher

Dhruv Tripath - ML Trainer 

📜 License

This project is licensed under the MIT License – feel free to use and modify with attribution.

