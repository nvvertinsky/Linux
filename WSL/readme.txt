Посмотреть все WSL:
wsl --list --all

Экспорт:
wsl --export Ubuntu C:\Projects\WSL\Ubuntu.tar


Импорт: 
wsl --import Имя дистрибутива Путь установки Имя файла
wsl --import Ubuntu C:\Users\Users\Documents\WSL C:\Users\User\Downloads\Ubuntu.tar
wsl --distribution Ubuntu