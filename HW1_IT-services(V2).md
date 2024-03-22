# HW1_IT-servises
## Определения
### Caddy
Caddy — это обратный прокси-сервер.
Он написан на языке Go и является полностью бесплатным проектом с открытым исходным кодом под лицензией Apache 2.0.
Основные особенности Caddy:
- поддержка HTTP/2, HTTP и HTTPS;
- автоматическое получение и обновление сертификатов Let's Encrypt;
- кроссплатформенность (можно установить на любую ОС);
- поддержка разных архитектур процессоров.
- Caddy можно использовать в Docker-контейнере.
### Nginx
Nginx — это программное обеспечение с открытым исходным кодом для создания лёгкого и мощного веб-сервера. Также его используют в качестве почтового или обратного прокси-сервера.
Особенности Nginx:
- Высокая скорость, особенно заметна при работе со статическим контентом, который не нужно постоянно обновлять.
- Гибкость: программное обеспечение можно настраивать под потребности инфраструктуры.
- Малое потребление памяти: Nginx использует выделенный сегмент памяти — «пул». Он динамический и может расширяться при увеличении длины запроса.
- Хорошая поддержка: у Nginx активное комьюнити и хорошая клиентская поддержка, а документация доступна на русском языке.
- Доступность: программа бесплатная и распространяется по свободной лицензии.
### Apache
Apache — это открытое кросс-платформенное программное обеспечение для размещения и поддержки веб-сервера.
Особенности Apache:
- Модульность: Apache HTTP Server поддерживает модульную архитектуру, что позволяет легко расширять его функциональность.
- Конфигурация: Apache предлагает гибкую систему конфигурации, позволяющую настраивать сервер под конкретные потребности. Конфигурация может быть выполнена через файлы конфигурации, которые легко редактировать.
- Совместимость: Apache поддерживает широкий спектр протоколов и стандартов, включая HTTP/1.1, HTTP/2, SSL/TLS для безопасного соединения, и многие другие.
- Расширенные возможности: с помощью модулей Apache можно добавить расширенные функции, такие как поддержка сжатия контента, кэширование, аутентификация и авторизация пользователей, поддержка виртуальных хостов и многое другое.
- Поддержка различных операционных систем: Apache HTTP Server поддерживает множество операционных систем, включая Linux, Windows, macOS и другие.
## Достоинства и недостатки Caddy, Nginx и Apache
### Caddy
Достоинства:
- Автоматическое обновление SSL-сертификатов: Caddy автоматически получает и обновляет SSL-сертификаты от Let's Encrypt, что упрощает процесс настройки безопасного соединения.
- Простота конфигурации: Caddy использует синтаксис Caddyfile, который прост для понимания и настройки, особенно для новичков.
- Модульность: Caddy поддерживает модули, что позволяет легко расширять его функциональность.

Недостатки:
- Меньшая популярность: Caddy не так широко распространен, как Apache или Nginx, что может означать меньшую поддержку сообщества и меньшее количество доступных ресурсов.
- Меньшее количество плагинов: Несмотря на модульность, Caddy может иметь меньше доступных плагинов по сравнению с более старыми и более широко используемыми серверами.
### Nginx
Достоинства:
- Высокая производительность: Nginx известен своей высокой производительностью и способностью обрабатывать большое количество одновременных запросов.
- Модульность: Nginx поддерживает модули, что позволяет легко расширять его функциональность.
- Поддержка HTTP/2: Nginx поддерживает HTTP/2, что улучшает производительность веб-сайтов.

Недостатки:
- Конфигурация: Конфигурация Nginx может быть сложной для новичков из-за его синтаксиса.
- Отсутствие автоматического обновления SSL-сертификатов: В отличие от Caddy, Nginx не предоставляет встроенного механизма для автоматического обновления SSL-сертификатов.
### Apache
Достоинства:
- Широкая поддержка: Apache имеет большое и активное сообщество, что обеспечивает широкую поддержку и множество доступных ресурсов.
- Модульность: Apache поддерживает модули, что позволяет легко расширять его функциональность.
- Поддержка различных протоколов: Apache поддерживает множество протоколов, включая HTTP/1.1, HTTP/2 и SSL/TLS.

Недостатки:
- Производительность: По сравнению с Nginx, Apache может быть менее производительным при обработке большого количества одновременных запросов.
- Конфигурация: Конфигурация Apache может быть сложной и неинтуитивной для новичков.
## Github 
Servers | Stars | Watching | Forks 
:---- | :-----: | :--------: | -----:
Caddy | 52.8k | 826 | 3.8k |
Nginx | 20k | 975 | 6.5k |
Apache | 23k | 946 | 12.9k |

Из полученных данных видно, что:
- Наибольшим количеством звезд (Stars) был отмечен сервер Caddy
- Сервером с наибольшим количеством пользователей (Watching), проявляющих интерес к проекту в данный момент, является Nginx
- Наибольшее количество копий репозитория (Forks) насчитывается у Apache
## Топ серверов (2020, Yandex, Google)
![image](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/60129d87-e107-4af1-a365-c20467a8aa71) 
https://timeweb.com/ru/community/articles/nginx-apache-cloudflare-statistika-i-obzor-populyarnyh-veb-serverov
## Топ серверов (2024, Yandex)     
Top | Name                               
:--- | ----:
1 | Apache HTTP Server |
2 | Nginx Web Server |
3 | Lighttpd Web Server |
4 | Apache Tomcat |
5 | Caddy Web Server |
6 | OpenLiteSpeed Web Server |
7 | Hiawatha Web Server |
8 | NodeJS |

https://www.tecmint.com/best-open-source-web-servers/

## Топ серверов (2024, Google)
Top | Name
:--- | ----:
1 | Apache - 39.94% |
2 | Nginx - 28.68% |
3 | IIS - 10.07% |
4 | LiteSpeed - 2.79% |
5 | Apache Traffic Server - 0.51% |
6 | OpenGSE - 0.42% |
7 | Phusion Passenger - 0.35% |
8 | Apache Tomcat - 0.15% |
9 | Netlify - 0.13% |
10 | Tengine - 0.11% |

https://hostadvice.com/marketshare/server/

## Производительность (Caddy, Nginx, Apache)
![image](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/3872f561-eb6b-4d64-83e7-6c71dbcddab4)
https://blog.logrocket.com/comparing-best-web-servers-caddy-apache-nginx/

## Использование веб-серверов (измеряемые показатели: ось x - дата, ось y - количество пользователей, выраженное в миллионах)
![image](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/134c872f-70d2-4ec5-8a87-1aabe3eb8975)

https://operavps.com/blog/caddy-vs-nginx-vs-apache/

## Отказоустойчивость
![10 клиентов рисунок](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/cbd97be9-dacd-4a99-8c5f-6ed62d8e469a)

Нагрузка при 10 клиентах

![200 клиентов](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/ad5543c4-f4a3-4b8c-b597-2a2ffc8a1d94)

Нагрузка при 200 клиентах

![500 клиентов](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/63c1b0a4-3dc9-4d2f-a569-45d95147066e)

Нагрузка при 500 клиентах

![1000 клиентов](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/06ab95d3-14bc-4fd1-9f12-83e2ef549454)

Нагрузка при 1000 клиентах

![10000 клиентов](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/e17b2d54-7219-45e0-abe1-fc39c8d35a6f)

Нагрузка при 10000 клиентах

https://blog.tjll.net/reverse-proxy-hot-dog-eating-contest-caddy-vs-nginx/

## Google Trends
![Servers](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/a0d1e939-fb0c-488a-9b59-eb8f1d774ab7)
### Динамика по всему миру за последние 5 лет
![Динамика по всему миру за последние 5 лет](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/f18a68c7-d9f6-4dec-b1b8-7c4ef70d76c7)
### Динамика по всему миру за последний год
![Динамика по всему миру за последний год](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/d2e5b4a0-3fcb-4366-93f2-b8cd21dc777d)
### Динамика по России за последние 5 лет
![Динамика по России (5 лет)](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/25eaecad-b4b4-40d6-ab19-5072bc7f2f7c)
### Динамика по России за последний год
![Динамика по России (год)](https://github.com/valeevartur/HW1_IT-servises/assets/163173033/c8615c46-139e-4b29-8478-3e9cc510de13)

## Вывод
Сравнивая Caddy, Nginx, и Apache, можно выделить следующие ключевые аспекты:

Caddy:

Прост в использовании и настройке благодаря автоматической поддержке HTTPS и минимальным конфигурационным файлам.
Поддерживает TLS 1.3, что является новейшим стандартом безопасности транспорта.
Хотя Caddy показывает конкурентоспособную производительность с Apache, он немного отстает от Nginx в плане обработки запросов в секунду и стабильности при высокой нагрузке 1.

Nginx:

Известен своей высокой производительностью и масштабируемостью, благодаря асинхронной, событийно-ориентированной и неблокирующей архитектуре.
Использует модель с несколькими процессами, что позволяет поддерживать тысячи одновременных сетевых соединений на каждый рабочий процесс.
Часто используется для оптимизации производительности и является выбором для более чем 40% из 10 000 самых популярных сайтов 1.

Apache:

Основан на модульной архитектуре, что позволяет гибко настраивать сервер для различных задач, от обслуживания динамического контента до работы в качестве балансировщика нагрузки.
Поддерживает различные модули Multi-Processing Modules (MPM), такие как mpm_prefork, mpm_worker, и mpm_event, что делает его подходящим для широкого спектра сценариев использования.

Хотя Apache может быть более настраиваемым, его производительность может ухудшаться при высокой нагрузке, особенно при использовании mpm_prefork 2.
Выбор лучшего веб-сервера зависит от конкретных требований к проекту. Если важно максимальное количество статического контента и высокая производительность, Nginx может быть лучшим выбором. Для гибкости и настройки, особенно в контексте динамического контента и сложных сценариев, Apache может быть предпочтительнее. Caddy представляет собой хороший выбор для тех, кто ценит простоту и безопасность, особенно в контексте автоматического обновления сертификатов SSL/TLS.

Важно отметить, что выбор веб-сервера также может зависеть от предпочтений команды разработки и специфики проекта. В некоторых случаях, комбинирование двух или более веб-серверов может быть оптимальным решением для достижения желаемых результатов