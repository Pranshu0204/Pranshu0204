<!-- ============================================================
     HERO BLOCK
     Design decision: Dark gradient (deep navy → emerald) signals
     "applied ML systems engineer" rather than "data viz dashboard kid".
     The tagline names what he actually ships, not generic ML buzzwords.
     ============================================================ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,30&height=220&section=header&text=Pranshu%20Gupta&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Building+LLM+systems+that+ship+%E2%80%94+RAG%2C+multi-agent%2C+fine-tuning&descSize=15&descAlignY=58&descColor=10b981" />
</p>

<!-- ============================================================
     TYPING TAGLINE
     Design decision: Lines pulled from real projects — RecruitSense,
     AEGIS, dual-engine sentiment. Color #10b981 (emerald) sets the
     accent palette used consistently throughout.
     ============================================================ -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1000&color=10B981&center=true&vCenter=true&width=650&lines=Applied+AI+%2F+LLM+Systems+Engineer;RAG+%2B+Multi-agent+DAGs+%2B+QLoRA+fine-tuning;Building+evaluation-first+ML%2C+not+demo-first;Clinical+AI+%E2%80%A2+Recruiting+AI+%E2%80%A2+Computer+Vision;Chennai+%E2%80%A2+always+shipping" />
</p>

<p align="center">
  <a href="https://github.com/Pranshu0204">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://twitter.com/Pranshu45581230">
    <img src="https://img.shields.io/badge/Twitter%2FX-1DA1F2?style=for-the-badge&logo=Twitter&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=Pranshu0204&style=for-the-badge&color=10b981&label=PROFILE+VIEWS" />
</p>

---

<!-- ============================================================
     ABOUT ME BLOCK
     Design decision: Each bullet is grounded in a SHIPPED project.
     No "I'm passionate about AI" — instead, "I built an X that does Y".
     The last line frames his philosophy, which differentiates him
     from every other ML resume.
     ============================================================ -->

## 🧠 About Me

- 🤖 I build **production-grade LLM systems** — RAG fusion pipelines, multi-agent DAGs (LangGraph), and local-first QLoRA fine-tuning with auto device detection (CUDA / MPS / CPU)
- 🏥 I work on **clinician-supervised clinical AI** — multimodal triage agents on Gemini Live API with structured JSON outputs across 9 languages
- 📊 I'm **evaluation-obsessed** — every system I ship has a `/benchmark` endpoint, JSON-parse rates, MAE per dimension, or tier-accuracy reports
- 🛡️ I architect for **responsible AI** — decoupling bias detection from scoring, separating observation from influence, designing for auditability
- 🛣️ My foundations are in **classical CV** — OpenCV + Hough transforms, real-time stream processing with confidence scoring
- 📍 Based in Darmstadt 🇩🇪 — currently exploring research collaborations in healthcare AI and applied ML

---

<!-- ============================================================
     TECH STACK BLOCK
     Design decision: Reorganized around what he ACTUALLY ships now.
     LLM tooling first (LangGraph, Qdrant, HuggingFace, Gemini),
     then ML foundations, then web/infra. No aspirational padding.
     ============================================================ -->

## ⚡ Tech Stack

**LLM & Agents**

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenRouter-000000?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/PEFT%2FQLoRA-FF6F00?style=for-the-badge" />
</p>

**RAG & Data**

<p>
  <img src="https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/BGE--large-10b981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
</p>

**ML / CV / NLP**

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,sklearn" />
  <img src="https://img.shields.io/badge/NLTK-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TextBlob-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

**Backend & Web**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,flask,react,typescript,vite,tailwind" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
</p>

**Languages & Infra**

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,javascript,docker,git,github,linux,vscode" />
</p>

---

<!-- ============================================================
     FEATURED PROJECTS BLOCK
     Design decision: 4 projects in a 2-column table — RecruitSense
     and AEGIS are the headline acts, then sentiment + lane detection
     show range (CV, NLP, evaluation). Each card emphasizes the
     SYSTEMS DESIGN DECISION that makes it interesting, not a generic
     "what it does" blurb.
     ============================================================ -->

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎯 <a href="https://github.com/Pranshu0204">RecruitSense</a></h3>
      <p><b>LLM-powered resume screener with RAG, multi-agent DAG, bias decoupling, and local QLoRA fine-tuning.</b></p>
      <p>5-dimension weighted scoring · RAG Fusion (Qdrant + BGE-large) with Reciprocal Rank Fusion · LangGraph DAG running RAG ∥ bias in parallel · deterministic composite math · QLoRA pipeline auto-detecting CUDA/MPS/CPU.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
        <img src="https://img.shields.io/badge/Qdrant-DC382D?style=flat-square&logo=qdrant&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/QLoRA-FF6F00?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏥 <a href="https://github.com/Pranshu0204/Aegis">AEGIS — Clinical AI Assistant</a></h3>
      <p><b>Clinician-supervised, non-diagnostic multimodal AI for overloaded clinics. Voice + docs + text, 9 languages, 6 modules.</b></p>
      <p>Built on Gemini 2.0 + Live API · structured JSON triage with severity-coded UI · role-aware prompts (Clinician / Patient / Caregiver) · WebSocket live voice via LiveClient · graceful Markdown fallback when JSON parsing fails.</p>
      <p>
        <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/Pranshu0204/Twitter-Sentiment-Analysis-using-tweepy">Dual-Engine Sentiment Analysis</a></h3>
      <p><b>TextBlob lexicon vs Gemini 2.0 Flash — side-by-side with a benchmarking endpoint.</b></p>
      <p>Two engines on the same input · agreement flag + polarity delta · <code>/benchmark</code> reports per-method accuracy and per-sample correctness · graceful LLM fallback on quota exhaustion. Designed as a mini eval framework, not just a classifier.</p>
      <p>
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/TextBlob-3776AB?style=flat-square" />
        <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🛣️ <a href="https://github.com/Pranshu0204/Road-Lane-Detection-System">Road Lane Detection System</a></h3>
      <p><b>Real-time CV pipeline with structured per-frame stream logging and confidence scoring.</b></p>
      <p>OpenCV + Canny + Hough transform · per-frame JSON records (status, confidence, fps) · DETECTED / PARTIAL / NO_LANES tiers · summary metrics on exit · annotated video output. Treats CV like a streaming data system, not a script.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
        <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<details>
  <summary><b>🔬 More projects — research & experiments</b></summary>
  <br/>
  <ul>
    <li><a href="https://github.com/Pranshu0204/Beyond-the-Siren-Evaluation-of-Equitable-Emergency-Care-in-Low-and-Middle-Income-Countries"><b>Beyond the Siren</b></a> — Evaluation framework for equitable emergency care in low- and middle-income countries</li>
    <li><a href="https://github.com/Pranshu0204/MLJAK2-Biotech-"><b>MLJAK2-Biotech</b></a> — ML applied to biotech / JAK2 research workflows</li>
    <li><b>Company Culture Analysis</b> — NLP-driven culture analysis from employee reviews using sentiment scoring, tokenization, and word-frequency visualization</li>
    <li><a href="https://github.com/Pranshu0204/Maxwell-s-Right-Hand-thumb-Rule-using-Augmented-Reality"><b>Maxwell's Rule in AR</b></a> — WebXR experience visualizing electromagnetic theory ⭐</li>
  </ul>
</details>

---

<!-- ============================================================
     GITHUB STATS BLOCK
     Design decision: tokyonight theme matches the dark + emerald
     palette established in the hero. Side-by-side stats + streak
     gives a clean two-pane look. Activity graph adds temporal depth.
     ============================================================ -->

## 📊 GitHub Stats

<p align="center">
  <table>
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=Pranshu0204&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
      </td>
      <td>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Pranshu0204&theme=tokyonight&hide_border=true" />
      </td>
    </tr>
  </table>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pranshu0204&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Pranshu0204&theme=tokyonight&no-frame=true&column=6&margin-w=10" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pranshu0204&theme=tokyo-night&hide_border=true&area=true" />
</p>

---

<!-- ============================================================
     CONNECT BLOCK
     Design decision: CTA names exactly the kind of work he wants —
     LLM systems, healthcare AI, applied ML research. Specific asks
     get specific replies; generic asks get nothing.
     ============================================================ -->

## 🤝 Let's Connect

<p align="center">
  <a href="https://github.com/Pranshu0204">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://twitter.com/Pranshu45581230">
    <img src="https://img.shields.io/badge/Twitter%2FX-1DA1F2?style=for-the-badge&logo=Twitter&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Open to collaborations and roles in <b>LLM systems engineering</b>, <b>applied ML research</b>, and <b>responsible healthcare AI</b>.<br/>If you're shipping evaluation-first ML or building agentic systems with care for safety and bias — let's talk.</i>
</p>

<!-- ============================================================
     FOOTER WAVE
     Design decision: Matching close keeps the page framed.
     Same gradient as the header, lighter height for balance.
     ============================================================ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,24,30&height=120&section=footer" />
</p>
