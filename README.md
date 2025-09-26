
VisualIntelligence-XAI
This project compares the performance of a 2D Convolutional Neural Network (CNN) and a Scattering Network (ScatNet) for binary classification of lung cancer histopathological images. It also implements and evaluates an Explainable AI (XAI) method Occlusion to generate attribution maps for both models.

🎯 Objectives
Train a CNN and ScatNet on lung cancer histopathology images (adenocarcinoma vs benign).
Perform k-fold cross-validation to assess generalization.
Compare filters extracted from both models.
Implement an XAI method Occlusion from scratch.
Use Captum library to validate attribution maps.
Analyze and interpret the explainability results.
📁 Dataset
Source: Kaggle Dataset
Original Paper: arXiv:1912.12142v1
Classes Used: Adenocarcinoma vs Benign (binary classification)
🛠️ Technologies
Python, PyTorch, TorchVision
OpenCV, PIL, NumPy, Matplotlib
Scikit-learn, TQDM, Seaborn
Captum (for XAI comparison)
📊 Methodology
Dataset preprocessing and splitting
Implementation of:
CNN with fully connected classifier
ScatNet with same classifier structure
K-Fold cross-validation on both models
Evaluation: Accuracy and F1 Score
Filter extraction and comparison
Custom implementation of XAI method
Attribution maps with custom XAI and Captum
Visual and analytical comparison
📈 Results
CNN and ScatNet performance compared using mean Accuracy & F1 Score.
Filter visualization for both models.
Attribution maps validated via Captum.
Insightful comparison of interpretability and model behavior.
▶️ How to Run
Clone the repo
Install dependencies:
pip install -r requirements.txt
