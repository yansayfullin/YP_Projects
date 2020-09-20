### Прогнозирование количества заказов такси  
**Описание:**  
Имеются исторические данные о заказах такси. Необходимо построить модель для прогнозирования количества заказов такси.
  
**Инструменты:**  
LightGBM, Scikit-learn, Statsmodels, Pandas.  
Времянные ряды, машинное обучение, создание признаков.

**Цель:**  
Построить модель для прогнозирования количества заказов такси и минимизировать метрику RMSE.

**Выводы:**  
Получилось добиться результата RMSE 38.09 на тестовой выборке. Наиболее влияющие на точность предсказания признаки: простая скользящая средняя с периодом 5 (17% от общего веса) и сдвиг с периодом 3 (14% от общего веса).

**Статус проекта:**  
Завершен.