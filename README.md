# WebTestInMemory
### Этот тот же самый [проект](https://github.com/kreslojerry/WebTest) (Golang MVC + MongoDB).  
Только авторизированные пользователи хранятся не в базе, а в памяти приложения, 
то есть специальной карте (struct mapTokens).  
Я подумал как-то глупо каждый раз обращаться к БД, чтобы проверить пользователя, теперь обращение к БД происходит только тогда, когда пользователь пытается залогиниться.  
Сами пользователи все также хранятся в базе.
