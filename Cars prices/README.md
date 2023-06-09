#Car's price

<b>Статус:</b> завершен

<b>Цель проекта:</b>

Нужно построить модель для вычисления рыночной стоимости автомобиля. 

<b>Задачи проекта:</b>

•	рассмотрим датасэт, содержащий: технические характеристики, комплектации и цены автомобилей.

•	избавимся от аномалий в данных.

•	подготовим данные для обучения.

•	обучим данные несколькими моделями.

<b>Итоги:</b>

Мы проанализировали датасэт с данными об автомобилях. Целью задачи было построение модели предсказания цены автомобиля.

На этапе предобработки данных:
•	удалили аномальные значения.
•	заполнили пропуски.
•	удалили неинформативные столбцы с датами и количеством фото.

На этапе обучения моделей рассмотрели:
•	DecisionTree
•	Ridge
•	Lasso
•	RandomForestRegression
•	LinearRegression

Модели бустинга:
•	LightGBM
•	CatBoostRegressor

Расчитали метрики RMSE и время выполнения моделей. Узнали важность признаков для каждой модели.

Лучший результат показала модель CatBoostRegressor RMSE=1574. Проверка на тестовой выборке подтвердила результат.

Самые важные признаки для этой модели:
•	год регистрации
•	мощность
•	пробег
•	бренд

<b>Используемый стек инструментов </b>

• python 
• pandas 
• sklearn 
• matplotlib 
• RMSE 
• catboost
• LightGBM
• RandomForest
• LabelEncoder
• Lasso
• Ridge
• cross_val_score
• gridSearch
• randomizedSearch
• DecisionTree
