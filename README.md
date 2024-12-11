### App-Based Solution for Rice Plant Disease Detection using TensorFlow

![Untitled_Export_V1](https://github.com/user-attachments/assets/20a47ee4-46bb-4e7f-8ace-8b9b96c635e6)

Rice Plant Disease Detection Application-In this project we have mainly focused on 3 diseases namely Bacterial Blight, BrownSpot and SheathRot, i have uploaded the model and the code for it , use android studio and kotlin for the in built libraries for easy creation of the application , will upload the code for the application soon,Read this file for better understanding of the model

This project aims to develop a mobile application that assists farmers in identifying rice plant diseases in real-time using advanced deep learning techniques. The application focuses on three major rice diseases: Bacterial Blight, Brown Spot, and Sheath Rot. By leveraging the YOLOv5 deep learning framework, the app provides accurate disease detection and offers localized treatment recommendations.

### Key Features
- **Real-Time Disease Detection**: Quickly identify rice plant diseases using your mobile device.
- **High Accuracy**: Achieves a model accuracy of 98.8% for disease detection.
- **Optimized for Mobile**: The app is designed to work efficiently on mid-range smartphones.
- **Offline Capability**: Use the app without an internet connection.

### Project Highlights
- **Data Collection and Preparation**: High-resolution images of rice leaves were collected and categorized into four groups: Bacterial Blight, Blast, Brown Spot, and Healthy. Data augmentation techniques were used to enhance the model's generalization capability.
- **Model Architecture**: The model is based on DenseNet with Squeeze-and-Excitation (SE) blocks and depthwise separable convolutions to improve feature recalibration and reduce computational cost.
- **Model Training**: The model was trained using a categorical cross-entropy loss function, achieving an accuracy of 98.8%.
- **Mobile Deployment**: The trained model was converted to TensorFlow Lite for mobile deployment, with post-training quantization applied for size reduction and compatibility with mid-range devices.
- **Android Application**: Developed using Android Studio and Kotlin, the app integrates the TensorFlow Lite model for real-time inference and provides an interactive interface for users to upload or capture images for analysis.

### Technical Details
- **Frameworks/Tools**: TensorFlow Lite, Android Studio, Kotlin
- **Model Performance**: 
  - Bacterial Blight: 99.1%
  - Sheath Rot: 98.75%
  - Brown Spot: 98.50%
  - Healthy Leaves: 99.25%
  - Inference Time: Less than 1 second per image on a mid-range device
  - Battery Efficiency: Optimized for low energy consumption

### Conclusion
This project provides a valuable tool for farmers, enabling them to manage rice plant diseases effectively and improve crop yield. The combination of advanced deep learning techniques and mobile technology offers a practical solution for real-world agricultural challenges.
