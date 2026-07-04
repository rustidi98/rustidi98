<div align="center">

# Hi, I'm Rustem 👋

### I took a healthcare AI product from an empty page to daily use in a real clinic — solo.

I'm a founder and **AI product engineer**. I built **Signalo** — an AI platform for medical
clinics — end to end: the iOS and Android apps, the web portal, the backend, and the AI that
runs it. It's used every day in a clinic doing **~$5.1M a year**. Before software, I spent
years building and selling my own companies — which is why I build for what survives real use,
not for a demo.

_Most people who can run a business can't ship the product. Most who can ship the product have
never carried a P&L. I've done both — and there's a live medical product to prove it._

<br/>

![Relocating](https://img.shields.io/badge/🌏_Relocating-NZ_%2F_Australia-1f6feb?style=flat-square)
![Role](https://img.shields.io/badge/AI_Product_Engineer-6f42c1?style=flat-square)
![Open to work](https://img.shields.io/badge/Open_to-AI_product_%26_applied--AI_roles-2ea44f?style=flat-square)
[![Email](https://img.shields.io/badge/Email-rust.idi98@gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rust.idi98@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rustem_Idiatullin-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rustem-idiatullin)

**[Signalo →](https://github.com/rustidi98/signalo-showcase)**  ·  **[How I build with AI →](https://github.com/rustidi98/ai-engineering-showcase)**  ·  **[Email me →](mailto:rust.idi98@gmail.com)**

</div>

---

## 🤖 How I build

Here's how I work, up front: **I build by directing AI, not by hand-writing code.** I own the architecture, break the work into pieces, steer coding agents (Claude, Codex), review every change, and stand behind everything that ships. It's how one self-funded person built and now runs a product a 100-person clinic depends on every day — at the pace of a small team.

My edge is **leadership, business logic, and product judgment** — seeing how a thing should work, how people will actually use it, and getting production-grade output from a team, human or AI. **The code is the output; the judgment is the work.**

It's real software all the same — iOS (Swift), Android (Kotlin), a Next.js web app, a NestJS backend, and GPU workers for the AI — and I designed and directed every part of it.

Three rules I hold the work to:

- **Honest output over a good demo.** Left alone, an AI model will happily write a clinical detail that was never said — so stopping that isn't a nice-to-have, it's the product. If something couldn't be confirmed, it's never shown as a fact.
- **Reliable even when the parts aren't.** Patients were getting logged out mid-visit — it happened eight times before I stopped patching symptoms and fixed the principle: only end a session when it's positively dead, never on a network blip.
- **Cost is a feature.** Every AI call is tracked; moving the GPUs to a scale-to-zero setup killed a ~$20/day leak without hurting speed. If a simple rule does the job, it doesn't get an expensive model.

## 🩺 What Signalo actually does

In every appointment, important things get said — what the patient wants, what was promised, what was discussed. Normally that stays in one person's head and is lost the moment they leave or the patient sees someone else.

Signalo records the visit, turns the messy audio into a structured medical note, and pulls it together with the clinic's CRM and practice-management system — so the knowledge stays with the clinic, not just the person. On top of that it coaches staff on how they talk with patients, and flags what's slipping through the cracks (a big treatment plan discussed, but no follow-up booked). The result: the clinic keeps its knowledge when people come and go, and stops losing patients and money to things that quietly fell through.

## 😁 Signalo Smile — a second product, +20% case acceptance

**Signalo Smile** shows a patient their future smile, instantly, right in the chair. The wow-effect is immediate — they see the result before they commit — and in the clinic it lifted **case acceptance (patients saying yes to treatment) by ~20%**. Another product born from a real problem in a clinic, built the same way: me, directing AI.

## 🧠 What I work on

1. **Turning conversations into clear notes.** Real, messy audio into structured medical notes — with safeguards against invented facts, and eval checks so swapping a model can't quietly make the notes worse.
2. **Speech-to-text at scale.** A self-hosted GPU system (GigaAM-v3, which beats Whisper on Russian) that transcribes visits, separates who is speaking, and recognises staff by voice across visits.
3. **Medical data done right.** Records you can sign and lock, a full history of every change, and strong privacy — the bar a real clinic and its lawyers expect.
4. **An AI-orchestrated way of building.** Reusable tools, review agents and automatic checks that let one person build and run a product this size without cutting corners.

## 🏗️ How it's built

```
 iOS · Android · Web  →  NestJS API  →  BullMQ workers  →  GPU speech-to-text (RunPod · GigaAM-v3)
                             │                                    │
                    PostgreSQL · Redis · R2            AI pipeline (Claude · Gemini)
                             │
     Medical notes · Coaching · CRM auto-notes · Owner analytics · iDent + amoCRM
```

## 🧭 How I got here

Before I built software, I spent years building and running my own businesses. When it's your own money and your own customers on the line, a nice demo means nothing — what matters is whether it actually works. I build products the same way.

| When | What | Notes |
|:---|:---|:---|
| **2026 → now** | **Signalo** — Founder & builder | AI product for medical clinics, built solo, used every day in a paying dental clinic |
| **2023 – 25** | **Matrius** — Director of Marketing (CMO) | Children's-education company. Joined at ~**$190K/mo** revenue, grew it to ~**$380K/mo** (company ~**$4.5M/yr**) at **350–400% ROMI**; ran a 15-person marketing team; offered equity |
| **2020 – 23** | **StudyWay** — Founder & CEO | Online exam-prep school — grew it to **~1,000 students/yr** and a team of 50, then **sold it in 2023** |
| **2017 – 20** | **Electronics retail** — Founder & Owner | My own **Apple & Xiaomi shop** — grew it to **$64–90K/mo**, then **sold it in 2020** |
| **2012 – 16** | **First ventures, from age 14** | Fixing **Apple devices** — from a bench at home to a repair centre |

## 📦 Showcase repos

The product code stays private — patient data and live commercial products. These repos are the *story* of what I built and how, with clean, representative examples.

| Repo | What it shows |
|:---|:---|
| 🧠 **[signalo-showcase](https://github.com/rustidi98/signalo-showcase)** | AI for clinical conversations — the architecture, the decisions, real problems I hit and fixed |
| 🤖 **[ai-engineering-showcase](https://github.com/rustidi98/ai-engineering-showcase)** | How I build with AI agents — my actual method, tools and quality checks |
| 📚 **[tasks-knowledge-showcase](https://github.com/rustidi98/tasks-knowledge-showcase)** | A knowledge & task platform — notes, databases-in-documents, an AI workspace |
| 📞 **[callbase-showcase](https://github.com/rustidi98/callbase-showcase)** | Data engineering — handling large contact databases: import, clean, filter, export at scale |

<details>
<summary>📖 <b>The longer story</b> — from a repair bench to production AI</summary>

<br/>

I've been building and fixing things since I was a kid. It started at home, repairing Apple phones and laptops at the kitchen table. That turned into a job at a repair centre, and then my own shop selling and fixing Apple and Xiaomi devices. I was young, and already running the whole thing myself.

Then I went bigger. I started an online school that prepared kids for their exams, grew it to about 1,000 students a year and a team of 50, and sold it. After that I ran marketing at a children's-education company, leading a 15-person team and growing revenue past ~$4.5M a year.

Then I found the problem I really cared about: healthcare, and I focused on dental clinics. This time I made a choice that surprised people — instead of hiring engineers or just running the business, I'd build the product myself. Not by becoming a classic programmer, but by getting very good at directing the AI that writes the code.

That's what I did. Signalo runs in a real clinic every day, and I directed and shaped every part of it — the apps, the website, the backend, the AI. I understand exactly why it works, because I built all of it.

</details>

## 🤝 How I work with people

I've led teams of up to 50 people. Two things come up again and again from people who worked for me: I bring order to messy, chaotic work, and I actually invest in the people doing it — a growth plan for each person, honest feedback, and clear standards the team can rely on.

> "Rustem can bring order to the messiest processes fast — and he showed me by his own example what a genuinely invested head of marketing looks like. After he left, I was promoted to Head of Marketing on the system he built."
> — **Vasilisa Levina**, my Performance Marketing lead → now at Yandex Praktikum

**[Connect on LinkedIn →](https://linkedin.com/in/rustem-idiatullin)** — references from former colleagues available on request.

## 🧰 Tech in the product

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RunPod GPU](https://img.shields.io/badge/RunPod_GPU-673AB7?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)

## 🌏 Moving abroad — with my family, for good

My wife, our daughter and I are planning a full move abroad, and we're looking seriously at both **New Zealand and Australia**. We haven't picked a city yet. This isn't a short trip — we want to move, settle, and build our life there for good.

I don't have a work visa yet — I'm ready for a full move and open to a company sponsoring my visa (New Zealand's AEWV). What matters most is a good role and enough income to settle and grow.

**I'm open to AI Product Engineer / Applied AI roles in New Zealand and Australia** — building real products with AI, especially in health-tech and SaaS.

### 🌱 Outside the code

<img align="right" width="300" src="assets/family.jpg" alt="Rustem with his family"/>

**Family first.** My wife **Adelya** and I have been together since we were 14 — we've built everything as a team. Now we're raising our four-year-old daughter, **Olivia**. Building a good life for them is a big part of why we're making this move.

I recharge outdoors and with my hands — hiking, life out of the city with a bit of land to look after, and cooking on the grill. I like having room to breathe.

**Also into:** 🥊 boxing · 🎾 tennis · 🏍️ motocross · 🧱 Lego · 🎮 CS2 · 🧖 banya. No bad habits — I'd rather be in the ring or on the trail.

<br clear="right"/>

<div align="center">

📫 **[rust.idi98@gmail.com](mailto:rust.idi98@gmail.com)**  ·  [LinkedIn](https://linkedin.com/in/rustem-idiatullin)  ·  [github.com/rustidi98](https://github.com/rustidi98)

</div>
