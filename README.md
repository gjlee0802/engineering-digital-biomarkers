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

## KAIST ICLab Project - Research Intern
Period: 2024.07.01 ~ 2024.08.23 (5th Week ~ 8th Week)  
[Final Presentation Google Slide](https://docs.google.com/presentation/d/1L_wW0U8q1avQ7Idslrm_KxD4gqB5mlhuEmSXQoU07ZQ/edit?usp=sharing)
## Code Description
- [exploring_digital_biomarkers_a_day.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/exploring_digital_biomarkers_a_day.ipynb) : Data **Exploration**(for a day) Phase Related Code
- [feature_engineering.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/feature_engineering.ipynb) : Code of the **Data Preprocessing & Feature Engineering (Feature Extraction)** step
- [xgboost_regressor.ipynb](https://github.com/gjlee0802/engineering-digital-biomarkers/blob/main/xgboost_regressor.ipynb) : **XGBoost Regressor**(Cross Validation Methods: Leave One Subject Out, Partial Personalization)
- [SHapley Additive ex-Planations (SHAP) results](https://github.com/gjlee0802/engineering-digital-biomarkers/tree/main/shap_results): force_plot | heatmap | summary_plot per a day
- [Prediction plots](https://github.com/gjlee0802/engineering-digital-biomarkers/tree/main/prediction_plots)
## Preview Images
![prediction_vs_true_id_8_day_2](https://github.com/user-attachments/assets/2570ad97-8757-4235-ab86-05128499cc43)  
![xgbr_personalized_8_day_2_heatmap](https://github.com/user-attachments/assets/59f79190-b099-4f0b-8dd9-a21621ecbbcf)  
## Citation
### Resource
Cho, P., Kim, J., Bent, B., & Dunn, J. (2023). BIG IDEAs Lab Glycemic Variability and Wearable Device Data (version 1.1.2). PhysioNet. https://doi.org/10.13026/zthx-5212.

### Original publication
Bent, B., Cho, P.J., Henriquez, M. et al. Engineering digital biomarkers of interstitial glucose from noninvasive smartwatches. npj Digit. Med. 4, 89 (2021). https://doi.org/10.1038/s41746-021-00465-w
