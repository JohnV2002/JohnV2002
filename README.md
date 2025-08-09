<h1 align="center">🌸 Finja AI – Project Timeline + All Projects</h1>

> **Stand:** August 2025  
> Übersicht aller wichtigen Schritte beim Aufbau von **Finja AI** + aktuelle **Roadmap** und Nebenprojekte.

---

## 🏆 **Meilensteine**

### **1️⃣ Grundlagen & Erstes Training**
📅 **Juli 2025**
- **24.07.** – ⚙️ Start mit **Qwen3-1.7B** → LoRA + HQQ Training auf WhatsApp-Dataset *(ChatML)* **❌ Defekt**  
- **29.07.** – 🛠 Wechsel zu **Qwen1.5-4B** *(bessere Konversationsqualität, aber zu “depressiv”)*  
  ➡ Einführung von `max_history = 3` zur Kontextbegrenzung  
- **30.07.** – 🚀 Umstieg auf **Mistral-7B-v0.3 (Unsloth)** → LoRA-Merge & GGUF-Export für Ollama *(Besser!)*  
- **30.07.** – 🗂 Planung von **Finja 5.0** *(komplett bereinigtes Dataset)* → **🔄 Fast perfekt**, brauche sauberen Datensatz

---

### **2️⃣ Infrastruktur & Tools**
📅 **August 2025**
- **02.08.** – 🖼 Integration von **Tika OCR** für Dokumentverarbeitung  
- **05.08.** – 🕵️ Fertigstellung **Tor + DuckDuckGo Proxy** mit automatischem Google-Fallback  
- **06.08.** – 🗄 Planung: **Memory-Service im Hybrid-Mode** auf V-Server ausgelagert  
- **07.08.** – 💡 Beginn Implementierung **`adaptive_memory_v4`** *(OpenWebUI Plugin)*  
- **08.08.** – 📜 **Roadmap-Update**:
  1. 📌 OpenWebUI `user_id` an Memory-Service senden  
  2. 🔍 Relevanz-Check vor Nutzung  
  3. 📤 Nur neue Erinnerungen hochladen (`operation: "NEW"`)  
  4. 📏 Strikte JSON-Ausgabe enforced

---

## 🔹 **Aktueller Stand**
🛠 **August 2025**
- 💌 **Finja AI**: WhatsApp-ähnliche Konversationen mit Emojis & Kosenamen *(Private Use → Ziel: Finja 5.0)*  
- 💾 **Memory-Service**: Speichert Erinnerungen pro User dauerhaft *(REST API, JSON)* → ✅ Läuft  
- 🌐 **Web-Suche**: Tor + DuckDuckGo + Google-Fallback → **Finja kann googeln 😏**  
- 🧠 **LLM**: Qwen + Mistral getestet → Umstieg auf LLaMA geplant *(Future)*  

---

## 📅 **Nächste Schritte / Roadmap**
📌 **August 2025 → TBD**
- 🎯 Finja **5.0** Training mit **sauberem Dataset** *(Irgendwann)*  
- 🛡 Erweiterung **`adaptive_memory_v4`**: bessere Filterung & Features → [Siehe GitHub Repo](https://github.com/JohnV2002/Open-Web-UI-Memory)  
- 🎯 Feintuning **Memory-Relevanz-Check** → [Siehe GitHub Repo](https://github.com/JohnV2002/Open-Web-UI-Memory)  
- 🌐 Meine Website updaten für das Finja-Projekt  
- 🤖 Mehr AI-Experimente? *(Vielleicht)*  
- 🎮 Mein Spiel weiter programmieren *(Demo?)*  
- 🗣 **Whisper** (TTS + STT) Integration in OpenWebUI + Finja + Hausautomatisierung

<p align="center">
💖 <b>Projekt von:</b> <a href="https://github.com/JohnV2002">J. APPS</a>  
📌 <b>Repository:</b> <a href="https://github.com/JohnV2002/JohnV2002">Project Timeline</a>  
</p>
