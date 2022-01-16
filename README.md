# pyshniy_kopatych_cv

Репозиторий по хакатону http://ivision.citylink.pro. Трек - Juniors.

Структура проекта:
```python3
pyshniy_kopatych_cv:
    model_inference.ipynb
    model_train.ipynb
models on Google Drive:
    ResNet50: https://drive.google.com/file/d/1yDUEkeqfDGaSOgKFP_1OVayCrPm91fBk/view?usp=sharing
```

Модель тестировалась с помощью GPU на Google Collab (tensorflow GPU).
Файл model_train.ipynb - подготовка данных, обучение модели, evaluation.
Файл model_inference.ipynb - ноутбук для проверки модели.

Для проверки модели, необходимо заменить переменную test_videos_path в model_inference.ipynb на путь к папке с тестовыми видео.

Результат хранится в переменной results структуры dict: {video_name : Car accident | No car accident}.