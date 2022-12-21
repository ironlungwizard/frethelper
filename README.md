#frethelper

##Цель

Разработка веб-приложения для помощи при игре на струнных ладовых инструментах. Приложение должно показывать расположение нот на грифе при различных конфигурациях инструмента и давать возможность самостоятельно его конфигурировать.

##Юзкейсы

###Usecase 1 

Пользователю нужна 6-струнная гитара в стандартном строе. (соответствующая настройка установлена в системе по умолчанию)

1. Пользователь заходит на страницу сервиса.

###Usecase 2
Пользователю нужна 7-струнная гитара в стандартном строе. (изначально в системе установлена 6-струнная гитара в стандартном строе)
1.Пользователь заходит на страницу сервиса.
2.Нажимает на кнопку "настроить инструмент".
3.Регулирует количество струн кнопками "+" и "-".
4.Настраивает ноту добавленной струну кнопками со стрелками.
5.Нажимает кнопку "сохранить изменения"

###Usecase 3
Пользователю нужен 4-струнный бас в строе drop-D. (изначально в системе установлена 6-струнная гитара в стандартном строе)
1.Пользователь заходит на страницу сервиса.
2.Нажимает на кнопку "сменить инструмент".
3.Выбирает 4-струнный бас.
4.Выбирает строй drop-D.

###Usecase 4
Пользователю нужен 4-струнный бас в строе drop-С. (изначально в системе установлена 6-струнная гитара в стандартном строе)
1.Пользователь заходит на страницу сервиса.
2.Нажимает на кнопку "сменить инструмент".
3.Выбирает 4-струнный бас.
4.Выбирает строй drop-D.
5.Нажимает на кнопку "настроить инструмент".
6.Настраивает тональность кнопками со стрелками.
7.Нажимает кнопку "сохранить изменения"

###Usecase 5
Пользователю нужна 7-струнная гитара в стандартном строе. (пользотватель случайно сделал изменения при редактировании уже настроенной гитары)
1.Нажимает кнопку "отменить изменения"