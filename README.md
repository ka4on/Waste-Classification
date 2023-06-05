# Waste-Classification

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML311-Coursera/labs/Module3/L2/img/transfer_learning.gif" width="600" height="300">

The goal of this project is to use neural network to do image classification, specifically for waste. 

## Data
The data source comes from [kaggle](https://www.kaggle.com/datasets/techsash/waste-classification-data?datasetId=233210&sortBy=voteCount), contains 22500 images of organic and recyclable objects.

**Train:**  22564 images divided into Organic (O) and Recyclable (R)

**Test:** 2513 images divided into Organic (O) and Recyclable (R)

An overview of images: 

<img src="https://www.kaggleusercontent.com/kf/100295176/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..A9f1s0N3BmYo4Z3WLWT-aQ.C2bS7URU9ZqrWDcoej11pR09_3s397mUdXKZL6iE2OaeuWGojWEw4aoQm-IKNb4VsrhZr46LPkyW3_UK9GNatF3C6_ZVj27ioC45pj27XdtiGjoxxeqCLwHH3dGy5AJxVvwg-SEX1d3HK16Qi5AoCXNJIziD3TZ9xlnM5Iwozno0uVJOnHbQLP32XdcNReVyelsOHWR_9kysliJG3BPI1l7Z93IfKLmqPcGRTKihaFNuStvN733Ag39nDI76vXK_21QUlYd69HJZ80mDV7HB371WNR1083KkvqfkFgoQzkYsxRi1eXr32dsQ0PDb_qNHGQ19K9myawksD8VIL2J7ltqI7lUB8AlfTgoP1mqOOTH94_-Ll7IdlK1z6vKLg5O37OeYEFUT3lxhjymsl-vEF0gFcp8aTEVi8oLGPMk9hBa9yooh1UZaGm_lR4qOdJ2-i0Wjcsn3L-tlsaJ9PwmyMsiUN3oBohK1np7B0ruRSs1-sxrdSxTZvMyiAJTBAr08HXibj4siMlwcACbTyGDK4EzYTWUjkGiHkC-toJz3NN9ID9P-YNXx7A7I8DmXkKyBqo64aoeSH0TMAY1qsoGkamoJ0IcspDq8hf6oXLras8hdz2xFpqqSE6dxt4jfCeNiIB0di53tuJqE2l6uPTRjBvoM9cdKC4tIjNvEL7dXSp4.M70AKBIa46ObkyRPEgGhpw/__results___files/__results___10_0.png" width="600" height="400">

## Methodology
This project tries 4 different models: custom CNN, transfer learning with vgg16, a fine-tuned version, and transfer learning with Inception. Follow the [link](https://github.com/ka4on/Waste-Classification/blob/main/Final_Project.ipynb) to check out the notebook.

## Result
The fine-tuned VGG16 model performs the best with 91% accuracy on test data.
