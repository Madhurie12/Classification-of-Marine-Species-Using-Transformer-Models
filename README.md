# Shark Species Classification using Vision Transformers

This repository contains notebooks and code for classifying shark species using various Vision Transformer (ViT) architectures. The project leverages the **Shark Species** dataset from Kaggle: [https://www.kaggle.com/datasets/larusso94/shark-species](https://www.kaggle.com/datasets/larusso94/shark-species).

## 📂 Notebooks

The following Jupyter notebooks are included:

| Notebook | Description |
|----------|-------------|
| **ViT.ipynb** | Fine-tuning a Vision Transformer (ViT) model for shark species classification. |
| **Swin.ipynb** | Implementing a Swin Transformer for shark species classification. |
| **DEiT.ipynb** | Training a Data-efficient Image Transformer (DeiT) model on the shark dataset. |

## 🦈 Dataset: Shark Species

- **Source**: [Kaggle - Shark Species](https://www.kaggle.com/datasets/larusso94/shark-species)
- **Description**: A collection of images of various shark species, labeled by species name.
- **Usage**: The dataset should be downloaded and organized as follows:
  ```
  /data/
    /train/
      /species_1/
      /species_2/
      ...
    /val/
      /species_1/
      /species_2/
      ...
  ```

## 🚀 Getting Started

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Dependencies include:
- PyTorch
- Transformers (Hugging Face)
- timm (PyTorch Image Models)
- torchvision
- matplotlib
- scikit-learn
- Jupyter

### 2️⃣ Prepare the Dataset

- Download the dataset from [Kaggle](https://www.kaggle.com/datasets/larusso94/shark-species).
- Unzip and arrange the data into `train` and `val` folders.

### 3️⃣ Run the Notebooks

Open the desired notebook (`ViT.ipynb`, `Swin.ipynb`, or `DEiT.ipynb`) and execute the cells to train the models.

## 📊 Model Architectures

- **ViT (Vision Transformer)**: The original transformer model for image classification.
- **Swin Transformer**: A hierarchical Vision Transformer that computes representations with shifted windows.
- **DeiT (Data-efficient Image Transformer)**: A lightweight Vision Transformer that performs well with less data.

## 📈 Evaluation

Each notebook includes:
- Training and validation loops
- Loss and accuracy metrics
- Model saving/loading
- Visualization of results

## 📌 Notes

- All models are trained on the Shark Species dataset.
- Feel free to experiment with hyperparameters, data augmentation techniques, and different model architectures.

## 📧 Contact

For questions, please reach out via issues or discussions.