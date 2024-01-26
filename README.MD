#Информация

| Название    | Версия      |
| ----------- | ----------- |
| PHP         | 8.3-fpm     | 
| MySql       | 8.0         |
| Nginx       | 1.21        |
| Redis       | 6.0         |
| phpMyAdmin  | latest      |

##Информация
Если у вас не установлен `docker` выполните следующие команды:

```bash
$  curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh
```

## Установка
Скопируйте репозиторий:
```bash
$ git clone https://github.com/hidelocker/create_php_app.git
```

Запустите контейнеры в папке `docker`:
```bash
$ docker compose up -d
```

*Ваш проект запущен на порту 80*