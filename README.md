# Учебный Telegram-бот

Пример бота на Python и aiogram 3 для урока по Telegram Bot API. Бот отвечает
на `/start`, `/help` и повторяет полученный текст.

## Запуск

1. Создайте бота через [@BotFather](https://t.me/BotFather) и получите токен.
2. Активируйте виртуальное окружение проекта.
3. Установите зависимости:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Создайте `.env` в корне проекта:

   ```env
   BOT_TOKEN=токен_от_BotFather
   ```

5. Запустите бота:

   ```bash
   python main.py
   ```

Остановить бота можно сочетанием `Ctrl+C`. Не публикуйте токен: файл `.env`
уже добавлен в `.gitignore`.