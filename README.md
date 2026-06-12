<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=0,20,25&height=240&section=header&text=Pranshu%20Gupta&fontSize=62&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Applied+AI+Engineer+%C2%B7+LLM+Systems+%C2%B7+Evaluation-First&descSize=14&descAlignY=56&descColor=10b981" alt="banner" />
</p>

<p align="center">
  <a href="https://github.com/Pranshu0204">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&pause=1200&color=10B981&center=true&vCenter=true&width=700&repeat=true&lines=StyleShift+%C2%B7+intrinsic+multi-author+style+change+detection;RecruitSense+%C2%B7+RAG+fusion+%2B+LangGraph+DAG+%2B+QLoRA+fine-tuning;AEGIS+%C2%B7+clinician-supervised+multimodal+AI%2C+9+languages;Evaluation-first%3A+F1+%2B+AUC-PR+%2B+Brier%2C+never+raw+accuracy;Darmstadt+%E2%86%92+wherever+the+next+hard+problem+is" alt="typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Pranshu0204"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  &nbsp;
  <a href="https://twitter.com/"><img src="https://img.shields.io/badge/Twitter%2FX-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter/X" /></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=Pranshu0204&style=for-the-badge&color=10b981&label=PROFILE+VIEWS" alt="profile views" />
</p>

<br/>

<h3 align="left">// whoami</h3>

<p align="left">
<table>
  <tr><td>🎓</td><td>MSc Computer Science · TU Darmstadt · LLMs, CV, PGMs, Quantum Computing, Scalable Data Management</td></tr>
  <tr><td>📍</td><td>Darmstadt, DE 🇩🇪 — by way of Chennai, IN</td></tr>
  <tr><td>🌙</td><td>Architecture decisions happen on late-night walks. The whiteboard comes later.</td></tr>
  <tr><td>🎮</td><td>Call of Duty Mobile between training runs</td></tr>
  <tr><td>📖</td><td>Reads documentation the way other people read fiction. Unironically.</td></tr>
  <tr><td>🤝</td><td>Open to: healthcare-AI research collabs, applied ML roles, LLM systems engineering</td></tr>
  <tr><td>🧭</td><td>Currently circling: evaluation frameworks, responsible AI design, multi-agent orchestration, fine-tuning pipelines</td></tr>
  <tr><td>⚡</td><td><i>"If it has no eval loop, it's just a demo."</i></td></tr>
</table>
</p>

<br/>

<h3 align="left">// featured projects</h3>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔬 StyleShift <img src="https://img.shields.io/badge/NEW-10b981?style=flat-square" alt="NEW" /> ⭐</h3>
      <b>Intrinsic multi-author style change detection</b> — no reference texts, no author profiles, pure internal comparison, framed as pairwise binary classification.
      <br/><br/>
      Dual-stream ensemble: 163-dim stylometric difference vectors → SVM, plus a Siamese Transformer over frozen <code>all-mpnet-base-v2</code>, fused by an LR meta-learner trained strictly on the validation split — leakage kept out by construction. Three difficulty tiers (Easy/Medium/Hard by topic diversity) double as a built-in ablation axis; the Hard tier shows exactly where pure stylometry hits its ceiling once topic is controlled — consistent with published PAN SOTA.
      <br/><br/>
      <code>Ensemble Macro F1 = 0.606</code> · <code>AUC-PR = 0.404</code> · <code>PAN @ CLEF 2025</code>
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
      <img src="https://img.shields.io/badge/sentence--transformers-10b981?style=flat-square" alt="sentence-transformers" />
      <br/><br/>
      <a href="https://github.com/Pranshu0204/StyleShift">→ repo</a>
    </td>
    <td width="50%" valign="top">
      <h3>🧭 RecruitSense</h3>
      <b>Agentic resume intelligence</b> — bias detection runs in a parallel LangGraph branch, decoupled from scoring by design, not as an afterthought.
      <br/><br/>
      RAG Fusion with Reciprocal Rank Fusion over Qdrant, parallel DAG orchestration, and QLoRA fine-tuning with automatic device detection (CUDA/MPS/CPU). Retrieval and judgment are separate concerns, wired that way on purpose.
      <br/><br/>
      <code>RRF fusion</code> · <code>parallel DAG</code> · <code>QLoRA</code>
      <br/><br/>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
      <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/PEFT%2FQLoRA-3b82f6?style=flat-square" alt="PEFT/QLoRA" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🩺 AEGIS — Clinical AI Assistant</h3>
      <b>Non-diagnostic by design</b> — structured JSON triage with graceful Markdown fallback when parsing fails, because clinical systems can't crash silently.
      <br/><br/>
      Clinician-supervised multimodal assistant: image + text intake, severity triage, and localization across 9 languages, streamed over WebSockets.
      <br/><br/>
      <code>9 languages</code> · <code>graceful-degradation parser</code>
      <br/><br/>
      <img src="https://img.shields.io/badge/Gemini%202.0-3b82f6?style=flat-square" alt="Gemini 2.0" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/WebSocket-10b981?style=flat-square" alt="WebSocket" />
    </td>
    <td width="50%" valign="top">
      <h3>⚖️ Dual-Engine Sentiment Analysis</h3>
      <b>Built as a mini eval framework</b> — same input, two engines, one <code>/benchmark</code> endpoint reporting per-method accuracy and per-sample agreement.
      <br/><br/>
      LLM-based and lexicon-based sentiment side by side, so disagreement is a first-class signal instead of noise you average away.
      <br/><br/>
      <code>/benchmark endpoint</code> · <code>per-sample agreement</code>
      <br/><br/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
      <img src="https://img.shields.io/badge/Gemini-3b82f6?style=flat-square" alt="Gemini" />
      <img src="https://img.shields.io/badge/TextBlob-10b981?style=flat-square" alt="TextBlob" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛣️ Road Lane Detection System</h3>
      <b>Treats CV as a streaming data system</b> — per-frame JSON records with <code>DETECTED / PARTIAL / NO_LANES</code> tier classification and summary metrics on exit.
      <br/><br/>
      Classical pipeline (Canny + Hough + ROI masking) instrumented like a production service, not a notebook demo.
      <br/><br/>
      <code>per-frame JSON telemetry</code>
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
    </td>
    <td width="50%" valign="top">
      <h3>🧪 Research & Experiments</h3>
      <b>Beyond the Siren</b> — emergency-response analysis work; the depth indicator, not the headline.
      <br/><br/>
      <b>Maxwell's Rule in AR</b> — physics visualization in augmented reality, because some intuitions need to be walked around, not read about.
      <br/><br/>
      <code>research</code> · <code>AR / physics</code>
      <br/><br/>
      <img src="https://img.shields.io/badge/Research-10b981?style=flat-square" alt="Research" />
      <img src="https://img.shields.io/badge/AR-3b82f6?style=flat-square" alt="AR" />
    </td>
  </tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>
<ul>
  <li><b>MLJAK2-Biotech</b> — ML pipeline for JAK2 mutation analysis in biotech workflows.</li>
  <li><b>Company Culture Analysis</b> — NLP over employee-review corpora to surface culture signals beyond star ratings.</li>
</ul>
</details>

<br/>

<h3 align="left">// tech stack</h3>

<b>⚡ Current Focus</b>
<p>
  <img src="https://img.shields.io/badge/active-StyleShift%20%7C%20PAN%202025-10b981?style=flat-square&labelColor=0d1117" alt="StyleShift" />
  <img src="https://img.shields.io/badge/active-QLoRA%20Fine--Tuning%20Pipelines-10b981?style=flat-square&labelColor=0d1117" alt="QLoRA" />
  <img src="https://img.shields.io/badge/active-Evaluation%20Framework%20Design-10b981?style=flat-square&labelColor=0d1117" alt="Eval frameworks" />
</p>

<b>LLM & Agents</b>
<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Gemini-3b82f6?style=flat-square" alt="Gemini" />
  <img src="https://img.shields.io/badge/PEFT%2FQLoRA-3b82f6?style=flat-square" alt="PEFT/QLoRA" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
</p>

<b>RAG & Data</b>
<p>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant" />
  <img src="https://img.shields.io/badge/BGE--large-10b981?style=flat-square" alt="BGE-large" />
  <img src="https://img.shields.io/badge/sentence--transformers-10b981?style=flat-square" alt="sentence-transformers" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
</p>

<b>ML · CV · NLP</b>
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="spaCy" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
</p>

<b>Backend & Web</b>
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/WebSocket-10b981?style=flat-square" alt="WebSocket" />
</p>

<b>Languages & Infra</b>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-10b981?style=flat-square" alt="SQL" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
</p>

<br/>

<h3 align="left">// github stats</h3>

<table align="center">
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Pranshu0204&show_icons=true&hide_border=true&bg_color=0d1117&title_color=10b981&icon_color=10b981&text_color=e5e7eb&ring_color=10b981&count_private=true&include_all_commits=true" alt="GitHub stats" />
    </td>
    <td>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=Pranshu0204&hide_border=true&background=0d1117&ring=10b981&fire=10b981&currStreakLabel=10b981&sideLabels=6b7280&dates=6b7280" alt="streak stats" />
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pranshu0204&layout=compact&bg_color=0d1117&title_color=10b981&text_color=e5e7eb&hide_border=true" alt="top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pranshu0204&theme=tokyo-night&hide_border=true&area=true" alt="activity graph" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Pranshu0204&theme=tokyonight&no-frame=true&column=6&margin-w=10" alt="trophies" />
</p>

<br/>

<h3 align="left">// connect</h3>

<p align="left">
If you're building something where evaluation rigor matters — healthcare AI, LLM systems, agentic pipelines — my inbox is open. I'd rather see your failure cases than your demo video.
<br/><br/>
Currently benchmarking on PAN @ CLEF 2025 — if you're working on authorship analysis, forensic NLP, or style-based evaluation, I want to hear from you.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=0,20,25&height=100&section=footer" alt="footer" />
</p>
