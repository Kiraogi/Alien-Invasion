# Игра "Инопланетное вторжение"

Каждый игрок управляет кораблем, который находится в середине нижнего края экрана.
Игрок перемещает корабль вправо и влево клавишами управления курсоров; клавиша "Пробел" используется для стрельбы.
В начале игры флот прищельцев находится в верхней части экрана и постепенно опускаеться вниз, также смещаясь в сторону.
Игрок выстрелами уничтожает прищельцев.
Если ему удасться сбить всех прищельцев, появляется новый флот, который движется быстрее предыдущего.
Если пришелец сталкивается с короблем игрока или доходит до нижнего края экрана, игрок теряет корабль.
Если игрок теряет все три корабля,игра заканчивается.

### Если вы хотите поиграть в увлекательную игру детства, где вы управляете космолетом, который отражает нашествие пришельцев, то для запуска игры на своем компьютере проделайте следующи шаги: (они описаны на примере Pycharm CE, но думаю, вы легко адаптируете их и для своей IDE).
1) Откройте Pycharm и на приветственном окне выберите кнопку "Get from VSC".
2) В открывшемся окне, в строке URL укажите ссылку: https://github.com/Kiraogi/Alien-Invasion
3) После того как репозиторий будет клонирован, Pycharm предложит создать виртуальное окружение, сделайте это.
4) Если во время создания виртуального окружения Pycharm не спросил у вас, нужно ли установить зависимости из файла requirements.txt, то в терминале выполните следующую команду "pip install -r requirements.txt" или пропишите в терминале "pip install pygame".
5) Все, приложение готово к запуску. Игра запускается в полноэкранном режиме, поэтому для выхода из игры используйте клавишу "Q".


# P:S
На разных операционных системах настройки скорости кораблей могут отличаться,
сейчас настройки выставлены под macOS,
поэтому если вам кажется, что корабль движется слишком медленно или наоборот, слишком быстро,
то поэкспериментируйте с настройками скорости в файле settings.py (ship_speed).

# Удачной игры!
