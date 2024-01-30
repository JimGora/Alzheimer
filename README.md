# Histopatology Image Classification

This project uses TensorFlow/Keras and the EfficientNetB0 architecture to perform image classification on a 4-category dataset.

## Data Source

The proejct builds a model trained, validated and tested using the dataset from the paper:
["Hard Sample Aware Noise Robust Learning for Histopathology Image Classification"](https://ieeexplore.ieee.org/document/9600806){:target="_blank"}

```bash
@article{zhuhard,
  title={Hard Sample Aware Noise Robust Learning for Histopathology Image Classification},
  author={Zhu, Chuang and Chen, Wenkai and Peng, Ting and Wang, Ying and Jin, Mulan},
  journal={IEEE transactions on medical imaging}
}
```

## Repository Structure

- `data/`: Contains the training, validation and testing data sets.
- `notebooks/`: Jupyter notebooks with additional analysis and visualizations.
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
