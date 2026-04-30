# Лабораторные работы

Репозиторий содержит лабораторные работы по учебным дисциплинам, связанным с машинным обучением, методами искусственного интеллекта и компьютерным зрением.

Работы выполнены в формате Jupyter Notebook / Google Colab. В ноутбуках представлены этапы загрузки данных, предобработки, построения моделей, оценки качества и визуализации результатов.

## Содержание репозитория

### Методы искусственного интеллекта

| Файл | Тема | Используемые данные и методы |
|---|---|---|
| `ai_methods_lab_01_clustering_digits.ipynb` | Кластеризация и снижение размерности | Digits dataset, PCA, t-SNE, KMeans, DBSCAN, оценка качества кластеризации |
| `ai_methods_lab_02_ag_news_classification.ipynb` | Классификация текстовых новостей | AG News, TF-IDF, Logistic Regression, Linear SVM, Random Forest, GridSearchCV |
| `ai_methods_lab_03_california_housing_regression.ipynb` | Регрессионный анализ | California Housing, Linear Regression, Ridge, Random Forest, XGBoost, cross-validation |

### Математические методы машинного обучения

| Файл | Тема | Используемые данные и методы |
|---|---|---|
| `ml_lab_01_mnist_classification.ipynb` | Классификация изображений рукописных цифр | MNIST, нейронная сеть на Keras/TensorFlow |
| `ml_lab_02_lstm_sentiment_analysis.ipynb` | Анализ тональности текстовых отзывов | McDonald's Store Reviews, LSTM, обработка текстов, confusion matrix |
| `ml_lab_03_dcgan_celeba.ipynb` | Генерация изображений | CelebA, DCGAN, генератор и дискриминатор на TensorFlow/Keras |

### Компьютерное зрение

| Файл | Тема | Используемые данные и методы |
|---|---|---|
| `computer_vision_yolo_constellations.ipynb` | Детекция объектов на изображениях | YOLOv11, Roboflow dataset, Ultralytics, Optuna, оценка качества на validation/test |

## Используемые технологии

В работах используются:

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Hugging Face Datasets
- Ultralytics YOLO
- Roboflow
- Optuna
- KaggleHub
- Google Colab

## Как открыть работы

Ноутбуки можно открыть несколькими способами:

1. Через GitHub — открыть нужный `.ipynb` файл прямо в репозитории.
2. Через Google Colab — скачать файл или открыть его из GitHub.
3. Локально — через Jupyter Notebook / JupyterLab.

Для локального запуска рекомендуется установить зависимости:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow xgboost datasets transformers ultralytics optuna roboflow kagglehub

