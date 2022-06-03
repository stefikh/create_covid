# Карта динамики распространения коронавируса по данным телеграм-канала BBC RUSSIA

У нас появилась идея визуализировать данные одного из популярных новостных каналов — BBC news | Русская служба.

Нашей задасей было создать карту, с помощью которой можно будет увидеть:
1) Состояние эпидемии в мире (где распространился вирус) на конкретный момент времени, что будет показано через закрашивание областей на карте
2) Насколько неблагоприятна в стране/регионе/области эпидем-обстановка, что будет отображаться как более яркое/бледное закрашивание области

Для того, чтобы осуществить задуманное мы написали код, который:
1) выкачивает новости, связанные с коронавирусной обстановкой в мире
2) выявляет положительную/отрицательную динамику в каждой из упомянутых в новостях стран/регионов/городов
3) выводит все данные на интерактивной карте, отражающей ситуацию в период с января 2020 по февраль 2022 года

Таким образом мы хотели выяснить, насколько подробно освещалась данная тема именно в рассматриваемом нами канале.
