# Linux VPS Setup

Развёртывание и базовая защита Linux VPS.

## Окружение

- Ubuntu / Debian
- Nginx
- SSH
- UFW
- SSL/TLS
- DNS

## Что сделал

- [Создал нового пользователя и выдал ему права root](images/systemuser.png)
- [Настроил SSH-доступ по ключам и запретил удаленный доступ по root](images/ssh.png)
- [Настроил UFW](images/ufw.png)
- [Настроил Nginx](images/nginx.png)
- [Подключил SSL-сертификат](images/https.png)
- [Настроил DNS](images/dns.png)

## Результат

Рабочий Linux-сервер с веб-сервисом, HTTPS
и базовой защитой SSH.
