## Skin Cancer Detection Project: A Machine Learning Approach Using Deep Learning

### Overview
This project focuses on developing an machine learning solution for detecting skin cancer using deep learning techniques. Leveraging pre-trained convolutional neural network (CNN) models, this project aims to provide a accurate and efficient method for dermatological diagnosis.

### Highlights
- **Models Used**: DenseNet121, InceptionV3, Xception
- **Accuracy Achieved**: DenseNet121 (96%), InceptionV3 (76%), Xception (93%)
- **Dataset**: HAM10000 (10,000 dermoscopic images)

### Comparison of Models Accuracy, F1-Score and Macro Average ROC AUC
![Comparison of Models Accuracy, F1-Score and Macro Average ROC AUC](https://github.com/Html5intheway4/Skin_Cancer_Detection_Project/assets/69881519/4c826013-188f-4ecf-a7d8-954a58255bcc)

### Comparison of Average Accuracy of All Classes in percentage
![Comparison of Average Accuracy of All Classes in percentage](https://github.com/Html5intheway4/Skin_Cancer_Detection_Project/assets/69881519/5399d699-c27f-4241-a47c-010a95730076)

### Training and Validation Loss/ DENSENET 121
![Training and Validation Loss/ DENSENET 121](https://github.com/Html5intheway4/Skin_Cancer_Detection_Project/assets/69881519/a6e483b1-5529-494b-98d5-39b5a16cf842)

### Training and Validation Accuracy/ DENSENET 121
![Training and Validation Accuracy/ DENSENET 121](https://github.com/Html5intheway4/Skin_Cancer_Detection_Project/assets/69881519/5b5b5e9d-626a-494f-b59b-15bbcd58c7ee)


### Features
- **Transfer Learning**: Implemented transfer learning by fine-tuning the last layers of DenseNet121, InceptionV3, and Xception models, and adding custom classification layers for precise skin cancer classification.
- **Data Preprocessing**: Comprehensive preprocessing of the HAM10000 dataset, including image resizing and normalization, to ensure optimal training conditions and model performance.
- **Model Evaluation**: Thorough evaluation using accuracy metrics to compare model performance, highlighting DenseNet121's superior accuracy.

### Innovation and Impact
This project demonstrates the potential of deep learning in medical diagnostics, achieving competitive accuracy rates. By leveraging pre-trained models and fine-tuning them for specific tasks, it showcases the adaptability and power of CNNs in solving complex medical challenges.

### Real-World Application
- **Mobile Integration**: Developed a user-friendly mobile application using the Flutter framework, integrating TensorFlow Lite for real-time inference on dermoscopic images captured via camera or uploaded from the gallery. This app enhances accessibility to skin cancer detection, providing instant results and recommendations for further medical evaluation. [🔗](https://github.com/Html5intheway4/skin_cancer_detection)
<p float="left">
  <img src="https://github.com/Html5intheway4/Skin_Cancer_Detection_Project/assets/69881519/783e977f-6e9a-4b9f-8a9b-7a5a22c590bc" alt="Screenshot 2" width="200"/>
  <img src="https://github.com/Html5intheway4/Skin_Cancer_Detection_Project/assets/69881519/7489bce0-427d-4982-80b1-b8ac3f2e5fa4" alt="Screenshot 1" width="200"/>
</p>

### Technical Skills
- **Languages**: Python, Dart
- **Frameworks and Tools**: TensorFlow, Keras, Flutter, VS Code, GitHub, Anaconda, Android Studio

### Conclusion
This Skin Cancer Detection Project not only highlights the effectiveness of deep learning in medical applications but also demonstrates practical implementation through a mobile app. The high accuracy rates and real-time inference capabilities make it a valuable tool for aiding dermatological diagnosis.

## Contributors:
- Aman Prakash Kanth
- Giriraj Garg
- Ashutosh Kumar
- Shubh Raj

## Disclaimer:
This application is for educational and informational purposes only. It is not intended to provide medical advice or diagnosis. Always consult a qualified healthcare professional for medical advice and diagnosis.

## Feedback and Contributions:
Feedback and contributions are welcome! Feel free to open an issue or submit a pull request with any improvements or suggestions.
