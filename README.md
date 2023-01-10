# New Year project

## Drawing a snowflake
### Рисуем снежинку с использованием Черепашки

#### Рисуем один луч снежинки:
1) C помощью переменной line задаем длину луча
2) Заводим переменные size() и color()
3) Продвигаем черепашку на длину нашей линии, затем возвращаем ее назад на треть этой длины
4) Поворачиваем налево на 45 градусов, чтобы нарисовать узор на конце нашего луча. И продвигаемся вперед на треть длины луча.
5) Везвращаемся назад и повернем теперь направо уже на 90 градусов, чтобы нарисовать вторую часть нашего узора.
6) Повторяем команды, которые мы делали для рисования левой части.
7) После этого поворачиваем налево на 45 градусов, чтобы Черепашка смотрела в ту же сторону, в какую мы рисовали наш луч.
8) Возвращаемся в самое начало, откуда мы начали движение, проделав оставшиеся 2/3 пути.

#### Заводим цикл со счетчиком for, так как таких лучей у снежинки несколько:
1) Добавляем переменную n, отвечающую за количество лучей.
2) В конце цикла добавляем поворот Черепашки налево на 360/n, чтобы развернуть Черепашку и нарисовать другие лучи снежинки.


## Choice of wish
### Читаем случайно выпавшее пожелание из списка:
1) Создвем список из нескольких пожеланий
2) С помощью функции random.choice нам выпадает одно из пожкланий из списка
