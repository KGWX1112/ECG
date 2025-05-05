This capstone project explores advanced deep learning methods for electrocardiogram (ECG) signal classification, emphasizing transformer-based models that capture both local and long-range temporal dependencies.

📊 How to Run

1. Download the ECG_Research.ipynb file within the repo.
2. Run using programs that support .ipynb file such as Jupyter Notebook, Google Colab, or MS Visual Studio

🔍 Problem

Traditional models like K-Nearest Neighbors (KNN) struggle with ECG’s temporal structure. This project investigates whether hybrid CNN-Transformer architectures can improve classification performance while maintaining clinical relevance and interpretability.

🧠 Models Implemented

Model A: CNN + Transformer with Link Constraint Regularization

Model B: Lightweight CNN + Transformer for single-lead ECG (optimized for wearables)

Model C: Baseline KNN Classifier

🧪 Dataset & Methods

Dataset: ECG5000 (UCR Time Series Archive)

Preprocessing: Normalization, segmentation, and resampling

Evaluation Metrics: Accuracy, F1-Score, Precision, Recall, Confusion Matrix
