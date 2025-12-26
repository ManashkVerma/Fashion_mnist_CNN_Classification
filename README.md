# Fashion MNIST CNN Classification

## 📌 Problem Statement

The goal of this project is to build a **Convolutional Neural Network (CNN)** that can automatically classify images of clothing items from the **Fashion-MNIST dataset**.
Given a grayscale image of size **28×28 pixels**, the model predicts which category of clothing the image belongs to.

This is a **multiclass image classification** problem with **10 classes**.

---

## 🧠 Dataset Description

Fashion-MNIST is a dataset of Zalando’s article images, intended as a drop-in replacement for the original MNIST dataset.

- **Training samples:** 60,000
- **Test samples:** 10,000
- **Image size:** 28 × 28 (grayscale)
- **Classes:** 10

### Class Labels

| Label | Category      |
| ----- | ------------- |
| 0     | T-shirt / Top |
| 1     | Trouser       |
| 2     | Pullover      |
| 3     | Dress         |
| 4     | Coat          |
| 5     | Sandal        |
| 6     | Shirt         |
| 7     | Sneaker       |
| 8     | Bag           |
| 9     | Ankle Boot    |

---

## 📂 Dataset Availability

🚫 **The dataset files are NOT included in this repository** due to GitHub’s file size limits.

You can download the dataset from the official source:

👉 [https://github.com/zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)

Alternatively, the dataset can be loaded directly using machine learning libraries such as TensorFlow or PyTorch.

---

## ⚙️ Project Workflow

1. Load and inspect the Fashion-MNIST dataset
2. Preprocess the data (normalization & reshaping)
3. Visualize sample images
4. Build a CNN model
5. Train the model on the training set
6. Evaluate performance on the test set

---

## 🧪 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow / Keras
- Jupyter Notebook

---

## 📁 Project Structure

```
├── index.ipynb        # Jupyter notebook for data exploration & model training
├── README.md          # Project documentation
├── .gitignore         # Ignored files (datasets, system files)
```

---

## 🎯 Objective

The objective is to understand:

- How CNNs work on image data
- How to preprocess image datasets
- How to evaluate classification models
- Best practices for structuring machine learning projects

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Data augmentation
- Deeper CNN architectures
- Model performance comparison

---

This project is for **educational purposes**.
