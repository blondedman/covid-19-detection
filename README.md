# detecting COVID-19 with chest X-rays using PyTorch
this project focuses on the image classification of chest X-rays, categorizing them into one of three classes: normal, viral pneumonia, or COVID-19.

## DATASET
the model is trained on the [COVID-19 Radiography Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) from kaggle.

## MODEL USED

the classification is performed using a pre-trained `resnet18` model from PyTorch's `torchvision` library. the final fully connected layer is modified to output 3 classes.

## GETTING STARTED
install the necessary libraries using pip:

```bash
pip install torch torchvision numpy matplotlib pillow
```

## NOTEBOOK STRUCTURE
the notebook is organized into the following sections:
- Importing Libraries
- Preparing Training and Test Sets
- Creating Custom Dataset
- Image Transformations
- Prepare Dataloader
- Data Visualization
- Creating Model
- Training Model

## RESULTS
the model is trained to classify the X-ray images with the goal of achieving high accuracy. the training process includes evaluation steps to monitor validation loss and accuracy. the training stops when an accuracy of 95% is reached.