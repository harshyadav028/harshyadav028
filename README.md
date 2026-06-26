<h1 align="center">Hi, I'm Harsh Yadav 👋</h1>

<p align="center">
  <b>CSE @ IIT Mandi</b> &nbsp;·&nbsp; AI / ML Systems &nbsp;·&nbsp; Full-Stack
</p>

<p align="center">
  <a href="http://linkedin.com/in/harsh-yadav-40208a333"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:harsh110406@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 👨‍💻 About Me

I'm a Computer Science & Engineering undergraduate at **IIT Mandi** who likes building systems that hold up under real load and real scrutiny — from LLM context-compression pipelines to a production academic ERP serving ~2,000 students.

- 🔭 Working across **Agentic AI / NLP**, and  **full-stack web**
- ⚙️ Currently a **Full-Stack Developer** on IIT Mandi's *Sootrank* academic ERP
- 🧩 I care about measurable results — most projects below ship with benchmarks, not just claims

---

## 🛠️ Tech Stack

**Languages:** `Python` · `C++` · `C` · `JavaScript` · `TypeScript` · `SQL`

**AI / ML:** `PyTorch` · `TensorFlow` · `Transformers` · `Hugging Face` · `LangChain` · `spaCy` · `FAISS` · `scikit-learn`

**Web & Backend:** `React` · `Next.js` · `Node.js` · `Express` · `Django` · `Flask` · `FastAPI` · `REST APIs`

**Data & Infra:** `PostgreSQL` · `MongoDB` · `SQLite` · `Firebase` · `Docker` · `Nginx` · `Git` · `Linux`

---

## 🚀 Featured Projects

### 🏛️ Sootrank — Academic ERP for IIT Mandi
*Django · PostgreSQL · PgBouncer · Gunicorn · Docker · OWASP ZAP · Locust · CI*
> Full-stack academic ERP digitising the entire semester lifecycle across 5 roles on a 29-model schema. I work across security, DevOps, and feature development.
- 🔒 Authored a **business-logic & access-control audit** over ~100 endpoints × 5 roles, surfacing a confirmed prerequisite-bypass and 5 endpoints serving `200 OK` to unauthorized roles
- ⚡ Engineered **PgBouncer connection pooling** that fixed connection exhaustion under concurrent load
- 📈 **Load-tested to 231 req/s over 6,542 requests with 0 failures**; refactored an 11,600-line monolithic `views.py` into focused, paginated modules

🔗 <!-- TODO: add Sootrank repo or live link (or "private — internal IIT Mandi project") -->

---

### 🧠 ContextOS — Context-Compression Middleware for Multi-Turn LLM Agents
*Python · PyTorch · HuggingFace Transformers · FAISS · spaCy · LLMLingua · Gradio*
> A 7-layer pipeline that shrinks LLM conversation context ~90% while **never dropping safety-critical constraints** (allergies, budgets, deadlines).
- 🏗️ Architected a pipeline sequencing NER → token compression → salience scoring → FAISS retrieval → knowledge-graph safety check
- 💰 Cut context tokens **~90%** (~10× mean, up to **44× peak**) and per-session inference cost ~90%; **0 context overflows vs 19** in the naive baseline
- ✅ **100% critical-constraint retention**, proven model-agnostic across SmolLM2-1.7B and Qwen2.5-3B
- 🥈 **2nd place**, Context Compression track @ Hack 60 (HCLTech, IIT Mandi), 450+ participants

🔗 [View Repository](https://github.com/harshyadav028) <!-- TODO: replace with the exact ContextOS repo URL -->

---

### 👁️ Diff-IrisPAD — Unsupervised Iris Presentation-Attack Detection *(Research)*
*Python · PyTorch · Latent Brownian Bridge Diffusion (LBBDM-f4) · ViT-B/16 · VQGAN*
> A spoof detector trained **only on genuine irises** — zero attack labels at any stage — that flags 8 attack types by reconstruction divergence. Under review at IJCB 2026.
- 🎯 **30.46% ACER** under the strict Zero-Attack-Knowledge protocol on LivDet-Iris 2025 (50,612 attack images), beating the AnoDDPM baseline by **9.27 pp**
- 🔬 Ran a systematic scoring-method ablation over a **125,854-image** preprocessing pipeline, selecting ViT-B/16 CLS cosine divergence as the final scorer
- 📊 Benchmarked against 5 supervised baselines (ResNet50, ViT-B, MaxViT, DINOv1, DINOv2)

🔗 [View Repository](https://github.com/harshyadav028) <!-- TODO: replace with the exact Diff-IrisPAD repo URL -->

---

---

### 💸 Finance Tracker — Agentic Real-Time Finance Platform
*Next.js · Fetch.ai uAgents · Python · LangChain · FAISS · Gemini · Docker*
> A multi-service finance tracker where users chat with an AI advisor that runs **RAG over their transaction history** via two cooperating Fetch.ai agents.
- 🤖 Engineered a multi-agent RAG pipeline: a user agent forwards queries to a RAG agent that embeds transactions in FAISS and answers with Gemini
- 🐳 Containerized a **6-service, 3-language** system into a single Docker image
- 🥉 **3rd place**, Fetch.ai track @ FrostHack '25 (IIT Mandi)

🔗 [View Repository](https://github.com/Aman071106/FrostHack2025)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=harshyadav028&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=harshyadav028&theme=radical&hide_border=true" alt="GitHub Streak" height="165"/>
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshyadav028&layout=compact&theme=radical&hide_border=true&langs_count=8" alt="Top Languages"/>
</p>

---

<p align="center"><i>Open to SDE / ML / research internships — let's build something measurable.</i></p>
