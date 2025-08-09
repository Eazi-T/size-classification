# size-classification
This project aims to correctly sort apples and tomatoes into various classes (Small, Medium, Large)

## 📁 Project Structure
```
fruit-size-classification/
├── size_class/
│    ├── Small
│    ├── Medium
│    └── Large
├── notebooks/
│   └── Apple_size_CNN
│   ├── Tomato_size_CNN
└── README.md
```

## 🎯 Objective
Compare traditional machine learning (SVM) with deep learning (CNN) in size classification of fruits.

## 🧠 Approach
Manual (SVM):
- Feature extraction using contour area, aspect ratio, and bounding box dimensions.
- Classification using Support Vector Machine (SVM).

Automatic (CNN):
- End-to-end classification using image pixels.
- Convolutional Neural Network trained on labeled fruit size images.

## 🛠️ Tools & Libraries
- Python
- OpenCV
- scikit-learn (SVM)
- TensorFlow / Keras (CNN)
- Matplotlib

## ✅ Conclusion
While SVM performed reasonably well with handcrafted features, CNN outperformed it by automatically learning relevant features from raw image data.
