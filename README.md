# 🧠 Хакатон "Альфа Кампус Джуниор" — команда "Думаем" (May 2025)

## 📄 Задание хакатона

Это решение задачи, представленной на ML-хакатоне, проходившем в мае 2025 года в Лицее НИУ ВШЭ.  
[описание задачи](./task_description.pdf)

**Кратко о задаче**:  
Цель — предсказать перемещение клиентов по кластерам продуктов Альфа Банка.

---

## 📁 Структура проекта
```
├── data/
│ ├── train_data.pqt
│ ├── test_data.pqt
│ ├── sample_submission.csv
│ ├── features_description.xlsx
│ └── cluster_weights.xlsx
│ 01_data_overview.ipynb
│ 02_feature_engineering.ipynb
│ 03_model_training.ipynb
├── models/ # Сохранённые модели
│ ├── best_model.pkl
├── submissions/ # Финальные сабмиты
│ ├── submission.csv
├── task_description.pdf # Задание от организаторов
├── requirements.txt # Список зависимостей
└── README.md
```

---

## 📓 Описание ноутбуков

| Файл                           | Назначение                                                                                                      |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------|
| `01_data_overview.ipynb`       | Предварительный анализ данных, визуализация, выявление пропусков                                                |
| `02_feature_engineering.ipynb` | Создание новых признаков, кодирование категориальных переменных                                                 |
| `multiply_features.ipynb`      | Получение новых фичей путем перемножения важных признаков "всех со всеми". Отбор новых признаков с помощью feature importance |

---

## 🚀 Как запустить

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/BlackfireZZZ/AlphaBankHack
   cd AlphaBankHack
2. Установите зависимости:
   ```bash 
   pip install -r requirements.txt```
