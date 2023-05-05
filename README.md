# Анализ свечных графиков

## Краткое описание
Данный pet-project выполняется совместно с другим участником.
Проект направлен на анализ свечных графиков, выявления закономерностей и прстроения прогноза по дальнейшему развитию графика.

Задача:
- Загрузить данные и привести в читаемый вид для дальнейшей обработки;
- Построить свечные графики по разным временным промежуткам;
- Для каждого открытия посчитать дельту отклонения к цене закрытия предыдущего дня.

Результаты:
- Написана функция для вывода свечных графиков с нужными периодами времени;
- Подсчитана дельта отклонения к уене закрытия прошлого дня.

Данные по ценам закрытия/открытия не выкладываются в общий доступ в связи с конфеденциальностью.

Стэк:

- Python
- JupiterHub

## Библиотеки для работы с графиками

```
import pandas as pd
import time
from datetime import datetime

# Библиотека для финансов
import mplfinance as mpf

# Библиотеки для визуализации
import seaborn as sns
import matplotlib.pyplot as plt
```
