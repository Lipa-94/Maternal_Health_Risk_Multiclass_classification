# Прогностическая модель группы риска для беременных (многоклассовая классификация)

**Цель**\
Создать модель, определяющую группу риска для беременных.

**Метрика**\
Определяется самостоятельно (F1-macro).

**Данные**\
В качестве источника данных взят датасет с Kaggle https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data
| Показатель | Описание |
|------------|----------|
| Age | Age in years when a woman is pregnant|
| SystolicBP | Upper value of Blood Pressure in mmHg, another significant attribute during pregnancy |
| DiastolicBP | Lower value of Blood Pressure in mmHg, another significant attribute during pregnancy |
| BS | Blood glucose levels is in terms of a molar concentration, mmol/L |
| HeartRate | A normal resting heart rate in beats per minute |
| Risk Level | Predicted Risk Intensity Level during pregnancy considering the previous attribute |

**Описание файлов**
* Maternal Health Risk Data Set.csv - датасет с данными;
* Maternal_Health_Risk.ipynb - тетрадь Jupyter Notebook с EDA и подбором модели.

**Используемые библиотеки**
* numpy
* pandas
* matplotlib
* seaborn
* phik
* shap
* sklearn
* catboost
