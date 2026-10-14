<h1 align="center">Hi, I'm Vaibhav 👋</h1>

<p align="center">
  <b>Computer Engineering @ NTU Singapore</b> · I build systems from first principles, then put them to work on real problems.
</p>

<p align="center">
  <a href="https://vaibenz.github.io"><img src="https://img.shields.io/badge/Portfolio-vaibenz.github.io-0C8A68?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/vaibhav-peddakadapa-064666216/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:vaibhavpk718@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### About me

- 🎓 B.Eng (Hons) Computer Engineering with a Minor in Business at **Nanyang Technological University**, class of 2029
- 💼 Previously **Full Stack Developer Intern at Tata Consultancy Services**, building Java/Spring Boot and React for the Singapore Airlines Offshore Delivery Centre in Chennai. First TCS Singapore intern to complete an overseas placement under the Global Ready Talent Programme
- 🏅 NTU-Google Career Certificate Scholar · AWS AI & ML Scholar
- 🤝 Mentee in the SC x NTU LevelUP! programme, mentored by Trust Bank Singapore's Executive Director of Technology Operations
- 🌏 Most excited by distributed systems, applied ML, and fintech for underserved businesses in Southeast Asia

---

### 🔧 Systems, built from scratch

| | |
|---|---|
| **[cserve](https://github.com/vaibenz/cserve)** · `C` `epoll` `Linux`<br>Event driven HTTP/1.1 server with edge triggered epoll, one reactor per thread and zero copy `sendfile`.<br>⚡ **~139k req/s** on a 2 vCPU VM, **1.87x** scaling from one worker to two | **[raft-kv](https://github.com/vaibenz/raft-kv)** · `Java 21` `Raft`<br>Fault tolerant replicated key value store on a from scratch Raft (PreVote, pipelined replication, fast backtracking), zero dependencies.<br>🛡️ Linearizable under crashes and partitions, checked by randomized fault injection · **7.6x** throughput from group commit |
| **[search-engine](https://github.com/vaibenz/search-engine)** · `Python` `IR`<br>Polite concurrent crawler, BM25 inverted index, PageRank and hybrid semantic search with a web UI.<br>📈 **+7% MAP**, **+4% nDCG@10** over BM25 on Cranfield, median query **< 2 ms** | |

### 🤖 Applied AI and ML

| | |
|---|---|
| **[agentdesk](https://github.com/vaibenz/agentdesk)** · `Google ADK` `Gemini` `Cloud Run`<br>Multi agent support desk: a router delegates to knowledge, ticketing and escalation agents sharing session state.<br>🔭 OpenTelemetry span on every agent step, cost and tokens/s per request streamed to BigQuery | **[docbridge](https://github.com/vaibenz/docbridge)** · `LangGraph` `pgvector` `Gemini`<br>Enterprise RAG over PDFs and tables with access control enforced inside the SQL query.<br>🔁 Corrective RAG loop that grades, rewrites and declines rather than guessing · zero access leaks by test |
| **[content-recsys](https://github.com/vaibenz/content-recsys)** · `PyTorch` `LightGBM`<br>Two stage news recommender on Microsoft's MIND click logs: two tower retrieval, LambdaRank ranking, quality aware re-rank.<br>🧪 Cold start breakdowns and a bootstrapped A/B harness | **[content-quality-classifier](https://github.com/vaibenz/content-quality-classifier)** · `scikit-learn` `PyTorch`<br>Clickbait detector feeding the recommender. Found and removed a casing shortcut that faked F1 0.995.<br>🎯 **F1 0.986**, ROC AUC **0.998** on 3,200 held out headlines |

### 💸 Fintech for small businesses

Built as extensions of my NTU PEAK consulting case with **Monee** on financing for rural Indonesian MSMEs (a ~US$235B gap).

| | |
|---|---|
| **[sme-credit-risk-model](https://github.com/vaibenz/sme-credit-risk-model)** · `LightGBM` `scikit-learn`<br>Credit scoring and risk based pricing on **307,511** real loan applications, with a cut-off simulator.<br>📊 Calibrated LightGBM **AUC 0.771**, Gini 0.542 on an untouched test set | **[temanusaha-bookkeeping-app](https://github.com/vaibenz/temanusaha-bookkeeping-app)** · `React` `Vite`<br>Mobile bookkeeping and financing readiness app for warung owners.<br>📱 **[Live demo](https://vaibenz.github.io/temanusaha-bookkeeping-app/)** with a sample warung |
| **[suarausaha](https://github.com/vaibenz/suarausaha)** · `Gemini` `FastAPI` `React`<br>Voice first bookkeeping in everyday Bahasa Indonesia via Gemini function calling, with an offline parser fallback.<br>♿ Designed to WCAG 2.1 AA for low literacy and low vision users | |

---

### 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

---

<p align="center"><i>Open to internships in software engineering, AI and fintech. Always happy to talk systems.</i></p>
