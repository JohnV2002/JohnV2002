# 🌸 Finja AI – Project Timeline + ALL PROJECTS

> **Stand:** August 2025  
> Übersicht aller wichtigen Schritte beim Aufbau von Finja AI – von den ersten Trainingsversuchen bis zum fertigen Memory-System.

---

## 🏆 Meilensteine

### **1. Grundlagen & Erstes Training**
📅 **Juli 2025**
- **24.07.** – Start mit **Qwen3-1.7B**, LoRA + HQQ Training auf WhatsApp-Dataset im ChatML-Format.  <- War defekt
- **29.07.** – Wechsel zu **Qwen1.5-4B** für bessere Konversationsqualität.    <---- ZU Deprissiv XD
  Einführung von `max_history = 3` zur Kontextbegrenzung.  
- **30.07.** – Umstieg auf **Mistral-7B-v0.3 (Unsloth)**, LoRA-Merge & GGUF-Export für Ollama.  <- War besser
- **30.07.** – Planung von **Finja 5.0** (komplett bereinigtes Dataset). <- Fast perfekt brauche sauberen datensatz

---

### **2. Infrastruktur & Tools**
📅 **August 2025**
- **02.08.** – Integration von **Tika OCR** für Dokumentverarbeitung.  
- **05.08.** – Fertigstellung **Tor + DuckDuckGo Proxy** mit automatischem Google-Fallback.  
- **06.08.** – Planung: Memory-Service im **Hybrid-Mode** auf V-Server ausgelagert.  
- **07.08.** – Beginn Implementierung `adaptive_memory_v4` (OpenWebUI Plugin).  
- **08.08.** – **Roadmap-Update**:
  1. OpenWebUI `user_id` an Memory-Service senden  
  2. Relevanz-Check vor Nutzung  
  3. Nur neue Erinnerungen hochladen (`operation: "NEW"`)  
  4. Strikte JSON-Ausgabe enforced

---

### **3. Aktueller Stand**
🛠 **August 2025**
- **Finja AI**: WhatsApp-ähnliche Konversationen mit personalisierten Emojis & Kosenamen 💌  <-- FÜR PRIVATE USE BUT WANTED TO SAY LOOK (FOR FINJA 5.0)
- **Memory-Service**: Speichert Erinnerungen pro User dauerhaft (REST API, JSON) auf V-Server  <-- RUNS Look at the adaptive memory reposetory
- **Web-Suche**: Tor + DuckDuckGo mit Google-Fallback  <-- FINJA Can google lol
- **LLM**: Getestet mit Qwen, Mistral – Umstieg auf LLaMA geplant  <-- FUTURE

---

### **4. Nächste Schritte**
📌 **August 2025 - ####**
- Finja **5.0** Training mit bereinigtem Dataset  <-- IRGENDWANN!
- Erweiterung `adaptive Memory v4` bessere filterung von Memorys and more <--- Look at the Github   
- Feintuning **Memory-Relevanz-Check**  <--- Look at the Github
- Meine Website updaten für Mein Finja projekt
- Mehr AI? <-- VLLT
- Mein Spiel weiter programmieren <-- DEMO???
- Whisper (TTS und STT) für Open Web UI + Finja + fürs Haus

---
