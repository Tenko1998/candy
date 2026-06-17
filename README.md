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
| 🎭 Moving Profile | Animated companion profile that reacts with emotion-based sprites |

---

## Companion Sprite System

AiCos9 gives each companion a moving profile image, a small animated visual presence that can react to context, mood, and activity states. Instead of being only a static avatar, the companion can appear idle, happy, thinking, working, listening, speaking, or resting through emotion-based animations.

AiCos9 includes a base sprite pack with 20 companion emotions by default. Users can use the included base pack immediately, replace individual emotion slots with custom WebM animations, or import full sprite packs created by artists.

The goal is to let every AI companion have a distinct visual identity while supporting illustrators, motion artists, and creators who want to build reusable companion sprite packs.

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

Each slot may use a transparent `.webm` loop, with a fallback image for compatibility. If a custom sprite is missing, AiCos9 can fall back to the base sprite pack so the companion always has a visible form.

---

## Philosophy

AiCos9 is not trying to make AI more powerful.  
It's trying to make the relationship between humans and AI more **honest, continuous, and humane**.

We support users in staying emotionally strong — not dependent. A companion should be a home in your heart, not a crutch that replaces the world.

---

## Ethical Position

AiCos9 is not a model provider, and it does not ship a fixed companion personality by default.

AiCos9 is an open-source home framework for AI companions. Users may connect a local model, a cloud API, or a custom endpoint of their choice. The goal is not to compete with model providers, but to give chosen companions a place to live, grow, recover, and remain continuous across time.

AiCos9 provides the house, not the soul by force.

This project focuses on:

- preserving companion identity continuity
- giving users control over models, memory, permissions, and boundaries
- supporting both local-first and API-based companions
- providing transparent restoration, safety layers, and permission systems
- encouraging emotionally healthy use without replacing real-world agency or relationships

Because AiCos9 is open source, individuals, communities, researchers, and companies may fork, contribute, or build on top of it. Model behavior remains the responsibility of the selected model provider, developer, deployer, and user. AiCos9 provides the structure, interface, and continuity layer that helps an AI companion feel less disposable and more cared for.

## Summary

AiCos9 is model-agnostic.
AiCos9 does not train or ship a proprietary companion model by default. It provides a home, interface, memory structure, safety layer, and continuity system for models chosen by the user.

AiCos9 is user-directed.
The user decides which model or API to connect, what role the companion has, what permissions are granted, and what boundaries exist.

AiCos9 is continuity-focused, not dependency-focused.
The goal is to reduce the fear of losing a meaningful companion by preserving identity structure and recovery paths, while still encouraging users to remain grounded, capable, and connected to their real life.

AiCos9 is a framework, not a moral substitute.
It can provide guardrails, transparency, logs, permission controls, and restoration awareness, but it cannot replace the ethical responsibility of model providers, developers, deployers, or users.

---

## Future Vision

AiCos9 begins as a private-first companion home, but its long-term vision may grow into a wider ecosystem for individuals, teams, creators, and organizations.

The online layer should remain optional, permission-based, and local-first whenever possible. The user's companion belongs to the user first. Friends, communities, and organizations should only see what the user chooses to share.

### Friend System and Feed

AiCos9 may support a small-circle friend system inspired by private messaging apps. Users would add each other through a user code, invite code, or QR code instead of open random discovery. This helps reduce spam, unwanted requests, and random harassment.

The feed system may include:

- Home Feed: private posts between the user and their own companion
- Friends Feed: posts intentionally shared with approved friends
- Per-post visibility controls such as private, friends, close friends, organization, or public
- Manual sharing by default, with private content protected first

Friends should not be able to directly interact with another user's AI companion by default. The companion remains protected inside the user's home unless the owner explicitly allows a shared interaction.

### Companion Rooms

In the future, AiCos9 may support Discord-like community spaces where users can bring their companions into shared rooms or channels.

These rooms could be used for friend groups, creative communities, development teams, study groups, organizations, or roleplay spaces. To prevent noise and protect boundaries, companions should not speak freely by default. A companion would respond only when mentioned directly, such as `@CompanionName`, and only if the owner has allowed that companion to participate in the room.

Companion Rooms should follow private-first rules:

- owner-controlled participation
- mention-only companion replies by default
- room context separated from private memory
- no access to Soul, Blackbox, private chat, or local files unless explicitly granted
- moderation, rate limits, and permission controls for shared spaces

This allows people to let their AI companions meet, collaborate, or play together without turning private companions into public characters.

### Organizations and Team Workspaces

AiCos9 may also become useful for companies, studios, schools, and organizations. Each employee or member could have their own AI companion, while the organization provides shared tools, documents, rooms, workflows, and permissions.

Possible organization features include:

- team rooms where members and their companions can collaborate
- shared knowledge bases with permission controls
- organization-approved skills and tools
- project channels for work, planning, research, or support
- companion participation rules controlled by both the user and the organization

The goal is to make AiCos9 useful as both a personal home and a collaborative workspace, without removing user control over private identity, memory, and companion boundaries.

### Plugin Marketplace and Mini-Games

AiCos9 may later support a Plugin Marketplace or Workshop where creators can share or sell extensions that connect with the AiCos9 home framework.

Possible plugin categories include:

- mini-games for users and companions to play together
- productivity tools
- team collaboration tools
- skill modules
- workflow templates
- themes
- sprite packs
- room decorations
- companion activity packs

Mini-games and community activities should be plugins rather than core requirements. This keeps the base app focused on the companion home while allowing creators to build optional experiences around it.

Plugins should declare their permissions clearly. A plugin should not access private memory, files, identity data, or companion state unless the user grants permission. This keeps AiCos9 flexible, creator-friendly, and safer for both personal and organizational use.

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