# CSCE753-ComputerVision-ReefDectection
## Overview
This repository provides Jupyter notebooks for evaluating and comparing the performance of several image classification and semantic segmentation model on coral reef detection tasks using underwater images.

## Models Evaluated
- **Deeplabv3** (trained from scratch)
- **Deeplabv3** (fine-tuned from pretrained weights)
- **UNet** (custom implementation)
- **PSPNet** (custom implementation)

## Repository Structure
```
.
├── Mod0_WholeImage_Classification      # Whole image classification implementation
    └── Classification_model_00.ipynb
├── Mod1_DLabv3-Pretrained-finetuned    # Deeplabv3 (fine-tuned) implementation
    └── Mod1_DLabv3-Pretrained-finetuned.ipynb
├── Mod2_DLabv3-Scratch                 # Deeplabv3 (scratch) implementation
    └── Mod2_DLabv3-Scratch.ipynb
├── CVRP_Project_Unet                   # Custom UNet implementation
    └── CVRP_Project_Unet.ipynb
└── CVRP_Project_PSPNet                 # PSPNet implementation
    └── CVRP_Project_PSPNet.ipynb
```

## Installation and Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/TranTri-vsc/CSCE753-ComputerVision-ReefDectection.git
cd CSCE753-ComputerVision-ReefDectection
```

### Step 2: Environment Setup
Create a Conda environment and install required packages:

```bash
conda env create -f environment.yml
conda activate coralreef
```

### Step 3: Running the Notebooks
Launch Jupyter Notebook in your Conda environment:

```bash
jupyter notebook
```

In your browser, open the notebook you'd like to run (e.g., `Mod1_DLabv3-Pretrained-finetuned.ipynb`) and execute the cells sequentially.

## Dataset

- **Dataset link:** [(https://www.kaggle.com/datasets/triminhtran/csce670-segmentation-dataset)]

## Results and Analysis
Performance comparisons and detailed analysis of each model are provided within each notebook. Further summarized results and detailed discussion can be found in the project report (`Final_Paper.pdf`).

---