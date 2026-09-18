# Amarnath Mishra

### Product Builder · Product Analyst · Full-Stack Engineer

I build products at the intersection of **users, business problems, product thinking, and engineering**.

My current focus is **AI-powered product development** — taking a problem from discovery and workflow design through technical execution, validation, and iteration.

**Currently building:** **AIBOT** — an AI-powered lead conversation platform.

[![AIBOT](https://img.shields.io/badge/Building-AIBOT-FF6A00?style=flat-square)](https://github.com/Rrachet/AIBOT)
[![Live Product](https://img.shields.io/badge/Live-AIBOT-151515?style=flat-square)](https://aibot-amar-proj.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amarnath%20Mishra-151515?style=flat-square&logo=linkedin)](https://in.linkedin.com/in/amarnath-mishra)
[![GitHub](https://img.shields.io/badge/GitHub-Rrachet-151515?style=flat-square&logo=github)](https://github.com/Rrachet)

---

## 🚀 AIBOT — Current Flagship

### [AIBOT](https://github.com/Rrachet/AIBOT)

**AI-powered lead calling, conversation intelligence, follow-ups and sales workflow platform.**

AIBOT is my main product and engineering project.

```text
LEAD → AGENT → CAMPAIGN → CONVERSATION
                         ↓
                    OUTCOME
                         ↓
              FOLLOW-UP → WHATSAPP
                         ↓
                    ANALYTICS
```

### What I'm building

- Lead management with CSV / Excel import
- Configurable AI agents
- Campaign-based conversations
- Conversation outcomes and summaries
- Automated follow-up workflows
- WhatsApp workflow preparation
- Analytics around conversation performance
- Multi-tenant workspaces with PostgreSQL + RLS
- **Zemo** — a contextual product copilot
- Demo voice previews in English, Hindi and Hinglish
- Provider-agnostic architecture for future telephony, messaging and AI integrations

### Engineering approach

- Clear domain boundaries
- Workspace-level multi-tenancy
- RLS-first data isolation
- Provider abstractions
- Server-side authorization
- Deterministic demo behaviour
- Typed application state
- Regression testing before refactoring core flows
- Real product workflows instead of placeholder UI

---

## 🤖 Zemo

**Zemo is AIBOT's product-native copilot.**

It is intentionally not a generic chatbot.

Zemo understands:

- the current page
- what the page is for
- the next useful action
- contextual product tips
- the current voice-preview state
- safe navigation actions

Its architecture is deliberately replaceable:

```text
ZemoInput → ZemoIntent → ZemoAction → AIBOT
```

The recognition layer is separated from application actions so a future LLM or voice input provider can be introduced without rebuilding the product.

---

## 🎙️ Voice

AIBOT's demo voice architecture separates the conversation from how it is spoken:

```text
Conversation Engine
       ↓
Speech Provider
       ↓
Speech Plan
       ↓
Browser Voice
```

The demo supports:

- English
- Hindi
- Hinglish
- Six sales scenarios
- Play / pause / resume / stop / replay
- Capability-gated live voice preview

There is **one conversation source of truth**. The voice layer does not create calls, leads, follow-ups or analytics records.

---

## 🛠️ Product + Technical Toolkit

**Product:** Product discovery · PRDs · user journeys · requirements · prioritization · roadmaps · MVP definition · experimentation · KPI thinking · GTM

**Analytics:** SQL · Python · Pandas · NumPy · funnel analysis · product metrics

**Frontend:** React · Next.js · TypeScript · JavaScript · Vite · HTML/CSS

**Backend:** Node.js · Express · REST APIs · PostgreSQL · Supabase · Prisma

**AI:** LLM application architecture · conversation systems · prompt design · AI provider abstraction · speech interfaces

**Cloud:** Vercel · Netlify · Azure · GitHub · CI/CD

---

## 📌 Selected Work

| Project | Product signal | Technical signal |
|---|---|---|
| **AIBOT** | AI product development, workflow design, validation | Next.js + Supabase + PostgreSQL + RLS |
| **APIAtlas** | Developer problem, trust and reliability | Next.js + validation + health checks |
| **LaunchPad** | Requirements → system design | React + REST + PostgreSQL |
| **SupportHub** | Customer operations and service workflows | Workflow/state modelling |
| **AI Enhancement Tool** | AI experimentation and evaluation | Next.js + AI integrations |
| **AirCanvas** | Real-time interaction and experimentation | Computer vision + FastAPI + WebSockets |

---

## 📚 All repositories

AIBOT is the flagship. The rest of my public repositories are listed below so this profile represents the breadth of my technical work rather than a single project.

### ⭐ Flagship

| Repository | Focus |
|---|---|
| **[AIBOT](https://github.com/Rrachet/AIBOT)** | AI lead conversations, voice, follow-ups, WhatsApp workflows, analytics, Supabase/RLS |

### 🧠 AI, Product & Full-Stack

| Repository | Focus |
|---|---|
| **[APIAtlas](https://github.com/Rrachet/apiatlas)** | API discovery, validation, reliability and developer tooling |
| **[AI Enhancement Tool](https://github.com/Rrachet/AI-enhancement-tool)** | AI application and enhancement workflows |
| **[LaunchPad](https://github.com/Rrachet/LaunchPad)** | Full-stack application architecture |
| **[TwoFold](https://github.com/Rrachet/TwoFold--App-for-Task-management)** | Task management application |
| **[SupportHub](https://github.com/Rrachet/SupportHub)** | Customer support and service workflows |
| **[Loggin](https://github.com/Rrachet/Loggin)** | Authentication, roles and access workflows |
| **[AirCanvas](https://github.com/Rrachet/AirCanvas)** | Computer vision and real-time interaction |
| **[DSA-Forge](https://github.com/Rrachet/DSA-Forge)** | Data structures and algorithms practice |

### 🌐 Web, Events & Client Projects

| Repository | Focus |
|---|---|
| **[FrogStudio](https://github.com/Rrachet/FrogStudio)** | Branding / marketing agency website |
| **[Heroes of Hyderabad](https://github.com/Rrachet/heroofhyderabad)** | Event website and nomination experience |
| **[India Inclusive Summit](https://github.com/Rrachet/indiainclusivesummit)** | Event website |
| **[VisualWebsite](https://github.com/Rrachet/VisualWebsite)** | Visual web project |
| **[demo_web](https://github.com/Rrachet/demo_web)** | Web application / experimentation |
| **[PWD](https://github.com/Rrachet/PWD)** | Public project workspace |
| **[AppleProject](https://github.com/Rrachet/AppleProject)** | Web / frontend project |
| **[NudgedNation](https://github.com/Rrachet/NudgedNation)** | Web product project |
| **[Gun2Gun](https://github.com/Rrachet/Gun2Gun)** | Web application project |
| **[ThriiLocal](https://github.com/Rrachet/ThriiLocal)** | Thrii product / hiring workflow project |

### 🏗️ Platform Architecture

| Repository | Focus |
|---|---|
| **[LaunchPad-Frontend](https://github.com/Rrachet/LaunchPad-Frontend)** 🔒 | Private frontend codebase |
| **[LaunchPad-Backend](https://github.com/Rrachet/LaunchPad-Backend)** 🔒 | Private backend codebase |
| **[Woodrock](https://github.com/Rrachet/Woodrock)** 🔒 | Private project |

> GitHub's profile page already exposes the full **Repositories** tab. The list above is intentionally kept in the profile README so a recruiter can understand the portfolio without hunting through the repository tab. GitHub also recommends using a profile README plus up to six pinned repositories to showcase your strongest work. citeturn0search1turn0search2

## 🧭 How I build

```text
USER / BUSINESS PROBLEM
        ↓
DISCOVERY
        ↓
PROBLEM DEFINITION
        ↓
SUCCESS METRICS
        ↓
OPTIONS + TRADE-OFFS
        ↓
MVP
        ↓
ENGINEERING
        ↓
SHIP
        ↓
OBSERVE
        ↓
ITERATE
```

For substantial projects, I try to make four things visible:

**Why this problem?**  
**Why this solution?**  
**How do we know it worked?**  
**What should we build next?**

---

## 🎯 Current Direction

I'm moving from:

> **"I can build software."**

toward:

> **"I can identify what should be built, explain why, work with engineering to build it, and measure whether it created value."**

My GitHub is becoming a portfolio of **real product systems with technical proof**.

### Target roles

**Product Manager · Technical Product Manager · Product Analyst · Associate Product Manager · AI Product Manager**

> **Find the problem. Define the outcome. Build the right thing. Measure the result.**
