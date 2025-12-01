# LLM Fine-tuning Project

This repository contains a Large Language Model (LLM) fine-tuning and classification project.

## 📁 Project Structure

```
LLM_classification/
├── notebooks/           # Jupyter notebooks for training and analysis
│   └── llm-finetuning.ipynb
├── models/             # Trained model files (tracked with Git LFS)
│   └── model.pth
├── data/               # Dataset and data files (tracked with Git LFS)
│   └── archive.zip
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- PyTorch
- Jupyter Notebook
- Git LFS (for handling large files)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Likitha-Gedipudi/LLM_finetuning.git
cd LLM_finetuning
```

2. Install Git LFS if not already installed:
```bash
git lfs install
```

3. Pull LFS files:
```bash
git lfs pull
```

## 📊 Dataset

The dataset is stored in `data/archive.zip`. Extract it before training:
```bash
cd data
unzip archive.zip
```

## 🧠 Model

The trained model is saved as `models/model.pth` (701 MB) and is tracked using Git LFS.

## 📓 Notebooks

- **llm-finetuning.ipynb**: Main notebook containing the fine-tuning pipeline and training code

## 💾 Large Files

This project uses Git LFS to manage large files:
- Model files (`*.pth`)
- Archive files (`*.zip`)

## 📝 License

This project is open source and available for educational purposes.
