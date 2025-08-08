## Описание

Этот проект представляет собой анализ постов со стены пользователя VK с использованием Python, SQL и машинного обучения. Основная цель — извлечь статистику лайков в зависимости от различных факторов, таких как:
- День недели
- Время суток (утро, день, вечер, ночь)
- Интервалы между публикациями

## Содержание

├── .gitignore 
├── Interpretation_Rand_Forest.ipynb # Jupyter ноутбук для ML-интерпретации (Random Forest)
├── SQL_query.ipynb # SQL-анализ постов
├── requirements.txt 
├── res_sql_day_period.csv # Результаты SQL-запроса по времени суток
├── res_sql_posts_time_interval.csv # Результаты SQL-запроса по интервалам между постами
├── res_sql_week_days.csv # Результаты SQL-запроса по дням недели
└── vk_posts.db # SQLite база данных с постами

## Как запустить

1. Установить зависимости:
   ```bash
   pip install -r requirements.txt
   ```
Открыть и последовательно выполнить ноутбуки:
```
SQL_query.ipynb — SQL-анализ и визуализация

Interpretation_Rand_Forest.ipynb — Определение важности признаков через ML
```
Полученные результаты сохраняются в .csv или доступны через SQLite (vk_posts.db)

## Результаты

res_sql_week_days.csv — лайки по дням недели
res_sql_day_period.csv — лайки по времени суток
res_sql_posts_time_interval.csv — лайки по интервалам между постами
