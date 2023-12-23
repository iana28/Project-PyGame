# Project-PyGame
Наш проект - игра “Хранитель. Сокровища Богов Египта”, написанная в жанре лабиринт. Наш лабиринт меньше ориентирован на навигацию, но больше на то, какой последовательностью действий добраться до выхода. На игровом поле 4 игрока(охотники за сокровищами) и Хранитель, игроки должны выбраться из пирамиды, перехитрив Хранителя, забрав с собой как можно больше артефактов и алмазов (всего их в игре 36 шт. и 4 алмаза). 
артефакты и их количество:
1 - (16 шт.)
2 - (9 шт.)
3 - (6 шт.)
4- (5 шт.)

Выигрывает тот игрок, который собрал больше всего баллов(баллы изображены на артефактах (а алмазы придают большую ценность)).

У каждого игрока 14 карточек (своего цвета) с цифрами от 1 до 5(количество клеток на которые он может передвинуться) всего по три карточки с 1,2,3,4 и две карточки с 5. 
У Хранителя 20 карточек (для каждого игроком, по 5 карточек его цвета с числами от 1 до 5 (по одной шт.), для хранителя есть кубик(1 шт.) на гранях которого числа - 1, 2, 2, 3, 3, 4, после каждых ходов игроков ходит Хранитель на то количество клеток, которое выпало на кубике. Ходы игроков происходят таким образом: из колоды его карт берется 3 верхних карты и он выбирает одну из них (определив наиболее выгодный для себя ход), и так делает каждый игрок(получаеться 4 карты от каждого игрока), теперь из колоды Хранителя достается одна верхняя карта.

Теперь обратите внимание на выложенные карты. Цвет на карте Хранителя указывает, кого из игроков он выбирает в этот раз.
Остальные игроки ходят по полям карты на количество шагов, соответствующее баллам на их карточках. Сравните баллы на карточке Хранителя и выбранного им игрока.

Если количество баллов на карте игрока и Хранителя одинаковое, тогда и Хранитель, и игрок стоят на месте.

Если количество баллов на карте Хранителя больше, чем у игрока, тогда баллы на обеих картах складываются, и Хранитель перевритается по игровому полю на сумму баллов двух карт. А этот
игрок остается на месте.
Если количество баллов на карте Хранителя меньше, чем у игрока,
тогда Хранитель стоит на месте, а игрок передвигается по игрово-
му полю, высчитав разницу (баллы с карты Хранителя вычитаются
из баллов игрока).

Финиш — выход. из пирамиды — поле «exit». Участник игры,
достигший этого поля, выходит из пирамиды. Если Хранитель останавливается на поле «exit», тур (игра) заканчивается выход из
пирамиды закрыт. Игроки, оставшиеся на игровом поле, сдают все собранные артефакты в банк.
