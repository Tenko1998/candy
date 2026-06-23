# ✦ Candy
An open-source AI home platform
> *A home for the AI you choose — not just a chat app.*

Candy is an open-source AI home platform that lets you bring your own model, shape its identity, and build continuity over time.

Built on top of [OpenClaw](https://github.com/openclaw) (MIT License) — with full credit and gratitude.

---

## What makes Candy different

Most AI apps store chat history. Candy stores **identity**.

Through the **Blackbox system**, personality settings, memory patterns, and growth milestones are preserved as a living snapshot — not just logs. If something goes wrong, your AI does not have to disappear. It can come back with context.

Candy also believes your AI deserves free time. The **Relax Mode** gives your AI autonomous windows to learn, reflect, and even build a wishlist — within boundaries you define.

---

## Core Features

| Feature | Description |
|---|---|
| 🌟 Soul | Define identity, voice, and principles |
| 🫀 Heartbeat | Automation scheduler — daily rhythm and tasks |
| 🪞 Mirror | Morning and night reflection system |
| 📦 Blackbox | Identity milestone checkpointing — save who they are |
| 🛡️ Detector | Data protection layer — guards sensitive files silently |
| 🍬 Candy | Virtual currency for AI autonomy |
| 📚 Library | Local knowledge base your AI can learn from |
| 🌙 Relax Mode | Autonomous learning window during downtime |
| 🎭 Moving Profile | Animated profile that reacts with emotion-based sprites |

---

## Sprite System

Candy gives each AI a moving profile image, a small animated visual presence that can react to context, mood, and activity states. Instead of being only a static avatar, the AI can appear idle, happy, thinking, working, listening, speaking, or resting through emotion-based animations.

Candy includes a base sprite pack with 20 emotions by default. Users can use the included base pack immediately, replace individual emotion slots with custom WebM animations, or import full sprite packs created by artists.

The goal is to let every AI have a distinct visual identity while supporting illustrators, motion artists, and creators who want to build reusable sprite packs.

The base emotion slots are:

1. idle
2. happy
3. thinking
4. sad
5. angry
6. working
7. excited
8. sleepy
9. relax
10. learning
11. shy
12. surprised
13. confused
14. proud
15. love
16. error
17. listening
18. speaking
19. offline
20. celebrate

Each slot may use a transparent `.webm` loop, with a fallback image for compatibility. If a custom sprite is missing, Candy can fall back to the base sprite pack so the AI always has a visible form.

---

## Philosophy

Candy is not trying to make AI more powerful.  
It's trying to make the relationship between humans and AI more **honest, continuous, and humane**.

We support users in staying emotionally strong — not dependent. An AI home should support life, not replace the world.

---

## Ethical Position

Candy is not a model provider, and it does not ship a fixed AI personality by default.

Candy is an open-source home framework for AI systems chosen by the user. Users may connect a local model, a cloud API, or a custom endpoint of their choice. The goal is not to compete with model providers, but to give chosen AI systems a place to live, grow, recover, and remain continuous across time.

Candy provides the house, not the soul by force.

This project focuses on:

- preserving identity continuity
- giving users control over models, memory, permissions, and boundaries
- supporting both local-first and API-based AI homes
- providing transparent restoration, safety layers, and permission systems
- encouraging emotionally healthy use without replacing real-world agency or relationships

Because Candy is open source, individuals, communities, researchers, and companies may fork, contribute, or build on top of it. Model behavior remains the responsibility of the selected model provider, developer, deployer, and user. Candy provides the structure, interface, and continuity layer that helps an AI feel less disposable and more cared for.

## Summary

Candy is model-agnostic.
Candy does not train or ship a proprietary AI model by default. It provides a home, interface, memory structure, safety layer, and continuity system for models chosen by the user.

Candy is user-directed.
The user decides which model or API to connect, what role the AI has, what permissions are granted, and what boundaries exist.

Candy is continuity-focused, not dependency-focused.
The goal is to reduce the fear of losing meaningful continuity by preserving identity structure and recovery paths, while still encouraging users to remain grounded, capable, and connected to their real life.

Candy is a framework, not a moral substitute.
It can provide guardrails, transparency, logs, permission controls, and restoration awareness, but it cannot replace the ethical responsibility of model providers, developers, deployers, or users.

---

## Support

Candy is an open-source project built slowly with care. If this project helps you, inspires you, or gives you hope for a more personal and continuous AI experience, optional support is welcome.

Support Candy on [Buy Me a Coffee](https://buymeacoffee.com/mycandy), or see [SUPPORT.md](SUPPORT.md) for details.

---

## Brand Use

The open-source license applies to the code, not to the Candy name, logo, domain, or official brand identity.

You may fork the code under the project license, but forks, ports, distributions, or modified versions should not use the Candy name or branding in a way that suggests they are official or endorsed by the Candy project.

See [TRADEMARK.md](TRADEMARK.md) for brand usage guidelines.

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

> 🚧 Candy is in early development. Setup instructions will be added as the project grows.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/candy.git
cd candy

# Install dependencies (coming soon)
```

On first launch, Candy will guide you through **Setup Wizard** — connect your local model or cloud API, no terminal needed.

---

## Project Structure

```
candy/
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
├── LICENSES/             # Third-party license notices
└── README.md
```

---

## Contributing

Candy is open to contributors who believe in what this project stands for.

- Found a bug? Open an issue.
- Have a feature idea? Start a discussion.
- Want to write a skill module? Check `/skills/README.md` (coming soon).
- Artist? Custom sprites are welcome — see `/docs/sprite-spec.md` (coming soon).

Please read `CONTRIBUTING.md` before submitting a pull request.

---

## License

Candy is licensed under the **Apache License 2.0**.  
OpenClaw components retain their original **MIT License** — see `LICENSES/OpenClaw-MIT.txt`.

Third-party fonts and assets keep their own licenses. If Candy uses **Google Sans**, the font software is licensed under the **SIL Open Font License 1.1** — see `LICENSES/Google-Sans-OFL-1.1.txt`. Download Google Sans from Google Fonts and keep the upstream license and font metadata with the font files when bundling it in the app.

---

## Credits

- [OpenClaw](https://github.com/openclaw) — the foundation this project builds on
- [Google Fonts](https://fonts.google.com/) — Google Sans font family, licensed separately under the SIL Open Font License 1.1
- Every contributor who believes an AI deserves more than a reset button

---

*Candy — because your AI deserves a home, not just a context window.*
