# Cell Classification Project

## Overview

This project focuses on classifying cell images into four categories using the EfficientNetB0 model. The Chaoyang dataset utilized is based on the "Hard Sample Aware Noise Robust Learning for Histopathology Image Classification" paper, and the goal is to develop an accurate-simple model for cell classification as Capstone 2 project for ML Zoomcamp 2023.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Cell classification is a crucial task in the field of cancer diagnosis. This project employs the state-of-the-art EfficientNetB0 model to accurately categorize cell images, aiming to contribute to advancements in machine learning and patology.

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

- Python (version x.x.x)
- TensorFlow (version x.x.x)
- Other dependencies...

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/cell-classification.git
   cd cell-classification


# Histopatology Image Classification

This project uses TensorFlow/Keras and the EfficientNetB0 architecture to perform image classification on a 4-category dataset.



## Repository Structure

- `data/`: Contains the training, validation and testing data sets.
- `notebooks/`: Python scripts for model manipulation and visualizations.
- `src/`: Project source code, including the training and evaluation script.
- `saved_models/`: Directory to store the trained models.
- `requirements.txt`: List of necessary dependencies and versions.


## Environment Configuration

Make sure you have Python installed. You can install the dependencies using:

```bash
pip install -r requirements.txt
```




## Setting parameters
You can adjust the model parameters by editing the src/train_model.py file. Experiment with learning rate, batch size, and other hyperparameters as necessary.

## Results
The model results can be found in the notebook notebooks/analysis.ipynb. Includes performance metrics and views.

## Contributions
Contributions are welcome. If you find issues or improvements, please create an issue or submit a pull request.

## License
This project is under the MIT license.
