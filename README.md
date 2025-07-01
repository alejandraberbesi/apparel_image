# 👚 Apparel Image Classification (2020)

This project uses a CNN to perform **multi-label classification** on apparel images from a Kaggle dataset. Each image is labeled with color and clothing type (e.g., `red pants`, `white dress`).

---

## 📦 Dataset

- Source: [Kaggle - Apparel Image Dataset](https://www.kaggle.com/datasets/airplane2230/apparel-image-dataset-2)
- 11 possible labels: `black`, `blue`, `brown`, `dress`, `green`, `pants`, `red`, `shirt`, `shoes`, `shorts`, `white`
- Combined data from `train`, `val`, and `test` into a single dataframe

---

## 🧠 Model

- Architecture: **ResNet34**
- Library: **fastai**
- Approach: Multi-label image classification using one-cycle training policy
- Accuracy threshold: **~98.7%** on validation set after 5 epochs

---

## 🛠 Tools

- Python
- fastai
- Pandas
- Kaggle CLI
