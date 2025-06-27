# 🎧 MediaGenieBot

MediaGenieBot — это Telegram-бот, который умеет:
- 🎵 Находить музыку по названию и отправлять mp3
- 🎬 Искать фильмы через OMDb API
- 🎌 Искать аниме через Jikan API

## 🚀 Команды

```bash
/start          # Главное меню
/music <запрос> # Найти музыку
/movie <назв.>  # Найти фильм
/anime <назв.>  # Найти аниме
```

## 🛠 Настройки

Создайте файл `.env` и добавьте:

```env
TOKEN=ваш_telegram_token
OMDB_API_KEY=ваш_omdb_api_ключ
```

## 📦 Установка

```bash
pip install -r requirements.txt
python main.py
```

---

Создано с ❤️ для обучения и практики.
