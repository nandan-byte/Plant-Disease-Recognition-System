# 🌿 Plant Disease Recognition System

A Deep Learning based web application that detects plant diseases from leaf images using a trained Convolutional Neural Network (CNN). The system allows users to upload a plant leaf image and predicts the disease category in real time.

This project demonstrates how **computer vision and machine learning can assist farmers and agricultural researchers in early disease detection**, helping reduce crop loss and improve agricultural productivity. Plant disease detection using AI has become an important application of deep learning in agriculture because manual disease identification is slow and requires expert knowledge. ([IJRASET][1])

---

# 🚀 Demo

Streamlit Web App

Upload a plant leaf image and the model will predict the disease.

---

# 📌 Features

• Upload plant leaf images
• Deep learning model predicts plant disease
• Supports **38 plant disease classes**
• Built with **TensorFlow / Keras**
• Interactive **Streamlit web interface**
• Fast image prediction

---

# 🧠 Model Overview

The system uses a **Convolutional Neural Network (CNN)** trained on a plant leaf dataset to classify plant diseases.

### Model Workflow

1. Image Upload
2. Image Preprocessing
3. CNN Model Prediction
4. Disease Classification Output

---

# 🧠 Model Architecture

The model is a **Convolutional Neural Network (CNN)** designed to extract visual features from plant leaf images and classify them into 38 disease categories.

Architecture summary:

1. **Input Layer**
   - Image size: **128 × 128 × 3**

2. **Convolution Layers**
   - Extract features such as leaf texture, color patterns, and disease spots.

3. **Max Pooling Layers**
   - Reduce spatial size while keeping important features.

4. **Flatten Layer**
   - Converts extracted features into a single vector.

5. **Dense (Fully Connected) Layers**
   - Learn complex patterns for classification.

6. **Output Layer**
   - **Softmax activation**
   - Predicts one of **38 plant disease classes**

Training configuration:

- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  
- **Epochs:** 10  
- **Batch Size:** 32  
- **Validation Accuracy:** ~97%

---

# 📊 Dataset

The model is trained on the **PlantVillage dataset** containing approximately:

* **87,000+ RGB images**
* **38 plant disease classes**
* Training / Validation split

Dataset structure:

```
Plant_Disease_Dataset
│
├── train
├── validation
└── test
```

---

# 🛠️ Tech Stack

**Programming Language**

Python

**Libraries**

* TensorFlow
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Pillow

**Framework**

Streamlit

---

# 📂 Project Structure

```
Plant-Disease-Recognition-System
│
├── app.py
├── requirements.txt
├── runtime.txt
├── trained_plant_disease_model.keras
├── training_hist.json
├── home_page.jpeg
├── image.png
├── Train_plant_disease.ipynb
├── Test_plant_disease.ipynb
└── README.md
```

---

# ⚙️ Installation

Clone the repository

```
git clone https://github.com/nandan-byte/Plant-Disease-Recognition-System.git
```

Navigate to the project folder

```
cd Plant-Disease-Recognition-System
```

Install dependencies

```
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```
streamlit run app.py
```

Open browser:

```
http://localhost:8501
```

---

# 🧪 Model Prediction Pipeline

1️⃣ Upload plant leaf image
2️⃣ Image resized to **128×128**
3️⃣ Pixel normalization
4️⃣ Model inference using TensorFlow
5️⃣ Predicted disease displayed

---

# 📈 Future Improvements

• Improve model accuracy using transfer learning
• Add Grad-CAM visualization for explainability
• Deploy API using FastAPI
• Add mobile support for farmers
• Integrate real-time disease treatment suggestions

---

# 🤝 Contributing

Contributions are welcome!

Steps:

```
1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
```

---

# 📜 License

This project is open source and available under the **MIT License**.

---

# 👨‍💻 Author

**Nandan Deshmukh**

GitHub
https://github.com/nandan-byte

---

⭐ If you found this project useful, consider **starring the repository**.

[1]: https://www.ijraset.com/research-paper/plant-disease-detection-system?utm_source=chatgpt.com "Plant Disease Detection System"
