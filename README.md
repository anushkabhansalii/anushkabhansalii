<div align="center">
  <img src="assets/hero.svg" width="100%" alt="Anushka Jain - Full Stack & AI/ML Engineer" />
</div>

<br />

---

## `$ whoami`

CS undergrad at **BITS Pilani** (CGPA 9.22) based in Bangalore. I build things end-to-end - from parsing pipelines and vector databases to product UIs and APIs. My focus is full-stack engineering with a strong pull towards AI systems: RAG pipelines, LLM evaluation, and production-grade ML infrastructure.

Not here to build demos. Here to ship.

<br />

---

## `$ cat stack.json`

<table align="center" width="100%">
  <tr>
    <td align="center" valign="top" width="20%">
      <br />
      <img src="https://img.shields.io/badge/-Python-05070C?style=flat-square&logo=python&logoColor=3776AB" />&nbsp;
      <img src="https://img.shields.io/badge/-JavaScript-05070C?style=flat-square&logo=javascript&logoColor=F7DF1E" />&nbsp;
      <img src="https://img.shields.io/badge/-TypeScript-05070C?style=flat-square&logo=typescript&logoColor=3178C6" />&nbsp;
      <img src="https://img.shields.io/badge/-Java-05070C?style=flat-square&logo=openjdk&logoColor=ED8B00" />&nbsp;
      <img src="https://img.shields.io/badge/-C++-05070C?style=flat-square&logo=cplusplus&logoColor=00599C" />&nbsp;
      <img src="https://img.shields.io/badge/-SQL-05070C?style=flat-square&logo=postgresql&logoColor=4169E1" />
      <br /><sub><b>LANGUAGES</b></sub><br /><br />
    </td>
    <td align="center" valign="top" width="20%">
      <br />
      <img src="https://img.shields.io/badge/-React-05070C?style=flat-square&logo=react&logoColor=61DAFB" />&nbsp;
      <img src="https://img.shields.io/badge/-Next.js-05070C?style=flat-square&logo=nextdotjs&logoColor=ffffff" />&nbsp;
      <img src="https://img.shields.io/badge/-Node.js-05070C?style=flat-square&logo=nodedotjs&logoColor=5FA04E" />&nbsp;
      <img src="https://img.shields.io/badge/-Express-05070C?style=flat-square&logo=express&logoColor=ffffff" />&nbsp;
      <img src="https://img.shields.io/badge/-FastAPI-05070C?style=flat-square&logo=fastapi&logoColor=009688" />&nbsp;
      <img src="https://img.shields.io/badge/-Streamlit-05070C?style=flat-square&logo=streamlit&logoColor=FF4B4B" />
      <br /><sub><b>MERN + FRAMEWORKS</b></sub><br /><br />
    </td>
    <td align="center" valign="top" width="20%">
      <br />
      <img src="https://img.shields.io/badge/-PostgreSQL-05070C?style=flat-square&logo=postgresql&logoColor=4169E1" />&nbsp;
      <img src="https://img.shields.io/badge/-MongoDB-05070C?style=flat-square&logo=mongodb&logoColor=47A248" />&nbsp;
      <img src="https://img.shields.io/badge/-pgvector-05070C?style=flat-square&logo=postgresql&logoColor=A78BFA" />&nbsp;
      <img src="https://img.shields.io/badge/-Milvus-05070C?style=flat-square&logo=milvus&logoColor=00A1EA" />&nbsp;
      <img src="https://img.shields.io/badge/-Docker-05070C?style=flat-square&logo=docker&logoColor=2496ED" />&nbsp;
      <img src="https://img.shields.io/badge/-GCP-05070C?style=flat-square&logo=googlecloud&logoColor=4285F4" />
      <br /><sub><b>INFRA & DATABASES</b></sub><br /><br />
    </td>
    <td align="center" valign="top" width="25%">
      <br />
      <img src="https://img.shields.io/badge/-PyTorch-05070C?style=flat-square&logo=pytorch&logoColor=EE4C2C" />
      <img src="https://img.shields.io/badge/-scikit--learn-05070C?style=flat-square&logo=scikitlearn&logoColor=F7931E" />
      <img src="https://img.shields.io/badge/-Groq-05070C?style=flat-square&logo=groq&logoColor=ffffff" />
      <img src="https://img.shields.io/badge/-Gemini-05070C?style=flat-square&logo=google&logoColor=4285F4" />
      <img src="https://img.shields.io/badge/-OpenAI-05070C?style=flat-square&logo=openai&logoColor=ffffff" />
      <img src="https://img.shields.io/badge/-Figma-05070C?style=flat-square&logo=figma&logoColor=F24E1E" />
      <br /><sub><b>AI / ML & DESIGN</b></sub><br /><br />
    </td>
  </tr>
</table>

<br />

---

## `$ ls -la ./projects`

### ⬡ Gradonix - LLM Exam Evaluation Engine

OCR plus LLM-based answer scoring pipeline built from scratch. Achieved 94.3% agreement with human evaluators across 300+ answer sheets - 60% faster than manual grading. Designed full product UX in Figma, ran usability testing with 20+ educators, drove outreach to 200+ registrations.

<div align="center">
  <img src="assets/gradonix.svg" width="100%" alt="Gradonix - Answer Sheet to OCR to LLM Judge to Score Report" />
</div>

**Pipeline:** Answer Sheet Scan → OCR + PDF Parse → LLM Judge Matrix → Grade Report

**Stack:** Python · OCR · LLM APIs · Figma · FastAPI

[![Live](https://img.shields.io/badge/LIVE-gradonix.com-7C3AED?style=flat-square&logo=vercel&logoColor=white)](https://gradonix.com/)

---

### ⬡ Recruitify - AI Recruitment Platform

Built the PDF parsing and async batch resume upload pipeline for a 5-person team. Semantic candidate ranking via pgvector embeddings. Integrated LLM-based bias detection in job descriptions. Caught and rolled back unauthorized file changes introduced by an AI coding agent mid-sprint.

<div align="center">
  <img src="assets/recruitify.svg" width="100%" alt="Recruitify - Resume Upload to Embed and Rank to Bias Detection to Interview Schedule" />
</div>

**Pipeline:** Resume Upload → OCR/Parse → Embed → Rank → Bias Flag → Interview Scheduling

**Stack:** FastAPI · PostgreSQL (pgvector) · Next.js · Google Gemini · pdfplumber

[![Live](https://img.shields.io/badge/LIVE-recruitify.vercel.app-84CC16?style=flat-square&logo=vercel&logoColor=black)](https://recruitify-mu-rosy.vercel.app/)

---

### ⬡ DocuMind - NotebookLM Clone with RAG + Voice

Document-grounded AI assistant that grounds every answer in your source material with accurate citations. Supports PDF, audio, YouTube, web pages, and text. Migrated the full stack from OpenAI to open-source alternatives (Groq Llama 3.3 70B + BAAI Embeddings + Milvus Lite) with zero performance loss. Multi-session memory via Zep temporal knowledge graphs. Includes AI podcast generation with multi-speaker TTS. Runs at zero API cost.

<div align="center">
  <img src="assets/documind.svg" width="100%" alt="DocuMind - NotebookLM Clone with RAG and Voice" />
</div>

**Stack:** Groq (Llama 3.3 70B) · BAAI Embeddings · Milvus Lite · Zep Cloud · Streamlit

`ZERO API COST` &nbsp; `RAG + VOICE + AUDIO`

<br />

---

## `$ git log --stat`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=anushkabhansalii&show_icons=true&theme=transparent&hide_border=true&title_color=A78BFA&icon_color=84CC16&text_color=C4B5FD&bg_color=050810" width="48%" alt="GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=anushkabhansalii&theme=transparent&hide_border=true&ring=7C3AED&fire=84CC16&currStreakLabel=A78BFA&sideLabels=C4B5FD&dates=4B5563&stroke=1E1E35&background=050810" width="48%" alt="GitHub Streak" />
</div>

<br />

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anushkabhansalii&layout=compact&theme=transparent&hide_border=true&title_color=A78BFA&text_color=C4B5FD&bg_color=050810" width="40%" alt="Top Languages" />
</div>

<br />

---

## `$ ping anushka.build`

| Interface | Endpoint | Status |
| :--- | :--- | :--- |
| 🌐 **Portfolio** | [anushka.build](#) *(coming soon)* | `BUILDING` |
| 💼 **LinkedIn** | [linkedin.com/in/anushka-jainn](https://linkedin.com/in/anushka-jainn) | `ACTIVE` |
| 💻 **GitHub** | [github.com/anushkabhansalii](https://github.com/anushkabhansalii) | `ACTIVE` |
| 📧 **Email** | anushkaj460@gmail.com | `OPEN` |

<br />

---

> `[LOG]` *"I don't build to learn. I learn because I have to ship."*

<div align="center">
  <sub>BITS PILANI · FULL STACK · AI/ML · BANGALORE // STATUS: BUILDING</sub>
</div>
