# Парсер статей Pedsovet.org

Программа для сбора информации об образовательных статьях с главной страницы Pedsovet.org.

## Установка
```bash
pip install -r requirements.txt
'''
Запуск
'''bash
python parse_pedagogy.py
Результат
Создается файл education_articles.json со списком статей

Данные выводятся в консоль

Формат: название статьи + ссылка на полную версию

Зависимости
Python 3.6+

beautifulsoup4

requests

lxml
