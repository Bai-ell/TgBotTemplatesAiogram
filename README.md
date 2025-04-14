TgBotTemplatesAiogram



📦 Готовые заготовки для создания Telegram-ботов на Aiogram
Этот репозиторий содержит шаблоны, упрощающие старт разработки телеграм-ботов. Используется aiogram 3.x, структура проекта уже организована: маршруты, middlewares, handlers, конфиги — всё готово, бери и пиши логику.



🧱 Состав шаблона

Структура проекта по best practices
Разделение логики по модулям
Конфигурация через .env
Простая система логирования
Поддержка middlewares
Возможность масштабирования


🚀 Быстрый старт

1.Клонируй репозиторий:
        git clone https://github.com/Bai-ell/TgBotTemplatesAiogram.git
        cd TgBotTemplatesAiogram



2.Создай виртуальное окружение и активируй его:
        python -m venv venv
        source venv/bin/activate  # Windows: venv\Scripts\activate



3.Установи зависимости:
        pip install -r requirements.txt



4.Сконфигурируй .env файл:
Создай .env по примеру .env.example и заполни:
        BOT_TOKEN=твой_бот_токен


5.Запусти бота:
        python bot.py



🧩 Структура проекта


TgBotTemplatesAiogram/
├── main.py                 # Точка входа
├── config.py               # Загрузка конфигурации
├── handlers/               # Хендлеры сообщений и команд
├── middlewares/            # Middleware-логика
├── keyboards/              # Клавиатуры
├── utils/                  # Утилиты, states и прочее
├── .env.example            # Пример конфигурации
├── requirements.txt        # Зависимости




🛠️ Требования

Python 3.10+
Aiogram 3.x