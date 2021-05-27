# resolved_case
Task from factory

pytrends.ipynb - основной файл для получения данных из Google Trends. Для MVP по трем странам (Китай, Россия и США) получен датафрейм 749384 rows × 39 columns. Его пример (sample на 50 000 строк) - daily_stat_by_countries_sample.csv

create_mvp_dataset.ipynb - немного визуализации данных и подготовка датасета для дальнейшего анализ

### Другие датасеты и вспомогательные данные:
ISO_country_codes - код парсинга перечня стран и их ISO кодов из википедии (в результате получился ISO_contry_codes.csv)

usa_codes.csv - список почтовых кодов штатов США

United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv - официальная статистика для каждого шатата. Centers for Disease Control and Prevention (CDC)

final_mvp_usa_df.csv - объединенный датасет
