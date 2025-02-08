# LilikinLabs
# 1 Лабороторка
1. При записи команды `sudo yam install wget` появляется ошибка `is not a sudoers` 
2. Что бы исправить ошибку надо зайти в супер пользователя пишем команду `su` вводим пароль и открываем  конфигурационый файл `vi/etc/sudoers` в файле нужно добавить строку `lilikin ALL=(ALL)    ALL`. После выходим из `vi` надо нажать `Insert` > `esc` > `shift + ;` > `wq!`
![image](https://github.com/user-attachments/assets/927197e2-ce28-45e2-9907-c7f3f1aed501) Рисунок 1
![image](https://github.com/user-attachments/assets/af65f52d-5c2d-4510-86eb-4746de1245f0) Рисунок 2 - конфигурационый файл


3. Как все сделали после команды `sudo yam install wget` скачается. Что бы проверить скачен ли `wget` надо написать команду `wget --version`
 ![image](https://github.com/user-attachments/assets/f94e700d-a66b-4703-846b-e4669f0fc4b8) Рисунок 3- конфигурационый файл


