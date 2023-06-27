# Air Quality Index Prediction - проект по предсказанию индекса качества воздуха.

Цель проекта построить модель,
которая будет предсказывать качество воздуха в регионе, на основании предыдущих измерений. В качестве данных будут использоваться основные загрязнители:
O3, SO2, NO2, CO, PM10, PM2.5

Члены команды:
* Чавдарь Дмитрий
* Чешко Георгий

Руководитель:
* Никитина Ксения


Запустить проект можно выполнив команду в директории проекта: <br>
* bash run.sh


Пример запроса для получения результата: <br>
* GET http://localhost:8000/predict?days=5 <br>
days - количество дней на которое предсказываем
