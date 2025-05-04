# Notes API — система для ведения заметок  

🚀 **Описание**: Веб-приложение для создания, редактирования и хранения заметок с бэкендом на FastAPI и фронтендом. 

## 🔥 Возможности  
- Создание/удаление заметок  
- Аутентификация пользователей  
- Адаптивный интерфейс  

## 🛠 Технологии  
- **Backend**: Python, FastAPI, SQLite  
- **Frontend**: Html, css, js 
- **Деплой**: Docker, Nginx  

## 🚀 Как запустить?  
```bash
git clone https://github.com/keymorks/notes-api.git
cd notes-api
docker compose build --no-cache
docker compose up -d
```
Приложение будет доступно на `http://localhost:8000`.  

Для перезапуска
```bash
docker compose down -v
docker compose build --no-cache
docker compose up -d
```

## ⚙️ Конфигурация
Настройки проекта находятся в `notes-api/notes_api/config.py`

Настройки сборки Docker образа находятся в файлах:
```
`notes-api/Dockerfile` - сайт
`notes-api/notes_api/sql/Dockerfile.postgres` - база данных
```

После изменения config.py, docker-compose.yml, Dockerfile или Dockerfile.postgres требуется перезапуск.

## 📸 Скриншоты  
![Главная страница](/screenshots/main.png)  
![Главная страница](/screenshots/login.png)
![Главная страница](/screenshots/register.png)
![Главная страница](/screenshots/my1.png)
![Главная страница](/screenshots/my2.png)  
![Главная страница](/screenshots/editing.png)  
