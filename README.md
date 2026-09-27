# RobloxAI
# 🤖 RobloxAI 

![Roblox](https://img.shields.io/badge/Roblox-Luau-00A2FF?style=flat-square&logo=roblox)
![Version](https://img.shields.io/badge/Version-1.0.0-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

**RobloxAI** — это легковесный модуль на Luau для быстрой интеграции нейросетей (LLM) в ваши плейсы Roblox. Создавайте умных NPC, динамические квесты и чат-ботов с минимальными усилиями.

## ✨ Особенности
* 🚀 **Простая настройка:** Подключение за пару минут через `HttpService`.
* 🧠 **Умные NPC:** Персонажи, которые понимают контекст и отвечают игрокам.
* 🛡️ **Безопасность:** Защита API-ключей на стороне сервера (ServerScriptService).

## 🛠️ Установка
1. Включите **Allow HTTP Requests** в настройках вашей игры (Game Settings -> Security).
2. Скопируйте код из `RobloxAI.lua` в новый `Script` внутри `ServerScriptService`.
3. Вставьте ваш API-ключ в переменную `API_KEY`.

## 📖 Пример использования
```lua
-- Игрок пишет в чат "!ai Расскажи про этот мир"
-- Скрипт перехватывает сообщение и генерирует осмысленный ответ от лица NPC.
