### Урок 4


Составить грамотную нормализованную схему хранения этих данных в БД. Внести в нее 4–5 фильмов, расписание на один день и несколько проданных билетов.
Сделать запросы, считающие и выводящие в понятном виде:
>ошибки в расписании (фильмы накладываются друг на друга), отсортированные по возрастанию времени. Выводить надо колонки «фильм 1», «время начала», «длительность», «фильм 2», «время начала», «длительность»;
>перерывы 30 минут и более между фильмами — выводить по уменьшению длительности перерыва. Колонки «фильм 1», «время начала», «длительность», «время начала второго фильма», «длительность перерыва»;
>список фильмов, для каждого — с указанием общего числа посетителей за все время, среднего числа зрителей за сеанс и общей суммы сборов по каждому фильму (отсортировать по убыванию прибыли). Внизу таблицы должна быть строчка «итого», содержащая данные по всем фильмам сразу;
>число посетителей и кассовые сборы, сгруппированные по времени начала фильма: с 9 до 15, с 15 до 18, с 18 до 21, с 21 до 00:00 (сколько посетителей пришло с 9 до 15 часов и т.д.).

####Полностью сделать не удалось. Успел только корректно прописать таблицы с данными. Не удалось оформить ни один из расчетев, - нашел пример решения на MySQL, но так и не удалось преобразовать его на H2