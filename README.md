# Асинхронный парсер  документов PEP на базе фреймворка Scrapy.

---
## Используемые технологии:
- Python
- Scrapy

---
## Установка:

- Клониеруем репозиторий.
```
git clone https://github.com/JabbaS15/scrapy_parser_pep.git
```
- Переходим в папку проекта.
```
cd scrapy_parser_pep
```
- Устанавливаем виртуальное окружение.
```
python -m venv venv
```
- Автивируем виртуальное окружение.
```
venv/scripts/activate
```
- Обновляем pip.
```
python -m pip install --upgrade pip
```
- Устанавливаем зависимости.
```
pip install -r requirements.txt
```
- Запускаем парсер pep.
```
scrapy crawl pep
```

---
### Автор проекта: [Jabba](https://github.com/JabbaS15/scrapy_parser_pep)