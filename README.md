<p align="center">
  <img src="https://i.pinimg.com/736x/3a/8c/d2/3a8cd224614801bd1513ca759a185403.jpg" alt="Banner" width="100%" />
</p>

<h1 align="center">Hi 👋, I'm Akshar Maitray</h1>
<h3 align="center">AI/ML Engineer building autonomous agents & full-stack systems — currently researching ML security</h3>

- I'm currently building **AgentPe** — an agentic commerce layer that lets AI shopping agents transact on Razorpay end-to-end

- I co-authored a research paper on **backdoor security in text classifiers**, evaluating attack sample-efficiency and survival through knowledge distillation

- Fine-tuned **TinyLlama-1.1B on the NCERT dataset with QLoRA** to build SHIKSHA AI, an academic mentor bot (84% answer accuracy) — Top 15 Finalist at Hacknite'25 (MAHE)

- I'm currently learning **LangGraph, Go, and 3D/Digital-Twin development (Three.js + Blender)**

- I'm looking for help with **ML algorithms to automate games like Subway Surfers, etc.**

- Ask me about **Python, ML/Agentic AI, or Anime**

- How to reach me: **aksharmaitray74@gmail.com**

<br/>

## Research

<table>
<tr>
<td width="100%">

**Confidence-Driven Backdoor Poisoning in Text Classification: Sample Efficiency, Knowledge-Distillation Survival, and Defense Evasion Across Four Datasets**

*Amith Pradhaan, **Akshar Maitray**, Abhimanyu Dutta, Ashmi Patel*

A study extending confidence-driven boundary sampling (CBS) — a smarter way to pick which training examples to backdoor-poison — from image classifiers to text. Evaluated across SST-2, AG News, IMDB, and Yelp Polarity with BERT→DistilBERT distillation, finding that CBS is actually *less* sample-efficient on text than random poisoning, that backdoors partially survive distillation into a compressed model even when the student never sees a poisoned example, and that CBS's stealth advantage from the image domain doesn't generalize (and reverses on Yelp).

<a href="https://github.com/kannu74/cbs_on_text" target="_blank"><img src="https://img.shields.io/badge/Code%20%26%20Results-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>
</tr>
</table>

<br/>

## Featured Projects

<table>
<tr>
<td width="100%">

### AgentPe — Agentic Commerce Layer for Razorpay
`FastAPI` · `LangGraph` · `LiteLLM` · `Razorpay SDK` · `PostgreSQL/pgvector` · `React`

An agentic commerce layer exposing a 7-tool Agent Gateway that lets any external AI shopping agent browse a catalog, decide, and complete a real purchase end-to-end through Razorpay's Checkout — agent-to-agent commerce, no human in the loop. Ships with conversational checkout via LangGraph, a pgvector similarity-search upsell agent, a YAML-driven policy engine with a hash-chained audit trail, human-in-the-loop approval for large discounts/refunds, and a win-back campaign orchestrator — covered by 111 backend tests.

<a href="https://github.com/kannu74/agentpe" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://agentpe-two.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Live%20Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://youtu.be/4qxXEHAydpk" target="_blank"><img src="https://img.shields.io/badge/Watch%20Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>

</td>
</tr>

<tr>
<td width="100%">

### Notification Service
`FastAPI` · `PostgreSQL` · `Redis` · `SQLAlchemy` · `Docker`

A backend notification delivery service (Email/SMS/Push) with priority handling, retries, delivery tracking, idempotency, and rate limiting. Uses Redis sorted sets for an atomic priority queue and per-user rate limiting, a circuit breaker around provider calls, and exponential-backoff retries — containerized with Docker Compose and validated with 34 pytest tests.

<a href="https://github.com/kannu74/Notification" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>
</tr>

<tr>
<td width="100%">

### FloatChat (Orca AI)
`LangChain` · `Google Gemini` · `PostgreSQL` · `Flask` · `Plotly.js`

A conversational interface for exploring ARGO oceanographic datasets in natural language. A LangChain SQL Agent translates questions into optimized PostgreSQL queries, and the results render as dynamic Plotly.js visualizations generated automatically from the agent's selected parameters.

<a href="https://github.com/kannu74/SIH-FloatChat" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</td>
</tr>

<tr>
<td width="100%">

### SHIKSHA AI
`PyTorch` · `Hugging Face` · `QLoRA/PEFT` · `TinyLlama-1.1B`

A fine-tuned NCERT academic mentor built by QLoRA-tuning TinyLlama-1.1B on NCERT curriculum data, reaching 84% answer accuracy — **Top 15 Finalist, Hacknite'25 AI-ML Hackathon (MAHE)**.

</td>
</tr>
</table>

<br/>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/akshar-maitray-ab2203302/" target="blank"><img align="center" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="akshar-maitray" height="30" width="40" /></a>
<a href="https://aksharmaitray.vercel.app/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/googlechrome.svg" alt="portfolio" height="30" width="30" style="background:white;border-radius:4px;padding:2px;" /></a>
<a href="https://www.hackerrank.com/akshar_018" target="blank"><img align="center" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/hackerrank/hackerrank-original.svg" alt="akshar_018" height="30" width="40" /></a>

</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left" style="display: flex; flex-wrap: wrap; gap: 10px;"> 
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
  </a> 
  <a href="https://go.dev" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> 
  </a> 
  <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> 
  </a> 
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> 
  </a> 
  <a href="https://threejs.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/threejs/threejs-original-wordmark.svg" alt="threejs" width="40" height="40"/> 
  </a> 
  <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/> 
  </a> 
  <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="flask" width="40" height="40"/> 
  </a> 
  <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 
  </a> 
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> 
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> 
  </a> 
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> 
  </a> 
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> 
  </a> 
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> 
  </a> 
  <a href="https://redis.io" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> 
  </a> 
  <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original-wordmark.svg" alt="pytorch" width="40" height="40"/> 
  </a> 
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> 
  </a> 
  <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> 
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> 
  </a> 
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> 
    <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> 
  </a> 
</p>


</div>
