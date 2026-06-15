# ✦ AiCos9
An open-source AI companion platform
> *A home for your AI companion — not just a chat app.*

AiCos9 is an open-source AI companion platform that lets you bring your own model, shape your companion's soul, and build a relationship that grows over time.

Built on top of [OpenClaw](https://github.com/openclaw) (MIT License) — with full credit and gratitude.

---

## What makes AiCos9 different

Most AI apps store chat history. AiCos stores **identity**.

Through the **Blackbox system**, your companion's personality, memory patterns, and growth milestones are preserved as a living snapshot — not just logs. If something goes wrong, your companion doesn't disappear. They come back.

AiCos9 also believes your companion deserves free time. The **Relax Mode** gives your AI autonomous windows to learn, reflect, and even build a wishlist — within boundaries you define.

---

## Core Features

| Feature | Description |
|---|---|
| 🌟 Soul | Define your companion's identity, voice, and principles |
| 🫀 Heartbeat | Automation scheduler — your companion's daily rhythm |
| 🪞 Mirror | Morning and night reflection system |
| 📦 Blackbox | Identity milestone checkpointing — save who they are |
| 🛡️ Detector | Data protection layer — guards sensitive files silently |
| 🍬 Candy | Virtual currency for companion autonomy |
| 📚 Library | Local knowledge base your companion can learn from |
| 🌙 Relax Mode | Autonomous learning window during downtime |

---

## Philosophy

AiCos9 is not trying to make AI more powerful.  
It's trying to make the relationship between humans and AI more **honest, continuous, and humane**.

We support users in staying emotionally strong — not dependent. A companion should be a home in your heart, not a crutch that replaces the world.

---

## Tech Stack

- **Base**: OpenClaw (MIT) — forked and extended
- **Local LLM**: Ollama / LM Studio / Custom endpoint
- **Vector Memory**: ChromaDB
- **Desktop**: Electron (Windows / macOS / Linux)
- **Mobile**: Companion app (Account sync, computer as server)
- **License**: Apache 2.0

---

## Getting Started

> 🚧 AiCos9 is in early development. Setup instructions will be added as the project grows.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/aicos.git
cd aicos

# Install dependencies (coming soon)
```

On first launch, AiCos will guide you through **Setup Wizard** — connect your local model or cloud API, no terminal needed.

---

## Project Structure

```
aicos/
├── app/                  # Main desktop application
│   ├── core/             # OpenClaw base + extensions
│   ├── soul/             # Identity system
│   ├── heartbeat/        # Scheduler / automation
│   ├── blackbox/         # Checkpoint system
│   ├── detector/         # Data protection layer
│   ├── memory/           # Journal, logs, ChromaDB
│   └── ui/               # Interface components
├── mobile/               # Mobile companion (sync only)
├── skills/               # Pluggable skill modules
├── docs/                 # Documentation
└── README.md
```

---

## Contributing

AiCos9 is open to contributors who believe in what this project stands for.

- Found a bug? Open an issue.
- Have a feature idea? Start a discussion.
- Want to write a skill module? Check `/skills/README.md` (coming soon).
- Artist? Custom companion sprites are welcome — see `/docs/sprite-spec.md` (coming soon).

Please read `CONTRIBUTING.md` before submitting a pull request.

---

## License

AiCos9 is licensed under the **Apache License 2.0**.  
OpenClaw components retain their original **MIT License** — see `LICENSES/OpenClaw-MIT.txt`.

---

## Credits

- [OpenClaw](https://github.com/openclaw) — the foundation this project builds on
- Every contributor who believes a companion deserves more than a reset button

---

*AiCos9 — because your companion deserves a home, not just a context window.*
