**<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:001F3F,50:0074D9,100:2ECC40&height=200&section=header&fontColor=EAF6FF&fontSize=40&fontAlignY=38&text=Mohammed%20Abdul%20Omer&desc=AI%20%2F%20Machine%20Learning%20Engineer&descSize=18&descAlignY=60&descColor=7FDBFF" width="100%"/>

<p>
<em>GenAI · RAG · LLM Fine-tuning · Agentic AI · MLOps · Computer Vision</em>
</p>

<a href="https://www.linkedin.com/in/mohammad-abdul-omer/">
  <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white&style=for-the-badge" />
</a>
&nbsp;
<a href="https://mohdomer.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" />
</a>
&nbsp;
<a href="mailto:mohammedabdulomer99@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://huggingface.co/mohdomer">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
</a>
&nbsp;
<a href="https://github.com/MOHD-OMER">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

## About

AI/ML Engineer focused on building and deploying LLM-based systems end to end — from data and fine-tuning through retrieval pipelines, multi-agent orchestration, and production APIs. I work across the full stack of a modern AI product: modeling, evaluation, experiment tracking, and cloud deployment.

Currently completing a B.E. in Computer Science (AI & ML) at Lords Institute of Engineering, Hyderabad, and open to AI / ML Engineer roles.

- **Core focus:** LLM engineering, RAG pipelines, fine-tuning (QLoRA/PEFT), agentic systems, MLOps, computer vision
- **Primary stack:** Python, PyTorch, LangChain, LangGraph, CrewAI, FastAPI, Hugging Face

| Area | Focus |
|------|-------|
| **AI Routing & Orchestration** | Multi-provider routing, task classification, benchmark-driven evaluation |
| **Advanced RAG** | Hybrid retrieval (BM25 + vector + re-ranking), agentic and multi-document QA |
| **LLM Engineering** | QLoRA/PEFT fine-tuning, prompt orchestration, Groq / Gemini / OpenRouter APIs |
| **Agentic AI** | Multi-agent systems with CrewAI and LangGraph ReAct agents |
| **MLOps** | MLflow tracking, Evidently AI drift monitoring, W&B, reproducible pipelines |
| **Computer Vision** | Object detection (YOLOv8), medical imaging, Grad-CAM explainability |
| **APIs & Deployment** | FastAPI, Django, Docker, Railway, Render, Hugging Face Spaces |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### AI Orchestrator — Multi-Provider Model Router

Routes each task to the most suitable model across Groq, Gemini, OpenRouter, and Ollama based on priorities such as speed, quality, cost, or on-device privacy. Classifies across 10 task types, supports 17+ models, includes a benchmark mode to validate routing decisions, and falls back automatically on provider failure. Ships with a full CLI.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)

[GitHub](https://github.com/MOHD-OMER/ai-orchestrator) · [Live Demo](https://ai-orchestrator-nu86.onrender.com)

</td>
<td width="50%" valign="top">

### Multi-Agent Research System

Three specialized agents — researcher, analyst, and writer — divide a research task, pull live web data via Tavily, and hand off work through CrewAI to produce a structured report. Provide a topic; receive a complete report.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=flat-square&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Tavily](https://img.shields.io/badge/Tavily-0EA5E9?style=flat-square&logoColor=white)

[GitHub](https://github.com/MOHD-OMER/multi-agent-researcher) · [Live Demo](https://huggingface.co/spaces/mohdomer/nexus-research)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### LLM Fine-tuning — Mistral-7B Medical QA

Fine-tuned Mistral-7B-Instruct-v0.2 on a medical Q&A dataset using QLoRA/PEFT on a Kaggle T4 GPU, resolving quantization compatibility across library versions along the way. Model weights and a Gradio demo are published on Hugging Face.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT%2FQLoRA-8B5CF6?style=flat-square&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=flat-square&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

[GitHub](https://github.com/MOHD-OMER/llm-finetuning) · [Model](https://huggingface.co/mohdomer/mistral-7b-medical-qa-qlora) · [Demo](https://huggingface.co/spaces/mohdomer/mistral-medical-qa-demo)

</td>
<td width="50%" valign="top">

### Multi-Document RAG Chatbot

RAG chatbot built on a LangGraph ReAct agent with hybrid retrieval — ChromaDB for vector search, BM25 for keyword matching, and FlashRank for re-ranking. FastAPI handles streaming over SSE, with generation by Groq's llama-3.1-8b-instant. Includes Streamlit and Gradio frontends.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

[GitHub](https://github.com/MOHD-OMER/rag-agent)

</td>
</tr>
</table>

<div align="center">
<a href="https://mohdomer.vercel.app/">
  <img src="https://img.shields.io/badge/View%20All%20Projects-Portfolio-%23000000?style=flat-square&logo=vercel&logoColor=white"/>
</a>
</div>

---

## Tech Stack

**AI / ML & Deep Learning**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
</p>

**LLM Engineering & Agentic AI**

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/CrewAI-000000?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/PEFT%2FQLoRA-8B5CF6?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white"/>
</p>

**MLOps & Experiment Tracking**

<p>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black"/>
  <img src="https://img.shields.io/badge/Evidently%20AI-6C5CE7?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

**APIs, UI & Deployment**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace%20Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black"/>
</p>

**Developer Tools**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=MOHD-OMER&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="54%" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=MOHD-OMER&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="40%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=MOHD-OMER&theme=tokyonight&hide_border=true" width="60%" />
</p>

---

<div align="center">

**Open to AI / ML Engineer roles.** Interested in discussing AI systems or opportunities?

<a href="https://www.linkedin.com/in/mohammad-abdul-omer/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-%230077B5?style=flat-square&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://mohdomer.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-View-%23000000?style=flat-square&logo=vercel&logoColor=white"/>
</a>
&nbsp;
<a href="https://huggingface.co/mohdomer">
  <img src="https://img.shields.io/badge/Hugging%20Face-Models-%23FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
</a>

</div>
**
