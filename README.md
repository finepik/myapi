# Первый учебный проект на Django DRF
Сайт с информацией про знаменитых женщин

## Описание:

Несколько view, написанных разными способами
Первое знакомство с Docker и Docker Compose

## Установка

1. **Клонируйте репозиторий:**

   ```bash
   git clone https://github.com/finepik/myapi.git
   cd myapi
   ```
2. **Установите зависимости**
    ```bash
    pip install -r requirements.txt
    ```
3. **Примените миграции:**
    ```bash
    cd myapi
    python manage.py migrate
    ```
   
5. **Запуск сервера**
    ```bash
    python manage.py runserver
    ```

## Использование
После запуска сервера вы сможете получить доступ к приложению по адресу:
- Django API: http://localhost:8000/
