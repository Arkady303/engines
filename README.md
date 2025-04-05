# Кейс – Прогнозирование отказа моторов

В этом проекте разработана регрессионная модель для предсказания момента отказа мотора.

Анализ выполнялся с использованием *Python* и *Jupyter Notebook*.

---

## Задача

Необходимо создать модель, которая определяет последний цикл работы мотора перед его поломкой.

Данные о работе моторов представлены в файле `data_engines.csv`.

### Описание данных

| Поле | Описание |
|------|----------|
| id | Уникальный идентификатор мотора |
| cycle | Номер цикла |
| P00-P20 | Данные с датчиков |
| S1-S2 | Дополнительные показания счетчиков |

---

## Реализация проекта

- Проведел **разведочный анализ данных**.
- Визуализировал данные по циклам работы и показаниям датчиков для последних и остальных циклов.
- Подготовил **тренировочные и тестовые выборки**.
- Проведел **стандартизация признаков** для регрессионной модели.
- Обучил модель **Logistic Regression**.
- Оценил точность модели с помощью **матрицы ошибок** и **ROC-AUC**.
- Проведел эксперименты с альтернативными моделями машинного обучения (*Random Forest, Boosting*).
