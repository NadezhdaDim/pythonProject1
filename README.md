glavsnab parser
Парсит все товары одной категории с сайта https://glavsnab.net/. Сохраняет полученный результат в csv файл

Установка
Разработка велась на Python версии 3.12.0, советую использовать ее же. Скопируйте проект и установите зависимости, желательно использовать при этом виртуальное окружение/

Запуск
Поместите url категории в файл main.py и количество товаров в данной категории. Пример url: "https://glavsnab.net/stroymateriali/pilomateriali/vagonka.html?limit=100"

  python main.py
Результат появится в файле glavsnab.csv
