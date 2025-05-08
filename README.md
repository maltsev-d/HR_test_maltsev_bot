# 🤖 Telegram HR Bot

Телеграм-бот для автоматизации подбора персонала. Поддерживает сбор информации о кандидатах, обработку отказов, приглашения на интервью и финальные HR-решения.

## 🚀 Запуск

### 1. Клонируйте репозиторий

```bash
git clone https://github.com/maltsev-d/test_hr_bot_maltsev_all_bot.git
cd test_hr_bot_maltsev_all_bot
```

### 2. Установите зависимости

Убедитесь, что у вас установлен Python 3.10 или выше.

```bash
pip install -r requirements.txt
```

### 3. Запустите бота

```bash
python main.py
```

## 🧠 Используемые технологии

- [Aiogram 3.7.x](https://docs.aiogram.dev/en/latest/)
- Python 3.10+

## 🗂 Структура проекта

- `main.py` — логика бота и маршрутизация
- `texts.py` — все текстовые сообщения
- `keyboards.py` — генерация inline-клавиатур
- `states.py` — состояния FSM
- `vacancies.py` — список вакансий
- `analytics.py` — сохранение данных кандидатов
- data
  - `analytics.csv` - файл с данными аналитики

