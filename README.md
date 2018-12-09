# -CSSSR
Автотест страницы вакансии CSSSR (http://blog.csssr.ru/qa-engineer/), который демонстрирует  наличие кликабельных чек боксов.
Инструменты для запуска автотеста:
IntelliJ IDEA 2017.2.3 x64,
Maven,
Selenium Webdriver 
https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java/3.12.0 ,

Подключенный драйвер ChromeDriver 2.44
http://chromedriver.chromium.org/downloads ,

Фреймворк TestNG 
https://mvnrepository.com/artifact/org.testng/testng/6.13.1 ,

Браузер Google Сhrome 
Версия 70.0.3538.110 (Официальная сборка), (64 бит)

//Можно было бы попробовать сделать с применением ассертов, но думаю данных действий достаточно чтобы убедиться,
// что чекбоксы кликабельны. В нашем случае это недопустимо, так как исходный макет не предполагает такую функциональность.

// Тест подтверждает наличие кликабельных чекбоксов. 
