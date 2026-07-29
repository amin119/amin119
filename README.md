<div align="center">

```
$ whoami
```

</div>

<h1 align="center">Ahmed Amin Chabbah</h1>
<p align="center"><i>I don't build agents. I build the systems that keep them honest.</i></p>

<div align="center">

`INSAT, Tunisia` · `Software Engineering` · `Agentic AI / Multi-Agent Systems`

</div>

<br>

```
[orchestrator] booting session...
[orchestrator] loading agents: reviewer, planner, retriever, infra
[orchestrator] status: 3 companies, 1 nervous system
[orchestrator] ready.
```

---

## trace / what actually happens when I work

```
> task received: "build something that doesn't fall over at 2am"
> routing to: backend-agent, ml-agent, infra-agent
> backend-agent    -> FastAPI, PostgreSQL/PostGIS, Redis, JWT/RS256
> ml-agent         -> PyTorch, TensorFlow, BERT, YOLOv8/v11, embeddings
> infra-agent      -> S3, real-time SSE, multi-tenant orchestration
> orchestrator     -> merges outputs, ships to production
> result: a system with real users, not a demo
```

I spend most of my time in the gap most engineers skip — the part between "the model works in a notebook" and "the system survives contact with real users." That gap is where multi-agent orchestration, retries, state, and cost control actually live. That's my job.

---

## artifacts recovered from production

**`argus/`** — a multi-tenant, stateless multi-agent platform built on the Claude API that automates PR security and quality review end to end: gateway, orchestration layer, S3-backed storage. Turned a days-long review cycle into minutes.
→ `github.com/amin119/argus`

**`sahali/`** — civic infrastructure reporting for Tunisian municipalities. FastAPI backend, PostGIS geo-routing, RS256 JWT auth, a real-time SSE dashboard that citizens and municipal staff actually use, live, right now.
→ `github.com/amin119/SAHALI`

**`tunisiradar/`** — a multi-country tourism price-comparison engine. Amadeus/RapidAPI ingestion normalized across PostgreSQL and MongoDB, Redis-driven discount alerts, XGBoost underneath.
→ `github.com/amin119/TunisiRadar`

**`gl3-ppp/`** — an HR matching engine that reads a CV the way a tired recruiter wishes they could: fine-tuned BERT semantic similarity, TF-IDF, NER. 84.3% matching accuracy, screening automated end to end.
→ `github.com/amin119/GL3-PPP`

---

## dependencies

```
runtime        Python · FastAPI · PostgreSQL · Redis
intelligence   Claude API · PyTorch · TensorFlow · scikit-learn
frontend       React · Vue.js · Flutter
scale          Apache Spark · Kafka · Docker
currently      RAG pipelines · embedding retrieval · agent evaluation
```

---

## background process

```
[nadas-group]     agentic AI product features, ongoing
[metis-digital]   backend engineering, France
[securinets]      president, INSAT chapter — national cybersecurity assoc.
[status]          open to AI/ML & agentic engineering internships
```

---

<div align="center">

*If you're building something that needs more than one agent to think straight —
that's a conversation I want to have.*

`ahmedamin.chabbah@insat.ucar.tn` · `linkedin.com/in/ahmed-amin-chabbah`

</div>