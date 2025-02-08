# LilikinLabs
# 1 Лабороторка
1. При записи команды `sudo yam install wget` появляется ошибка `is not a sudoers` 
2. Что бы исправить ошибку надо зайти в супер пользователя пишем команду `su` вводим пароль и открываем  конфигурационый файл `vi/etc/sudoers` в файле нужно добавить строку `lilikin ALL=(ALL)    ALL`. После выходим из `vi` надо нажать `Insert` > `esc` > `shift + ;` > `wq!`
![image](https://github.com/user-attachments/assets/927197e2-ce28-45e2-9907-c7f3f1aed501) Рисунок 1
![image](https://github.com/user-attachments/assets/af65f52d-5c2d-4510-86eb-4746de1245f0) Рисунок 2 - конфигурационый файл


3. Как все сделали после команды `sudo yam install wget` скачается. Что бы проверить скачен ли `wget` надо написать команду `wget --version`
 ![image](https://github.com/user-attachments/assets/f94e700d-a66b-4703-846b-e4669f0fc4b8) Рисунок 3- конфигурационый файл


# 2 Пара 
# 2 Лабороторка
1. Установить `sudo yum install curl`  `curl`-Именование пакета который нужно установить
![image](https://github.com/user-attachments/assets/f717596e-4011-4add-8332-d547c4b196df) Устанавливаем `curl`
2. Надо загрузить файл репозитория Docker `sudo wget -P /etc/yum.repos.d/ https://download.docker.com/linux/centos/docker-ce.repo`
![image](https://github.com/user-attachments/assets/6caf3e4c-3565-4d16-a336-9d7050a086ab) Рисунок 2 - Загрузка файла репозитория Docker
3. Команда устанавливает Docker и его компоненты в систему которая использует менеджер пакетов YUM `sudo yum install docker-ce docker-ce-cli containerd.io` 
![image](https://github.com/user-attachments/assets/e3c93ff6-adab-4f06-abe0-3b6ff397ee0b) Рисунок 3 - Устанавливаем Docker
4. Данная команда запускает Docker и включает её автозапуск при загрузке системы `sudo systemctl enable docker --now`   
![image](https://github.com/user-attachments/assets/bd879567-06b1-459d-8a21-49081cb8c8f0) 
Рисунок 4 - конфигурационый файл
