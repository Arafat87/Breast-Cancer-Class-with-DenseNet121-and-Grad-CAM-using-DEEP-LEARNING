🧠 Hierarchical Breast Cancer Classification with DenseNet121
📘 Overview

This project builds a hierarchical deep learning model to classify breast cancer images into both binary (benign vs. malignant) and multi-class subtypes using DenseNet121. The goal is to leverage transfer learning and modern convolutional architectures to enhance diagnostic accuracy and support early cancer detection.

🎯 Objectives

- Stage 1 – Binary Classification: Distinguish between benign and malignant cases.

- Stage 2 – Multi-Class Classification: Further categorize samples into specific subtypes within each group.

- Goal: Develop an efficient, interpretable pipeline for hierarchical medical image classification.

🧩 Key Features

- Transfer learning with DenseNet121 pre-trained on ImageNet.

- Hierarchical modeling structure for stepwise cancer classification.

- Data augmentation and preprocessing pipeline for medical imaging.

- Performance metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

- Visualization of learned features and model predictions.

🧰 Tech Stack

- Languages: Python

- Frameworks: TensorFlow / Keras

- Libraries: NumPy, Pandas, Matplotlib, scikit-learn, OpenCV

- Environment: Jupyter Notebook / Google Colab

📊 Results

- The model demonstrates strong performance in identifying cancerous tissues, particularly through hierarchical classification, which improves interpretability and diagnostic precision.
