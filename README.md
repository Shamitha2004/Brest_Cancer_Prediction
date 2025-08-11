# Breast Cancer Detection using Machine Learning

# What is Breast Cancer?
Breast cancer occurs when abnormal cells in the breast grow and divide uncontrollably, often forming a tumor. While it is more common in women, men can also be affected. If untreated, the cancer can spread (metastasize) to other parts of the body, often through the lymphatic system.

Globally, breast cancer is one of the most common cancers in women and a major cause of cancer-related deaths. Early detection plays a crucial role in improving survival rates.

#🌍 Facts and Figures
Most common cancer in women and second most common cancer overall.
In 2018, there were over 2 million new cases worldwide.
Incidence rates per 100,000 women:
Netherlands: 95.3
France: 94.6
USA (White women): 90.6
India: 30.9


#💡 Role of Machine Learning in Detection
Mammograms are a common tool for early detection, but interpreting them accurately can be challenging for physicians.
Machine Learning can assist by analyzing patterns in breast tumor data to help classify tumors as benign (non-cancerous) or malignant (cancerous) with high accuracy.

#🧪 Project Description
This project demonstrates Breast Cancer detection using Machine Learning, specifically the Support Vector Machine (SVM) algorithm.

Key Highlights:
Dataset: Breast Cancer Wisconsin (Diagnostic) dataset
Directly available via sklearn.datasets.load_breast_cancer
Also included as a CSV file in this repository
Model: Support Vector Machine (SVM) with optimized parameters (C and Gamma)
Accuracy: ~97% after normalization and hyperparameter tuning

#📊 Results
Model	Accuracy
SVM (default)	96%
SVM (optimized)	97%

###📂 How to Run
Clone this repository:
git clone https://github.com/yourusername/breast-cancer-detection.git
cd breast-cancer-detection

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook Brest_Cancer.ipynb


