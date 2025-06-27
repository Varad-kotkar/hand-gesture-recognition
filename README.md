# 🌟 Hand Gesture Recognition using CNN

A deep learning-based system that recognizes **10 static hand gestures** using a Convolutional Neural Network (CNN). Built using the [LeapGestRecog dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog), this project is part of the **SCT Machine Learning Track (Task 4)** and aims to demonstrate practical computer vision skills using TensorFlow, Keras, and scikit-learn.

## 🎓 Description

This project trains a CNN model to classify 10 hand gestures captured under different lighting conditions and backgrounds. The dataset is preprocessed using TensorFlow's ImageDataGenerator, and the model is evaluated using classification metrics and visualization tools. This model can serve as a foundation for gesture-controlled interfaces in accessibility tools, robotics, and AR/VR applications.

## 📂 Dataset

* **Name**: LeapGestRecog
* **Source**: [Kaggle - gti-upm/leapgestrecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
* **Structure**: 10 folders labeled 00 to 09, each representing a different hand gesture

## 🛠️ Technologies Used

* Python 3.10+
* TensorFlow & Keras
* NumPy, Matplotlib, Seaborn
* scikit-learn
* Kaggle API

## 📊 Project Highlights

* ✅ Loads dataset directly from Kaggle using the Kaggle API
* ✅ Preprocesses gesture images using `ImageDataGenerator`
* ✅ CNN model with Conv2D, MaxPooling, Dropout, and Dense layers
* ✅ Trained model achieves \~95% accuracy on validation set
* ✅ Model evaluation with classification report and confusion matrix
* ✅ Visualizes training history (accuracy and loss)
* ✅ Saves model as `model.h5`

## 📆 How to Run

1. Upload your `kaggle.json` to Colab
2. Clone this repo or upload files
3. Run all cells in `gesture_recognition.ipynb`

## ⚙️ Kaggle Setup

```python
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
!kaggle datasets download -d gti-upm/leapgestrecog
```

## 🚀 Future Work

* Real-time gesture recognition using OpenCV
* Deploy with Streamlit/Flask as a web app
* Use transfer learning with pre-trained models

## 📃 Files in Repo

* `gesture_recognition.ipynb`: Main notebook with model code
* `requirements.txt`: Python packages required
* `model.h5`: Trained model (saved)
* `preview.png`: Visualization of results (optional)

## 🧑‍💻 Author

**Varad Kotkar**
[GitHub](https://github.com/Varad-kotkar) • [LinkedIn](www.linkedin.com/in/varad-kotkar-1b5011294)

## ✨ License

Licensed under the [MIT License](LICENSE).

---

> This project was developed as part of **SkillCraft Machine Learning Track (Task 4)** and demonstrates practical application of CNNs in computer vision. Feel free to fork, contribute, or extend this into a live gesture recognition system!
