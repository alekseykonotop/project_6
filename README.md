# Проект №6 по итогам юнита №7 "Machine Learning в продакшн"  
## Введение  
Вас перевели в отдел инновационной разработки рекомендательных систем. Ваш работадель хочет увеличить средний чек продаж. После короткого изучения статей вы поняли, что ключом к успеху будет качественные рекомендации на сайте. Чем лучше вы сможете рекомендовать товар пользователю, тем чаще он будет добавлять товары в корзину. Простая логика, если пользователю нравится товар, он его добавляет в корзину -> средний чек растёт. Мы нашли золото!  

## Датасет  
У вас будет история оценок пользователя вместе с его обзором.  
Вы можете использовать текст рецензии в качестве дополнительной информации.  
Все оценки пользователей нормированы для бинарной классификации, если человек  
поставил оценку продукту больше 3 (не включительно), то мы считаем, что продукт  
ему понравился, если меньше 4, то продукт не понравился.    

**test.csv** - набор данных, для которого вы должны сделать предсказания.  
У каждого наобора userid, itemid есть свой id, для которого вы должны сделать предсказание.

- overall - рейтинг, который поставил пользователь
- verified - был ли отзыв верифицирован
- reviewTime - когда был отзыв написан
- reviewerName - имя пользователя
- reviewText - текст отзыва
- summary - сжатый отзыв
- vote - количество голосований за отзыв
- style - метаданные
- image - изображение продукта
- userid - id пользователя
- itemid - id товара
- id - id для предсказания  

## Этапы работы над проектом  
- Объединение датасетов  
- EDA  
- Data preprocessing  
- Feature engineering  
- outliers processing  
- Model (обучение, пресказание)
- Получение рекомендаций  

## Метрики  
В качестве метрики для оценки ваших рекомендаций используется RocAuc.  

## Никнейм на Kaggle  
Aleksey Konotop  
[Ссылка на лидерборд:](https://www.kaggle.com/competitions/recommendationsv4/leaderboard#)