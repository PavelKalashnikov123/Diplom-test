# Дипломный проект по профессии «Инженер по тестированию»

# Приложение «Мобильный хоспис»

## Задача
Дипломный проект представляет собой ручное функциональное тестирование и разработку автоматизированных тестов для проверки мобильного приложения "В Хосписе".

Приложение включает в себя:
* страницу авторизации;
* новостную ленту хосписа и функционал для работы с новостями;
* информацию о заявках и функционал для работы с ними;
* тематические цитаты.

**В результате выполнения проекта:**
* Проведено ручное тестирование мобильного приложения «Мобильный хоспис»
* Составлены чек-листы и тест кейсы для проверки приложения
* Автоматизированы проверки тестовых сценариев

## Запуск автотестов

**Порядок запуска автотестов:**

**1.** Склонировать репозиторий

    https://github.com/Stjushenka/qamid-diplom-tests  

**2.**  Установить приложение "Мобильный хоспис" на мобильное устройство или в эмуляторе.

**3.** Данные для авторизации:
- В поле "Логин" ввести: **login2**
- В поле "Пароль" ввести: **password2**

## Инструкция по запуску

1. Открыть склонированый проект
2. Запустить эмулятор Pixel 6 API 29 или подключить устройство для тестирования.
3. Запустить тесты из пакета, путь: app/src/androidTest/java/ru/netology/qa/Tests/
4. Запустить тесты командой ./gradlew connectedCheck


## Отчетная документация
* [План тестирования](https://github.com/Stjushenka/qamid-diplom-tests/blob/master/Plan.md)
* [Чек-лист](https://github.com/Stjushenka/qamid-diplom-tests/blob/master/Check%20list.xlsx)
* [Тест-кейсы](https://github.com/Stjushenka/qamid-diplom-tests/blob/master/Cases.xlsx)