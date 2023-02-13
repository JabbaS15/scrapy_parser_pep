# Scrapy PEP - Асинхронный парсер документов PEP на базе фреймворка Scrapy.

[![Python](https://img.shields.io/badge/-Python-464646?style=flat&logo=Python&logoColor=ffffff&color=013220)](https://www.python.org/)
[![Scrapy](https://img.shields.io/badge/-Scrapy-464646?style=flat&logo=Scrapy&logoColor=ffffff&color=013220)](https://scrapy.org/)

## Описание проекта:

Парсер, собирающий информацию с сайта https://www.python.org/
- версии языка и авторов версий;
- статусы всех стандартов PEP.

Вся собранная информация сохраняется в файлы с расширением **csv**:
- Информация о стандарте: номер, статус, автор-(ы);
- Колличество каждого статуса на сайте + общая сумма.

## Инструкция по развёртыванию:
1. Загрузите проект:
```bash
git clone https://github.com/JabbaS15/scrapy_parser_pep.git
```
2. Установите и активируйте виртуальное окружение:
```bash
python -m venv venv
source venv/Scripts/activate
python3 -m pip install --upgrade pip
```
3. Установите зависимости:
```bash
pip install -r requirements.txt
```
4. Запускаем парсер pep.
```
scrapy crawl pep
```


### Автор проекта:
[Шведков Роман](https://github.com/JabbaS15)
