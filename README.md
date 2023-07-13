# Zero Shot Learning

This repository contains the code and resources for the Zero Shot Learning. The project focuses on exploring and implementing various techniques and algorithms for zero-shot learning, a challenging task in the field of computer vision.

## Requirements

To run the code in this repository, ensure you have the following dependencies installed:

- Python 3.7 or above
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scikit-learn

Additionally, the implementation in the `ZSL_5flower.ipynb` and `ZSL_17flower.ipynb` files utilizes the CLIP model from OpenAI. 

## Datasets

The following datasets are used in the examples provided:

- 17 Flower Dataset: The [17 Flower Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/17/index.html) is used for experiments in the `ZSL_17flower.ipynb` file. It consists of images of 17 different flower categories. Please download and preprocess the dataset before running the code.

- 5 Flower Dataset: The [5 Flower Dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition) is used for experiments in the `ZSL_5flower.ipynb` file. It contains images of 5 different flower classes. Make sure to download and preprocess the dataset before running the code.

## Usage

This repository contains 3 files.

- `ZSL_5flower.ipynb` is using 5 flower dataset and CLIP model.
- `ZSL_17flower.ipynb` is using 17 flower dataset and CLIP model.
- `Transfer_Learning_TensorFlow.ipynb` is using 5 flower dataset and traditional DL approach using Tensorflow.

## Confusion Matrix

During the evaluation of the models, a confusion matrix is generated to visualize the performance of the models in predicting the correct labels. The confusion matrix provides insights into the true positive, true negative, false positive, and false negative predictions made by the model.

You can find the confusion matrix generated for the 5 Flower Dataset and Transfer Learning using Tensorflow. The matrix showcases the accuracy and performance of the model in classifying the flower images.

## Contributions

Contributions to this project are welcome! If you have any suggestions, bug fixes, or new implementations to contribute, please feel free to open an issue or submit a pull request.

## Acknowledgments

- [OpenAI CLIP](https://openai.com/research/clip/) for providing the CLIP model and resources used in the project.

Happy zero-shot learning!
