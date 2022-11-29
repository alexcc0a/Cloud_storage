# Дипломная работа “Облачное хранилище”

## Требования к приложению:

- Сервис предоставляет REST интерфейс для интеграции с FRONT
- Сервис реализовывает методы:
  1. Вывод списка файлов
  2. Добавление файла
  3. Переименование файла
  4. Удаление файла
  5. Авторизация
- Информация о пользователях сервиса (логины для авторизации) и данных хранятся в базе данных (PostgreSQL)

## Требования к реализации:

- Приложение разработано с использованием Spring Boot
- Использован сборщик пакетов maven
- Для запуска используется docker, docker-compose
- Код размещен на github
- Код покрыт unit тестами с использованием mockito

## Запуск:

По-умолчанию FRONT запускается на порту 8081 и доступен по url в браузере http://localhost:8081

## В корневом каталоге выполнить команду:

docker-compose up

## Данные для входа:

login: user@mail.ru
password: user1234
