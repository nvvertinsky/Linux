# Linux

# Основные команды
```
sudo useradd -p password -s /bin/bash test1  # Добавить пользователя с каталогом
sudo passwd pg                               # назначить пользователю пароль
sudo usermod -aG sudo pg                     # включить пользователя в группу sudo
wget --no-check-certificate “URL”            # Загрузить пакеты без проверки сертификата
tar -xvf postgresql-14.3.tar.gz              # распаковать архив tar
cat /etc/passwd                              # посмотреть пользователей
ssh: ssh user@192.168.1.9					 # Подключение по SSH
find -name "spreport*"                       # Поиск файла по имени spreport%
nano /etc/ssh/sshd_config                    # Здесь можно настроить вход по паролю
```

