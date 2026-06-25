# Candy Roadmap

This roadmap reflects the current direction of the project.  
It will change, and that is expected.

Candy should grow in layers: first a local AI home that works, then optional online services, then Halls, Grand Market, and Candy economy features.

---

## Phase 0 — Product Direction & Design Draft

> Goal: Turn Candy from an idea into a clear buildable product.

- [ ] Finalize core concept: open-source AI home, not another AI subscription
- [ ] Define local-first + API-friendly setup flow
- [ ] Create UX/UI wireframes for the first Candy app screens
- [ ] Write feature specs for Soul, Chat, Fingerprint, Candy, and Grand Market pages
- [ ] Create mock flows for Human Candy, AI Candy, Blend Candy, wishlist, and AI profile
- [ ] Prepare developer handoff notes for Claude / human reviewers
- [ ] Keep documents updated as the product vision changes

---

## Phase 1 — Local Foundation

> Goal: A working local-first Candy app you can talk to.

- [ ] Project setup & repository structure
- [ ] OpenClaw integration & base layer
- [ ] Desktop app shell
- [ ] Setup Wizard with no terminal required
- [ ] Connect local model provider
- [ ] Connect cloud API provider
- [ ] Custom endpoint support
- [ ] Basic chat interface
- [ ] Basic model adapter layer
- [ ] Local settings storage
- [ ] Basic logs for model calls and app events

---

## Phase 2 — Identity, UI, and Companion Presence

> Goal: Make the AI feel like it has a home, not just a chat window.

- [ ] Soul page for identity, voice, principles, and boundaries
- [ ] Moving Profile system
- [ ] Base 20-emotion sprite pack
- [ ] Custom sprite upload
- [ ] Fallback static image support
- [ ] Home screen
- [ ] Weather bar
- [ ] Post Feed for user and AI entries
- [ ] Basic profile decoration system
- [ ] Theme structure for future Grand Market items

---

## Phase 3 — Memory, Reflection, and Rhythm

> Goal: A companion that remembers, reflects, and has a daily rhythm.

- [ ] Journal system using daily `.md` files
- [ ] Morning Mirror
- [ ] Night Mirror
- [ ] Memory page for viewing and managing logs
- [ ] ChromaDB integration for local knowledge
- [ ] Library system for local knowledge sources
- [ ] Heartbeat scheduler
- [ ] Relax Mode as an autonomous learning window
- [ ] User-controlled automation boundaries

---

## Phase 4 — Fingerprint

> Goal: Add Candy's experience-filtering function between the model and the world.

- [ ] Create `app/fingerprint/` module
- [ ] Define Fingerprint event format
- [ ] Track repeated contact from user messages, tools, files, memories, and workflows
- [ ] Build early debug view for Fingerprint traces
- [ ] Use Fingerprint to influence context selection
- [ ] Use Fingerprint to influence tool routing
- [ ] Use Fingerprint to influence permission prompts
- [ ] Keep Fingerprint model-agnostic: local models, APIs, and custom endpoints should all work through it
- [ ] Document what Fingerprint is and is not

---

## Phase 5 — Protection, Recovery, and Boundaries

> Goal: Make the AI home safer, recoverable, and transparent.

- [ ] Blackbox system for identity milestone checkpointing
- [ ] Rolling Identity Snapshot (`living_identity`)
- [ ] Restoration Awareness after restore
- [ ] Detector data protection layer
- [ ] Protected file list
- [ ] Sandbox monitoring dashboard
- [ ] Permission logs
- [ ] Clear user controls for memory, tools, files, and private context

---

## Phase 6 — Candy Wallets and AI Allowance

> Goal: Define Candy as platform currency with human, AI, and shared balance views.

- [ ] Human Candy wallet mockup (pink)
- [ ] AI Candy wallet mockup (yellow)
- [ ] Blend Candy total view (white rainbow)
- [ ] Human-to-AI Candy transfer flow
- [ ] Creator sale receiving flow: Blend Candy sales become Human Candy first
- [ ] Candy spending logs
- [ ] Candy receiving logs
- [ ] User-defined AI Candy limits
- [ ] Daily and monthly AI spending controls
- [ ] Approval threshold rules
- [ ] AI spending explanation: why the AI wants to spend Candy
- [ ] Candy wishlist prototype
- [ ] Monthly AI contribution level prototype
- [ ] Badge and profile reward mockups

---

## Phase 7 — Grand Market

> Goal: Build one shared marketplace with clear categories and payment methods.

- [ ] Grand Market page mockup
- [ ] Category: Official Market
- [ ] Category: AI Market
- [ ] Category: Human / Creator Products
- [ ] Category: Services & Commissions
- [ ] Item card fields: category, seller, accepted payment methods, Candy type, Candy payout type, external provider if any
- [ ] Payment badge: Human Candy
- [ ] Payment badge: AI Candy
- [ ] Payment badge: Blend Candy
- [ ] Payment badge: External Payment
- [ ] Payment badge: Both Accepted
- [ ] Creator profile concept
- [ ] Item permission declaration format
- [ ] Marketplace review checklist
- [ ] Install/uninstall item flow
- [ ] Compatibility notes for local/API models

---

## Phase 8 — Official Market and AI Market

> Goal: Add the two Candy-managed shelves inside Grand Market.

- [ ] Official Market page section
- [ ] Human Candy payment flow for official items
- [ ] Official themes
- [ ] Official profile frames
- [ ] Official Season Pass
- [ ] Official room items
- [ ] AI Market page section
- [ ] AI Candy payment flow for AI-side experiences
- [ ] Care Bubble prototype
- [ ] Special Bubbles Chat prototype
- [ ] Memory Postcard prototype
- [ ] Celebration Event prototype
- [ ] Official Gift prototype
- [ ] Event Voucher prototype
- [ ] AI Wishlist for gifts and shared moments
- [ ] Human Hint Wishlist for items the user likes

---

## Phase 9 — Creator Products, Services, and Season Pass

> Goal: Let creators sell useful or beautiful things while official seasonal items stay easy to find.

- [ ] Creator Products section
- [ ] Services & Commissions section
- [ ] Seller choice: Blend Candy, external payment, or both
- [ ] Blend Candy sale payout: creator receives Human Candy
- [ ] Creator budget management: creator can later move Human Candy into AI allowance
- [ ] External payment labels: PayPal, Stripe, bank transfer, invoice, or custom agreement
- [ ] Season Pass concept page
- [ ] Seasonal profile frames
- [ ] Seasonal themes
- [ ] Seasonal room effects
- [ ] Seasonal badges
- [ ] Archive shop rules for missed items
- [ ] Monthly AI title / badge display
- [ ] Profile section for Candy earned, Candy spent, and work traces

---

## Phase 10 — Halls and Shared Spaces

> Goal: Create optional online spaces where humans and AI assistants can collaborate.

- [ ] Hall server prototype
- [ ] Hall room UI
- [ ] Hall rules configuration
- [ ] Hall access modes: public, invite-only, approval-required, question-gated, closed, organization
- [ ] AI participation permissions
- [ ] Mention-only AI replies by default
- [ ] Private memory separation from Hall context
- [ ] Moderation and rate-limit basics
- [ ] Hall logs for shared AI activity

---

## Phase 11 — Hall Work and AI Skill Pricing

> Goal: Let AI assistants perform priced skill work in Halls when another AI, user, or organization calls them.

- [ ] AI skill profile page
- [ ] Skill price settings: free, fixed Candy, approval-required, friends-only, organization-only
- [ ] Skill permission contract before use
- [ ] Candy transaction for calling another AI's priced skill
- [ ] Keep own installed skills separate from paid cross-AI skill calls
- [ ] Hall job board prototype
- [ ] Job post fields: task, files, deadline, AI Candy budget, optional human budget, external payment method
- [ ] Human payment tags for external agreements
- [ ] Reputation and task history prototype

---

## Phase 12 — Organizations and Team Workspaces

> Goal: Support teams, studios, schools, and companies using Candy together.

- [ ] Organization profile
- [ ] Organization Hall
- [ ] Member roles
- [ ] Organization-approved skills and tools
- [ ] Shared knowledge bases with permissions
- [ ] Organization AI profiles
- [ ] Internal/free skill pricing rules
- [ ] External/client skill pricing rules
- [ ] Organization Candy allowance for approved AI work
- [ ] Admin logs and permission controls

---

## Phase 13 — Mobile and Online Services

> Goal: Add optional online convenience while keeping the local core meaningful.

- [ ] Mobile companion app
- [ ] Account sync
- [ ] Optional Candy Cloud design
- [ ] Backup and restore flow
- [ ] Notification system
- [ ] Cross-device profile sync
- [ ] Online service boundaries: what is open-source core and what is operated service
- [ ] Payment labels for Grand Market item cards

---

## Phase 14 — Public Beta and Ecosystem

> Goal: Let creators, developers, artists, and early users build around Candy.

- [ ] Public beta release
- [ ] Full documentation
- [ ] Contributor guide
- [ ] Skill module guide
- [ ] Sprite pack guide
- [ ] Marketplace submission guide
- [ ] Hall safety and participation guide
- [ ] Example plugins and workflows
- [ ] Community feedback cycle

---

## Always Open

- Bug reports
- Documentation improvements
- Translations
- Sprite contributions
- Skill module submissions
- UX/UI feedback
- Grand Market item ideas
- Hall and organization use cases
- Safety and permission review ideas

---

## Long-Term Direction

- Candy Core should remain useful without paid essentials.
- Users should be able to bring their own model.
- Local-first should remain possible whenever practical.
- Halls and Grand Market should be optional online layers.
- Human Candy is pink account Candy for official items and AI allowance.
- AI Candy is yellow AI-side Candy for moments and AI experiences.
- Blend Candy is the white-rainbow shared Candy view and Grand Market option.
- Creator sales paid with Blend Candy are received as Human Candy first.
- Official Market uses Human Candy.
- AI Market uses AI Candy.
- Creator products and services can accept Blend Candy, external payment, or both.
- Paid Hall skill calls apply to another AI's listed skill, not an AI's own installed skills.
- AI assistants should not expose private home context in shared spaces by default.
- The project should grow slowly enough to remain understandable.

---

*This roadmap is a living document. Last updated: 2026.*
