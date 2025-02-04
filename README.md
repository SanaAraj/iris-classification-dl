# 🌺 Iris Classification with Deep Learning 🌟

This project uses a **Deep Learning model** built with TensorFlow and Keras to classify the famous **Iris Flower Dataset**. The model is trained to predict the species of an Iris flower (Setosa, Versicolor, Virginica) based on its sepal and petal measurements.

---

## 📋 Features

- 📊 **Dataset Loading and Exploration**:
  - Loads the Iris dataset from a public repository.
  - Explores the dataset structure and checks for missing values.

- 🧹 **Data Preprocessing**:
  - Standardizes feature values using **StandardScaler**.
  - Encodes categorical labels into numerical format using **LabelEncoder**.

- 🧠 **Deep Learning Model**:
  - Constructs a neural network with fully connected layers.
  - Uses regularization techniques like **Dropout** and **L2 Regularization** to prevent overfitting.
  - Implements **EarlyStopping** to optimize training.

- 📈 **Evaluation Metrics**:
  - Generates a **classification report** with precision, recall, and F1-score.
  - Visualizes performance with a **confusion matrix**.

---

## 📝 Dataset Information

- The Iris dataset contains 150 samples of three species:
  - **Setosa**
  - **Versicolor**
  - **Virginica**
- Each sample has 4 features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

---

## 🛠️ Model Architecture

- **Input Layer**:
  - 4 features (sepal and petal dimensions)
- **Hidden Layers**:
  - Fully connected layers with **Dropout** and **L2 Regularization**
- **Output Layer**:
  - 3 neurons (one for each class) with **softmax activation**

---



## 🌟 Acknowledgments

Special thanks to **Dr. Mustafa** for guidance and support throughout this project. 🙌

---



