# 🌸 Finja AI – My Personal AI Ecosystem

> **Status:** Work in Progress (August 2025)  
> **Vision:** Creating a personalized, hybrid AI companion that is deeply integrated into my daily digital life, from streaming on Twitch to smart home automation.

This repository serves as a timeline, roadmap, and overview of all projects related to the Finja AI ecosystem.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" />
</p>

---

## 🚀 Core Projects within the Ecosystem

| Projekt | Beschreibung | Status |
| :--- | :--- | :--- |
| 🤖 **[Finja AI Ecosystem](https://github.com/JohnV2002/Finja-AI-Ecosystem)** | Das Haupt-Repository mit allen Modulen wie dem Memory-Service, Web-Crawler, OCR und den V-Pet Mods. | ✅ **Active** |
| 🧠 **[Adaptive Memory v4](https://github.com/JohnV2002/Open-Web-UI-Memory)** | Ein Fork/Rewrite des OpenWebUI-Plugins für einen externen, persistenten Memory-Service. | ✅ **Active** |
| 🎮 **Game Project (Titel TBD)** | Mein eigenes Spiel, das ich in meiner Freizeit entwickle. |  pausa **Paused** |

---

## 🔹 Aktueller Stand & Roadmap

- 💌 **Finja AI**: Trainiert für WhatsApp-ähnliche Konversationen *(Ziel: Finja 5.0 mit sauberem Dataset)*.
- 💾 **Memory-Service**: Speichert Erinnerungen pro User dauerhaft via REST API. → ✅ **Läuft**
- 🌐 **Web-Suche**: Kann über Tor + DuckDuckGo (mit Google-Fallback) selbstständig googeln. → ✅ **Läuft**
- 🗣 **Whisper Integration**: Geplant für TTS (Text-to-Speech) und STT (Speech-to-Text) in OpenWebUI und zur Hausautomatisierung. → ấp **Upcoming**
- 🎮 **Game Dev**: Mein Spielprojekt ist aktuell pausiert, aber eine Demo ist ein zukünftiges Ziel.

---

<details>
<summary>📖 Klick hier, um die detaillierte Projekt-Timeline (Meilensteine) auszuklappen</summary>

### 🏆 **Meilensteine**

#### **1️⃣ Grundlagen & Erstes Training**
📅 **Juli 2025**
- **24.07.** – ⚙️ Start mit **Qwen3-1.7B** → LoRA + HQQ Training auf WhatsApp-Dataset *(ChatML)* **❌ Defekt** - **29.07.** – 🛠 Wechsel zu **Qwen1.5-4B** *(bessere Konversationsqualität, aber zu “depressiv”)* ➡ Einführung von `max_history = 3` zur Kontextbegrenzung  
- **30.07.** – 🚀 Umstieg auf **Mistral-7B-v0.3 (Unsloth)** → LoRA-Merge & GGUF-Export für Ollama *(Besser!)* - **30.07.** – 🗂 Planung von **Finja 5.0** *(komplett bereinigtes Dataset)* → **🔄 Fast perfekt**, brauche sauberen Datensatz
- **14.07.** - 🌸 Finja - Streaming Ai ? :3 Future
- 
#### **2️⃣ Infrastruktur & Tools**
📅 **August 2025**
- **02.08.** – 🖼 Integration von **Tika OCR** für Dokumentverarbeitung  
- **05.08.** – 🕵️ Fertigstellung **Tor + DuckDuckGo Proxy** mit automatischem Google-Fallback  
- **06.08.** – 🗄 Planung: **Memory-Service im Hybrid-Mode** auf V-Server ausgelagert  
- **07.08.** – 💡 Beginn Implementierung **`adaptive_memory_v4`** *(OpenWebUI Plugin)* - **08.08.** – 📜 **Roadmap-Update**:
  1. 📌 OpenWebUI `user_id` an Memory-Service senden  
  2. 🔍 Relevanz-Check vor Nutzung  
  3. 📤 Nur neue Erinnerungen hochladen (`operation: "NEW"`)  
  4. 📏 Strikte JSON-Ausgabe enforced
- **14.09.** - 🚀 Upload von dem Ganzen Finja AI Ecosystem :3

</details>

---

<p align="center">
💖 <b>Projekt von:</b> <a href="https://github.com/JohnV2002">J. APPS</a>  
📌 <b>Repository:</b> <a href="https://github.com/JohnV2002/JohnV2002">Project Timeline</a>  
</p>
