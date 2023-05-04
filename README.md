#№ № lab11
# Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачиваю ngrok
```$ ngrok config add-authtoken 2PKbzb6AEriDGu6L6K93IrXMr5V_4BfyzYiXcSMHNhGHVgDHH``` - Добавляю свой токен в ngrok.yml
```$ sudo apt-get install openssh-server``` - скачиваю сервер 
```$ sudo systemctl start ssh``` - запускаю
```$ sudo systemctl status ssh``` 
новое окно консоли
```$ python3 -m http.server``` - распакова модуля http.server 
новое окно консоли
```$ nano index.html``` - создаю
```$ ngrok tcp 22``` - запускаю TCP туннель

***2.tcp.eu.ngrok.io -p 17867*** 
