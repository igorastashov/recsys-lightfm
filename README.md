## Реализация рекомендательной системы на основе модели LightFM

Асташов И.В., 2024.

Проект выполнен в рамках курса «Машинное обучение» магистерской программы НИУ ВШЭ [«Машинное обучение и высоконагруженные системы»](https://www.hse.ru/ma/mlds/).


## Цель и задачи

**Цель**: Разработать рекомендательную систему с использованием модели LightFM и алгоритма ALS.


**Задачи**:

1. Загрузить и предобработать данные, включая удаление стоп-слов и лемматизацию текста;
2. Обучить модель LightFM с использованием различных признаков, включая текстовые описания, и оценить её качество на тестовой выборке;
3. Подобрать оптимальные гиперпараметры модели LightFM для улучшения ее качества;
4. Реализовать и вычислить метрики precision@k, recall@k и NDCG@k для оценки качества модели на тестовой выборке;
5. Сравнить результаты модели LightFM с встроенными метриками библиотек;
6. Реализовать и и обучить алгоритм ALS для построения рекомендаций и оценить его качество.

## Результаты

- Модель LightFM показала Precision@10 на тестовой выборке примерно 0.0074;
- Модель ALS показала Precision@10 на тестовой выборке примерно 0.0036.

## Выводы

- Модель LightFM имеет более высокую точность предсказания по сравнению с алгоритмом ALS на данном наборе данных;
- Для улучшения качества модели LightFM можно провести более тщательную оптимизацию гиперпараметров и использовать дополнительные признаки.