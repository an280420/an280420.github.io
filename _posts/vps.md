# VPS

Digital Ocean

1. регистрация на digital ocean
1. установка ubuntu-server на digital ocean. Хосту дадим имя rails-deploy
1. Создание пользователя deploy на сервере. `adduser deploy`
дадим права `adduser deploy sudo`

Настройка входа пользователя с ssh `echo public_key_string >> ~/.ssh/authorized_keys`
Строка приветствия в консоли станет выглядеть так
```
deploy@rails-deploy:~$
```

1. Установка ruby через rbenv
https://gorails.com/setup/ubuntu/21.04


1. Перед руби устновить yarn (или после)
https://linuxize.com/post/how-to-install-yarn-on-ubuntu-20-04/

1. Установка web serves  passenger + nginx
https://www.phusionpassenger.com/docs/advanced_guides/install_and_upgrade/nginx/install/oss/focal.html


1. Ставим  postgresql
Создаем пользователя пример 
```
postgres=# CREATE USER deploy WITH PASSWORD 'deploy';
```
