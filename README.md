# Исследование методов кластеризации на примере данных немецкого банка

## О проекте
В этом проекте я исследую различные методы кластеризации (k-means, иерархическая кластеризация, DB-Scan) для анализа клиентских данных банка. Основная цель - понять, как можно эффективно сегментировать клиентскую базу и какие инсайты можно получить из такого анализа.

## Что было сделано

### 1. Анализ и подготовка данных
- Провел исследовательский анализ данных (EDA) для понимания структуры и особенностей датасета
- Выполнил преобразование категориальных признаков в числовые
- Применил масштабирование данных для корректной работы алгоритмов кластеризации

### 2. Применение методов кластеризации
- Реализовал и сравнил три метода кластеризации:
  - K-means
  - Иерархическая кластеризация
  - DBSCAN
- Для определения оптимального количества кластеров использовал:
  - Метод локтя (Elbow method)
  - Silhouette plot
- Применил методы снижения размерности (PCA, UMAP, tSNE) для визуализации результатов

### 3. Анализ результатов
- Провел детальный анализ полученных кластеров
- Исследовал средние значения признаков для каждого кластера
- Построил визуализации (boxplot) для выявления характерных особенностей каждого сегмента
- Сформулировал практические выводы о структуре клиентской базы

## Используемые данные
В работе использовался датасет German Credit Risk: [https://www.kaggle.com/uciml/german-credit](https://www.kaggle.com/uciml/german-credit)

Файлы
bank-customer-clustering-research.ipynb - Jupyter notebook с решением

MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.