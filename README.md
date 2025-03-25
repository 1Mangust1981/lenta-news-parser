# Lenta.ru News Parser

Этот проект парсит новости с сайта Lenta.ru, извлекает заголовки, даты и ссылки, и сохраняет их в CSV-файл.
Возможности

![Lenta.ru](https://lenta.ru/favicon.ico)  
*Парсер новостей с Lenta.ru, созданный для простого анализа данных.*

    Извлекает заголовки, даты и ссылки.
    Сохраняет данные в CSV.
    Прост в использовании.

Требования

    Python 3.6+.
    Библиотеки: requests, beautifulsoup4.

Установка

    Проверьте Python: python3 --version
    Установите библиотеки: pip3 install requests beautifulsoup4
    Скачайте lenta_news_parser.py.

Использование

    Перейдите в папку: cd ~/Документы/3Пайтон
    Запустите скрипт: python3 lenta_news_parser.py
    Результат будет в lenta_news.csv.

Пример результата
text
title,date,url
"В России начался новый кризис","25 марта 2025","https://lenta.ru/news/2025/03/25/crisis/"
"Учёные нашли новый вид рыбы","25 марта 2025","https://lenta.ru/news/2025/03/25/fish/"
Структура проекта

    lenta_news_parser.py — скрипт.
    lenta_news.csv — результат.
    README.md — описание.
    .gitignore — исключения.

Примечания

    Парсит главную страницу Lenta.ru.
    Lenta.ru может изменить структуру.
    Используйте ответственно.

Автор

mangust1981
Лицензия

MIT. Подробности в LICENSE
