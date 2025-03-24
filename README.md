# 🏥 Skin Lesion Classification - Data Exploration & Model Training

## 📌 Overview
This repository contains a **Jupyter Notebook** that explores, preprocesses, and builds a **machine learning model** using the **HAM10000 dataset** for **skin lesion classification**. The notebook focuses on **data cleaning, visualization, preprocessing, and model training**.

---

## 📂 Dataset
The dataset used in this project is **HAM10000_metadata1.csv**, which contains metadata related to skin lesion images, including:

- **Lesion ID**
- **Image ID**
- **Diagnosis (dx)**
- **Diagnosis type**
- **Age**
- **Sex**
- **Localization of lesion**
- **Dataset source**

---

## 🔑 Key Steps in the Notebook

### 1️⃣ Data Exploration
- Loaded the dataset and **inspected its structure**.
- Checked for **missing values** and unknown values in important columns.
- Dropped incorrect or missing values (e.g., **unrealistic age values like 0**).

### 2️⃣ Data Visualization
- Plotted the **distribution of skin lesions** by localization on the body.
- Analyzed the **age distribution** of different lesion types.
- Identified **class imbalances** in the dataset.

### 3️⃣ Image Preprocessing
- **Addressed class imbalance** through **data augmentation**.
- **Normalized pixel values** for better model performance.
- Loaded and **converted images to RGB format** for model input.

### 4️⃣ Model Building & Training
- Encoded target labels using `LabelEncoder` from `sklearn.preprocessing`.
- Loaded **image data** from the dataset folder.
- Converted images into an **appropriate format** for model training.
- Implemented a **machine learning model** for classification.
- **Trained the model** using appropriate training and validation datasets.
- Evaluated **model performance** based on **accuracy and other metrics**.

---

## 📦 Requirements
To run the notebook, install the following dependencies:

```sh
pip install pandas matplotlib seaborn numpy scikit-learn opencv-python tensorflow keras
```

---

## 🚀 Usage

### 1️⃣ Clone this repository:
```sh
git clone https://github.com/yourusername/skin-lesion-analysis.git
cd skin-lesion-analysis
```

### 2️⃣ Open and run the Jupyter Notebook:
```sh
jupyter notebook 2235080.ipynb
```

---

## 🤝 Contributions
Feel free to **fork this repository** and submit **pull requests** for improvements! 🚀
