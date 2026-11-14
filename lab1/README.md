[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KseniaApaleeva/AI-course/blob/main/lab1/notebooks/lab1.ipynb)

# Практическое занятие 1. Рабочее окружение

Автор: Апалеева Ксения Андреевна, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в VS Code и выбрать ядро .venv

## Сравнение локальной среды и Colab

| | VS Code | Colab |
|---|---|---|
| Версия Python | 3.14.5 | 3.13 |
| Версия pandas | 3.1.1 | 2.2.3 |
| Где хранятся файлы | На моем компьютере (диск D) | На серверах Google (временно) |
| Что потребовалось для запуска | Установка Python, Git, VS Code, настройка окружения | Только браузер и аккаунт Google |