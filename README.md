# :see_no_evil: *Описание проекта*:
Проект команды Ya.Praktikum, направленный на обучение API.
Бэкенд для сайта с постами. Возможность создать своё небольшое сообщество для общения и поста интересных тем!

# :ghost: *Запуск проекта*:
1. Для начала Вам необходимо склонировать репозиторий к себе в рабочую область. / To begin with, you need to clone the repository to your workspace.
`git@github.com:Rendlolx/api_final_yatube.git`

2. Создать и активировать виртуальное окружение. / Create and activate your venv
- python(python3 on *nix system) -m venv venv
- source venv/Scripts/activate (source venv/bin/activate for *nix system)

3. Установить зависимости / Install dependencies
- pip install -r requirements.txt

4. Выполнить миграции / Perform migrations
- python(python3 on *nix system) manage.py migrate

5. Запустить проект на локальном компьютере / Run the project on the local computer
- python(python3 on *nix system) manage.py runserver

# :ok_hand: *Примеры запросов*:
- `http://127.0.0.1:8000/api/v1/users/` - **регистрация нового пользователя**
- `http://127.0.0.1:8000/api/v1/jwt/create/` - **получить токен для логирования**
- `http://127.0.0.1:8000/api/v1/` - **получить список API для запросов(только после логирования)**
- `http://127.0.0.1:8000/api/v1/posts/` - **список постов**
- `http://127.0.0.1:8000/api/v1/group/` - **список групп**
- `http://127.0.0.1:8000/api/v1/posts/{id_posts}/comments/` - **получить список комментариев**