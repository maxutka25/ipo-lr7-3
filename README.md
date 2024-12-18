Написать программу которая:

При запуске выводит меню из которого человек выбирает следующие пункты (по средствам ввода номера пункта):
Вывести все записи
Вывести запись по полю
Добавить запись
Удалить запись по полю
Выйти из программы
После выполнения пунктов меню (кроме “выйти из программы”) меню отображается снова
Все записи хранятся в виде .json файла (любое название)
Пункт “Вывести все записи” — выводит в форматированном виде все записи из файла
Пункт “Вывести запись по полю” — выводит одну запись по определённому полю (поле id), а так же ее позицию в словаре.
Пункт “Добавить запись” — запрашивает у пользователя нужные данные и добавляет запись в файл
Пункт “Удалить запись по полю” — удаляет запись из файла по определенному полю (поле id)
Пункт “Выйти из программы” — завершает выполнение программы, но перед этим вводит на экран количество выполненных операций с записями
Пункты “Вывести запись по полю” и “Удалить запись по полю” должны выводить предупреждение если нужная запись не найдена
Программа должна хранить записи о городах
Структура записи:

id — номер записи
name — название города
country — название страны в котором находится город
is_big — хранить булевый тип данных, указывает на то является ли население города больше 100 000 человек
people_count — население города
