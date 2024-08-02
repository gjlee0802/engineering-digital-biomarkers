# Predicting glucose levels with data collected by non-invasive wearable device
This is a project to predict glucose by learning data collected by wearable devices and food logs.

With collected data(Accelerometer, Blood volume pulse, Electrodermal activity, Temperature, Interbeat interval, Heart rate, Food Log, Interstitial glucose concentration), feature engineering is performed to utilize meaningful features for learning.

## Data Science Lecture Team Project - Team members (May 20th ~ June 9th)
Led this project as a data science lecture team project.  
From: 24.05.20  
To: 24.06.09  
- [이경주 (Team Leader)](https://github.com/gjlee0802)
- [서민경](https://github.com/mingg12)
- [김지수](https://github.com/itsthejisoo)
- [남광규](https://github.com/kwanggyu99)

## Code Description
- [exploring_digital_biomarkers_a_day.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/exploring_digital_biomarkers_a_day.ipynb) : Data **Exploration**(for a day) Phase Related Code
- [feature_engineering.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/feature_engineering.ipynb) : Code of the **Data Preprocessing & Feature Engineering** step
- [df_glucose_histogram.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/df_glucose_histogram.ipynb) : **Histograms of three glucose level** classifications(PersLow / PersNorm / PersHigh)
- [randomforest_regressor.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/randomforest_regressor.ipynb) : LOOCV Random Forest Regressor & **Feature Importance**
- [LightGBM_Classifier_forPull.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/LightGBM_Classifier_forPull.ipynb) : **Classifier** Model Using **LightGBM**
## Citation
### Resource
Cho, P., Kim, J., Bent, B., & Dunn, J. (2023). BIG IDEAs Lab Glycemic Variability and Wearable Device Data (version 1.1.2). PhysioNet. https://doi.org/10.13026/zthx-5212.

### Original publication
Bent, B., Cho, P.J., Henriquez, M. et al. Engineering digital biomarkers of interstitial glucose from noninvasive smartwatches. npj Digit. Med. 4, 89 (2021). https://doi.org/10.1038/s41746-021-00465-w
