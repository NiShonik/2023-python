# 2023-python
Лабораторные по курсу "Язык программирования Python", группы ИС-33, ИС-34

Для работы необходим python 3.9 и выше.
Библиотеки: numpy, matplotlib, tkinter
Редактор любой. Из неплохих: IDLE (родной, идёт вместе с установщиком), Visual Studio Code, notepad++, PyCharm, vim (для любителей сначала страдать, потом наслаждаться)

Работа с блокнотами онлайн, с возможностью подключение удалённых мощностей гугла (GPU, TPU): https://colab.research.google.com/

Таблица, где я буду отмечать сданные работы: 

Презентация (будет обновляться в течение семестра): https://docs.google.com/presentation/d/1CqyrZYSh15dsVWt57eu14UDtm2-GFpSF5TD2_tVLaCc/edit?usp=sharing

Хорошая книга по python, очень простым языком и на понятных примерах: https://wombat.org.ua/AByteOfPython/AByteofPythonRussian-2.02.pdf

Сервер в Дискорд, где буду дублировать: https://discord.gg/MzPkCYf4Dh

Мой контакт: nsmorozov@rf.unn.ru

В своей папке можете делать все что угодно, в чужие не залезать, в корневую тоже. Я буду ориентироваться на файлы, где в названии будет номер лабораторной.

## [1] Работа со структурами данных
	
Исходные данные:

- свои ФИО, число, месяц, год рождения в виде кортежа;
- предметы в школьном аттестате (не меньше 14), как словарь из названия и оценки (можно мокать);
- имена (только) ближайших (до двоюродных включительно) родственников в списке;
- имя, которое вы бы дали своей домашней пушистой киве (строка).

Действия:

1) вывести среднюю оценку в аттестате;
2) вывести уникальные имена среди своих родственников (включая свое);
3) общая длина всех названий предметов;
4) уникальные буквы в названиях предметов;
5) имя вашей домашней пушистой кивы в бинарном виде;
6) отсортированный по алфавиту (в обратном порядке) список родственников;
7) количество дней от вашей даты рождения до текущей даты (должна быть всегда актуальной);
8) FIFO очередь, в которую можно добавлять предметы по вводимому с клавиатуры индексу (до команды остановки), после введения - вывести все;
9) по введеному индексу, поменять имя в отсортированном списке родственников на имя ацтекского правителя (https://en.wikipedia.org/wiki/List_of_rulers_of_Tenochtitlan) под номером, получаемым из вашей даты рождения: number = (day + month**2 + year) % 21 + 1;
10) ...в разработке
