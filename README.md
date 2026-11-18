<h1 align="center">
  Hi, I'm Kushagra Pratap Singh
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6E40C9&center=true&vCenter=true&width=700&lines=Backend+%26+AI+Engineer;LLM+Agents+%7C+RAG+%7C+Evals;Microservices+%26+Real-time+Systems;Looking+for+Internships+%7C+Graduating+2027" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kushagra-pratap-singh/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://kushagra-pratap-singh.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-6E40C9?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/mWLZR3GFyh/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  <a href="https://www.geeksforgeeks.org/user/kushagra0526/" target="_blank">
    <img src="https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
  </a>
  <a href="mailto:rajputkushagra26@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About Me

I'm a final-year B.Tech student in Communication and Computer Engineering at **LNMIIT, Jaipur** (graduating 2027). I build backends and AI systems, and I care about the part that comes after the demo: tests, evals, and what happens when the input is messy.

- I build LLM agents with tool calling, memory, approval steps and evals, mostly in Python with LangGraph.
- I write backends in Node.js and Python: microservices, GraphQL gateways, Kafka, role-based access and CI/CD.
- I was an SDE intern at **Marine Edge Technologies**, where I built role-based access and Razorpay payments for a platform with 7,000+ users.
- I research multi-objective optimization with evolutionary algorithms under a professor, with a paper in mind.
- I have solved **450+ DSA problems** on LeetCode and GeeksforGeeks.

I'm currently looking for internships in backend and AI engineering. The best way to reach me is email or LinkedIn.

---

## Featured Projects

### [OpsPilot](https://github.com/kushagra0526/OpsPilot)

An agent for support and operations work. It reads orders, a stock feed and policy documents, builds a plan, checks the plan against a deterministic risk policy, stops for human approval on risky steps, and logs every action for audit. It re-plans when a step fails.

I tested it on 12 scenarios and 8 held-out cases that I wrote separately. The held-out set found three bugs in my own code, which I fixed.

`Python` `LangGraph` `Groq` `ChromaDB` `SQLite` `Streamlit`

---

### [LangGym](https://github.com/kushagra0526/GYM-AI-Customer-Voice-Agent)

A gym support assistant with four agents (triage, booking, credits, cancellation) that hand customers to each other through tool calls. A Pipecat voice interface runs the same graph with speech-to-text and text-to-speech. An eval harness scores routing, latency and hallucination, and every turn is traced in LangSmith.

`Python` `LangGraph` `Pipecat` `FastAPI` `Claude` `LangSmith`

---

### [PaperQA](https://github.com/kushagra0526/PaperQA)

Upload a research paper and ask it a question. Every answer is a verbatim span from the document, shown with its page number, so you can check it yourself. I fine-tuned BERT to **85.05% F1** on SQuAD 2.0, retrieve passages with TF-IDF and re-rank them with a cross-encoder, and serve INT8 ONNX models through FastAPI inside a 512MB Docker container. I measured each stage: scoring takes about 29 ms and re-ranking adds about 730 ms.

`Python` `PyTorch` `BERT` `ONNX` `FastAPI` `React` `Docker`

---

### [Later, Probably](https://github.com/kushagra0526/Later-Probably) ([live](https://later-probably.vercel.app))

A task planner where Gemini turns freeform text into structured fields and a dashboard compares the AI's time estimate, your own estimate and the actual time. PostgreSQL with Prisma and a pgvector HNSW index over 1536-dimension embeddings. Stats are aggregated server-side, so no raw task data reaches the LLM.

`Node.js` `PostgreSQL` `Prisma` `pgvector` `Gemini` `React` `Recharts`

---

### [Voltline: E-Commerce Microservices](https://github.com/kushagra0526/ecom_microservice_graphql) ([storefront](https://frontend-phi-two-61.vercel.app))

Three independent services (user, product, order) behind an Apollo GraphQL gateway, with Kafka for events between services, JWT roles for buyers, sellers and admins, Joi validation, Swagger docs, Jest and Supertest tests, Docker, and CI/CD on GitHub Actions. A Next.js storefront sits on top.

`Node.js` `Express` `GraphQL` `Apollo` `Kafka` `MongoDB` `Docker` `Next.js`

---

### [Interlace](https://github.com/kushagra0526/Interlace) ([live](https://interlace-sepia.vercel.app/))

A collaborative code editor backend with a CRDT (RGA) that I wrote from scratch, with no Yjs or Automerge, so edits from several people typing at once converge on the same document. Every operation goes into an append-only MongoDB log, with JWT-secured Socket.io rooms.

`Node.js` `Express` `Socket.io` `MongoDB` `CRDT`

---

### Earlier projects

- [VoiceNotebook-QA](https://github.com/kushagra0526/VoiceNotebook-QA): speak a note, store it locally and search it later. TypeScript, Vite, React, Web Speech API.
- [Stock Predictor](https://github.com/kushagra0526/Stock-Predictor): an ANN that predicts Apple's next-day price from OHLC data, with Random Forest feature selection.
- [AgriSys](https://github.com/kushagra0526/Agri_Sys): a seed bank management system for small farmers in India. JavaScript, Node.js, MongoDB.

---

## Tech Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
</p>

### Backend and APIs

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/Apollo-311C87?style=for-the-badge&logo=apollographql&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
</p>

### Databases

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

### AI and ML

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" />
</p>

LangGraph, ChromaDB, pgvector, Claude, Gemini, MCP, RAG, embeddings and LLM evals.

### DevOps and Cloud

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

## Achievements

| | |
| --- | --- |
| 🏆 | **Runner-Up**, HackCrux Hackathon (Oarfin, an AI disaster-guidance platform) |
| 🧩 | **450+ DSA problems** solved on LeetCode and GeeksforGeeks |
| 🎓 | **GenAI Workshop** certificate at LNMIIT, scored 100/100 |
| 👥 | Lead a 7 to 10 member Creative Team at the ACM LNMIIT Student Chapter |
| 🤝 | Sponsorship Head of Vivacity, LNMIIT's annual fest |

---

## Reach Me

<p align="center">
  <a href="https://www.linkedin.com/in/kushagra-pratap-singh/">
    <img src="https://img.shields.io/badge/Let's_Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kushagra0526&color=6E40C9&style=for-the-badge&label=PROFILE+VIEWS" />
</p>
