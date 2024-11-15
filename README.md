# Анализ рекламных компаний
## Цели проекта:
+ Провести анализ предоставленных данных
+ Выявить аномалии
+ Вычислить среднее количество дней от даты создания рекламного клиента и первым запуском рекламного объявления этим клиентом
+ Вычислить конверсию из создания рекламного клиента в запуск первой рекламы в течение не более 365 дней
+ Определить сколько уникальных клиентов запустили свое первое объявление в первый месяц своего существования

## В работе использован следующий стек:  
  <a href="https://jupiter.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/640px-Jupyter_logo.svg.png" width="36" height="36" alt="jupiter-notebook" /></a>
  <a href="https://pandas.org/" target="_blank" rel="noreferrer"><img src="https://i.pinimg.com/originals/ce/6e/14/ce6e14ee46d262be29c3efef8cd2e86d.png" width="80" height="36" alt="pandas" /></a>
  <a href="https://numpy.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/1200px-NumPy_logo_2020.svg.png" width="80" height="36" alt="numpy" /></a>
  <a href="https://seaborn.org/" target="_blank" rel="noreferrer"><img src="https://habrastorage.org/getpro/habr/upload_files/6c6/887/78d/6c688778d9df0ab8413b0fe1f65b33bb.png" width="80" height="36" alt="seaborn" /></a>
  <a href="https://plotly.com/python/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Plotly-logo.png" width="100" height="36" alt="plotly" /></a>


## Применялись следующие подходы:
+ Join таблиц
+ скользящее среднее
+ деление массива на промежутки и просвоение пользователям категории

## В ходе проекта мной было сделано:
+ Произведена проверка качества данных (пропущенные значения, количество строк, формат данных)
+ Предобработка данных в датафрейме (очистка от дубликатов и лишних значений)
+ Создана сводная таблица
+ Построен интерактивный график
+ Произведен расчет конверсии

#### Результат работы: получены ответы на все интересующие заказчика вопросы

Ознакомиться с файлом решения [тут](https://github.com/ncherniy/Prj1-analysis_of_ads_camps/blob/main/ADS_campaigns.ipynb)

--------------------
