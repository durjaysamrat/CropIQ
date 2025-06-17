# 🌾 CropIQ – App-Based Rice Plant Disease Detection

![Mobile UI](https://github.com/user-attachments/assets/09131fb1-31d8-42fb-86ca-0f629213e45c)

Welcome to **[CropIQ](https://github.com/durjaysamrat/CropIQ)**, a smart, AI-powered mobile application that detects diseases in rice plants using deep learning models. Designed for farmers and agricultural experts, CropIQ provides fast, accurate, and actionable disease diagnosis using just a smartphone. 📱🌱

---

## 🔍 Problem Statement

Rice plant diseases like **Bacterial Leaf Blight**, **Brown Spot**, and **Leaf Smut** threaten food security and the livelihood of farmers. Traditional detection methods are:

- Time-consuming  
- Expert-dependent  
- Expensive for smallholder farmers

**CropIQ** automates and simplifies disease detection by providing a mobile-based solution that uses AI to classify and identify common rice plant diseases in real time.

---

## ✨ Key Features

✅ **Deep Learning-Powered Detection**  
   - Trained on thousands of annotated images  
   - High detection accuracy using TensorFlow & Keras  

✅ **User-Friendly Mobile Interface**  
   - Simple design for ease of use  
   - Farmers can capture and upload images from the app  

✅ **Real-Time Results**  
   - Disease name  
   - Recommended action (coming soon)  

✅ **Offline Support with TensorFlow Lite**  
   - Model converted to TFLite for on-device inference  
   - Ideal for remote rural areas  

---

## 💻 Tech Stack

| Layer            | Tools & Technologies                          |
|------------------|-----------------------------------------------|
| Machine Learning | TensorFlow, Keras, OpenCV                     |
| API Backend      | Flask (Python)                                |
| Mobile App       | Android Studio (Java/Kotlin, XML)             |
| Deployment       | TensorFlow Lite, REST API                     |
| Image Handling   | Pillow, NumPy, OpenCV                         |

---

## 🚀 Getting Started

### 📦 Prerequisites

- Python 3.7+
- pip (Python package manager)
- Android Studio
- Git

### 🔧 Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/durjaysamrat/CropIQ.git
cd CropIQ
2. Install Python Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Flask Server
bash
Copy
Edit
python app.py
4. Setup Mobile App
Open the /android-app folder in Android Studio

Connect your physical device or emulator

Update the API endpoint to match your Flask server (e.g., http://<your_ip>:5000/predict)

Run the app

🧪 Model Performance
Dataset: Labeled rice disease dataset (3 classes)

Architecture: CNN-based model

Test Accuracy: ~95%

Inference Time: ~1-2 seconds (on-device)

🧠 Disease Classes Detected
Bacterial Leaf Blight

Brown Spot

Leaf Smut

📷 Example Prediction
Input: Image of an infected rice leaf

Output:

yaml
Copy
Edit
Disease Detected: Brown Spot
Confidence: 96.4%


📈 Future Enhancements
 Add crop treatment suggestions

 Support for more crops (e.g., wheat, maize)

 GPS-based disease tracking

 Farmer analytics dashboard

🤝 Contribution Guide
We welcome contributors! Here's how you can help:

Fork the repository

Create a new branch: git checkout -b feature/my-feature

Make your changes

Commit and push: git push origin feature/my-feature

Submit a Pull Request

Found a bug or have a feature request? Create an Issue

📫 Contact & Connect
👨‍💻 Durjay Samrat Nandamudi




⭐ Support the Project
If you found CropIQ helpful, please consider giving it a ⭐ on GitHub and sharing it with your peers. Let’s revolutionize agriculture together. 🌿🚜

diff
Copy
Edit
