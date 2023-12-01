# Исследование авторынка Казахстана

**Заказчик**: pet-проект

**Цели исследования**: выявление тенденций авторынка Казахстана по состоянию на 2019 год

**Объект исследования**: данные по продажам автомобилей в Казахстане за 2019 год, содержащие сведения о месяце и сумме продажи автомобиля, характеристики проданного автомобиля в разрезе диллеров

**Используемые технологии**: Python, библиотеки Pandas, Matplotlib, Numpy

**Тетрадка проекта**: [доступна по ссылке](https://github.com/NataliaSolntseva/KazakhstanCarMarketResearch/blob/main/Kazakhstan_Car_Market_Research_SolntsevaNS.ipynb)

**Лицензия распространения кода проекта**: Apache License 2.0 

**Задачи, которые были решены в ходе исследования**:
  - Загрузка данных из источника
  - Предобработка данных:
      - Проверка наименований столбцов датасета и при необходимости их переименование
      - Анализ пропусков в столбцах датасета, оценка возможности их заполнения
      - Проверка корректности типов данных, их изменение при необходимости
      - Проверка дубликатов в датасете (полных и неявных) и при необходимости их удаление
      - Проверка на корреткность и аномалии значений количественных и качетсвенных параметров датасета
  - Проведение исследовательского анализа данныз (EDA):
      - Предварительная подготовка данных для исследования, добавление новых столбцов датасета при необходимости
      - Исследование количественных параметров - базовые статистические параметры, гистограмма, проверка аномалий и выбросов в значениях
      - Исследование качественных параметров - частота значений параметров
  - Общий анализ авторынка Казахстана - топ самых продаваемых марок, динамика продаж,
  - Операционные показатели в сравнении между отстающим диллером и лидерами
  - Формулирование ключевых результатов исследования по тенденциям авторынка Казахстана
