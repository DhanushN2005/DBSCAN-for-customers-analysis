# DBSCAN Clustering

This repository contains a Jupyter Notebook implementing the **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm — a popular unsupervised machine learning method used for clustering data points based on density. :contentReference[oaicite:1]{index=1}

## 📌 About DBSCAN
DBSCAN groups closely packed points into clusters and identifies points in low-density regions as noise (outliers).  
Unlike K-Means, it does **not** require specifying the number of clusters in advance. :contentReference[oaicite:2]{index=2}

## 📂 Repository Structure
├── dbscan.ipynb # Jupyter Notebook with the DBSCAN implementation
├── README.md # This file

markdown
Copy code

## 🛠️ Requirements
Make sure you have the following installed:

- Python 3.x  
- Jupyter Notebook  
- scikit-learn  
- pandas  
- matplotlib  
- numpy

Install dependencies with:
```bash
pip install jupyter scikit-learn pandas matplotlib numpy
▶️ How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/DhanushN2005/DBSCAN.git
Navigate to the project folder:

bash
Copy code
cd DBSCAN
Launch Jupyter Notebook:

bash
Copy code
jupyter notebook
Open and run dbscan.ipynb
