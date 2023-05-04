# lab11
## Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачиваю ngrok

```$ ngrok config add-authtoken 2PKbzb6AEriDGu6L6K93IrXMr5V_4BfyzYiXcSMHNhGHVgDHH``` - Добавляю свой токен в ngrok.yml

```$ sudo apt-get install openssh-server``` - скачиваю сервер 

```$ sudo systemctl start ssh``` - запускаю

```$ sudo systemctl status ssh``` 

новое окно консоли

```$ python3 -m http.server``` - распакова модуля http.server

![изображение](https://user-images.githubusercontent.com/113044257/236252607-d18a05df-227e-4902-afa8-18eb1c988e7b.png)

новое окно консоли

```$ nano index.html``` - создаю


```$ ngrok http 8000``` - запускаю HTTP туннель

![изображение](https://user-images.githubusercontent.com/113044257/236254375-f3573e5d-a7a3-4e91-92a6-48514557df4a.png)



```$ ngrok tcp 22``` - запускаю TCP туннель

![изображение](https://user-images.githubusercontent.com/113044257/236254262-3aeae265-0467-41ac-8e8a-5aa0e4af61f4.png)



***ssh 2.tcp.eu.ngrok.io -p 17867*** - с помощью этой команды подключаемся к туннелю
