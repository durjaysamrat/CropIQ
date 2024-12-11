![Untitled_Export_V1](https://github.com/user-attachments/assets/20a47ee4-46bb-4e7f-8ace-8b9b96c635e6)

Rice Plant Disease Detection Application-In this project we have mainly focused on 3 diseases namely Bacterial Blight, BrownSpot and SheathRot, i have uploaded the model and the code for it , use android studio and kotlin for the in built libraries for easy creation of the application , will upload the code for the application soon,Read this file for better understanding of the model

Project Overview
The present project undertakes the objective to develop an application meant for mobile bases with the objective of assisting farmers to get proper real-time identification of rice plant diseases through the adaptation of sophisticated deep learning techniques. The application is implemented using Kotlin and supports intervention by also recommending appropriate and prompt interventions while identifying prevalent rice diseases accurately.

Introduction
Rice is the primary crop among the cultivated, more so in the Indian region of Telangana. It acts as a primary aspect of the agricultural economy. However, quite often it falls under severe attacks of various diseases such as Bacterial Blight, Blast, and Brown Spot, which cut down the yield of the crop heavily. This project came up with an Android-based application using machine learning, which can rapidly diagnose these diseases, thus creating an armament for farmers with a critical tool for proper disease management.
Characteristics
Real-Time Disease Detection
High Model Accuracy: 98.8%
Optimized for Mobile Devices
Off-line Capability
Localized Therapy Recommendations**
Sequential Project Procedure

1. Data Collection and Preparation**
Images of rice leaves formed a high-resolution dataset, with samples falling into four categories-those affected by Bacterial Blight, Blast, Brown Spot, and Healthy.
Used data augmentation techniques to enhance generalization capability of the model. Here, were performing:
- Rotations to simulate diverse angles of a leaf.
- Shading: Enhancement to mimic other light intensities.
Horizontal and vertical flips should be incorporated into the process to create a model to verify robustness.
- Changes in color for testing changes that can be seen on natural leaves.

2. Evolution of the Architectural Framework
- The basis structure was taken from the DensNet for the feature reuse.
Implemented Squeeze-and-Excitation (SE) blocks to improve feature recalibration, allowing the model to focus on particular characteristics associated with diseases.
We applied depthwise separable convolutions to reduce computational cost without the trade-off in model accuracy.

3. Training the Model
Use a categorical cross-entropy loss function while training with a dataset of your choice, for the model.
The accuracy was 98.8%. Furthermore, the value of recall and precision for all categories of diseases were also high.

4. Improvement of the model
It converted the trained model to TensorFlow Lite for mobile deployment.
Applied post-training quantization on the model for size reduction and for obtaining compatibility with mid-range devices.

5. Design of Android Applications
- Developed in Android Studio employing Kotlin to guarantee that the application possesses a contemporary appearance and is user-friendly.
The TensorFlow Lite model was integrated to the app to enable real-time inference.
Allow the users to take a new image or upload an existing one for analysis through setting up the interface of your application.

6. Implementation of Application Features
A centralized disease-detection set up for off-line operation.
The interface is interactive with the prediction of the disease and the score confidence.
It will also provide region-specific information and treatment recommendations concerning Telangana to farmers.

7. Critical Evaluation and Practical Application
The application was tested on several Android-based devices to ensure it would work and be compatible.
Tested for speed and accuracy in a variety of situations, both with adequate daylight and with limited.

Technical Details
Frameworks/Tools: TensorFlow Lite, Android Studio, Kotlin.
DenseNet model with depthwise separable enhancement.
Deployment: Mobile-ready with real-time performance on mid-range smartphones.

Performance of Model
Cumulative Precision: 98.8%
Individual sickness detection
Bacterial Blight: 99.1%
Sheath Rot: 98.75% 
Brown Spot: 98.50% 
Healthy Leaves: 99.25% 
Inference Time: Less than 1 second per image on a mid-range device.
Battery Efficiency: Lower energy consumption enables high-level use in real-world environments.
