<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F5597,50:5046E5,100:8F7EF7&height=220&section=header&text=Archi%20Kumari&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Agent%20Developer%20%7C%20Full-Stack%20Builder&descAlignY=58&descSize=19" width="100%"/>

<img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="28"/>&nbsp;&nbsp;<b>Welcome to my profile!</b>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=23&pause=1000&color=5046E5&center=true&vCenter=true&width=650&lines=AI+%2B+ML+Developer;Full-Stack+Builder;Compiler+%26+Systems+Enthusiast;Turning+ideas+into+shipped+code" alt="Typing SVG" />
</a>

<p>
  📍 Noida, Uttar Pradesh &nbsp;·&nbsp; 🎓 B.Tech CSE (AIML) @ IILM University &nbsp;·&nbsp; 📫 archikumari0770@gmail.com
</p>

</div>

---

### 👩‍💻 About me

I build things that connect machine learning to real, usable software — from a 30-case AI diagnosis pipeline that hit a 96.7% human-reviewed acceptance rate, to a hand-written compiler with a DAG-based optimizer, to full-stack apps with real OAuth, real queues, and real external APIs wired end-to-end.

- 🔭 Currently building **NetSage AI**, an AI-powered network troubleshooting pipeline
- 🌱 Learning: deeper prompt-engineering and RCA workflows for LLM-based diagnosis systems
- 💬 Ask me about: PyTorch model evaluation, MERN-stack apps, or compiler internals
- ⚡ Fun fact: I've debugged an OAuth flow across three separate redirect hops and lived to tell the tale

---

### 🛠️ Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,java,c,js,pytorch,tensorflow,nodejs,react,express,mongodb,postgres,redis&theme=light" />
</div>

---

### 🚀 Featured Projects

#### 🔄 [ReachInbox Mini](https://github.com/archikumari0770/reachinbox-scheduler) — Email Scheduler + Dashboard

A production-shaped email scheduling system built around the idea that scheduling has to survive restarts, crashes, and duplicate attempts without ever double-sending or losing an email.

- ⚡ **Exact-time delivery** via BullMQ delayed jobs backed by Redis (AOF-persisted, so nothing's lost on restart)
- 🔒 **Idempotent by design** — deterministic job IDs + a database-level claim guard mean a job can never be processed twice, even under worst-case retries
- 🚦 **Per-sender hourly rate limiting** using atomic Redis counters, with over-limit emails automatically rescheduled (never dropped) into the next hour
- 🔔 **Live Slack alerts** the moment a rate limit is hit, via a real Slack OAuth v2 integration
- 🔍 **Elasticsearch-backed search** across sent/scheduled mail
- 🔑 **Real Google OAuth login**, deployed end-to-end on Railway + Vercel — including surviving a cross-domain cookie bug and two separate OAuth redirect-URI bugs along the way

#### ⚙️ [Mini Compiler](https://github.com/archikumari0770/mini-compiler) — Hand-Written 6-Phase Compiler Pipeline

A from-scratch Java compiler, no parser-generator libraries — every phase hand-written to actually understand how a compiler works internally, not just call one.

- 📝 **Full lexer** — keywords, identifiers, numbers, string/char literals, comments, multi-character operators
- 🌳 **Recursive-descent parser** with correct operator precedence (handles `*`/`/` binding tighter than `+`/`-`, and nested parentheses) via a proper `E → T → F` grammar
- 🧮 **Three-address code generation** from a post-order AST traversal
- 🚀 **DAG-based optimizer** that performs real **common-subexpression elimination** — if two expressions compute the same thing, it's computed once and reused, and dead (unused) values are dropped automatically
- ✅ **Semantic checking** for use-before-assignment, plus simulated x86-style assembly codegen to show the full pipeline end-to-end

#### 📊 [Regression Bias Detector](https://github.com/archikumari0770/Bais_Detector) — ML Model Diagnostics Tool

Turns "does my model look overfit?" from a judgment call into an automated, evidence-based verdict.

- 🔬 **14 diagnostic features** extracted per model — train/test error gap, residual statistics, cross-validation stability, learning-curve gap, model complexity, and more
- 🧠 **Neural network classifier**, trained on hundreds of synthetically generated underfit/overfit/well-fit examples, to make the actual call
- 🎯 **Confidence-scored verdict**: underfitting, overfitting, or well-fitted — not just a guess
- 🛠️ **Actionable fixes** — flags the *specific* hyperparameter likely causing the issue (e.g. `max_depth`, `alpha`) and suggests a concrete fix
- 📈 **Full diagnostic visualization** — a 6-panel report covering predicted-vs-actual, residuals, and learning curves in one image

#### 👗 [AI Fashion Recommender](https://github.com/archikumari0770/AI-fashion-Recommendation) — Weather-Based Outfit Generator

A full-stack MERN app that turns "what should I wear today?" into an API call.

- 🌦️ **Live weather integration** via the OpenWeatherMap API, classified into weather categories (hot/warm/cool/cold)
- 👕 **Smart outfit generation** — samples matching tops, bottoms, outerwear, accessories, and footwear from MongoDB based on the current weather category
- 🎨 **Color-compatibility filtering** — accessories are matched to actually complement the outfit's colors, not just picked at random
- 🔁 **"Get Different Outfit"** — re-roll for a new combination within the same weather category, instantly

---



### 🏆 Achievements

- 🥈 2nd Place, SGU College Hackathon (March 2026)
- 🏁 Internal SIH 2025 Finalist — built a brain-computer interface to detect words from brain signals
- 🏁 GDG Hackathon 2025 Finalist
- 👥 Executive Member, Coding Warrior — college coding club

---

<div align="center">

### 📫 Reach Me

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:archikumari0770@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8F7EF7,50:5046E5,100:2F5597&height=120&section=footer" width="100%"/>

</div>
