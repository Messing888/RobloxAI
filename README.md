# RobloxAI
# 🤖 RobloxAI 

![Roblox](https://img.shields.io/badge/Roblox-Luau-00A2FF?style=flat-square&logo=roblox)
![Version](https://img.shields.io/badge/Version-1.0.0-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

**RobloxAI** is a lightweight Luau module for quickly integrating neural networks (LLMs) into your Roblox experiences. Create smart NPCs, dynamic quests, and chatbots with minimal effort.

## ✨ Features
* 🚀 **Simple Setup:** Connect in just a few minutes via `HttpService`.
* 🧠 **Smart NPCs:** Characters that understand context and respond intelligently to players.
* 🛡️ **Security:** API key protection is handled entirely on the server side (ServerScriptService).

## 🛠️ Installation
1. Enable **Allow HTTP Requests** in your game settings (Game Settings -> Security).
2. Copy the code from `RobloxAI.lua` into a new `Script` inside `ServerScriptService`.
3. Paste your API key into the `API_KEY` variable.

## 📖 Usage Example
```lua
-- A player types "!ai Tell me about this world" in the chat
-- The script intercepts the message and generates a meaningful response from the NPC.
