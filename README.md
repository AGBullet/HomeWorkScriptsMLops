# MLOps Homework №1 Scripts
Этот репозиторий содержит набор скриптов для автоматизации работы с моделью машинного обучения. Скрипты создают наборы данных, выполняют предобработку, обучают модель и проверяют ее работу на тестовых данных.

## Репозиторий содержит следующие скрипты:

- data_creation.py - генерирует наборы данных для обучения и тестирования модели. Сохраняет данные в папки train и test.
- model_preprocessing.py - выполняет предобработку данных, используя StandardScaler из библиотеки sklearn. Сохраняет предобработанные данные в папки train и test.
- model_preparation.py - создает и обучает модель машинного обучения на предобработанных данных из папки train. Сохраняет обученную модель в файл model.pkl.
- model_testing.py - проверяет работу обученной модели на предобработанных тестовых данных из папки test. Выводит результаты проверки на экран.
## Запуск скриптов
Для запуска скриптов необходимо выполнить следующие шаги:

**1. Установить необходимые библиотеки:**

pip install numpy pandas sklearn joblib

**2. Запустить скрипт pipeline.bat(для Windows):**

Скрипт должен быть запущены из корневой директории репозитория. Результат работы скриптов будут сохранены в соответствующих папках и файлах, а также выведены на экран.
**2. Запустить скрипт pipeline.sh(для Linux):**

Скрипт должен быть запущены из корневой директории репозитория. Результат работы скриптов будут сохранены в соответствующих папках и файлах, а также выведены на экран.
