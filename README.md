# Игра про космос.

Игра в жанре классической аркады, вдохновлённая "Космическими Рейнджерами".

## Функционал
Реализованы 4 основные функции:
* Игра
  * Управляя космическим кораблём необходимо уничтожать корабли противника.
* Предыстория
  * Краткая предыстория мира игры и завязка сюжета.
* Настройки
  * Выбор схемы управления "WASD" и "стрелочки".
  * Настройка громкости фоновой музыки и эффектов.
* Выход.
  * Выход из программы.

## Использование

* Используя клавиши из схемы управления, выбранной в настройках игры, игрок может двигать корабль.
При нажатии на клавишу "пробел" происходит выстрел. Зажатие клавиши не изменяет количество выстрелов.
При попадании в корабль игрока у него снимается часть здоровья, индикатор которого расположен в верхнем правом углу.
При попадании игроком в корабль-противник без индикации уровня здоровья корабль уничтожается и за него начисляются очки, счётчик которых расположен в левом верхнем углу.
При попадании игроком в корабль-противник c индикацией уровня здоровья корабль теряет часть здоровья, что отображается на соответствющем индикаторе. При полном исчерпании здоровья корабль уничтожается и за него начисляются очки, счётчик которых расположен в левом верхнем углу.

* Снаряд игрока летит прямолинейно. Снаряд противника летит по оптимальной траектории для достижения позиции корабля игрока на момент выстрела.

* При потере игроком всего здоровья игра заканчивается и игрок может записать своё имя в таблицу рекордов.

* Игра содержит 10 уровней, генерируемых программой с учётом разрешения дисплея устройства.
