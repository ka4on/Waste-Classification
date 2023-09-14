# Waste-Classification

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML311-Coursera/labs/Module3/L2/img/transfer_learning.gif" width="600" height="300">

The goal of this project is to use neural network to do image classification, specifically for waste. 

## Data
The data source comes from [kaggle](https://www.kaggle.com/datasets/techsash/waste-classification-data?datasetId=233210&sortBy=voteCount), contains 22500 images of organic and recyclable objects.

**Train:**  22564 images divided into Organic (O) and Recyclable (R)

**Test:** 2513 images divided into Organic (O) and Recyclable (R)

## Methodology
This project tries 4 different models: custom CNN, transfer learning with vgg16, a fine-tuned version, and transfer learning with Inception. Follow the [link](https://github.com/ka4on/Waste-Classification/blob/main/Final_Project.ipynb) to check out the notebook.

## Result
The fine-tuned VGG16 model performs the best with 91% accuracy on test data.
