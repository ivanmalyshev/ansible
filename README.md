# mariadb-server, php, php-mysql, php8.1-fpm, supervisor, python3-pymysql, php-mysql
## установка

1. установить на машину ансибл 

   **apt-get install ansible**

2. Склонировать репозиторий

3. Добавить ip-адреса и ssh ключ в файл inventory. **Ансибл читает приватный ключ!!!**

   Публичная часть ключа, соответственно, должна быть на стороне целевой машины. *.pub

4. Запустить плейбук через команду **ansible-playbook playbook2.yml**
