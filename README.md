# Задача
Построить классификатор для определения того, является ли электронное письмо спамом или нет.

# Данные
Набор данных представляет из себя корпус документов, который разбит по классам:

- spam - спам (1);
- ham - не спам (0).

В обеих директориях датасета файлы представляют из себя набор .mbox файлов.

# Цели

1. Загрузите данные и подготовьте их для использования в модели классификации.
2. Используя алгоритм машинного обучения на ваш выбор, обучите классификатор на обучающей выборке.
3. Оцените производительность модели на тестовой выборке.
4. Визуализируйте несколько случайных электронных писем из тестовой
выборки и выведите предсказание модели для каждого электронного письма.

# Ссылки
- kaggle https://www.kaggle.com/code/miketsvirkunov/test1
- данные https://drive.google.com/uc?export=download&id=1LV_kUVFsz5eN0lul1jNVjVX6lpChNU9B
- модели https://drive.google.com/drive/folders/1yjBAqLEuUtJX5pVsQO55bfKVAI5HdG7X?usp=sharing

# Настройка среды
```bash
~/project$ python3 -m venv venv
~/project$ pip install -r req.txt
```
