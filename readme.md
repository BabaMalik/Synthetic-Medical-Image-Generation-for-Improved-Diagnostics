# Synthetic Medical Image Generation for Improved Diagnostics

### Objective
###### Address the common problem of limited and imbalanced datasets in medical imaging by using GANs to generate realistic synthetic images of rare conditions. This can improve the training of diagnostic AI models.

# File Structure
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
