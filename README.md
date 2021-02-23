# CoronaVirusApp
Spring Boot приложение для вывода статистики по числу заболевших коронавирусом по миру. 

  Из репозитория на github (Data repository for the 2019 Novel Coronavirus Visual Dashboard operated by the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE)) 
берем информацию в виде csv файла. Данный файл автоматически обновляется ежедневно и содержит информацию о подтвержденных заболевших в странах по миру.  

  Разработано web приложение, получающее информацию с помощью http запроса, затем производится парсинг csv формата. Приложение разработано с помощью паттерна MVC.
  Для отображения информации о статистике с помощью HTML был использован Thymeleaf (шаблонный файл home.html).

Репозиторий: https://github.com/CSSEGISandData/COVID-19 
