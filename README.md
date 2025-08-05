
# Pneumonia-XRay-Detector

A deep learning project using Convolutional Neural Networks (CNNs) to classify chest X-ray images and detect pneumonia. This model is designed to assist in medical diagnostics by providing a fast, automated tool for screening pneumonia from radiology images.

## 📌 Features
- Trains a CNN model on labeled chest X-ray images.
- Uses transfer learning with pretrained models (optional).
- Evaluates performance using confusion matrix and classification report.
- Includes data preprocessing, augmentation, and visualization.
- Splits data into training, validation, and testing sets.

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn
- Scikit-learn

## 🗂️ Project Structure
```
├── Pneumonia_Detection.ipynb     # Main notebook
├── dataset/                      # Chest X-ray image dataset
│   ├── train/
│   ├── val/
│   └── test/
├── models/                       # Saved model files
├── results/                      # Plots, confusion matrix, etc.
└── README.md                     # Project documentation
```

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/Pneumonia-XRay-Detector.git
cd Pneumonia-XRay-Detector
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook Pneumonia_Detection.ipynb
```

## 📊 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- Classification Report

## 📁 Dataset
This project uses the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) dataset from Kaggle.

## 📃 License
This project is licensed under the MIT License.

---
*This project is intended for educational and research purposes only. Not to be used for clinical diagnosis.*
