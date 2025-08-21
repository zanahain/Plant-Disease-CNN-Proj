# 🌿 Plant Disease Detection using CNN (MobileNetV2)

An AI-powered **plant disease detection system** that uses a **Convolutional Neural Network (CNN)** based on **MobileNetV2** to classify plant leaf images into multiple disease categories with **92% accuracy**.  

---

## 📌 Project Overview
Plant diseases significantly affect agricultural productivity and economy. Early and accurate detection of diseases can help farmers take preventive measures.  
This project leverages **Deep Learning** to automate disease detection by analyzing plant leaf images.

---

## 🚀 Features
- 📸 **Image Classification** → Detects plant diseases from leaf images.
- 🧠 **Transfer Learning** → Uses **MobileNetV2** for faster training and higher accuracy.
- 📊 **92% Accuracy** on the test dataset.
- 🛠️ **Scalable & Deployable** → Can be integrated with web/mobile apps for farmers.

---

## 🧠 Model Architecture
We used **MobileNetV2** and fine-tuned it:
- Loaded pretrained MobileNetV2 weights.
- Unfroze the **last 10 layers** for retraining.
- Added a **custom classification head**.
- Optimized using **Adam optimizer** & **categorical crossentropy**.

---

## 🗂️ Dataset
- **Dataset Size** → 50,000+ images  
- **Classes** → Multiple plant diseases + healthy leaves  
- **Source** → Publicly available plant disease dataset.

---

## 📈 Training Details
- **Model** → MobileNetV2 (Transfer Learning)
- **Input Shape** → `224x224x3`
- **Optimizer** → Adam
- **Loss Function** → Categorical Crossentropy
- **Accuracy Achieved** → **92%**
- **Frameworks** → TensorFlow & Keras

---

## 🛠️ Tech Stack
- **Programming Language** → Python 🐍  
- **Deep Learning** → TensorFlow, Keras  
- **Data Handling** → NumPy, Pandas  
- **Visualization** → Matplotlib, Seaborn  
- **Deployment Ready** → Flask / Streamlit (future scope)

---

## 📦 Installation & Setup
```bash
# Clone the repository
git clone https://github.com/zanahain/Plant-Disease-CNN-Proj.git

# Navigate into the project directory
cd Plant-Disease-CNN-Proj

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook or train the model
jupyter notebook
