# 🤖 CLOYD-SWARM V62.1
> **Multi-Agent AI Swarm Framework - 100% Autonomous & Offline.**

CLOYD-SWARM adalah sistem AI dual-engine yang menggabungkan kecepatan **C++ Native Engine** dengan kecerdasan **Python Autonomous Scavenger**.

## 🔥 Fitur Utama
- **C++ Brain:** Engine chat super ringan tanpa beban library JSON eksternal.
- **Autonomous Scavenger:** Agen Python yang menjelajah internet otomatis.
- **20-Agent Swarm:** Mendukung hingga 20 agen pencari informasi secara paralel.
- **Privacy First:** 100% berjalan di mesin lokal menggunakan Ollama.

## 🚀 Instalasi
1. Install requirements: `pip install ddgs trafilatura`
2. Compile C++: `g++ -O3 cloyd.cpp -o cloyd_engine -lcurl`
3. Download Models: `ollama pull qwen2.5-coder:14b` & `ollama pull llama3.2:1b`

## 🎮 Cara Pakai
1. Terminal 1: `python3 scavenger.py`
2. Terminal 2: `./cloyd_engine`

---
*Developed by alcatraz* 🐧
