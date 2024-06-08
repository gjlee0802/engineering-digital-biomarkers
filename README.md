# Predicting glucose levels with data collected by non-invasive devices
This is a project to predict glucose by learning data collected by wearable devices.

With collected data(Accelerometer, Blood volume pulse, Electrodermal activity, Temperature, Interbeat interval, Heart rate, Food Log, Interstitial glucose concentration), feature engineering is performed to utilize meaningful features for learning.

## Team members
- 이경주 (Team Leader)
- 서민경
- 김지수
- 남광규

## Code Description
- [exploring_digital_biomarkers_a_day.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/exploring_digital_biomarkers_a_day.ipynb) : Data Exploration(for a day) Phase Related Code
- [feature_engineering.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/feature_engineering.ipynb) : Code of the Feature Engineering step
- [df_glucose_histogram.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/exploring_digital_biomarkers_a_day.ipynb) : Histograms of three glucose level classifications(PersLow / PersNorm / PersHigh)
- [randomforest_regressor.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/randomforest_regressor.ipynb) : LOOCV Random Forest Regressor & Feature Importance
- [LightGBM_Classifier_forPull.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/LightGBM_Classifier_forPull.ipynb) : Classifier Model Using LightGBM
- [lightGBM_regressor.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/lightGBM_regressor.ipynb) : LOOCV Regressor Model Using LightGBM
- [pycaret_classifier_undersampling.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/lightGBM_regressor.ipynb) : Exploring classification model with PyCaret (Class-balanced Using Under Sampling)
- [pycaret_classifier_smote.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/lightGBM_regressor.ipynb) : Exploring classification model with PyCaret (Class-balanced Using SMOTE)
- [pycaret_regressor.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/pycaret_regressor.ipynb) : Exploring LOOCV regressor model with PyCaret (PCA performed)
## Citation
### Resource
Cho, P., Kim, J., Bent, B., & Dunn, J. (2023). BIG IDEAs Lab Glycemic Variability and Wearable Device Data (version 1.1.2). PhysioNet. https://doi.org/10.13026/zthx-5212.

### Original publication
Bent, B., Cho, P.J., Henriquez, M. et al. Engineering digital biomarkers of interstitial glucose from noninvasive smartwatches. npj Digit. Med. 4, 89 (2021). https://doi.org/10.1038/s41746-021-00465-w

### Standard citation for PhysioNet
Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
