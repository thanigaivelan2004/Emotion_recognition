# Emotion Recognition using CNN

This project is a Deep Learning-based Emotion Recognition system developed using Convolutional Neural Networks (CNNs). It classifies human emotions from facial images using a publicly available Kaggle dataset. The project focuses on building an accurate and efficient model with image augmentation, evaluation metrics, and visualizations.

---

## 📂 Dataset

- **Source**: [Kaggle - Emotion Recognition Dataset](https://www.kaggle.com/datasets/sujaykapadnis/emotion-recognition-dataset)
- **Classes**:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral

---

## 🚀 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 🧠 Model Architecture

- Convolutional Layers (Conv2D)
- MaxPooling
- Dropout
- BatchNormalization
- Dense Layers
- Activation: ReLU and Softmax
- Optimizer: Adam
- Loss Function: Categorical Crossentropy

---

## 🔁 Data Preprocessing

- Image resizing and normalization
- Train-test split using `train_test_split`
- Image augmentation using `ImageDataGenerator` (rotation, zoom, flip)

---

## 📈 Evaluation

- Accuracy and loss curves plotted over epochs
- Confusion matrix to evaluate class-wise performance
- Achieved validation accuracy: `XX%` *(fill in after training)*

---

## 🖼️ Visualizations

- Sample images per emotion class
- Training vs validation accuracy/loss graphs
- Confusion matrix heatmap using Seaborn

---

## 🧪 How to Run

1. Download the dataset from Kaggle.
2. Extract the files into the working directory.
3. Run the notebook: `dl_new_mini_project.ipynb`
4. Follow the cell outputs to view results and evaluations.

---

## ✅ Future Work

- Integrate transfer learning (e.g., MobileNetV2 or ResNet50)
- Deploy as a web application using Flask/Streamlit
- Apply real-time emotion detection using OpenCV webcam

---

## 👨‍💻 Author

**Thanigaivelan P**  
B.Tech - AI & ML  
Kongu Engineering College  
[GitHub](https://github.com/thanigaivelan2004) | [LinkedIn](https://linkedin.com/in/thanigaivelanp)

---

## 📜 License

This project is licensed under the MIT License. Feel free to use and improve upon it.

