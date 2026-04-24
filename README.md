ML-Based Intrusion Detection System (IDS)
This repository contains a machine learning framework for detecting network intrusions and anomalies using the NSL-KDD dataset. This project is part of a broader research initiative focused on improving security in IoT and Cyber-Physical Systems (CPS).

🚀 Project Overview
The goal of this project is to develop and evaluate robust detection models for various network attacks, including DoS, R2L, U2R, and Probing.

Current Status

[x] Repository initialized

[x] Dataset integration (NSL-KDD)

[ ] Data preprocessing and feature engineering

[ ] Baseline model implementation (CNN/RNN/Random Forest)

[ ] Integration of Selective State Space Models (Mamba)

[ ] Federated Learning implementation for decentralized IoT security

📊 Dataset
The project utilizes the NSL-KDD dataset, an improved version of the classic KDD'99 dataset.

Features: 41 features (38 numeric and 3 categorical)

Classes: Normal traffic and 4 main attack categories.

Files: KDDTrain+.txt is currently used for training and validation.

🛠️ Tech Stack
Language: Python 3.x

Environment: Jupyter Notebook / VS Code

Libraries: Pandas, NumPy, Scikit-learn, PyTorch (for Mamba/Deep Learning)

Version Control: Git & GitHub

📂 Project Structure
├── IDS_NSL-KDD.ipynb    # Main research notebook
├── KDDTrain+.txt        # NSL-KDD training data
├── .gitignore           # Files to be excluded from Git
└── README.md            # Project documentation

📖 Future Directions
A key focus of this research is the transition from traditional statistical methods to Federated Mamba. We aim to address the challenges of decentralized data and high-dimensional network traffic analysis in real-time IoT environments.