# Построение модели для анализа распространения COVID-19 на основании открытых данных поисковых систем
![image](https://user-images.githubusercontent.com/70141111/140964292-3bc703f6-89b0-43f8-9c54-b99c2f76a7df.png)

### Основные скрипты:
1. pytrends.ipynb - основной файл для получения данных из Google Trends. Для MVP по трем странам (Китай, Россия и США) получен датафрейм 749384 rows × 39 columns. Его пример (sample на 50 000 строк) - daily_stat_by_countries_sample.csv

2. create_mvp_dataset.ipynb - немного визуализации данных и подготовка датасета для дальнейшего анализа
![image](https://user-images.githubusercontent.com/70141111/140964824-603efcb7-df6a-4d3e-98cb-c194e48d747c.png)

3. fls_covid_mvp_baseline.ipynb - используем sklearn LinearRegression для предсказания
![image](https://user-images.githubusercontent.com/70141111/140964873-442cab9d-bff8-4ddb-bafe-52959dab150b.png)

### Другие датасеты и вспомогательные данные:
ISO_country_codes - парсинга перечня стран и их ISO кодов из википедии

usa_codes.csv - датасет со штатами США

United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv - официальная статистика для каждого шатата. Centers for Disease Control and Prevention (CDC)

final_mvp_usa_df.csv - объединенный датасет
