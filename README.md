# Установка

1. Клонируйте репозиторий
```bash
   git clone https://github.com/RayDe003/rest
```

2. Перейдите в директорию проекта
```bash
   cd library
```
3. Утсановите зависимости
```bash
   pip install django 
   pip install Pillow
```
# Запуск
1. Выполните миграции
   ```bash
    python manage.py makemigrations
    python manage.py migrate
   ```

2. Запустите сервер
   ```bash
     python manage.py runserver
   ```
