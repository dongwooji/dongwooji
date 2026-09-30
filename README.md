<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:4F46E5,100:7C3AED&height=240&section=header&text=DONGWOO%20JI&fontSize=52&fontColor=ffffff&fontAlignY=38" width="100%"/>
</p>

<div align="center">

### Computer Science & Artificial Intelligence

**Applied AI · Agentic RAG · Healthcare AI · Bioinformatics**

<br/>

<a href="https://github.com/dongwooji">
  <img src="https://img.shields.io/badge/GitHub-dongwooji-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</div>

---

## 👋 About Me

I am interested in building **AI systems that solve real-world problems**, from retrieval-augmented generation to healthcare and bioinformatics.

I have worked on projects involving **Agentic RAG, multimodal deep learning, biomedical signal analysis, and single-cell RNA-seq analysis**, with experience spanning research, model development, evaluation, and data pipelines.

- 🎓 B.S. in Computer Science & Artificial Intelligence, **Dongguk University**
- 🔎 Interested in **Applied AI, RAG, AI Systems, Healthcare AI, and Bioinformatics**
- 🧪 Experience in AI research and large-scale biomedical data analysis
- 📄 Published research in **Sensors (MDPI)**

---

## 🔬 Research & Technical Interests

<div align="center">

![Agentic RAG](https://img.shields.io/badge/Agentic_RAG-2563EB?style=for-the-badge)
![Information Retrieval](https://img.shields.io/badge/Information_Retrieval-7C3AED?style=for-the-badge)
![Applied AI](https://img.shields.io/badge/Applied_AI-0891B2?style=for-the-badge)
![Healthcare AI](https://img.shields.io/badge/Healthcare_AI-059669?style=for-the-badge)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-EA580C?style=for-the-badge)

</div>

---

## 📝 Publication

### Multimodal PPG-Based Arrhythmia Detection Using a CLIP-Initialized Multi-Task U-Net and LLM-Assisted Reporting

**Youngho Huh, Minhwan Noh, Dongwoo Ji, Yuna Oh, Sukkyu Sun**

*Sensors, 2026, 26(8), 2316*

[![DOI](https://img.shields.io/badge/DOI-10.3390%2Fs26082316-blue)](https://doi.org/10.3390/s26082316)
[![Paper](https://img.shields.io/badge/MDPI-Paper-00843D)](https://www.mdpi.com/1424-8220/26/8/2316)

- Developed a multimodal framework integrating **PPG waveforms, HRV features, and clinical information**
- Applied **CLIP-style contrastive learning** for multimodal representation learning
- Improved classification accuracy from **86.27% → 91.19%**
- Improved segmentation Dice score from **0.5815 → 0.7167**
- Integrated an **LLM-assisted RAG reporting pipeline** for interpretable diagnostic reporting

---

## 🔬 Research Experience

### Bioinformatics Research · ARPA-H Project
**Dongguk University × UNIST Collaboration**

- Analyzed colorectal cancer **single-cell RNA-seq** datasets to investigate differences between MSI and MSS tumor microenvironments
- Built a **Milo-based Differential Abundance analysis pipeline**
- Implemented preprocessing, dimensionality reduction, neighborhood construction, statistical testing, and visualization workflows
- Developed a custom **HDF5-based loader** for non-standard `.h5ad` datasets
- Containerized the analysis environment with **Docker** for reproducible execution on external computing resources

---

## 🚀 Featured Projects

| Project | Description | Core Stack |
| :--- | :--- | :--- |
| **[Agentic RAG Training](https://github.com/dongwooji/agentic-rag-training)** | Built an evaluation-driven Agentic RAG system with Dense, BM25, and Hybrid retrieval. Developed retrieval evaluation, tool interfaces, and evidence-based retrieval pipelines. | `Python` `RAG` `BM25` `Dense Retrieval` |
| **[PPG Arrhythmia Detection](https://github.com/dongwooji/ppg-arrhythmia-detection)** | Developed a multimodal PPG-based arrhythmia detection framework using contrastive pretraining and a multi-task U-Net for classification and segmentation. | `Python` `PyTorch` `Deep Learning` `RAG` |
| **[Single-cell Milo DA](https://github.com/dongwooji/singlecell-milo-da)** | Built a Differential Abundance pipeline for identifying MSI/MSS-associated cell populations in colorectal cancer single-cell RNA-seq data. | `Python` `Scanpy` `Milo` `Docker` |
| **[Bus Route Optimization](https://github.com/dongwooji/bus-route-optimization-gwacheon)** | Data-driven analysis project for public transportation and bus-route optimization. | `Python` `Data Analysis` |

---

## 🤖 Agentic RAG

### Evaluation-Driven Agentic RAG System

Rather than focusing only on LLM generation, this project explores the full **retrieval → evaluation → tool-use** pipeline.

**Key Components**

- Built a retrieval corpus and frozen evaluation dataset
- Implemented **Dense Retrieval, BM25, and Hybrid Retrieval**
- Designed evidence-group based retrieval evaluation
- Developed domain-specific tools for:
  - Training Logs
  - Metrics
  - Literature Retrieval
- Built automated tests for the tool layer
- Designed the system as a staged Agentic RAG architecture

**Retrieval Performance**

| Metric | Dense | BM25 | Hybrid |
| :--- | ---: | ---: | ---: |
| EvidenceGroupRecall@5 | 0.3963 | 0.4491 | **0.5120** |
| EvidenceGroupRecall@10 | 0.5630 | 0.5370 | **0.6602** |
| MRR | - | - | **0.4313** |

➡️ **[View Repository](https://github.com/dongwooji/agentic-rag-training)**

---

## 🛠 Tech Stack

<div align="center">

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### AI / Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### AI Systems / Data

![RAG](https://img.shields.io/badge/RAG-4F46E5?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

### Bioinformatics

![Scanpy](https://img.shields.io/badge/Scanpy-Single--Cell_Analysis-1F77B4?style=flat-square)
![Milo](https://img.shields.io/badge/Milo-Differential_Abundance-059669?style=flat-square)

</div>

---

## 📊 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dongwooji&show_icons=true&hide_border=true&rank_icon=github" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dongwooji&layout=compact&hide_border=true" height="165"/>

</div>

---

<div align="center">

### Building AI systems from research to real-world applications.

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=dongwooji&style=flat-square)

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:4F46E5,100:7C3AED&height=120&section=footer" width="100%"/>
</p>
