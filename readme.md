# Synthetic Medical Image Generation for Improved Diagnostics

### Objective
###### Address the common problem of limited and imbalanced datasets in medical imaging by using GANs to generate realistic synthetic images of rare conditions. This can improve the training of diagnostic AI models.

## 📁 Project Structure

synthetic_medical_gan/
├── data/
│   └── brain_tumor/
│       ├── yes/
│       └── no/
├── models/
│   ├── gan.py
│   ├── cnn_classifier.py
├── notebooks/
│   └── training_pipeline.ipynb
├── utils/
│   └── data_loader.py
└── main.py


### Description

- **data/brain_tumor/**: Contains subfolders `yes` and `no` for categorized brain tumor images.
- **models/**: Model definitions, including `gan.py` (GAN architecture) and `cnn_classifier.py` (CNN classifier).
- **notebooks/**: Jupyter notebooks for experiments and training pipelines.
- **utils/**: Utility scripts such as `data_loader.py` for data handling.
- **main.py**: Main entry point for running the project.

### How to Use

1. Clone the repository.
2. Prepare the dataset in the `data/brain_tumor/` directory.
3. Run `main.py` to start the project.

