<div align="center">

# Anurag Pappula

*Recent graduate, IIT Kharagpur*

### Software Engineer · Open Source

<p>
<a href="https://www.linkedin.com/in/anuragp2622"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:anuragp2622@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Anuragp22"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

</div>

---

I build backend systems and developer tools in Go, TypeScript, and Python. Most of my recent work focuses on production-grade plumbing: observability, adversarial testing, prompt-injection defenses, and the atomic transactions that prevent half-broken state.

---

### Survived contact with production

- **[TraceScope](https://github.com/Anuragp22/TraceScope)**: Built because "LGTM" stopped being a code review strategy. Go CLI that walks a SCIP-derived call graph backwards from your PR's changed lines and points at the functions about to break.
- **[JobVoice](https://interview-assistant-nu.vercel.app/)**: Because "3 years of React" deserves verification. Real-time AI interview simulator with three voice agents grilling the candidate, in-session RAG cross-checking the CV against the job description, and prompt-injection guards for the ones who try.
- **[SynthFlow](https://synth-flow-ai.vercel.app/)**: For everyone who needs to be a music producer for 3 minutes. Text-to-music platform on GPU with Inngest-queued inference, per-user concurrency, and atomic credit refunds for when generation fails, which generation does.
- **[apache/airflow#67522](https://github.com/apache/airflow/pull/67522)**: Loading a 95 MB Neo4j driver to parse a DAG file is a choice. Open PR to Apache Airflow making the import lazy in the Neo4j provider so the scheduler stops paying for it during DAG parsing.

---

### Tech I work with

<p align="center">
<img src="https://skillicons.dev/icons?i=go,ts,py,nodejs,fastapi,react,nextjs,tailwind,postgres,mongodb,redis,docker,aws&theme=dark" alt="Tech stack"/>
</p>

---

### Activity

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Anuragp22&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&area_color=58a6ff" width="95%" alt="Contribution activity"/>
</p>

---

### Things I think about

I read code reviews the way I read chess positions, scanning for the move that quietly loses three moves later. The same habit shapes how I build. Tests should catch the failure mode you did not predict. Telemetry should answer the question you have not asked yet. The right abstraction is the one you do not regret in six months.

<div align="center">

<i>Mostly compiling, occasionally shipping.</i>

</div>
