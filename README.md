# Демо-проект автоматизации тестирования
*наименование*

# Используемые технологии
![Java](readme_files/icons/java.png)
![Gradle](readme_files/icons/gradle.png)
![JUnit5](readme_files/icons/jUnit5.png)
![Selenide](readme_files/icons/selenide.png)
![RestAssured](readme_files/icons/restassured.png)
![Allure_Report](readme_files/icons/allure_report.png)
![Jenkins](readme_files/icons/jenkins.png)
![Selenoid](readme_files/icons/selenoid.png)
![Telegram](readme_files/icons/telegram.png)

- Java
- Gradle
- Junit5
- Selenide
- RestAssured
- Allure Report
- Jenkins
- Selenoid
- Telegram Bot

# Описание
Примеры автоматизированных тестовых сценариев для тестирования *описание тестируюемого функционала*

- Тесты запущены из Jenkins
- Для запуска браузеров в docker-контейнеров использован Selenoid
- Сгенерирован отчет Allure report (автоматически добавлены скриншоты и видео прохождения тестов)
- Отчет загружен в TMS - Allure TestOps
- На основании Allure-отчета в Allure TestOps автоматически созданы тест-кейсы 
- Для примера в Allure TestOps добавлен ручной тест
- Уведомление с отчетом о прохождении тестов отправлено в Telegram

## Отчеты Allure reports
### Общий отчет о прохождении тест-сьюта
![Allure reports overview](./readme_files/allure-report.jpg)
### Детальный отчет о прохождении конкретного теста
![Allure reports test](./readme_files/allure-report-test-with-screenshot.jpg)
### Видео прохождения теста
![Video](./readme_files/testVideo.gif)

## Отчеты Allure TestOps
### Запуски
![TestOps launches](./readme_files/testOpsLaunches.jpg)
- **id #2935** - Прохождение ручного тест-кейса
- **id #2933** - Прохождение автоматизированных тест-кейсов

### Тест-кейсы
![TestOps cases](./readme_files/testOpsSuites.jpg)
- **id #2449** - Ручной тест-кейс

### Allure TestOps Dashboard
![TestOps cases](./readme_files/testOpsDashboard.jpg)


## Уведомление в Telegram
![telegram](./readme_files/telegramBot.jpg)

## Ссылки
### Jenkins

### Allure reports

