🌾 CropIQ – App-Based Rice Plant Disease Detection


Welcome to CropIQ, a smart and scalable mobile solution that leverages deep learning to detect rice plant diseases in real time. Designed to assist farmers and agronomists, this app transforms a smartphone into a powerful diagnostic tool. 📱🧠

🔍 Problem Statement
Rice crop diseases like Leaf Smut, Brown Spot, and Bacterial Leaf Blight can significantly reduce yield and farmer income.
Manual detection is labor-intensive, error-prone, and inaccessible to small-scale farmers.

CropIQ solves this by providing:

Instant disease detection

Visual diagnosis via smartphone

Actionable recommendations to mitigate risk

🚀 Key Features
✅ AI-Powered Detection
Classifies diseases using TensorFlow-trained deep learning models with ~95% accuracy.

✅ Simple & Intuitive UI
Easy-to-use mobile interface for farmers and field workers.

✅ Real-Time Feedback
Upload or capture a leaf image and get results within seconds.

✅ Edge Deployment
Lightweight TensorFlow Lite models ensure offline inference in rural areas.

🧠 Tech Stack
Layer	Tools & Frameworks
AI Model	TensorFlow, Keras, OpenCV
Backend API	Python, Flask
Deployment	TensorFlow Lite
Mobile App	Android Studio, Java/Kotlin
UI Components	XML, Jetpack, Glide

⚙️ Getting Started
🧾 Prerequisites
Python ≥ 3.7

TensorFlow 2.x

Flask

Android Studio

🛠️ Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/durjaysamrat/App-Based-Solution-for-Rice-Plant-Disease-Detection-using-tensorflow.git  
cd App-Based-Solution-for-Rice-Plant-Disease-Detection-using-tensorflow  
Install Backend Dependencies

bash
Copy
Edit
pip install -r requirements.txt  
Start the Flask Server

bash
Copy
Edit
python app.py  
Launch Mobile App

Open /android-app in Android Studio

Run on emulator/device

Connect to Flask backend via IP or localhost tunnel

📈 Results & Insights
🧪 Model Accuracy
Achieved ~95% test accuracy on rice disease dataset.

🦠 Detected Classes
Bacterial Leaf Blight

Brown Spot

Leaf Smut

🖼️ Sample Prediction Output
Input: Rice plant leaf image
Output: Disease Detected: Brown Spot



🤝 Contributing
We welcome contributors and collaborators!

💡 Got feature ideas? Raise an issue

🛠 Found a bug? Submit a pull request

📚 Want to improve docs? We love that too!

📬 Connect with Me




⭐ Support This Project
If CropIQ helped or inspired you, please give the repo a ⭐ and share it with others.
Together, let’s make smart agriculture accessible to every farmer. 🌱🚜
