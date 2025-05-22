# 🧠 ML Hackathon Solution — Team "DataWizards" (May 2025)

## 📄 Hackathon Task

Это решение задачи, предложенной на ML-хакатоне, проходившем в мае 2025 года.  
Организаторы предоставили задание в PDF-документе: [task_description.pdf](./task_description.pdf)

**Кратко о задаче**:  
Цель — [вставьте краткое описание задачи, например: "предсказать отток клиентов по транзакционным данным", "классифицировать объекты по спутниковым изображениям", и т.д.]

---

## 📁 Структура проекта
```
├── data/ # Папка с данными (примерные или вымышленные)
│ ├── train.csv
│ ├── test.csv
├── notebooks/ # Jupyter-ноутбуки с экспериментами
│ ├── 01_data_overview.ipynb
│ ├── 02_feature_engineering.ipynb
│ ├── 03_model_training.ipynb
│ ├── 04_model_evaluation.ipynb
│ ├── 05_submission.ipynb
├── models/ # Сохранённые модели
│ ├── best_model.pkl
├── submissions/ # Финальные сабмиты
│ ├── submission.csv
├── task_description.pdf # Задание от организаторов
├── requirements.txt # Список зависимостей
└── README.md # Этот файл
```

---

## 📓 Описание ноутбуков

| Файл | Назначение |
|------|------------|
| `01_data_overview.ipynb` | Предварительный анализ данных, визуализация, выявление пропусков |
| `02_feature_engineering.ipynb` | Создание новых признаков, кодирование категориальных переменных |
| `03_model_training.ipynb` | Обучение моделей (baseline + экспериментальные) |
| `04_model_evaluation.ipynb` | Оценка качества моделей, построение метрик, кривые ROC/PR |
| `05_submission.ipynb` | Подготовка финального предсказания в формате submission.csv |

---

## 🚀 Как запустить

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. Установите зависимости:
```bash 
pip install -r requirements.txt```
