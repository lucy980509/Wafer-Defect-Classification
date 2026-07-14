# Wafer-Defect-Classification

## 1. Project Overview
This project focuses on developing a deep learning model to automatically classify wafer defect patterns, aiming to improve yield rates in semiconductor manufacturing. A core challenge addressed in this research is the **inherent data imbalance** in manufacturing datasets. By implementing effective **class-weighting strategies**, this project seeks to mitigate bias and optimize the classification performance of the model.

## 2. Key Approaches
* **Data Imbalance Mitigation**: Addressing the disproportionate distribution of defect classes by applying custom **class-weighting strategies** to the loss function.
* **Model Development**: Utilizing the `PyTorch` framework to design and train a robust neural network architecture suitable for capturing complex wafer defect patterns.

## 3. Project Structure
```text
├── notebooks/Wafer_Defect_Classification.ipynb
├── requirements.txt
└── README.md
```
## 4. Setup
To replicate the environment for this project, install the necessary dependencies using the following command:

bash
pip install -r requirements.txt
