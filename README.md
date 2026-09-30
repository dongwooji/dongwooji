markdown
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:4F46E5,100:7C3AED&height=240&section=header&text=DONGWOO%20JI&fontSize=52&fontColor=ffffff&fontAlignY=38" width="100%"/>
</p>

<div align="center">

### Computer Science & Artificial Intelligence

**AI Engineer · Agentic RAG · LLM · Healthcare AI**

<br/>

<a href="https://github.com/dongwooji">
  <img src="https://img.shields.io/badge/GitHub-dongwooji-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</div>

---

## 👋 소개

데이터와 AI 모델을 실제 문제 해결로 연결하는 **AI Engineer**를 지향합니다.

LLM/RAG 시스템, 멀티모달 의료 AI, 대규모 바이오 데이터 분석 프로젝트를 수행하며 **문제 정의부터 데이터 전처리, 모델 구현, 검색 시스템 구축, 성능 평가, 파이프라인 설계까지** 경험했습니다.

새로운 기술을 단순히 적용하는 데 그치지 않고, **비교 실험과 정량적 평가를 통해 성능을 검증하고 재현 가능한 시스템으로 구현하는 과정**을 중요하게 생각합니다.

- 🎓 동국대학교 **컴퓨터·AI학부**
- 🤖 **LLM, RAG, AI Systems, Applied AI** 중심으로 프로젝트 수행
- 🛠 데이터 처리부터 모델 개발·평가·시스템 구현까지 End-to-End 경험
- 📄 국제학술지 **Sensors (MDPI)** 논문 게재

---

## 🔬 연구 및 기술 관심 분야

<div align="center">

![AI Engineering](https://img.shields.io/badge/AI_Engineering-2563EB?style=for-the-badge)
![Agentic RAG](https://img.shields.io/badge/Agentic_RAG-4F46E5?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM-7C3AED?style=for-the-badge)
![Information Retrieval](https://img.shields.io/badge/Information_Retrieval-0891B2?style=for-the-badge)
![Healthcare AI](https://img.shields.io/badge/Healthcare_AI-059669?style=for-the-badge)

</div>

---

## 📝 논문

### Multimodal PPG-Based Arrhythmia Detection Using a CLIP-Initialized Multi-Task U-Net and LLM-Assisted Reporting

*Sensors (MDPI)*

- PPG 파형, HRV 및 임상 정보를 결합한 **멀티모달 부정맥 탐지 시스템** 개발
- 서로 다른 데이터 표현을 학습하기 위해 **CLIP 기반 대조학습 구조** 적용
- 분류 정확도 **86.27% → 91.19%** 향상
- Segmentation Dice Score **0.5815 → 0.7167** 향상
- 탐지 결과를 바탕으로 설명 가능한 리포트를 생성하기 위한 **LLM 기반 RAG 파이프라인** 구현

➡️ **[프로젝트 저장소](https://github.com/dongwooji/ppg-arrhythmia-detection)**

---

## 🔬 연구 경험

### ARPA-H Project · Single-cell RNA-seq Analysis

- 대장암 single-cell RNA-seq 데이터를 활용하여 **MSI와 MSS 종양 미세환경의 세포 구성 차이 분석**
- **Milo 기반 Differential Abundance 분석 파이프라인** 구축
- 데이터 전처리 → PCA → KNN Graph → Neighborhood 생성 → 통계 검정 → 시각화까지 분석 과정 구현
- 일반적인 방식으로 읽기 어려운 `.h5ad` 데이터 처리를 위해 **HDF5 기반 Custom Loader** 구현
- 외부 컴퓨팅 환경에서도 동일한 분석을 재현할 수 있도록 **Docker 기반 실행 환경 구성**
- 통계적으로 유의한 MSI/MSS enriched cell population을 추출하고 분석 결과 시각화

---

## 🚀 주요 프로젝트

| Project | Description | Core Stack |
| :--- | :--- | :--- |
| **[Agentic RAG Training](https://github.com/dongwooji/agentic-rag-training)** | Dense, BM25, Hybrid Retrieval을 비교·평가하는 Agentic RAG 시스템을 구축했습니다. 검색 성능 평가 체계를 설계하고 Training Log, Metric, Literature Tool 등 도메인별 Tool Layer를 구현했습니다. | `Python` `RAG` `BM25` `Dense Retrieval` `LangGraph` |
| **[PPG Arrhythmia Detection](https://github.com/dongwooji/ppg-arrhythmia-detection)** | PPG 신호와 임상 정보를 활용한 멀티모달 부정맥 탐지 시스템을 개발했습니다. CLIP 기반 사전학습과 Multi-task U-Net을 적용해 분류 및 구간 탐지 성능을 개선했습니다. | `Python` `PyTorch` `Deep Learning` `LLM` |
| **[Single-cell Milo DA](https://github.com/dongwooji/singlecell-milo-da)** | 대장암 single-cell RNA-seq 데이터에서 Milo 기반 Differential Abundance 분석을 통해 MSI/MSS에 따른 세포 집단 차이를 분석하는 파이프라인을 구축했습니다. | `Python` `Scanpy` `Milo` `Docker` |
| **[Bus Route Optimization](https://github.com/dongwooji/bus-route-optimization-gwacheon)** | 교통 및 버스 이용 데이터를 분석하여 과천 지역 대중교통 노선 개선안을 도출한 데이터 분석 프로젝트입니다. | `Python` `Data Analysis` |

---

## 🛠 Tech Stack

<div align="center">

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### AI / Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### LLM / AI Systems

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-4F46E5?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-7C3AED?style=flat-square)

### Backend / Application

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

</div>
