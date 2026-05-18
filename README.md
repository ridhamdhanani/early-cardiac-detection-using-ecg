# Early Detection of Cardiac Abnormalities Using ECG

This repository contains the implementation code developed for the Bachelor's thesis:

**“Early Detection of Cardiac Abnormalities Using ECG”**

The project focuses on the application of deep learning techniques for automated ECG heartbeat classification using the MIT-BIH Arrhythmia Dataset. Multiple deep learning architectures including CNN, RNN, and GRU were developed, trained, and evaluated for detecting cardiac abnormalities.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Deep Learning Models

The following models were implemented and compared:

- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)
- Gated Recurrent Unit (GRU)

---

## Dataset

The dataset used in this thesis is publicly available on Kaggle:

Dataset Link:  
https://www.kaggle.com/datasets/shayanfazeli/heartbeat/data

The dataset is based on the MIT-BIH Arrhythmia Database and contains annotated ECG heartbeat signals for multi-class classification.

---

## Features of the Project

- ECG signal preprocessing
- Noise removal and normalization
- ECG heartbeat segmentation
- Deep learning model training
- Accuracy and loss analysis
- Classification reports
- Confusion matrix evaluation
- Comparative analysis of CNN, RNN, and GRU models

---

## Model Performance

| Model | Accuracy |
|---|---|
| CNN | 98.27% |
| GRU | 97.80% |
| RNN | 82.84% |

---

## Running the Project

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open the notebook:

```bash
jupyter notebook
```

3. Run:

```bash
ecg_cardiac_abnormality_detection.ipynb
```

---

## Thesis Information

**Author:** Ridham Dhanani  
**Institution:** Turku University of Applied Sciences  
**Degree Programme:** ICT / Health Technology  
**Year:** 2026

---

## License

This repository is intended for academic and research purposes.
