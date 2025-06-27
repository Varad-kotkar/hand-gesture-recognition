# ✋ Hand Gesture Recognition with CNN

🌟 A deep learning-based project that classifies 10 hand gestures using a Convolutional Neural Network (CNN) trained on the LeapGestRecog dataset. This is part of the **SCT ML Task 4** and demonstrates key machine learning practices such as dataset handling, preprocessing, training, evaluation, and visualization.

---

## 📆 Project Overview

This project focuses on recognizing static hand gestures captured in images. Using TensorFlow/Keras, we build a CNN model trained on the LeapGestRecog dataset directly downloaded via Kaggle API. The final model classifies 10 gesture classes with high accuracy and includes complete model evaluation.

---

## 🌟 Key Features

* Directly download dataset from Kaggle using API
* Clean and scalable CNN architecture
* Train/test split using `ImageDataGenerator`
* Real-time data augmentation
* Classification Report and Confusion Matrix
* Model accuracy: \~95%
* Visualizations of accuracy, loss, and predictions
* Export trained model to `.h5` format

---

## 📄 Dataset

* **Name**: LeapGestRecog
* **Source**: [Kaggle - gti-upm/leapgestrecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
* **Structure**:

  ```
  LeapGestRecog/
  ├── 00/
  ├── 01/
  ├── ...
  └── 09/
  ```

---

## 📊 Results

* Training Accuracy: \~98%
* Validation Accuracy: \~94-95%
* Low overfitting due to dropout
* Strong performance across all gesture classes
* Model saved in `model.h5`

---

## 🛠️ Tech Stack

* Python 3.10
* TensorFlow / Keras
* Matplotlib, Seaborn
* scikit-learn
* Kaggle API
* Google Colab

---

## 📅 How to Run

1. Upload `kaggle.json` for Kaggle API access
2. Clone this repository or open notebook in Colab
3. Run `gesture_recognition.ipynb` sequentially
4. All dependencies listed in `requirements.txt`

---

## 🔧 Future Improvements

* Integrate with OpenCV for real-time recognition
* Extend to dynamic gestures (video input)
* Convert to Streamlit/Flask app for live demo

---

## 📁 Files

* `gesture_recognition.ipynb`: Full Colab-compatible notebook
* `requirements.txt`: Dependencies
* `preview.png`: Sample result visualization
* `.gitignore`: To exclude unwanted files (e.g., `.h5`, `.ipynb_checkpoints`)

---

## 🚀 About Me

**Varad Kotkar**
Aspiring ML Engineer | Passionate about AI, DL, and Computer Vision
[GitHub](https://github.com/Varad-kotkar) | [LinkedIn](https://www.linkedin.com/in/varad-kotkar-1b5011294)

---

## 📂 License

This project is open-source under the [MIT License](LICENSE).
