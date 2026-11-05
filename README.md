# Hi, I'm Mohammad Javad Amin 👋

**PhD student at [Università della Svizzera italiana (USI)](https://www.usi.ch), Lugano. I work on agentic AI, retrieval-augmented generation (RAG) and caching for LLM systems.**

I build the layer between LLM agents and the data they reason over. My goal is to make agents **faster, cheaper and more reliable** by reusing what earlier runs already learned, instead of re-retrieving and re-reasoning from scratch every time.

### 🔭 Current work

- **KAIROS** (*Knowledge Architecture for Incremental Reasoning Over Data Sources*): middleware between LLM agents and evolving knowledge graphs. Agents query Neo4j through an **MCP** server, and a **semantic cache** stores validated Cypher queries, results and distilled facts (never final answers), so similar questions skip rediscovery.
- **An agentic graph-QA benchmark** built on Neo4j's GRAPE: LangGraph agents with MCP tools, an LLM-as-judge, concurrent evaluation and per-tool-call instrumentation. Runs on cloud LLMs (OpenRouter) and local ones (llama.cpp).
- **Exploring:** approximate and semantic caching for RAG, KV-cache reuse, vector search (ANN/HNSW), and efficient serving of retrieval-augmented systems.

### 🧠 Research interests

`Agentic AI` · `Retrieval-Augmented Generation` · `LLM caching` · `Model Context Protocol` · `Knowledge graphs` · `Vector databases` · `Reinforcement learning` · `Distributed systems`

### 📌 Featured projects

| Project | What it is |
|---|---|
| [**ai-council**](https://github.com/mj-amin-ece/ai-council) | Ask Claude, ChatGPT and Gemini side by side, then let them review and improve each other's answers over several rounds. Runs locally on your existing subscriptions, with lean prompts and token and limit tracking. |
| [**GATN**](https://github.com/mj-amin-ece/GATN) | Graph attention transformer for multi-label retinal disease classification: EfficientNet features plus a label graph built from biomedical text embeddings. |
| [**Deep-Learning**](https://github.com/mj-amin-ece/Deep-Learning) | PyTorch coursework, including **GAN-BERT** for machine-generated text detection (SemEval-2024), which beats a BERT baseline at every label fraction. |
| [**RL**](https://github.com/mj-amin-ece/RL) | Deep RL: custom Gymnasium environments, n-step SARSA and Q-learning, DQN vs. Double DQN. |
| [**game-theory-surgical-allocation**](https://github.com/mj-amin-ece/game-theory-surgical-allocation) | Deferred-acceptance matching of surgery requests to hospitals under Poisson arrivals. |
| [**Data-Network**](https://github.com/mj-amin-ece/Data-Network) | OMNeT++ simulations of data-link, MAC and OSPF protocols, plus Linux networking. |

Earlier work: [Adaptive Noise Reduction](https://github.com/mj-amin-ece/Adaptive-Noise-Reduction) (LMS, NLMS and RLS in MATLAB) · [2×2 Rubik's Solver](https://github.com/mj-amin-ece/2x2-Rubik-s-Game-Solver) (C++ graph search) · [Course Media Player](https://github.com/mj-amin-ece/Course-Specific-Media-Player) (PyQt5) · [Advanced Programming](https://github.com/mj-amin-ece/Advanced-Programming) (C++17 and Python)

### 🎓 Background

- **PhD**, Università della Svizzera italiana (USI), Lugano: agentic AI, RAG and caching *(current)*
- **M.Sc. in Communication Systems**, Sharif University of Technology. Thesis: deep reinforcement learning (DQN, Dueling DQN, C51) for task offloading in edge–cloud computing
- **B.Sc.**, Amirkabir University of Technology (Tehran Polytechnic)
- **Neural Wave AI Hackathon** (Lugano), team NAMA: reverse-engineered a legacy insurance system's calculation rules into deterministic Python, matching the legacy outputs on 99.7–100 % of the training cases

### 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C)
![MCP](https://img.shields.io/badge/MCP-000000)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?logo=mathworks&logoColor=white)

### 📫 Contact

[![Email](https://img.shields.io/badge/aminm%40usi.ch-D14836?logo=gmail&logoColor=white)](mailto:aminm@usi.ch)
