# Портфолио учебных проектов курса "Full-stack веб-разработчик на Python" в SkillFactory 
#### Ревякин Иван
<hr>

### Модуль E9. Многопользовательский сервис планирования событий
```Flask, Heroku, Flask-Login, Flask-Migrate, Flask-SQLAlchemy, Flask-WTF```

Мультипользовательский сервис событий. Пользователи создают события, которое доступно остальным пользователям для просмотра.
* У каждого события есть следующие параметры: автор, время начала, время конца, тема и описание.
* Каждый пользователь может просматривать все события, которые созданы любыми пользователями.
* Каждый пользователь может редактировать, удалять и создавать события, где пользователем является он.
* На общей странице есть общий вид всех событий.

GitHub: https://github.com/LovingFox/PWS-15_e9_multiuser_event_manager <br/>
Демо: https://hidden-wave-17413.herokuapp.com/
<hr>

### Модуль E8. Микросервисная архитектура. Шина данных.
```Flask, SQLAlchemy, celery, redis, Docker```

Cервис, который считает, сколько раз встречается слово python на странице. Состоит из следующих частей:
- Веб-форма для внесения сайтов в спискок задач;
- Очередь, которая эти задания запускает;
- Часть, которая обрабатывает результаты;
- Табличка со статистикой с результатами.

GitHub: https://github.com/LovingFox/PWS-15_e8_celery_nsq <br/>
Демо: https://sf.rtru.tk/tasks
<hr>

### Модуль E7. SQL и NoSQL.
```Flask, Mongo, Flask-RESTful, Docker```

Cервис, в котором реализована доска объявлений. К каждому объявлению можно добавлять комментарии и теги. У этого сервиса доступна статистика по каждому объявлению, в которой дается количество тегов и комментариев.
* основная база данных MongoDB;
* для кеширования используется Redis.

GitHub: https://github.com/LovingFox/PWS-15_e7_mongo_redis <br/>
Демо: https://sf.rtru.tk/advs (см. README в GitHub)
<hr>


### Модуль E6. Работа с Docker-контейнерами.
```Flask, redis, Docker```

Сервис возвращает k-ое число Фибоначчи. Реализовано кеширование: если число уже было запрошено, результат должен браться из кеша, а не пересчитываться.

GitHub: https://github.com/LovingFox/PWS-15_e6_docker <br/>
Демо: https://sf.rtru.tk/fibonacci
<hr> 

### Модуль E2. Отложенное выполнение.
```Django, Heroku, SendGrid```

Сервис, который отправляет email через заданное количество секунд. Пользователь вводит параметры: текст сообщения, адрес email, куда слать сообщение, и через какое количество секунд его отправить. Пиьсмо планируется в отправку и отображаются последние письма, которые были поставлены в план (и те, что должны отправиться в будущем, и уже отправленные). У каждого письма в списке указан статус - отправлено оно или еще нет. Данный сервис реализован с применением многопоточности: после того, как письмо создано, создаться тред для отправки письма с задержкой.

GitHub: https://github.com/LovingFox/PWS-15_e2_sendgrid <br/>
Демо: https://pacific-refuge-00176.herokuapp.com/
<hr>

### Модуль E1. Использование travis-ci.
```travis-ci, pytest```

Покрытие тестами и непрерывная интеграция с travis-ci. Игру в виселицу. Приложение «загадывает» одно из следующих слов: skillfactory, testing, blackbox, pytest, unittest, coverage. И показывает количество букв в нём.

GitHub: https://github.com/LovingFox/PWS-15_e1_travis-ci <br/>
Демо: только в CLI
<hr>

### Модуль D10. Принципы организации Django-проектов. Debug.
```Django, Heroku, django-debug-toolbar```

Поиск по базе данных автомобилей с фильтрами.

GitHub: https://github.com/LovingFox/PWS-15_d10_Q (с debug панелью)<br/>
Демо: https://calm-island-00972.herokuapp.com/

GitHub: https://github.com/LovingFox/PWS-15_d10_Q/tree/e5 (без debug панели)<br/>
Демо: https://sf.rtru.tk/
<hr>

### Модуль D9. Разработка API в Django.
```Django, Heroku, djangorestframework```

REST-API для постов и их категорий. 

GitHub: https://github.com/LovingFox/PWS-15_d9_api <br/>
Демо: https://whispering-reef-52117.herokuapp.com/ (см. README в GitHub)
<hr>

### Модуль D7. Пользовательские профили и oauth-авторизация.
```Django, Heroku, django-allauth, oauth```

Сервис библиотеки. Без регистрации можно просматривать базу книг. Что бы что-то менять, нужно авторизоваться (локально, либо через GitHub). Удаление записей позволено только "Персоналу" (is_staff); например, пользователю admin (пароль pass).

GitHub: https://github.com/LovingFox/PWS-15_d7_users <br/>
Демо: https://thawing-island-83857.herokuapp.com/
<hr>

### Модуль D1. Работа с API из Python. Модуль requests.
```requests, trello.com```

Интерфейс коммандной строки для работы с сервисом trello.com через его API. Можно создавать/удалять задачи и колонки.

GitHub: https://github.com/LovingFox/PWS-15_d1_trello <br/>
Демо: только CLI
<hr>

### Модуль C4. Знакомство с фреймворком Vue.js.
```JavaScript, Vue```

Приложение ToDo. Используется либо localStorage в браузере, либо бэкэнд на localhost. Код бэкэнда на Python.

GitHub: https://github.com/LovingFox/PWS-15_c4 <br/>
Демо: https://lovingfox.github.io/PWS-15_c4/dist/
<hr>

### Модуль A6. Продолжаем изучать Javascript.
```JavaScript```

Игра "Собери 10 зеленых квадратов".

GitHub: https://github.com/LovingFox/PWS-15_m6_task2 <br/>
Демо: https://lovingfox.github.io/PWS-15_m6_task2/index.html
<hr>
