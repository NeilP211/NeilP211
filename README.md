<div align="center">

# Neil Patel

**Full-stack/AI Products**

![UNC Chapel Hill](https://img.shields.io/badge/UNC%20Chapel%20Hill-30363D?style=flat-square)
&nbsp;·&nbsp;
![Computer Science](https://img.shields.io/badge/Computer%20Science-30363D?style=flat-square)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/neil-patel-735132281/)
&nbsp;
[![Email](https://img.shields.io/badge/ndpatel@unc.edu-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:ndpatel@unc.edu)

</div>

---

## Cool Projects

| Project | What it does | Stack |
|---|---|---|
| ⭐ **[exfil](https://github.com/NeilP211/exfil)** | Browser-playable authoritative-server extraction shooter with competitive netcode (**64Hz tick**, client prediction, lag compensation). **Self-play RL drives the enemy AI**: a PPO policy trained on the bit-exact sim (**100% win rate** vs scripted/random) is exported and run **natively in the Go server** to control the in-game scavs, with a line-of-sight vision + memory layer. | `Go` `Rust/WASM` `TypeScript` `PyTorch` `RL` |
| ⭐ **[crypt](https://github.com/NeilP211/crypt)** | Geospatial visual search for haunted places **plus an in-app RAG agent**: ask a question and a **Claude** planner over a hybrid retriever (BGE + BM25, **Reciprocal Rank Fusion**, cross-encoder rerank) answers with cited places pinned on the map, scored by an **LLM-judge** eval harness. Backed by a from-scratch **Rust HNSW** index. | `Rust` `Next.js` `RAG` `Claude` `CLIP` `AWS` |
| **[distkv](https://github.com/NeilP211/distkv)** | From-scratch **Raft** consensus engine: no etcd/raft library. Leader election, log replication, snapshots, joint-consensus membership; verified by a deterministic chaos suite + linearizability checker. Live TUI dashboard, Prometheus/Grafana, Helm/K8s. | `Go` `gRPC` `Raft` `bbolt` `Kubernetes` |
| **[neuropeek](https://github.com/NeilP211/neuropeek)** | Mechanistic-interpretability lab reproducing **and** extending Olsson '22 induction heads on Pythia, with a custom **Triton kernel** for the hot probing path. Headline: scale-invariant emergence at step ~1000. | `Python` `PyTorch` `Triton` `Pythia` |
| **[runway](https://github.com/NeilP211/runway)** | An AI stylist that learns what goes together: a **GNN** trained on 35k Polyvore outfits scores compatibility (**0.848 AUC**), powering catalog search, color/brand filters, and an interactive "Catwalk" builder. | `Python` `PyTorch` `GNN` `Full-stack` |
| **[Five Nights at Wahmirs](https://github.com/NeilP211/five-nights-at-wahmirs)** | A browser **survival-horror game** in **Three.js**: no engine, no build step, everything procedural (canvas-noise materials, a synthesized **Web Audio** soundscape with a unique signature per creature, a cold post-fx grade). Five named AI threats including an **unkillable hunter**, a **diegetic phone** pillar (a radar you raise at the cost of watching the room) that one creature sabotages and another can only be tracked through, a warm-light ally, and a **5-night escape**. | `Three.js` `WebGL` `Web Audio` `JavaScript` |
| **[LookBetter](https://github.com/NeilP211/LookBetter)** | U-Max remake, Full-stack face-analysis app: FastAPI + **MediaPipe** detect 478 facial landmarks and score classic proportions (FWHR, symmetry), served to a React frontend. Looksmaxxing trend. | `FastAPI` `MediaPipe` `React` |
| **[fortnut-2](https://github.com/NeilP211/fortnut-2)** | A solo-built **Unity (C#)** FPS with custom Blender models, shipped to GameJolt. Built as a kid who really liked Fortnite. | `Unity` `C#` `Blender` |

---

## Tech w/ rainbow icons

**Languages**
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**ML &amp; AI**
&nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-1C7C54?style=flat)
![Reranking](https://img.shields.io/badge/Reranking-5C3EE8?style=flat)
![Reinforcement Learning](https://img.shields.io/badge/Reinforcement%20Learning-EE4C2C?style=flat)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-3776AB?style=flat)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![PyTorch Geometric](https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=flat&logo=pytorch&logoColor=white)
![Triton](https://img.shields.io/badge/Triton-76B900?style=flat&logo=nvidia&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![CLIP](https://img.shields.io/badge/OpenCLIP-412991?style=flat&logo=openai&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat&logo=google&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white)

**Web &amp; Frontend**
&nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=flat&logo=maplibre&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat&logo=framer&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white)

**Data &amp; Infra**
&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat&logo=grpc&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-0F9D58?style=flat&logo=protobuf&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

<div align="center">

**[LinkedIn](https://linkedin.com/in/neil-patel-735132281/)** &nbsp;·&nbsp; **[Email](mailto:ndpatel@unc.edu)** &nbsp;·&nbsp; **[GitHub](https://github.com/NeilP211)**

</div>
