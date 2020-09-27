# toxic_comments_detection_model_prototyping
012. Построение модели для выявления токсичных комментариев

<b><u>Цель проекта:</b></u> Построение модели для выявления токсичных комментариев;

<b><u>Сферы деятельности компаний:</b></u> Интернет-сервисы, социальные сети, мессенджеры;

<b><u>Навыки и инструменты:</b></u> Токенизация, лемматизация, SpaCy, NLTK, градиентиный бустинг.

1. Загружен .csv-файл, изучены данные.
2. Проанализировано соотношение классов.
3. Написаны токенизатор и трансформер, созданы списки стоп-слов и знаков препинания. Произведена TF-IDF-векторизация.
4. Классы сбалансированы апсемплингом.
5. Собран пайплайн для преобразований текстов и обучения моделей. Обучены линейная регрессия, LGBMClassifier и KNeighboursClassifier, получены метрики: accuracy, precision, recall, F1-мера.
6. В качестве финальной модели выбрана линейная регрессия, построены PR-кривая и кривая ошибок, выполнена оценка AUC-ROC.

## Установка библиотек:
```python3
pip install pandas
pip install numpy
pip install scipy
pip install sklearn
pip install lightgbm
pip install spacy
pip install matplotlib
pip install seaborn
pip install math
pip install pymystem3
pip install nltk
pip install torch
pip install transformers
pip install string
pip install joblib
```
