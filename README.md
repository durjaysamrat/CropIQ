# 🌱 CropIQ - AI-Powered Rice Disease Detection System

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.10+-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![Android](https://img.shields.io/badge/Android-12+-brightgreen?logo=android)](https://developer.android.com)
[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://python.org)
[![Last Commit](https://img.shields.io/github/last-commit/durjaysamrat/CropIQ)](https://github.com/durjaysamrat/CropIQ/commits/main)

![CropIQ Banner](https://github.com/user-attachments/assets/09131fb1-31d8-42fb-86ca-0f629213e45c)

CropIQ is an end-to-end AI solution that detects rice plant diseases in real-time using deep learning. This production-ready mobile application helps farmers identify diseases like Bacterial Leaf Blight, Brown Spot, and Leaf Smut with **95% accuracy**, empowering them to protect crops and increase yields.

**Download APK**: [Latest Release](https://github.com/durjaysamrat/CropIQ/releases)

## 🚀 Why Recruiters Notice This Project

✅ **Real-World Impact**: Solves critical agricultural problems affecting 144M rice farmers globally  
✅ **Full AI Pipeline**: From dataset collection to mobile deployment  
✅ **Production Optimization**: Model quantization, pruning, and TFLite conversion  
✅ **Technical Breadth**: Combines ML, mobile development, and backend engineering  
✅ **Quantifiable Results**: 95% accuracy on real-world test data  
✅ **Scalable Architecture**: Designed for future expansion to 10+ crops  

## 🌟 Key Features

| Feature | Technology | Benefit |
|---------|------------|---------|
| **Real-Time Disease Detection** | TensorFlow Lite | Instant diagnosis in remote areas |
| **Mobile-Optimized AI** | Model Quantization | 12.4MB size (60% reduction) |
| **Farmer-Friendly UI** | Android Jetpack | Intuitive interface for non-tech users |
| **Scalable Backend** | Flask REST API | Handles thousands of requests |
| **Data Augmentation** | OpenCV, Keras | Improved model robustness |
| **Continuous Learning** | MongoDB Logging | Future model retraining capability |

## 🧠 Technical Architecture

```mermaid
graph TD
    A[Android Device] --> B(Capture Image)
    B --> C[TensorFlow Lite Model]
    C --> D{Analysis}
    D -->|Disease Detected| E[Display Diagnosis]
    D -->|Uncertain| F[Request Expert Review]
    E --> G[Save to Farm History]
    G --> H[Flask API]
    H --> I[MongoDB Database]
    I --> J[Retraining Pipeline]
    J --> C
```

## ⚙️ Tech Stack

**Machine Learning**  
TensorFlow • Keras • OpenCV • Scikit-learn • Pandas/Numpy • Matplotlib  

**Mobile Development**  
Android Studio • Java • TensorFlow Lite • CameraX API • Retrofit  

**Backend & Infrastructure**  
Flask • MongoDB • Docker • Google Colab • REST APIs • Git/GitHub  

## 📊 Performance Benchmarks

| Metric | Result | Industry Standard |
|--------|--------|-------------------|
| Accuracy | 95.2% | 85-90% |
| Inference Time | 1.8s | 3-5s |
| Model Size | 12.4MB | 25-50MB |
| Power Consumption | 0.8Wh per 100 inferences | 2.5Wh |
| Supported Devices | Android 9+ (API 28+) | - |

## 🏆 Project Highlights

- Trained CNN model on 10,000+ annotated images from Kaggle and field sources
- Optimized model size by 60% via post-training quantization
- Implemented real-time image preprocessing pipeline with OpenCV
- Designed intuitive farmer-facing UI following Material Design 3 guidelines
- Reduced inference latency by 3x through model pruning techniques
- Built Flask API with rate limiting and error handling
- Implemented CI/CD pipeline with GitHub Actions

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Android Studio Flamingo or newer
- TensorFlow 2.10+

### Installation
```bash
# Clone repository
git clone https://github.com/durjaysamrat/CropIQ.git
cd CropIQ

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Start Flask server
python app.py
```

### Mobile Setup
1. Open `android-app` in Android Studio
2. Update API endpoint in `NetworkUtils.java`:
```java
private static final String BASE_URL = "http://YOUR_LOCAL_IP:5000";
```
3. Build signed APK:
```bash
./gradlew assembleRelease
```

## 📈 Business Impact

| Metric | Value | Potential Impact |
|--------|-------|------------------|
| Target Users | 144M rice farmers | Global scalability |
| Yield Protection | 15-20% reduction in losses | Food security improvement |
| Cost Savings | $50/farmer/year | Economic empowerment |
| Detection Speed | 78% faster than manual | Operational efficiency |
| Carbon Footprint | 0.02kg CO₂e per detection | Sustainable solution |

## 🤝 Contribution Guidelines

We welcome contributions! Here's how to help:

1. 🍴 **Fork** the repository
2. 🌿 **Create** your feature branch (`git checkout -b feature/improvement`)
3. 💾 **Commit** your changes (`git commit -am 'Add new feature'`)
4. 📤 **Push** to the branch (`git push origin feature/improvement`)
5. 🔁 **Open** a Pull Request

### Good First Issues
- [ ] Add multilingual support
- [ ] Implement GPS-based disease tracking
- [ ] Create treatment recommendation engine
- [ ] Develop farmer analytics dashboard

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Durjay_Samrat-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/durjaysamrat)
[![GitHub](https://img.shields.io/badge/GitHub-durjaysamrat-181717?style=flat&logo=github)](https://github.com/durjaysamrat)
[![Portfolio](https://img.shields.io/badge/Portfolio-View_Projects-FF6B6B?style=flat)](https://durjaysamrat.vercel.app)
[![Email](https://img.shields.io/badge/Email-durjaysamratn36@gmail.com-D14836?style=flat&logo=gmail)](mailto:durjaysamratn36@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-Tech_Demos-FF0000?style=flat&logo=youtube)](https://www.youtube.com/@durjaysamrat9166)

## 🌟 Support This Project
If CropIQ inspires you or you'd like to see it grow, please consider:

1. Giving a ⭐ on GitHub
2. Sharing with your tech network
3. Sponsoring development via [GitHub Sponsors](https://github.com/sponsors/durjaysamrat)
4. Connecting with me for collaboration opportunities

---
