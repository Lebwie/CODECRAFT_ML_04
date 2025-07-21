# 🤖 Hand Gesture Recognition - CODECRAFT_ML_04

This project implements a **Convolutional Neural Network (CNN)** to recognize hand gestures from grayscale images using the [LeapGestRecog dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog).  
It enables gesture-based control systems and intuitive human-computer interaction.

---

## 📁 Dataset

- **Source**: [Kaggle - LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Images**: 10 different gesture classes from 10 subjects
- **Grayscale, 64×64 resolution**

---

## 🧠 Model Architecture

- CNN with:
  - 2 × Conv2D + MaxPooling layers
  - 1 × Dense (128) + Dropout
  - Final output layer with Softmax (10 classes)

---

## 📊 Training & Results

- **Epochs**: 10  
- **Train/Val Split**: 80/20  
- **Final Test Accuracy**: `XX.XX%`  ← *(Replace with your result)*

### 📈 Training Curve

> *(Insert accuracy/loss plot image here)*

---

## 💾 Files

- `hand_gesture_model.h5`: Saved Keras model  
- `CODECRAFT_ML_04.ipynb`: Colab notebook with full code  
- `README.md`: You’re reading it.

---

## 🔗 Links

- 👨‍💻 **Author**: [Krishna Chopra](https://www.linkedin.com/in/krishnachopra)  
- 🐙 **GitHub**: [github.com/Lebwie](https://github.com/Lebwie)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
