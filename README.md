# Карта динамики распространения коронавируса по данным телеграм-канала BBC RUSSIA

У нас появилась идея визуализировать данные одного из популярных новостных каналов — BBC news | Русская служба.

Нашей задачей было создать карту, с помощью которой можно будет увидеть:
1) Состояние эпидемии в мире (где распространился вирус) на конкретный момент времени, что будет показано через закрашивание областей на карте
2) Насколько неблагоприятна в стране/регионе/области эпидем-обстановка, что будет отображаться как более яркое/бледное закрашивание области

Для того, чтобы осуществить задуманное мы написали код, который:
1) выкачивает новости, связанные с коронавирусной обстановкой в мире
2) выявляет положительную/отрицательную динамику в каждой из упомянутых в новостях стран/регионов/городов
3) записывает всё в датафрейм
4) выводит все данные на интерактивной карте, отражающей ситуацию в период с января 2020 по февраль 2022 года

Таким образом мы хотели выяснить, насколько подробно освещалась данная тема именно в рассматриваемом нами канале. У нас получилось осуществить всё задуманное. У карты есть две опции: перемещаться по временной шкале с помощью ползунка и смотреть полную анимацию с помощью кнопки "плей". Можно также останавливать на любом моменте.

Здесь вы можете увидеть саму карту в формате html *Map.html* и наш датафрейм, который был создан *dataframe.csv* . В папке *code* вы можете увидеть сам код, поделённый на несколько частей с достаточно подробным описанием функций каждой части. В папке *files_for_project* лежит большая часть файлов, которую можно загрузить на github, так как есть ограничение по размеру файлов, с описанием того, зачем они нужны
