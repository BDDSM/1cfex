# 1cfex
Simple automaticly download\upload files for 1C over FTP

Коды возврата:
1: Ошибка соединения
2: Не удалось открыть файл на FTP, его не существует или он занят другой программой
3: Не удалось скачать файл - Сетевая ошибка
4: Не удалось открыть локальный файл на запись, возможно он занят другой программой
5: Запись файла не возможна
6: Ошибка проверки файла - Это когда скаченный/закаченный файл по объёму не совпадает с оригиналом
7: Не удалось открыть локальный файл, его не существует или он занят другой программой
8: Не известная ошибка - не придумал названия для нее
9: Не известная ошибка - не придумал названия для нее

А вот и вывод справки (1cfex.exe -h)
-FileIn string
	Файл для загрузки
-FileOut string
    Файл для выгрузки
-LocalPath string
    Локальная папка из которой будет браться файл для выгрузки на сервер (default "C:/ftpswap/LocalObmenUAT/")
-Login string
    Логин для входа на сервер (default "kust")
-Password string
    Пароль для входа на сервер
-Path string
    Папка из которой будет браться файл с сервера (default "/srv/1cv8/uat/")
-ServerPort string
    Сервер и порт к которому необходимо подключиться(например 10.57.254.103:21) (default "10.57.254.103:21")