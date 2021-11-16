# Установка и запуск веб-сервера в Linux
## Цель работы
### Освоить основные навыки установки и первоначальной настройки веб-сервера в ОС Linux.
## Задания для выполнения
1.Используя apt-get установить Apache2 на виртуальную машину

![screenshot](images/1.jpg)

2.С браузера хост-машины по IP-адресу виртуальной машины увидеть приветствие

![screenshot](images/2.1.jpg)

![screenshot](images/2.2.jpg)

3.В настройках сервера изменить  порт на :8080

![screenshot](images/3.jpg)

4.Снова выполнить п 2, но с указанием порта

![screenshot](images/4.1.jpg)

![screenshot](images/4.2.jpg)

5.Изменить порт обратно и проверить как работает заглушка

![screenshot](images/5.1.jpg)

![screenshot](images/5.2.jpg)

6.В hosts хост-машины создать три домена: a1.com, b2.com, c3.com и связываем с IP виртуальной машины с Apache

![screenshot](images/6.jpg)

7.Для каждого домена проверить всё ли правильно, с помощью ping

![screenshot](images/7.jpg)

8.Зайти на все три домена, написав их вместо IP виртуальной машины

![screenshot](images/8.1.jpg)

![screenshot](images/8.2.jpg)

![screenshot](images/8.3.jpg)

9.Создать директории /var/www/a1.com, /var/www/b2.com, /var/www/c3.com

![screenshot](images/9.jpg)

10.В каждой из них создать пустой index.html

![screenshot](images/10.jpg)

11.В каждом из них написать различное содержимое

![screenshot](images/11.1.jpg)

![screenshot](images/11.2.jpg)

![screenshot](images/11.3.jpg)

12.Сделать так, чтобы из браузеров хост-машины открывались сайты из директории, а не общая заглушка

![screenshot](images/12.1.jpg)

![screenshot](images/12.2.jpg)

![screenshot](images/12.3.jpg)

![screenshot](images/12.4.jpg)