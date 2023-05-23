# Waste-Classification

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML311-Coursera/labs/Module3/L2/img/transfer_learning.gif" width="600" height="300">

The goal of this project is to use neural network to do image classification, specifically for waste. 

## Data
The data source comes from [kaggle](https://www.kaggle.com/datasets/techsash/waste-classification-data?datasetId=233210&sortBy=voteCount), contains 22500 images of organic and recyclable objects.

**Train:**  22564 images divided into Organic (O) and Recyclable (R)

**Test:** 2513 images divided into Organic (O) and Recyclable (R)

An overview of images: 

<img src="https://www.kaggleusercontent.com/kf/100295176/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..SbdCp9szTNuwq7JU5IDwxA.fTqexfcjtVaF7ej7SAVcElJhgJWJRBqenAg4mCVbWcIycKry7FvwoLrTNn9aaXoX9lKFyvI7rKwr5k4ZAPtwnEC81XNic4mTQqqq8U09iF8Cq4hS2k0ZbmTMXvwTHQU5Id8TIgvez6HxzpYCv9BC82a6dOZFUPDTpTP4ouDK-T7z2HOa3eOMQFJFiUhZ0t7oEffXLocrvvDO1xPbiACbtxvwlpCDaj_UalbKPAN5UYhSKyZ_MFNlIie7zqP0DTjqfuA3JpZnkaJWFt7iC7n_ZMIp2JxDqD8ILDM60Ne_JtEZfqWmVAXR6UehpsvtfQRwYLPYC4jafdlqjJW080BUJ95eRbZyNuMXZgtOD-WFCgZnR1DzlQsMIbk1cSvFAw939RAG6W0bqtF7_BoJBh2QSMkduWSOUYozD_digAH3ewLBD-VJIHbEclmz1GEoE4p7KYV7iNSpX_zCCDsMsg2zpXmnDTDGjzZCQC4LJ9Ka6P2Kb6JRn4JjWx1wz5F-pqcMfhW9UXmtdrh8stJbRsWFJ2hVo0h2HRSovpk5gQeaXXxEYO5eH4UwzM01fwGe1c5UtcF5o_2PhFdUETW1_vWsckan1ULbrIyfBd__8PfELObVW5PpVWELeMx244itof-GgHNsHbtb8g-Vbe7K-RJCJSD1ef_MZVQOtYr-w2M4hE8.L9j8pkra80MboouYCv1y3Q/__results___files/__results___10_0.png" width="600" height="400">

## Methodology
This project tries 3 different models: CNN, transfering learning with vgg16 and a fine-tuned one. Follow the [link](https://github.com/ka4on/Waste-Classification/blob/main/Final_Project.ipynb) to check out the notebook.

## Result
The fine-tuned model performs the best with 91% accuracy on test data.
