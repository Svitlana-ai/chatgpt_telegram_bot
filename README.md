# 🤖 ChatGPT Telegram Bot

Це простий Telegram-бот на Python, який використовує OpenAI ChatGPT API для відповіді на повідомлення користувача. Ідеально підходить для автоматизації відповідей, особистих помічників або AI-сапорту.

---

## 🔧 Функціонал

- Приймає повідомлення від користувача
- Відправляє їх до ChatGPT (gpt-3.5-turbo)
- Відповідає у чаті з Telegram
- Просте налаштування через `.env`

---

## 🚀 Швидкий старт

### 1. Клонуй репозиторій:

```bash
git clone https://github.com/Svitlana-ai/chatgpt_telegram_bot.git
cd chatgpt_telegram_bot
2. Встанови залежності:
bash
Копировать
Редактировать
pip install -r requirements.txt
3. Створи файл .env у корені проєкту:
env
Копировать
Редактировать
BOT_TOKEN=твій_токен_бота
OPENAI_API_KEY=твій_ключ_openai
Не публікуй .env — цей файл має залишатись приватним!

▶️ Запуск бота
bash
Копировать
Редактировать
python main.py
Бот запускається і чекає на повідомлення!

📦 Використані бібліотеки
python-telegram-bot

openai

dotenv

💡 Ідеї для розширення
Запам’ятовування контексту (memory)

Обробка зображень/голосу

Інтеграція з Google Sheets / CRM

Хостинг на Render / Railway / VPS

🧑‍💻 Автор
Світлана Ярем
Python & AI Developer from 🇺🇦
My Fiverr profile

📄 Ліцензія
Цей проєкт має MIT ліцензію. Вільно використовуй для навчання та комерційних цілей ✌️
