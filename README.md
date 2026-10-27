# Hi, I'm Sabeer 

I'm an MCA graduate building **agentic AI systems**. I like projects where an AI system has to be *tested, measured and made reliable*, not just demoed: typed outputs, hard loop limits, automated tests, CI and a live deployment.

I'm currently looking for **junior AI / LLM engineer roles**, and I'm open to junior Python and full-stack roles that work with AI.

---

##  Featured Project: Agent-Sec

**[Agent-Sec](https://github.com/Sabeer65/Agent-Sec)** is an autonomous red-teaming engine for LLM chatbots. It generates prompt-injection attacks, judges whether they worked, rewrites the chatbot's system prompt to close the hole, and re-tests, with a hard cap of 5 iterations.

- 4-node **LangGraph** state machine: attacker → target → evaluator → patcher
- Judge verdicts validated with **Pydantic** (typed, schema-checked LLM-as-a-judge)
- Local **Ollama** target; **Groq** free-tier models for the attacker and judge ($0 running cost)
- Every run saved as JSON and Markdown reports; **Streamlit** dashboard with live per-node streaming
- **Docker Compose**, **pytest** and **GitHub Actions** CI

 **[Live dashboard](https://agent-sec-project.streamlit.app/)** ·  **[Source code](https://github.com/Sabeer65/Agent-Sec)**

*Known limits:* it covers prompt injection and system-prompt leakage only, and the judge hasn't yet been measured against a labelled dataset (that's my next upgrade).

---

##  Tech I Use

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat&logo=googlegemini&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

---

##  What I Focus On

- Agentic workflows and multi-agent orchestration (LangGraph)
- LLM security: prompt-injection testing, prompt hardening, guardrails
- Evaluating LLM output: structured outputs and LLM-as-a-judge
- Local-first, zero-cost AI setups (Ollama and free-tier APIs)
- Computer vision for real-world problems

---

##  Selected Projects

| Project | What it is |
|---|---|
| **[Agent-Sec](https://github.com/Sabeer65/Agent-Sec)** | Autonomous LLM red-teaming and self-healing guardrail engine (see above). |
| **[API Breaking Change Detector](https://github.com/Sabeer65/AgentKit)** | Open-source AgentKit built in Lamatic Studio that evaluates JSON schema changes, with XML-delimiter prompt hardening. |
| **[Chat-with-your-PDF](https://github.com/Sabeer65/Chat-with-your-PDF)** | Local RAG app (LangChain, Streamlit, Ollama): ask questions about PDFs without sending data to external services. |
| **[Pothole Detection](https://github.com/Sabeer65/pothole-detection-yolo)** | YOLOv8 + PyTorch + OpenCV model for detecting road damage in images and video. |
| **[AI-FameTalk](https://github.com/Sabeer65/AI-FameTalk)** | React + Gemini chat interface exploring system-prompt design for consistent AI personas. |
| **Dungeon Master AI** | LLM-powered narrative system exploring controlled creativity and context handling. |
| **Linear Regression From Scratch** | Linear regression without ML libraries, to understand optimization, cost functions and model behavior. |

---

##  Background

**Master of Computer Applications (2023–2025)**
Mar Thoma Institute of Information Technology, Kerala, India

**Frontend Engineering Intern, Caltech Labs** (Jul–Dec 2025): React, REST integration, Git sprints.

---

##  Connect

- LinkedIn: [linkedin.com/in/sabeer-h](https://www.linkedin.com/in/sabeer-h/)
- GitHub: [github.com/Sabeer65](https://github.com/Sabeer65)
