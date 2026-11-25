# Учебный Telegram-бот

Бот на Python и Aiogram 3 для урока №2 по Telegram Bot API. 
Бот отвечает на `/start`, `/help` и повторяет полученный текст.

## Запуск
1. Создайте бота через [@BotFather](https://t.me/BotFather) и получите токен.
2. Активируйте виртуальное окружение проекта.
3. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```
4. Создайте `.env` в корне проекта:
   ```env
   BOT_TOKEN=токен_от_BotFather
   ```
5. Запустите бота:
   ```bash
   python name.py
   ```

Остановить бота можно сочетанием `Ctrl+C`. 