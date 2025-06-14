````markdown
# 🎯 Telegram Bot: Угадай число

Это простой Telegram-бот, написанный на Python с использованием библиотеки **aiogram**.  
Бот предлагает сыграть в игру **"Угадай число"**, где пользователь должен угадать число от 1 до 100 за ограниченное число попыток.

## 📌 Возможности

- `/start` — запуск бота
- `/help` — правила игры и список команд
- `/stat` — просмотр статистики (кол-во игр и побед)
- `/cancel` — выход из текущей игры
- Реакция на простые ответы: «да», «нет», числа от 1 до 100
- Ведется статистика по каждому пользователю

## 🧠 Логика игры

1. Бот загадывает число от 1 до 100.
2. У пользователя есть 5 попыток, чтобы его угадать.
3. После каждой попытки бот подсказывает: больше или меньше.
4. После победы или поражения — предлагает сыграть еще раз.

## ⚙️ Технологии

- Python 3
- [aiogram](https://docs.aiogram.dev) — асинхронный фреймворк для Telegram-ботов

## 🚀 Как запустить

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-username/ваш-репозиторий.git
   cd ваш-репозиторий
````

2. Установите зависимости:

   ```bash
   pip install aiogram
   ```

3. В файле `bot.py` замените строку:

   ```python
   BOT_TOKEN = 'BOT TOKEN HERE'
   ```

   на ваш реальный токен от [@BotFather](https://t.me/BotFather).

4. Запустите бота:

   ```bash
   python bot.py
   ```
