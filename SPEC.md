# Lamar Chisolm — Resume Landing Page Spec

## Brand & Design

- **Theme:** Dark / Cyberpunk-minimal
- **Background:** `#0a0a0f` (near-black)
- **Accent:** `#00f5d4` (electric cyan)
- **Text:** `#e8e8e8` (soft white), `#888` for secondary
- **Font:** Inter (body), JetBrains Mono (code/tech elements)
- **Vibe:** Builder, architect, founder — minimal ego, maximum output

---

## Page Sections

### 1. Hero

**Headline:**
> I Build Systems That Think.

**Subheadline:**
> Full-stack engineer specializing in multi-agent architectures, real-time dashboards, and infrastructure that scales quietly — without the buzzword theater.

**CTA:**
- `[GitHub]` `[Telegram]` `[Email]`

---

### 2. About

**Bio:**
> INTJ. Systems thinker. I don't ship features — I design states. My work sits at the intersection of autonomous agents, encrypted infrastructure, and interfaces that don't get in the way. Built distributed systems before it was trending, and I'll build them after the hype dies.

**Tagline:** *Architecting the infrastructure of independent agents.*

---

### 3. Skills

**Tech Stack (punchy, no fluff):**

- **React + TypeScript + Vite** — Zero-tolerance for runtime surprises. Type-safe UIs built at the speed of thought.
- **Node.js + Cloudflare Workers** — Edge-native. Sub-millisecond cold starts. Your API lives at the frontier.
- **Multi-Agent Orchestration** — Autonomous agents that coordinate, decide, and execute — no human in the loop by design.
- **PostgreSQL + Redis** — When the data matters, you don't compromise. Relational rigor with cache-layer speed.
- **Python + AI Integration** — LLMs that do work. Not chatbots — pipelines.

---

### 4. Projects

#### Multi-Agent System
> An autonomous agent network where independent processes collaborate on complex goals. Each agent owns its domain, communicates via structured protocols, and escalates gracefully. Built for reliability — not demo appeal.

#### Dashboard
> Real-time operational intelligence. Data flows in, context emerges, decisions accelerate. Built with React + Cloudflare for zero-latency updates at the edge.

#### Respirator
> Health monitoring infrastructure that respects your privacy. End-to-end encrypted, self-hosted option, zero vendor lock-in. Because your biometric data isn't their product.

#### Encrypted Vault
> Secure storage architecture with military-grade encryption and zero-knowledge access patterns. Your secrets don't touch the cloud unencrypted — ever.

---

### 5. Contact

- **Email:** lamarchisolm@proton.me
- **GitHub:** github.com/lamarchisolm
- **Telegram:** @lamarchisolm

**Footer note:** *Response time: < 24h. For serious inquiries only.*

---

## Animation Spec

- **Background:** CSS grid overlay (subtle, low-opacity cyan lines)
- **Scroll reveals:** `opacity: 0 → 1` + `translateY(20px → 0)` on intersection, 600ms ease-out, staggered 100ms
- **Hero parallax:** Slight `translateY` on scroll (0.3x rate)
- **Hover states:** Cyan glow on interactive elements (`box-shadow` pulse)
- **Font approach:** Inter for all body, JetBrains Mono for code snippets, tags, labels

## Technical Stack

- Single HTML file
- Tailwind CSS via CDN
- Google Fonts: Inter + JetBrains Mono
- Vanilla JS for scroll animations (Intersection Observer)
- No build step required
