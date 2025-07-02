# Курсовая работа: ML для прогнозирования эффективности и токсичности соединений

## Структура репозитория

  - `data/`  
    - `course_data.xlsx` — исходные данные
    - `course_data_clean_log.xlsx` — обработанные и очищенные данные после EDA


  - `models/`
    - `rf_ic50_model.pkl` — обученная модель RandomForest для IC50
    - `lasso_cc50.pkl` — обученная модель Lasso для CC50
    - `scaler_cc50.pkl` — скейлер для признаков CC50
      
  - 1)`eda.ipynb` — исследовательский анализ данных (EDA)
  - 2)`Regression_IC50.ipynb` — регрессия для IC50
  - 3)`Regression_CC50.ipynb` — регрессия для CC50
  - 4)`Regression_SI.ipynb` — регрессия для SI (включая вариант через предсказания CC50/IC50)
  - 5)`Classification_IC50.ipynb` — классификация IC50 (> медианы)
  - 6)`Classification_CC50.ipynb` — классификация CC50 (> медианы)
  - 7)`Classification_SI.ipynb` — классификация SI (> медианы)
  - 8)`Classification_SI8.ipynb` — классификация SI (> 8)
