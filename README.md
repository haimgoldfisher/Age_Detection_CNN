# Age Detection with Convolutional Neural Network

This repository contains a project on age detection using convolutional neural networks (CNNs), along with preprocessing and modeling notebooks.
The main goal of this project is to accurately predict age groups from facial images.

## Project Overview

Age estimation from facial images is a challenging task in computer vision.
In this project, we explore various architectures, including softmax classification, neural networks with softmax, and CNNs,
to predict age groups based on facial features. We use the UTKFace dataset and the Age Facial dataset, which provide annotated facial images 
categorized into seven age groups.

## Contents

- **`Preprocessing.ipynb`**: This Jupyter notebook contains the preprocessing steps undertaken before modeling. It includes data augmentation strategies, train-test split, normalization, and other preprocessing techniques.
  
- **`Models.ipynb`**: This Jupyter notebook contains the implementation of the convolutional neural network (CNN) model architecture. It includes model building, training, evaluation, and hyperparameter tuning.

- **`Age_Detection_CNN.pdf`**: This PDF document provides a detailed overview of the project, including the background, methodology, experiments, results, and conclusions.

## Results

Our experiments show promising results, with the CNN model achieving an accuracy of 67.5% on the test set. We also compare the performance of different architectures and regularization techniques, providing insights into their strengths and weaknesses.

## Future Work

- Explore fine-grained age estimation techniques for more precise predictions.
- Investigate multi-face age estimation by improving preprocessing techniques to handle multiple faces in a single image.
- Experiment with larger datasets and higher-resolution images to enhance model generalization and accuracy.

## Contributors

- Haim Goldfisher
- Eliya Shlomo
- Nerya Reznickovich


## References

For more details on the datasets and related work, please refer to the PDF document and the provided links in the bibliography section.

Feel free to reach out to the contributors for any inquiries or collaborations. We welcome contributions and feedback to improve the project further.
