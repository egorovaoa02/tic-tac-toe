### Вариант 1
Написать программу для игры в "Крестики-нолики" (tic-tac-toe) с компьютером на поле произвольного размера (от 3x3 до 10x10).

* * *

* Начинают ходить всегда крестики, кем играет человек определяется случайным образом. 
* Информация о датах и исходах всех партий, а также о всех ходах, сделанных во время игры, должна сохраняться в базе данных.
* Для каждой партии в базе должна храниться следующая информация:
    * Размер поля
    * Дата игры
    * Имя игрока
    * Какой фигурой играл человек
    * Какая фигура выиграла в партии
    * Запись ходов в формате: 
      `номер хода | координата X | координата O`
* В программе должны быть реализованы три режима:
    * Новая игра.
    * Вывод списка всех сохраненных партий.
    * Повтор любой сохраненной партии (то есть повтор всех ходов из этой партии).

## Требования
Минимальная версия PHP: 8.*
Минимальная версия Composer: 2.*

## Инструкция по установке и запуску игры
Из GitLab:

Склонировать проект на локальную машину;
Установить composer;
Перейти в корневой каталог;
Выполнить в консоли команду composer update;
Перейти в каталог bin из корнегого каталога и запустить Консоль и ввести "php start.php";

Из Packagist:

