# ✍️ Handwritten Digit Classification using RNN

## 📌 Problem Statement
Handwritten digit recognition is a fundamental problem in computer vision with applications in:
- Postal automation  
- Bank cheque processing  
- Digitizing handwritten documents  

Traditional machine learning approaches require manual feature extraction, which limits scalability and performance.

---

## 🎯 Objective
The objective of this project is to build a **Recurrent Neural Network (RNN)** model that can:
- Automatically learn patterns from handwritten digit images  
- Accurately classify digits from **0–9**  

---

## 📊 Dataset
- **Dataset Used:** MNIST  
- **Total Images:** 70,000  
- **Image Size:** 28 × 28 pixels  
- **Type:** Grayscale images of handwritten digits  

---

## 🧠 Approach

Although RNNs are typically used for sequential data, in this project:
- Each image is treated as a **sequence of rows (or pixels)**  
- The RNN processes the image step-by-step to learn patterns  

### Model Details:
- Model: **Recurrent Neural Network (RNN)**  
- Input Size: 28  
- Sequence Length: 28  
- Hidden Layers: (mention your value if you want)  
- Activation: ReLU / Tanh  
- Output: 10 classes (digits 0–9)  

---

## 🚀 Features
- Data preprocessing and normalization  
- Reshaping image data for RNN input  
- Model training using deep learning techniques  
- Performance evaluation using classification metrics  

---

## 🛠️ Tech Stack
- Python  
- PyTorch / TensorFlow (mention what you used)  
- NumPy  
- Matplotlib  

---

## 📈 Results
- ✅ Model achieved **96% accuracy** on test data  
- Successfully classified handwritten digits  
- Demonstrates how RNNs can be adapted for image-based tasks  

---

## 📊 Evaluation Metrics
- Accuracy  
- Confusion Matrix  

---

## 📁 Project Workflow
1. Data Loading (MNIST dataset)  
2. Data Preprocessing  
3. Reshaping for RNN input  
4. Model Building (RNN)  
5. Model Training  
6. Model Evaluation  

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
