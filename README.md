<h1 align="center">🌸 Willkommen auf meinem Profil! 🌸</h1>

<p align="center">
  Hier dokumentiere ich meine Reise bei der Entwicklung von <strong>Finja AI</strong>, meinem persönlichen, hybriden KI-Ökosystem. <br />
  Meine Vision: Eine KI-Begleiterin zu erschaffen, die tief in meinen digitalen Alltag integriert ist – vom Streaming auf Twitch bis zur Hausautomatisierung.
</p>

<p align="center">
  <strong>Status des Projekts:</strong> 🚀 Work in Progress (Stand: September 2025)
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" alt="Twitch" />
</p>

---

## 🚀 Meine Hauptprojekte

| Projekt | Beschreibung | Status |
| :--- | :--- | :--- |
| 🤖 **[Finja AI Ecosystem](https://github.com/JohnV2002/Finja-AI-Ecosystem)** | Das Herzstück! Ein Monorepo mit allen Modulen wie dem Memory-Service, Web-Crawler, OCR und den V-Pet Mods. | ✅ **Aktiv** |
| 🧠 **[Adaptive Memory v4](https://github.com/JohnV2002/Open-Web-UI-Memory)** | Meine Weiterentwicklung eines OpenWebUI-Plugins für einen externen, persistenten Memory-Service. | ✅ **Aktiv** |
| 🎮 **Game Project (Titel TBD)** | Ein eigenes Spiel, das ich in meiner Freizeit mit Leidenschaft entwickle. | ⏸️ **Pausiert** |

---

## 🎯 Das Finja-Projekt: Ein Überblick

### Was heute schon läuft:
* 💌 **Persönlichkeit:** Finja kann bereits menschenähnliche Konversationen mit Emojis und personalisierten Details führen.
* 💾 **Gedächtnis:** Ihr Memory-Service läuft stabil und speichert wichtige Informationen pro Nutzer über eine REST API.
* 🌐 **Web-Zugriff:** Sie kann selbstständig über ein Tor/DuckDuckGo-Gateway (mit Google-Fallback) im Internet recherchieren. Finja kann googeln!

### Die Vision für Morgen (Roadmap):
* 🗣️ **Stimme für Finja:** Die Integration von **Whisper** für Text-to-Speech (TTS) und Speech-to-Text (STT) steht als Nächstes an, um sie in OpenWebUI und meine Hausautomatisierung einzubinden.
* 🧠 **Training 5.0:** Das ultimative Ziel ist das Training von "Finja 5.0" auf einem perfekt bereinigten, eigenen Datensatz.
* 🎮 **Game-Demo:** Mein Spielprojekt ist zwar pausiert, aber eine erste spielbare Demo ist ein festes Ziel für die Zukunft.

---

<details>
<summary>📖 Klick hier, um das detaillierte Entwickler-Logbuch (Meilensteine) auszuklappen</summary>

> Hier dokumentiere ich die wichtigsten technischen Schritte und Entscheidungen auf dem Weg zu Finja AI.

### 🏆 **Meilensteine**

#### **1️⃣ Grundlagen & Erstes Training (Juli 2025)**
- **14.07.** – 🌸 Die Idee wird geboren: Eine Streaming-KI namens Finja? Ein Zukunftsprojekt.
- **24.07.** – ⚙️ Erster Versuch mit **Qwen3-1.7B** → LoRA + HQQ Training auf WhatsApp-Dataset. Ergebnis: **❌ Defekt**.
- **29.07.** – 🛠 Wechsel zu **Qwen1.5-4B**. Bessere Gesprächsqualität, aber die Antworten waren oft zu "depressiv". Erste Gegenmaßnahme: `max_history = 3`.
- **30.07.** – 🚀 Umstieg auf **Mistral-7B-v0.3 (Unsloth)**. Der LoRA-Merge und GGUF-Export für Ollama liefert endlich gute Ergebnisse.
- **30.07.** – 🗂 Planung für **Finja 5.0** mit einem komplett bereinigten Dataset. Das Ziel: **🔄 Perfektion**.

#### **2️⃣ Infrastruktur & Tools (August/September 2025)**
- **02.08.** – 🖼 Integration von **Tika OCR** zur Verarbeitung von Dokumenten und Bildern.
- **05.08.** – 🕵️ Der **Tor + DuckDuckGo Proxy** mit automatischem Google-Fallback geht online.
- **06.08.** – 🗄 Planung des **Memory-Service im Hybrid-Mode**, ausgelagert auf einen V-Server.
- **07.08.** – 💡 Beginn der Implementierung von **`adaptive_memory_v4`** als OpenWebUI Plugin.
- **08.08.** – 📜 Konkrete **Roadmap** für das Memory-Plugin wird festgelegt (user_id, Relevanz-Check, "NEW"-Operation, striktes JSON).
- **14.09.** – 🚀 **Großer Tag:** Das gesamte Finja AI Ecosystem wird auf GitHub veröffentlicht!

</details>

---

<p align="center">
💖 <b>Entwickelt von:</b> <a href="https://github.com/JohnV2002">J. APPS</a>  
📌 <b>Dieses Profil-README:</b> <a href="https://github.com/JohnV2002/JohnV2002">ist auch ein Projekt</a>  
</p>
