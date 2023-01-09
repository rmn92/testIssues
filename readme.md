## Глобальные команды:

1. git --version - версия гита
2. git config --global --list - проверка настроек (первоначальные настройки)
3. git status - проверяет состояние репозитория
4. git log --oneline - история работы с файлом
5. git log имя-ветки --graph --oneline - посмотреть историю ветки

## Создание SSH-ключа:
1. ssh-keygen - первый шаг для генерации ключа
2. Найдите в терминале строчку Your public key has been saved in /c/Users/user/.ssh/id_rsa.pub. Копируем адрес начиная с /.ssh
3. cat ~/.ssh/id_rsa.pub
4. на сайте добавить новый SSH. скопировать ключ из п.3

## Первоначальные настройки:
1. git config --global user.name "Name Surname" - настройка имени пользователя
2. git config --global user.email "email@email.com" - настройка email пользователя
3. git config --global core.autocrlf true - формат окончания строк
4. git config --global core.safecrlf warn - формат окончания строк
5. git config --global core.quotepath off - нечитаемые строки в неправильной кодировке
6. git config --global init.defaultBranch main - в новом репозитории основная ветка будет называться main