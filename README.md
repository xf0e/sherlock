# Sherlock

Демонстрацию работы приложения можно посмотреть на YouTube: https://www.youtube.com/watch?v=uXp471N9mIY

Репозиторий с кодом построения самого классификатора: https://github.com/vnetserg/traffic-v2

Для запуска приложения необходим интерпретатор Python версии 2.7.х
с установленными библиотеками PyQt4, pcapy, sklearn, dpkt и numpy.
В качестве ОС требуется Linux, ибо на Windows нет pcapy.

Запускать необходимо с правами суперпользователя, иначе захват трафика не сработает.

После запуска надо кликнуть по зелёной иконке 'play' и выбрать конкретный
сетевой интерфейс (например, eth0). Не выбирайте 'any', это так не сработает!

Во время захвата трафика можно дважды кликнуть по любой строке таблицы, и откроется
wireshark с дампом данного потока (при условии, что у вас wireshark находится в PATH).

Заранее прошу прощения, но код писался как прототип, поэтому он плохо
читаем, и комментарии тут не помогут. Читайте на свой страх и риск.
