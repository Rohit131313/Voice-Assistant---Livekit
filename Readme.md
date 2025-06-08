# Voice AI Agent

A voice-based AI agent powered by LiveKit, Deepgram, Google Generative AI, and Cartesia. This project uses multiple APIs and is designed to run through a console interface.

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Rohit131313/Voice-Assistant---Livekit.git
cd Voice-Assistant---Livekit
````

---

### 2. Create a Conda Environment

```bash
conda create -n voice-ai python=3.10
conda activate voice-ai
```

---

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

---

### 4. Setup `.env` File

Create a `.env` file in the root directory of the project and add the following:

```env
LIVEKIT_URL=""
LIVEKIT_API_KEY=""
LIVEKIT_API_SECRET=""
DEEPGRAM_API_KEY=""
CARTESIA_API_KEY=""
GOOGLE_API_KEY=""
```

> 🔐 Replace the empty strings with your actual API keys and URLs.

---

### 5. Run the Agent in Console

```bash
python agent.py console
```

---

## ✅ You're all set!

The agent will now be running in your console and will use the configured APIs for real-time voice interaction.
