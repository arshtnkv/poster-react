<h1>"Poster: Клиентская часть приложения - Пет проект"</h1>

<div align="center">
  <img height="500" width="500" src="src/meta/poster-image.png" />
</div>

<h2>Используемые технологии:</h2>
<ul>
  <li>React</li>
  <li>Typescript</li>
  <li>Redux Toolkit</li>
  <li>React Hook Form</li>
  <li>Next UI</li>
</ul>

# Для запуска проекта, необходимо выполнить следующие шаги:

1. Склонировать репозиторий с клиентским приложением по ссылке https://github.com/arshtnkv/poster-react.git на свой компьютер.
```
git clone https://github.com/arshtnkv/poster-react.git
```

2. Склонировать репозиторий с api по ссылке [https://github.com/brian7346/express-threads-api.git](https://github.com/brian7346/express-threads-api/tree/main) на свой компьютер.
```
git clone https://github.com/brian7346/poster-express.git
```

3. Открыть терминал (или командную строку) и перейти в корневую директорию сервера.
```
cd express-threads-api
```

4. Переименовать файл .env.local (убрать .local)
```
.env
```

5. Запустить команду docker compose которая поднимет сервер, клиент и базу данных
```
docker compose up
```

6. Открыть браузер и перейти по адресу http://localhost:80, чтобы увидеть запущенный проект.
