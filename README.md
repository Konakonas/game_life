# game_life
Игра Жизнь(Life).

В данной программе есть поле 8х8 клеток, в котором происходит действие алгоритма задания. При пересечение края доски, расчет переходит на другую сторону(замкнутая и бесконечная доска).

Функционал:
1) Start - на доске можно отметить конкретные квадраты, которые будут являтся начальным положением игры. После нажатия кнопки Start происходит запуск игры, и раз в 1 секунду производятся расчеты положения следующих точек.

2)Random start - на доске случайным образом заполняются клетки и после этого происходит запуск игры, аналогично первому пункту

3)Поле "Array start position" и кнопка Download and start - в данное поле можно ввести массив точек, который будет выведен на поле и после кнопки Download and start произойдет загрузка и запуск игры. Ограничения: диапазон значений: 0-7, максимальное количество точек: 64.

В поле Количество циклов показывается количество итераций после последнего запуска.

