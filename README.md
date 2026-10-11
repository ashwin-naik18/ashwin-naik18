<!-- ═══════════════════════════════════════════════════════════════
     Ashwin Naik — GitHub Profile README
     Save this as README.md in a repo named exactly: ashwin-naik18
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0f1e,50:0b3a5b,100:00d4ff&height=220&section=header&text=Ashwin%20Naik&fontColor=ffffff&fontSize=56&fontAlignY=38&desc=Building%20AI%20systems%20from%20the%20inside%20out&descAlignY=60&descSize=18" alt="Ashwin Naik banner" width="100%"/>

<a href="https://github.com/ashwin-naik18">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1400&color=00D4FF&center=true&vCenter=true&width=720&lines=Student+%7C+AI+Systems+Builder;Custom+GPT+from+scratch+(PyTorch);AI+agents+%E2%80%A2+FastAPI+%E2%80%A2+Python+SDKs+%E2%80%A2+RAG;Learning+by+building.+One+system+at+a+time." alt="Typing animation"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ashwin_Naik-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwin-naik-30b73b395)
[![LeetCode](https://img.shields.io/badge/LeetCode-Ashwin__Naik-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Ashwin_Naik/)
[![Location](https://img.shields.io/badge/Bengaluru-India-00d4ff?style=for-the-badge&logo=googlemaps&logoColor=white)](https://github.com/ashwin-naik18)

</div>

---

## `> whoami`

Hey, I'm **Ashwin** 👋, a student who likes knowing how things work *under the hood*.

Instead of only calling an AI API, I try to build the pieces myself: the **tokenizer → transformer → training loop → fine-tuning → agent → API → SDK**. Some of it is rough, all of it is real, and every project teaches me something new.

```python
class Ashwin:
    role     = "Student & AI systems builder"
    focus    = ["LLMs from scratch", "AI agents", "FastAPI backends", "RAG"]
    languages = ["Python", "C", "C++", "JavaScript"]
    toolbox   = ["PyTorch", "LangChain", "NumPy", "Pandas", "Matplotlib"]
    web       = ["HTML", "CSS", "JS", "Flask", "FastAPI"]
    learning = ["Transformers", "Evaluation", "Retrieval", "DSA patterns"]
    approach = "Learn it. Build it. Break it. Fix it. Document it."
```

---

## 🧠 The Stack I'm Building, Layer by Layer

```mermaid
flowchart LR
    A["🔤 Tokenization<br/>(BPE / tiktoken)"] --> B["🧬 GPT from scratch<br/>(PyTorch)"]
    B --> C["🎯 Fine-tuning<br/>(conversational SFT)"]
    C --> D["🤖 Agents<br/>(tools + memory)"]
    D --> E["⚙️ AI API<br/>(FastAPI)"]
    E --> F["📦 Python SDK"]
    G["📄 RAG<br/>(doc chat)"] -.-> D
    style A fill:#0a0f1e,stroke:#00d4ff,color:#fff
    style B fill:#0a0f1e,stroke:#00d4ff,color:#fff
    style C fill:#0a0f1e,stroke:#00d4ff,color:#fff
    style D fill:#0a0f1e,stroke:#00d4ff,color:#fff
    style E fill:#0a0f1e,stroke:#00d4ff,color:#fff
    style F fill:#0a0f1e,stroke:#00d4ff,color:#fff
    style G fill:#0a0f1e,stroke:#7c3aed,color:#fff
```

---

## 🚀 Featured Projects

### 🧬 Model Development

| Project | What it is | Tech |
|---|---|---|
| **[AshGPT](https://github.com/ashwin-naik18/AshGPT-llm)** ⭐ | A GPT-style, decoder-only language model implemented in PyTorch. Multi-head self-attention, feed-forward blocks, residual connections, layer norm, dropout, GPT-style init, BPE tokenization (`o200k_base`), token-based chunking, background data prefetching, mixed-precision training on CUDA, and temperature / top-k sampling. Trained on SimpleStories. | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[AshGPT Fine-tuning](https://github.com/ashwin-naik18/AshGPT-Finetuning-llm)** | Supervised fine-tuning that adapts my custom GPT model toward conversational behavior: data preprocessing, tokenization, sequence packing, and loss masking. | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

<details>
<summary><b>🧪 Earlier iterations & experiments</b></summary>
<br/>

The path to AshGPT went through a few versions. These repos show how I got there:

- [`gpt-from-scratch-v1`](https://github.com/ashwin-naik18/gpt-from-scratch-v1): my first GPT-from-scratch attempt
- [`mini-gpt-v2-chunked-training`](https://github.com/ashwin-naik18/mini-gpt-v2-chunked-training): second iteration, with chunked training
- [`mini-gpt-v3-chunked-training`](https://github.com/ashwin-naik18/mini-gpt-v3-chunked-training): third iteration, with chunked training

</details>

> ⚠️ *These are educational, from-scratch models. They're built to understand how LLMs work, not to compete with production models.*

### 🤖 Agents & Applications

| Project | What it is | Tech |
|---|---|---|
| **[AshCode](https://github.com/ashwin-naik18/Ash_Code)** | An autonomous AI coding agent built from scratch: tool calling, memory, terminal execution, and autonomous code editing. | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[WhatsApp Automation Bot](https://github.com/ashwin-naik18/whatsapp-automation-bot)** | An AI-powered WhatsApp assistant with intelligent conversations, browser automation, long-term memory, and tool calling. | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![NVIDIA](https://img.shields.io/badge/NVIDIA_Nemotron-76B900?style=flat-square&logo=nvidia&logoColor=white) |
| **[Doc Chat RAG](https://github.com/ashwin-naik18/doc-chat-rag)** 🚧 | Work in progress: chat with your documents using retrieval-augmented generation (ingestion → chunking → embeddings → retrieval → grounded answers). | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[Jarvis Cortex](https://github.com/ashwin-naik18/Jarvis_Cortex)** | An experimental AI assistant project. See the repo for details. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

### ⚙️ Backend & Developer Tooling

| Project | What it is | Tech |
|---|---|---|
| **[AshAI Server](https://github.com/ashwin-naik18/ashai-server)** | A production-inspired AI API platform: secure authentication, API-key management, rate limiting, usage logging, and model selection. | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[AshAI SDK](https://github.com/ashwin-naik18/ashai-sdk)** | The Python SDK for the AshAI API, a simple developer-friendly client instead of hand-written HTTP requests. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **[Collab Hub](https://github.com/ashwin-naik18/Collab_Hub)** | A Flask collaboration platform where people share project ideas, find collaborators, and apply to join projects. Registration, login, email OTP verification, MySQL. | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white) |

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Machine Learning, Deep Learning & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

**Backend & Web**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

> I know the web basics (HTML, CSS, JS), and my real depth is in Python, ML/DL, and backend work.

---

## 🎯 Currently Focused On

- 🔭 Finishing **Doc Chat RAG**: retrieval quality, source citations, and evaluation
- 🧪 Learning how to **evaluate** models and agents instead of just eyeballing outputs
- 🧹 Polishing my best repos with clearer READMEs, setup steps, and demos
- 🧩 Working through a **structured DSA roadmap**: Arrays & Hashing → Two Pointers → Sliding Window → Stack → Binary Search → Linked Lists → Greedy → DP → Trees → Backtracking → Heaps → Graphs

**Curious about (not built yet):** text-to-image models · blockchain internals · computer vision

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ashwin-naik18&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0a0f1e&title_color=00d4ff&icon_color=00d4ff" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashwin-naik18&layout=compact&theme=tokyonight&hide_border=true&bg_color=0a0f1e&title_color=00d4ff" alt="Top languages"/>

</div>

---

## 📈 Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ashwin-naik18&theme=tokyo-night&bg_color=0a0f1e&color=00d4ff&line=00d4ff&point=ffffff&area=true&area_color=00d4ff&hide_border=true" width="100%" alt="Contribution activity graph"/>

<img src="./profile-3d-contrib/profile-night-view.svg" width="100%" alt="3D contribution skyline"/>

</div>

---

## 🧩 LeetCode

<div align="center">

<a href="https://leetcode.com/u/Ashwin_Naik/">
  <img src="https://leetcard.jacoblin.cool/Ashwin_Naik?theme=dark&font=JetBrains%20Mono&ext=heatmap" alt="LeetCode stats"/>
</a>

*Practicing for patterns and understanding, not just problem counts.*

</div>

---

## 🤝 Let's Connect

I'm always happy to talk about LLMs, agents, backend design, or learning in public. Feel free to open an issue on any repo with feedback. I take it seriously.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwin-naik-30b73b395)
[![LeetCode](https://img.shields.io/badge/Follow_on_LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Ashwin_Naik/)

<br/>

*"Building AI systems from the inside out."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:0b3a5b,100:0a0f1e&height=120&section=footer" alt="footer" width="100%"/>

</div>
