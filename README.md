# Comparative Analysis of Machine Learning Models Using TensorFlow and Keras

## Description
This project aims to compare three machine learning models using TensorFlow, Keras, and a combination of both to classify mushroom data. The comparison is based on the accuracy and cost (loss) of the models.

## Contribution
This project is based on the original repository by [fiquinho](https://github.com/fiquinho/neural-network-projects/tree/master/tensorflow_base_models). We have extended the analysis and comparison of models, as well as implemented new visualization and evaluation techniques.

## Dataset
The dataset used in this project comes from Kaggle and can be found [here](https://www.kaggle.com/datasets/uciml/mushroom-classification). This dataset contains information about different types of mushrooms and their characteristics. It includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota family. Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended.

## Reference Paper
This project also draws on the paper [Deep Learning for Image Classification](https://arxiv.org/abs/2210.10351). The paper provides a theoretical and methodological foundation for the implementation of the models.

## Introduction
In this work, we compare two machine learning models: one using TensorFlow and the other using Keras. Additionally, we include the analysis of a model that combines both libraries. The importance of these libraries lies in their extensive use in image models, although in this case, we apply them to mushroom classification.

### Importance of TensorFlow and Keras
TensorFlow and Keras are two of the most popular libraries for developing deep learning models. TensorFlow is known for its ability to handle complex models and its accuracy in classification and prediction tasks. Keras, on the other hand, is a high-level library that facilitates the construction and training of models quickly and efficiently. Combining both libraries allows us to leverage the strengths of each, resulting in more efficient and accurate models.

### Model Analysis
- **Combined Model (TensorFlow and Keras)**: Offers the best combination of accuracy and cost. Combining both libraries allows us to leverage the strengths of each, resulting in a more efficient model.
- **TensorFlow Model**: High accuracy but higher cost. TensorFlow is known for its accuracy in complex models but can be more resource-intensive.
- **Keras Model**: Good accuracy and efficiency but not as efficient as the combined model. Keras is faster and easier to use, making it ideal for rapid prototyping.

### Results
The observed differences are slight due to the dataset size. However, with larger datasets, the differences in accuracy and cost would be more noticeable. Keras is faster, while TensorFlow is more accurate. Therefore, combining both is important to achieve a balanced model.

### Conclusion
The differences are slight due to the dataset size, but with larger datasets, the differences in accuracy and cost would be more noticeable. Combining TensorFlow and Keras offers the best efficiency and accuracy.

## Installation
To install the necessary dependencies, run the following command:
```sh
pip install -r requirements.txt



