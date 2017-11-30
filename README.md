## Описание

Starter-проект для Dialogflow веб-хука с деплоем на Heroku (Python2.7)

## Инструкция запуска

1. Регистрируемся на Heroku
2. Установить  [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
3. Выполняем команду логина

	`heroku login`
	
4. Клонируем репозиторий стартера

	`git clone https://github.com/stankevichevg/dialogflow-wh-py.git`
	
	`cd dialogflow-wh-py`
	
5. Подготавливаем Heroku принимать наш код. Создаем приложение.

	`heroku create`
	
6. Деплоим приложение

	`git push heroku master`
	
7. Говорим, что должен быть запущен один сервер
	
	`heroku ps:scale web=1`
	
8. открываем страничку приложения

	`heroku open`
	
9. смотрим логи

	`heroku logs`
	
	`heroku logs --tail`

    