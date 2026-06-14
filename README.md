# CICIDS Semi-Supervised Classification

## Overview  
This notebook demonstrates a semi-supervised deep learning approach to classify network traffic from the CICIDS dataset. It utilizes a hybrid CNN-GRU architecture and pseudo-labeling to leverage both labeled and unlabeled data for improved intrusion detection.

## Features  
- Data loading and preprocessing from multiple CICIDS CSV files  
- EDA with visualizations of feature distributions and class balances  
- Feature selection based on correlation with target labels  
- Label merging and encoding for class consolidation  
- Semi-supervised training using both labeled and pseudo-labeled data  
- Hybrid CNN and GRU deep learning model for classification  
- Model evaluation with classification report and confusion matrix visualization  

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- Libraries: NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn, TensorFlow, Keras  

## How to Use  
1. Mount your Google Drive containing the CICIDS dataset CSV files.  
2. Run each cell sequentially to preprocess data, build, train, and evaluate the model.  
3. Modify file paths and parameters as needed for different datasets or experiments.  

## Status  
This notebook is organized and formatted for clear presentation and reproducibility on GitHub.