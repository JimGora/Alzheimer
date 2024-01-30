# Cell Classification Project

## Overview

This project focuses on classifying cell images into four categories using the EfficientNetB0 model. The Chaoyang dataset utilized is based on the "Hard Sample Aware Noise Robust Learning for Histopathology Image Classification" paper, and the goal is to develop an accurate-simple model for cell classification as Capstone 2 project for ML Zoomcamp 2023.

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)
- [Future Improvement](#future-improvement)
- [License](#license)

## Introduction

Cell classification is a crucial task in the field of cancer diagnosis. This project employs the state-of-the-art EfficientNetB0 model to accurately categorize cell images, aiming to contribute to advancements in machine learning and patology.

## Repository Structure

- `data/`: Contains the training, validation and testing data sets.
- `notebooks/`: Python scripts for model manipulation and visualizations.
- `src/`: Project source code, including the training and evaluation script.
- `saved_models/`: Directory to store the trained models.
- `requirements.txt`: List of necessary dependencies and versions.

## Dataset

The dataset used in this project is derived from the ["Hard Sample Aware Noise Robust Learning for Histopathology Image Classification"](https://ieeexplore.ieee.org/document/9600806) paper. It consists of a diverse set of cell images labeled into four distinct categories. 

- (0) Normal cells.
- (1) Serrated cells.
- (2) Adenocarcinoma cells.
- (3) Adenoma cells. 

The dataset is preprocessed and divided into training, validation, and testing sets.

```bash
@article{zhuhard,
  title={Hard Sample Aware Noise Robust Learning for Histopathology Image Classification},
  author={Zhu, Chuang and Chen, Wenkai and Peng, Ting and Wang, Ying and Jin, Mulan},
  journal={IEEE transactions on medical imaging}
}
```

## Model Architecture

The model architecture chosen for this project is EfficientNetB0. EfficientNetB0 is a powerful convolutional neural network known for its efficiency and high performance in image classification tasks. The model has been fine-tuned on the cell dataset to optimize its performance for this specific task.

## Usage

### Requirements

- Python (version 3.10.12)
- TensorFlow (version 2.15.10)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/JimGora/Classification.git
   cd cell-classification

## Acknowledgments
Acknowledge any specific individuals, organizations, or tools that contributed to the project.
Express gratitude to the authors of the ABC paper for providing the dataset.

## Contact
For any inquiries or issues, please contact:

Jimmy Gora: jimmy.r.gora@gmail.com

## Future Improvements
Train a different model and compare with other dataset to improve the model.

## License
This project is under the MIT license.
