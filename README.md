# Первые шаги в программировании на PHP

## 1. Устанавливаем PHP, проверяем установку, учимся пользоваться
Проверь что ты выполнила все нужные шаги при установке и проверь работу
https://github.com/codedokode/pasta/blob/master/soft/php-install.md

## 2. Основы пользования командной строкой (читай только про Windows)
https://github.com/codedokode/pasta/blob/master/soft/cli.md

## 3. Для понимание что такое веб сервер и как это работает
Ничего делать не надо, просто читай
https://github.com/codedokode/pasta/blob/master/soft/web-server.md

## 4. Установка NGINX. Установка PHP-FPM для работы PHP с NGINX.
Не обязательно соблюдать такие же пути к папкам как у автора, можешь придумать свои. Например он использует директорию "E:/sites" для хранения директорий с сайтами которые будет показывать локальный веб сервер (NGIN + PHP-FPM), ты можешь указать другую директорию.
https://atzar.ru/nginx_php-fpm_windows/
Если все получилось, значит у тебя есть рабочий веб сервер.

## 5. Устанавливаем базу данных MySQL
Устанавливаем если ее еще нет, разумеется
https://www.wordpress-abc.ru/hosting/lokalnyiy-server/ustanovka-servera-mysql-5-7-11-na-windows-7.html

## 6. Начинаем настраивать наше yii2-app-advanced приложение
Выполняем пункты из главы "Preparing application", следуем моим комментариям по пунктам: https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/start-installation.md 
1. Используй первую команду и обрати внимание что "/path/to/php-bin/php" - это полный путь до php.exe
2. В указанном файле надо ввести данные установленой базы данных
3. Выполняем команду
4. Используем конфиг для NGINX
5. Выполняем как есть


## 7. Можно пробовать запускать тесты
Ожидаю что здесь возникнут сложности, но будем решать их по мере возникновения
https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/start-testing.md


