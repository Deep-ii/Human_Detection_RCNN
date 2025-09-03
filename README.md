# Human Detection with Faster R-CNN

This repository contains a deep learning project that fine-tunes **Faster R-CNN with a ResNet50-FPN backbone** for human detection.  
The model is trained on the **Human Detection Dataset** from Kaggle and demonstrates how to build a custom object detection pipeline with PyTorch and TorchVision.

---

## 🚀 Features
- Dataset: [Human Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/constantinwerner/human-detection-dataset)
- Model: **Faster R-CNN ResNet50-FPN** with transfer learning.
- Pipeline includes:
  - Data preprocessing and annotation generation.
  - Custom PyTorch `Dataset` and `DataLoader`.
  - Model fine-tuning with transfer learning.
  - Evaluation and visualization of predictions.

---

## 📂 Repository Structure
│── NORTH_DINO.ipynb # Main Jupyter Notebook (training + evaluation)
│── README.md # Project documentation
│── LICENSE # License file (MIT)
│── requirements.txt # Python dependencies
│── CONTRIBUTING.md # Contribution guidelines


---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/human-detection-fasterrcnn.git
   cd human-detection-fasterrcnn


Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the notebook:

jupyter notebook NORTH_DINO.ipynb


The notebook will:

Download the dataset from Kaggle.

Prepare annotations.

Train Faster R-CNN on the dataset.

Evaluate and visualize predictions.


Set up Kaggle API key:

Download your kaggle.json from Kaggle Account Settings
.
Place it in the project directory.
