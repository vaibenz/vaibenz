<h1 align="center">Hi, I'm Vaibhav 👋</h1>

<p align="center">
  <b>Computer Engineering @ NTU Singapore</b> · I like building software from the socket up: servers, consensus, search, and the backends that run on them.
</p>

<p align="center">
  <a href="https://vaibenz.github.io"><img src="https://img.shields.io/badge/Portfolio-vaibenz.github.io-0C8A68?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/vaibhav-peddakadapa-064666216/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:vaibhavpk718@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### About me

- 🎓 B.Eng (Hons) Computer Engineering with a Minor in Business at **Nanyang Technological University**, class of 2029
- 💼 Previously **Full Stack Developer Intern at Tata Consultancy Services**, shipping Java/Spring Boot services and React frontends for the Singapore Airlines Offshore Delivery Centre in Chennai
- 🏅 NTU-Google Career Certificate Scholar
- 🔭 Most interested in backend systems, distributed systems and performance work

---

### 🔧 Systems, built from scratch

| | |
|---|---|
| **[cserve](https://github.com/vaibenz/cserve)** · `C` `epoll` `Linux`<br>Event driven HTTP/1.1 server with edge triggered epoll, one reactor per thread and zero copy `sendfile`.<br>⚡ **~139k req/s** on a 2 vCPU VM, **1.87x** scaling from one worker to two | **[raft-kv](https://github.com/vaibenz/raft-kv)** · `Java 21` `Raft`<br>Replicated key value store on a from scratch Raft (PreVote, pipelined replication, fast backtracking), zero dependencies.<br>🛡️ Linearizable under crashes and partitions, checked by randomized fault injection · **7.6x** throughput from group commit |
| **[search-engine](https://github.com/vaibenz/search-engine)** · `Python` `IR`<br>Polite concurrent crawler, BM25 inverted index, PageRank and hybrid semantic search, with a web UI and JSON API.<br>📈 **+7% MAP**, **+4% nDCG@10** over BM25 on Cranfield, median query **< 2 ms** | |

### 🧱 Backend and full stack

| | |
|---|---|
| **[reconpilot](https://github.com/vaibenz/reconpilot)** · `Kotlin` `Ktor` `React` `TypeScript`<br>Payment reconciliation where an LLM proposes matches, deterministic checks verify them, and a human approves in a review queue.<br>🔒 Model can never invent an invoice or overpay: every proposal passes currency, amount, date, reference and counterparty checks | **[docbridge](https://github.com/vaibenz/docbridge)** · `PostgreSQL` `pgvector` `LangGraph`<br>Question answering service over PDFs and tables with access control enforced inside the SQL query.<br>🔁 Incremental re ingestion by content hash · zero access leaks, asserted in tests |
| **[agentdesk](https://github.com/vaibenz/agentdesk)** · `FastAPI` `Cloud Run` `OpenTelemetry`<br>Multi agent support desk on Google ADK with shared session state across agents.<br>🔭 A trace span on every step, cost and latency per request streamed to BigQuery | **[suarausaha](https://github.com/vaibenz/suarausaha)** · `FastAPI` `React` `SQLite`<br>Voice first bookkeeping for Indonesian micro businesses. The backend validates and executes every model call itself.<br>♿ WCAG 2.1 AA frontend with axe-core tests · offline parser fallback |

**Also built:** [sme-credit-risk-model](https://github.com/vaibenz/sme-credit-risk-model) (credit scoring on 307k loan applications, AUC 0.771) · [temanusaha-bookkeeping-app](https://github.com/vaibenz/temanusaha-bookkeeping-app) ([live demo](https://vaibenz.github.io/temanusaha-bookkeeping-app/)) · [content-quality-classifier](https://github.com/vaibenz/content-quality-classifier) (clickbait detection, F1 0.986)

---

### 🛠️ Toolbox

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <br/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

---

<p align="center"><i>Looking for software engineering internships. Always happy to talk systems.</i></p>
