# Яндекс.Метрика API 

## Общая информация
В данном репозитории приведен пример использования API для сбора данных из Яндекс.Метрики. Данные, использованные для примера, взяты из открытого источника - Metrica Live Demo. 

![](https://static.tildacdn.com/tild6464-6462-4538-b633-633337383561/icon256x256.png)


## Описание файлов
Файл `Yandex.Metrika_API` включает в себя:
1. Подключение к открытому счетчику
2. Написание функции для автоматического формирования API запроса
3. Написание функции для конечного препроцессинга собранных данных
4. Пример написания нескольких запросов к Яндекс.Метрике:
- Отслеживание динамики изменения популярности разных операционных систем на сайте за 2 разных временных промежутка
- Подсчет количества сессий, начатых со всех страниц входа, кроме: `https://metrica.yandex.com/about`
- Составление списка самых популярных поисковых запросов, распределение их по 3 группам - низкочастотные, среднечастотные, высокочастотные запросы
- Отслеживание динамики изменения средней глубины просмотра на всех страницах сайта 
5. Визуализацию собранных данных

Посмотреть на графики, выполненные при помощи библиотеки `plotly`, можно в файле HTML формата. 

Примеры, описанные в файле `Yandex.Metrika_API`, взяты для сравнения в два временных интервала:
> 31 октября 2022 г. - 30 ноября 2022 г.
> 
> 1 января 2022 г. - 31 января 2022 г.