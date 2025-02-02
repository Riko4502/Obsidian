![Разница между `HTTP/1` и `HTTP/2`?](https://youtu.be/-mWa7erZu64?t=265)

#### Ответ

![[Pasted image 20230703191042.png|600]]

*HTTP/2* – это новая версия протокола HTTP, которая была выпущена в 2015 году и заменила предыдущую версию - HTTP/1.1. Основные отличия между протоколами HTTP/2 и HTTP/1.1:

1. *Мультиплексирование*: HTTP/2 позволяет использовать одно TCP-соединение для множества запросов и ответов одновременно, что устраняет необходимость в нескольких соединениях между клиентом и сервером, ускоряя передачу данных.
    
2. *Бинарный формат*: HTTP/2 использует бинарный формат для передачи данных, в отличие от текстового формата, используемого в HTTP/1.1. Бинарный формат более компактный и эффективный для передачи данных.
    
3. *Сжатие заголовков*: HTTP/2 позволяет сжимать заголовки запросов и ответов, что уменьшает объем передаваемых данных и ускоряет передачу данных.
    
4. *Server Push*: HTTP/2 позволяет серверу отправлять ресурсы на клиент до того, как они будут запрошены, что уменьшает задержку при загрузке страницы.
    
5. *Приоритезация*: HTTP/2 позволяет определять приоритеты для каждого запроса, что позволяет ускорить передачу наиболее важных ресурсов.
    

В целом, HTTP/2 является более эффективным протоколом, чем HTTP/1.1, позволяя передавать данные быстрее и с меньшими задержками. Однако, не все серверы и браузеры поддерживают HTTP/2, поэтому, для совместимости с более старыми системами, все еще используется HTTP/1.1.

Подробнее: [[3.1 HTTP простым языком|HTTP]] , [[3.2 Обзор протокола HTTP|Обзор протокола HTTP]] , [Разъяснение http2](https://habr.com/ru/articles/221427/), [HTTP/2: готовимся к переходу](https://habr.com/ru/companies/selectel/articles/278167/)

___
#HTTP/1 #HTTP/2 #HTTP

___

#### [[000 Browser|Назад]]