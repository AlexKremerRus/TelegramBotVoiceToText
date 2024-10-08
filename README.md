# TelegramBotVoiceToText
Телеграмм бот для преобразования Голосовых сообщений в текст

---

# Telegram Voice to Text Bot

Этот репозиторий содержит исходный код для Telegram бота, который переводит голосовые сообщения в текстовые сообщения. Бот использует библиотеки `pydub` для конвертации аудиофайлов и `speech_recognition` для распознавания речи.

## Функциональность

- **Приветствие**: Бот отправляет приветственное сообщение в ответ на команду `/start`.
- **Распознавание речи**: Бот принимает голосовые сообщения, конвертирует их в текст и отправляет текстовое сообщение обратно пользователю.

## Установка

1. **Клонируйте репозиторий**:
   ```sh
   git clone https://github.com/AlexKremerRus/TelegramBotVoiceToText.git
   cd ваш_репозиторий
   ```

2. **Создайте файл `.env`**:
   ```sh
   touch .env
   ```

3. **Добавьте ваш токен Telegram бота в файл `.env`**:
   ```
   TELEGRAM_BOT_TOKEN=ваш_токен
   ```

4. **Установите необходимые зависимости**:
   ```sh
   pip install -r requirements.txt
   ```

5. **Запустите бота**:
   ```sh
   python main.py
   ```

## Зависимости

- `pydub`: для конвертации аудиофайлов.
- `speech_recognition`: для распознавания речи.
- `python-dotenv`: для загрузки переменных окружения.
- `pyTelegramBotAPI`: для взаимодействия с Telegram API.

## Пример использования

1. Отправьте команду `/start` боту, чтобы получить приветственное сообщение.
2. Отправьте голосовое сообщение боту.
3. Бот отправит вам текстовое сообщение с распознанной речью.

---
