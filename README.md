# Breast Cancer Classification Using Convolutional Neural Networks (CancerNet)

This project implements a deep learning classifier, **CancerNet**, to automatically detect malignant and benign breast cancer histology images using the IDC dataset.  
It demonstrates how Convolutional Neural Networks (CNNs) can assist pathologists in early diagnosis and improve treatment workflows.

---

## 📂 Project Structure

Project_2/

├── Breast_Cancer_Classification_1.ipynb # Main Jupyter Notebook with all code and results

├── requirements.txt # Python dependencies

├── README.md # Project overview and instructions

├── .gitignore # Files excluded from Git

└── datasets/ # (Place dataset here after download)


---

## 🚀 How to Install and Run

Follow these steps carefully:

### 1️⃣ Clone this repository

Open a terminal and run:

```bash
git clone https://github.com/Jathin-24/Project_2
cd Project_2
```

2️⃣ Set up a Python environment
```bash

python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
```
3️⃣ Install dependencies
```bash

pip install -r requirements.txt

```
4️⃣ Download the IDC Dataset
This project uses the IDC_regular dataset from Kaggle:
https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images

# Steps to download:

Log in to Kaggle and accept the terms.

Download the dataset ZIP file.

Extract it into the datasets/original folder inside your project directory so it looks like this:

datasets/
└── idc/
└── original/

Important:
Make sure your folder structure matches the expected Keras directory format or adjust the notebook paths accordingly.

5️⃣ Run the Notebook
```bash
jupyter notebook
```

