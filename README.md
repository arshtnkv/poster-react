# 🔥 Пет проект "Poster": Социальная сеть для публикации постов<br>

URL <a href="https://poster-react-eta.vercel.app/" target="_blank">https://poster-react-eta.vercel.app</a><br>
BACKEND <a href="https://github.com/arshtnkv/poster-express-api" target="_blank">https://github.com/arshtnkv/poster-express-api</a>

## ⚡ Клиентская часть приложения

<div align="center">
  <img height="500" width="500" src="src/meta/poster-image.png" />
</div>

### 🛠 Технологии:

- React
- Typescript
- Redux Toolkit
- React Hook Form
- Next UI

### ⚙️ В приложении доступны следующие функции:

- Создание постов: пользователи могут публиковать свои мысли
- Взаимодействие с контентом: возможность комментировать и лайкать посты других пользователей.
- Подписки: подписка на интересных пользователей и возможность отписаться от них в любое время.
- Профили: у каждого пользователя есть личный профиль, где можно редактировать информацию о себе.
- Лента новостей: отображение постов пользователей, на которых подписан пользователь.

<br clear="both">

## Для запуска проекта локально, необходимо выполнить следующие шаги:

<br clear="both">

1. Склонировать репозиторий с клиентским приложением по ссылке https://github.com/arshtnkv/poster-react на свой компьютер.

```
git clone https://github.com/arshtnkv/poster-react.git
```

2. Склонировать репозиторий с api по ссылке [https://github.com/arshtnkv/poster-express-api](https://github.com/arshtnkv/poster-express-api) на свой компьютер.

```
git clone https://github.com/arshtnkv/poster-express-api.git
```

3. Открыть терминал (или командную строку) и перейти в корневую директорию сервера.

```
cd poster-express-api
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
