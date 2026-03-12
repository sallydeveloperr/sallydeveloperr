<p align="center">
  <a href="#-about-me">소개</a> ·
  <a href="#-featured-projects">프로젝트</a> ·
  <a href="#-tech-stack">기술 스택</a> ·
  <a href="#-education--awards">수상 및 교육</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=220&section=header&text=Hello,%20I'm%20YuJeong&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Data%20Driven%20Solution&descAlignY=55&descAlign=50" />
</div>

<div align="center">

### 👋 Welcome to My GitHub

**"데이터 흐름을 설계하고, AI로 실무의 비효율을 해결합니다."**

문제의 본질을 파악하여 **최적의 모델을 선정(Model Selection)** 하고,  
사용자가 실제로 활용 가능한 **안정적인 서비스(Full-Stack AI)** 를 구축합니다.

</div>

---

## 🙋‍♂️ About Me

- 🎯 **Focus**: Domain-Specific **sLLM Fine-tuning**, **RAG Optimization**, **Agentic Workflow**
- 💡 **Strength**: 
  - **Full-Cycle Dev**: 기획부터 데이터 수집, 전처리, 모델링, 웹 서비스 배포까지 **E2E 개발** 을 주도합니다.
  - **Communication**: 복잡한 기술 개념을 명확히 문서화하고, PM으로서 팀의 목표를 조율하는 협업 역량을 갖췄습니다.
- 🚀 **Goal**: 단순한 기능 구현을 넘어, **비즈니스 임팩트(ROI, 효율화)** 를 창출하는 실용적인 AI 서비스를 만듭니다.

---

## 💼 Featured Projects

### 1) ⚖️ FTOGuard: 특허 침해 리스크 분석 플랫폼

> **SKN AI Camp 20기 — 5차 프로젝트**  
> **Repository**: [🔍 FTO 중심 특허·디자인 침해 리스크 판단 AI 에이전트](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN20-FINAL-2TEAM.git)  
> **🏆 Awards**: SK네트웍스 Family AI 캠프 **최우수상**

제품 출시 전 **특허 및 디자인 침해 리스크를 자동으로 분석**하는 AI 기반 FTO(Freedom To Operate) 분석 시스템입니다.  
RAG 기반 특허 검색과 파인튜닝된 sLLM을 결합하여 **법률 전문가 의존도가 높은 FTO 분석 과정을 자동화**했습니다.

- **Role**: AI Engineer & Backend Developer
- **Key Tech**:
  - **Hybrid RAG Retrieval**: KURE-v1 임베딩 + BM25 Sparse 검색을 결합한 Hybrid RAG로 **78,000건 특허 → Top 10 후보 특허 자동 선별**
  - **Domain sLLM Fine-Tuning**: Qwen2.5 모델을 QLoRA 기반으로 파인튜닝하여 **특허 청구항 해석 정확도 94.3% 달성**
  - **Multi-Agent Workflow**: LangGraph 기반 에이전트 구조로 **특허 분석·디자인 유사도 검색·리포트 생성 자동화**
  - **Vision-Language Analysis**: CLIP + Qwen2.5-VL을 활용하여 **디자인 특허 이미지 유사도 분석 및 리스크 설명 생성**
  - **Cloud AI Infrastructure**: AWS EC2/RDS/S3 + RunPod GPU 서버를 활용한 **LLM 추론 파이프라인 구축**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Agent%20Workflow-000000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-7C3AED?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20RDS%20%7C%20S3-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![RunPod](https://img.shields.io/badge/RunPod-GPU%20Inference-673AB7?style=flat-square)

---

### 2) 🤖 Boss Baby AI: RAG 기반 창업 지원 챗봇

> **SKN AI Camp 20기 — 4차 프로젝트**  
> **Repository**: [🚀 Boss Baby AI - 창업 지원 통합 플랫폼](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN20-4th-4TEAM)

15,510개 벡터 문서 기반으로 예비 창업자에게 정확한 정보를 제공하고, AI 사업계획서 분석과 일정 자동 추출까지 지원하는 올인원 창업 파트너입니다.

- **Role**: Frontend Developer, PM 보조, 문서화
- **Key Tech**:
  - **Hybrid RAG**: ChromaDB(벡터) + MySQL(정형) + Tavily API(웹 검색) 3-Way 라우팅으로 검색 정확도 **92.8%** 달성
  - **Auto-Schedule Extraction**: LLM이 답변에서 날짜를 감지해 캘린더에 자동 등록
  - **Real-time Streaming**: Django Channels + Redis 기반 타이핑 스트리밍 응답
  - **Stack**: Django · FastAPI · ChromaDB · MySQL · GPT-4o-mini · Docker

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

### 3) 🌙 Moonlog: AI 감정 코칭 다이어리 앱

> **서울여자대학교 Programming GURU2**  
> **Repository**: [Moonlog - 감정 일기 코칭 앱 🌙](https://github.com/yeongcho/Moonlog.git)  
> **Awards**: 서울여자대학교 Programming GURU2 **우수상**

하루를 마무리하며 감정을 기록하면, Gemini API가 원인을 분석하고 즉시 실행 가능한 행동을 제안하는 Android 감정 관리 앱입니다.

- **Role**: PM, 발표, 전체 일정 조율 (기획→개발→발표)
- **Key Tech**:
  - **AI Emotion Coaching**: Gemini API 기반 트리거 분석 + 3가지 맞춤 솔루션 제안
  - **비회원 → 회원 전환**: 세션 기반 비회원 데이터가 회원 전환 시 자동 마이그레이션
  - **Card Image Export**: 분석 결과를 이미지 카드로 저장 (갤러리 연동)
  - **Stack**: Android · Kotlin · Gemini API · Firebase

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

---

## 🛠 Tech Stack

### 🧠 AI & Data

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### 💻 Backend & Infra

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🏆 Education & Awards

### 🏅 Awards

- **서울여자대학교 Programming GURU1** | 수료 (2023.01)  
  - 주제: HTML/Python 22조 해커톤 팀장

- **서울여자대학교 Programming GURU2** | 우수상 (2026.01)  
  - 주제: AI가 감정을 분석하고 오늘 실천 가능한 감정 완화 솔루션을 제안하는 감정 코칭 애플리케이션

- **SK네트웍스 Family AI Camp 최종 프로젝트** | 우수상 (2026.03)  
  - 주제: FTO 중심 특허·디자인 침해 리스크 판단 AI 에이전트

### 🎓 Education

- **SK Networks Family AI Camp (20기)** | AI/SW 개발자 과정 수료 (2025.09 - 2026.03)
- **LG Aimers** | AI 전문가 양성 과정 Phase 1·2·3 수료
- **Corning AI Challenge** | 키워드 기반 AI 뉴스 추천 시스템 개발
- **광명시 청소년 멘토링 프로그램 (IT 멘토)** | 중·고등학생 대상 IT 기초 교육 및 진로 멘토링 수행
- **서울여자대학교 바롬종합설계프로젝트** | 불법 동영상 유포 및 저작권 침해 방지 캠페인 기획·수행
- **서울여자대학교** | 디지털미디어학과/ 소프트웨어융합학과 졸업 (학점 /4.5)
- **서울여자대학교 멋쟁이사자처럼 14기** | Backend Developer (2026.03 - 2026.12)

### 📜 Certificates

- **데이터분석 준전문가 (ADsP)** | 한국데이터산업진흥원
- **SQL 개발자 (SQLD)** | 한국데이터산업진흥원
- **정보처리기사** | 한국산업인력공단
- **리눅스마스터 2급** | 한국정보통신진흥협회
- **컴퓨터활용능력** | 대한상공회의소

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=100&section=footer" />

</div>
