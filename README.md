# Курсовой проект "Сервис перевода денег" (docker-compose)

### Описание

Репозиторий содержит субмодули (git submodule) REST сервиса перевода денег и FRON

### Запуск

- Клонировать репозиторий
- Инициализировать субмодули (git submodule init в консоли в корне рабочей копии)
- Обновить субмодули (git submodule update) (на этом шаге будут клонированы репозитории из субмодулей)
- Собрать проект (package)
- Выполнить в корне команды:
    - docker-compose build
    - docker-compose up
- Сервис доступен по адресу http://localhost:3000
- Тестовые номера карты можно взять тут https://docs.adyen.com/development-resources/test-cards/test-card-numbers