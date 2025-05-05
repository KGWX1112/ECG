This capstone project explores advanced deep learning methods for electrocardiogram (ECG) signal classification, emphasizing transformer-based models that capture both local and long-range temporal dependencies.

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

📈 Results

Model	Accuracy	F1-Score (Avg)	Remarks

A	94%	0.94	Strong feature learning with regularization

B	94%	0.94	Lightweight and efficient, ideal for embedded use

C	99%	0.99	Outperformed others on clean, low-dimensional data

📌 Key Takeaways
KNN surprisingly outperformed deep models on this dataset due to the clean, clustered feature space.

Deep models are better suited for complex or high-dimensional ECG scenarios.

Transformer-based architectures offer promising interpretability and performance tradeoffs.
