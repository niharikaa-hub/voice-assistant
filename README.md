
# 🎙️ Voice Virtual Assistant using ElevenLabs API

This project is a real-time voice assistant powered by [ElevenLabs Conversational AI](https://www.elevenlabs.io/). It listens to your voice, processes your speech with an LLM, and responds back using lifelike speech synthesis.

> 🔊 "Hello Niharika, how can I help you today?"

---

## 🚀 Features

- 🎤 Real-time microphone input
- 🤖 LLM-powered intelligent responses
- 🗣️ Text-to-speech replies using ElevenLabs voices
- 🔄 Supports first-message and system prompt customization
- 🧠 Easy to extend with your own schedule, personality, or tasks

---

## 🛠️ Technologies Used

- Python 🐍
- [ElevenLabs Python SDK](https://pypi.org/project/elevenlabs/)
- PyAudio
- `python-dotenv` for secure API key handling

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/voice-assistant.git
cd voice-assistant
```

### 2. Install Dependencies

```bash
pip install elevenlabs elevenlabs[pyaudio] python-dotenv
```

> 💡 Linux users:  
> `sudo apt install portaudio19-dev`  
> Mac users:  
> `brew install portaudio`

---

### 3. Create `.env` File

Inside your project folder, create a file named `.env`:

```env
API_KEY=sk_your_elevenlabs_api_key
AGENT_ID=your_agent_id_here
```

Make sure there are **no spaces** around `=`.

---

### 4. Run the Assistant

```bash
python voice_assistant.py
```

---

## 📌 Example Customization

You can personalize the assistant’s intro and behavior by editing:

```python
user_name = "Niharika"
schedule = "Meeting with Taipy at 10:00; Gym at 17:00"
first_message = f"Hello {user_name}, how can I help you today?"
```

---

## ⚠️ Security

- Your `.env` file is **ignored by Git** using `.gitignore` for safety.
- Never share your API key publicly.

---

## 🙋‍♀️ Created By

**Niharika Sri Mamidisetti**  
[LinkedIn](https://www.linkedin.com/in/niharikasri-mamidisetti) • [GitHub](https://github.com/YOUR_USERNAME)

---

## 📣 Credits

Thanks to [ElevenLabs](https://www.elevenlabs.io/) for the amazing Conversational AI platform!

---

## 📦 Future Ideas

- Add hotword activation (e.g., “Hey Niharika”)
- Integrate calendar and reminders
- Voice-controlled app automation
