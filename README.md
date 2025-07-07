# # 🫁 Chest X-Ray Pneumonia Classification

This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images as either **Normal** or **Pneumonia**. It is a binary image classification task implemented using TensorFlow and Keras.

## 📊 Model Performance

- **Validation Accuracy**: **91.13%**
- Trained using augmented chest X-ray data from the popular Kaggle dataset.

## 🧠 Key Features

- Custom CNN architecture for X-ray image classification
- Data preprocessing and augmentation to improve generalization
- Visualization of model accuracy and loss during training
- Evaluation on validation and test datasets

## 🗂 Dataset

The dataset used is the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) from Kaggle. It contains:

- **Normal** chest X-ray images
- **Pneumonia** (bacterial or viral) chest X-ray images

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Matplotlib
- NumPy

## 🚀 How to Run

1. Clone this repository.
2. Download the dataset from Kaggle and extract it into the working directory.
3. Open and run the notebook `Chest_X_Ray_classification.ipynb` using Jupyter Notebook or Google Colab.
4. Follow the code cells step-by-step to preprocess the data, train the model, and evaluate the results.

## 🧪 Example Output

- Training and validation accuracy/loss plotted over 10 epochs
- Final prediction examples with actual vs predicted class
- Model achieves **91.13% accuracy** on the validation set

## 📌 Motivation

Medical imaging is a powerful tool in diagnosis. Automating the detection of pneumonia can help doctors quickly identify critical cases and allocate resources efficiently. This project explores the effectiveness of CNNs in detecting pneumonia through chest radiographs.

---

### 📬 Contributions and Feedback

Feel free to fork the repo, raise issues, or suggest improvements. Feedback is always welcome!


