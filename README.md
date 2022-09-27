# Автотесты мобильного приложения Wikipedia
# :page_with_curl: Содержание:

- [Технологии и инструменты](#techno-технологии-и-инструменты)
- [Запуск автотестов](#arrow_forward-запуск-из-терминала)
- [Сборка в Jenkins](#jenkins-Jenkins-job)
- [Allure отчет](#report-Allure-отчет)
- [Пример выполнения теста](#telegram-Уведомление-в-Telegram-при-помощи-бота)

<a name="techno-технологии-и-инструменты"></a>
## :computer: Технологии и инструменты

<p align="center">
<img width="8%" title="IntelliJ IDEA" src="images/logo/Intelij_IDEA.svg">
<img width="8%" title="Java" src="images/logo/Java.svg">
<img width="8%" title="JUnit5" src="images/logo/JUnit5.svg">
<img width="8%" title="Selenide" src="images/logo/Selenide.svg">
<img width="8%" title="Gradle" src="images/logo/Gradle.svg">
<img width="8%" title="GitHub" src="images/logo/GitHub.svg">
<img width="8%" title="Jenkins" src="images/logo/Jenkins.svg">
<img width="8%" title="Allure Report" src="images/logo/Allure_Report.svg">
<img width="8%" title="Allure TestOps" src="images/logo/AllureTestOps.svg">
<img width="8%" title="Telegram" src="images/logo/Telegram.svg">
</p>

<a name="arrow_forward-запуск-из-терминала"></a>
## :keyboard: Запуск автотестов

Локальный запуск:
```
gradle clean android -DdeviceHost=local 
```

Удаленный запуск:
```
gradle clean android -DdeviceHost=browserstack
```

<a name="jenkins-Jenkins-job"></a>
## :robot: Сборка в Jenkins
### <a target="_blank" href="https://jenkins.autotests.cloud/job/012-IvanSidorenko-12_%20regres.inApiTesting/">Параметризированная сборка в Jenkins со всеми тестами</a>
<p align="center">
<img title="Jenkins Job Run with parameters" src="images/screenshots/Screenshot_401.png">
</p>

<a name="report-Allure-отчет"></a>
## :bar_chart: Allure отчет
- ### Главный экран отчета
<p align="center">
<img title="Allure Overview Dashboard" src="images/screenshots/Screenshot_402.png">
</p>

- ### Страница с проведенными тестами
<p align="center">
<img title="Allure Test Page" src="images/screenshots/Screenshot_403.png">
</p>

<a name="telegram-Уведомление-в-Telegram-при-помощи-бота"></a>
## :robot: Пример выполнения теста
<p align="center">
  <img src="images/screenshots/Screenshot_399.png" alt="job">
</p>

