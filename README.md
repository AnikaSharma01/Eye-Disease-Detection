# 👁️ Eye Disease Detection

This repository is used to detect types of eye diseases through integrating the concepts of Artificial Intelligence(AI). It aims to detect eye diseases such as glaucoma, diabetic retinopathy, cataract, and normal eye conditions using model trained on a dataset imported from Kaggle.

## 🚀 Project Overview

The Eye Disease Detection project leverages deep learning techniques to classify images of eyes into four categories:
- Glaucoma
- Diabetic Retinopathy
- Cataract
- Normal

## 📂 Dataset

The dataset used in this project is sourced from Kaggle and contains labeled images of eyes with various diseases. You can find the dataset [here](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification).

## 🛠️ Installation

1. Clone this repository
2. Install the required dependencies
3. Download the dataset from Kaggle and place it in the `data` directory.

## 🧠 Model Training

To train the model, run the following command:
```bash
python train.py
```
This script will preprocess the data, train the model, and save the trained model to the `models` directory.

## 🔍 Model Evaluation

To evaluate the model, run:
```bash
python evaluate.py
```
This script will load the trained model and evaluate its performance on the test set, providing metrics such as accuracy, precision.

## 📊 Results

The results of the model evaluation, along with sample predictions. Here is a summary of the model's performance:
- Accuracy and Precision:
- Class level:
- 1.Cataract: 0.9431
- 2.Diabetic Retinopathy: 0.9858
- 3.Normal: 0.7823
- 4.Glaucoma: 0.6758
 
## 🤝 Contributing

We welcome contributions to enhance the project! If you'd like to contribute, please fork the repository and submit a pull request.


## 🙏 Acknowledgements

- Kaggle for providing the dataset.
- The open-source community for their invaluable resources and tools.

 
