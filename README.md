[README.md](https://github.com/user-attachments/files/29042941/README.md)# Nova

A desktop AI with a pulse. Nova is a JARVIS-style assistant for Windows that listens, thinks out loud, and talks back — with an actual personality, powered by the Claude API.

🔗 **Live page:** https://nova.github.io/nova

---

## What it does

Nova isn't a chatbot stuck in a browser tab. It runs natively on your desktop and reacts visually to what it's doing, not just to what you type.

- **Voice & text input** — talk to Nova or type to it, switch between the two mid-conversation, no mode toggle needed.
- **Mood-reactive orb** — the animated orb in the GUI isn't a loading spinner. Its color and motion shift with what Nova is doing: idle, listening, thinking, or speaking.
- **Witty personality** — responses come from the Claude API with a distinct, sarcastic-but-helpful voice instead of flat, robotic replies.
- **Native Windows app** — built with Python and PyQt5, always one shortcut away.

## Tech stack

- Python 3.10+
- PyQt5 (GUI)
- Claude API (conversation + personality)
- Speech recognition for voice input

## Getting started

You'll need Python 3.10 or newer and a Claude API key from the [Anthropic Console](https://console.anthropic.com/).

```bash
# clone the repo
git clone https://github.com/YOUR-USERNAME/nova.git
cd nova

# install dependencies
pip install -r requirements.txt

# add your API key
# create a .env file in the project root with:
# ANTHROPIC_API_KEY=your_key_here

# run Nova
python nova.py
```

## Orb states

| State | Color | What it means |
|---|---|---|
| Idle | Violet | Nova's awake and waiting for input |
| Listening | Cyan | Taking in your voice or text |
| Thinking | Amber | Forming a response |
| Speaking | Magenta | Replying out loud |

## Roadmap

- [ ] Custom wake word
- [ ] More mood states
- [ ] Plugin support for quick commands
- [ ] Packaged `.exe` installer (no Python setup needed)

## Contributing

This is a personal/learning project, but issues and suggestions are welcome — open an issue if you spot a bug or have an idea.

## License

MIT — do whatever you want with it, just don't sell it as your own without credit.

---

Built by [Ayman](https://github.com/YOUR-USERNAME).

