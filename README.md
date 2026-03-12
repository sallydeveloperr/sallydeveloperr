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

예비 창업자와 초기 스타트업이 **지원사업 정보 탐색, 사업계획서 분석, 일정 관리**를 한 번에 수행할 수 있도록 설계된 **RAG 기반 창업 지원 AI 플랫폼**입니다.  
15,510개의 창업 관련 데이터를 벡터화하여 정확한 검색을 제공하고, AI 사업계획서 분석과 지원사업 일정 관리 기능을 통합한 올인원 창업 도우미 시스템입니다.

- **Role**: Backend Developer (Database & API)
- **Key Tech**:
  - **Advanced RAG Pipeline**: Query Transformation + Multi-Query 전략을 적용하여 **15,510개 문서 기반 검색 정확도 92.8% 달성**
  - **3-Way Retrieval Architecture**: **Internal RAG → Web Search → AI Fallback** 구조로 정보 공백 없는 100% 커버리지 구현
  - **AI Business Plan Analysis**: 벤처투자 전문가 페르소나 기반 **8개 항목 사업계획서 평가 및 개선 로드맵 생성**
  - **Calendar Event Extraction**: LLM 응답에서 날짜 패턴을 자동 감지하여 **지원사업 일정 자동 생성 및 D-Day 관리**
  - **Hybrid Web Architecture**: **Django (Frontend) + FastAPI (AI Backend)** 기반 마이크로 서비스 구조 설계
  - **Vector Search Infrastructure**: ChromaDB 벡터 DB와 OpenAI Embedding을 활용한 창업 데이터 검색 시스템 구축

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-7C3AED?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 3) 🌙 Moonlog: AI 감정 코칭 다이어리 앱

> **서울여자대학교 Programming GURU2**  
> **Repository**: [Moonlog - 감정 일기 코칭 앱 🌙](https://github.com/yeongcho/Moonlog.git)  
> **Awards**: 서울여자대학교 Programming GURU2 **우수상**

사용자가 하루의 감정과 일기를 기록하면 **AI가 감정 트리거를 분석하고 즉시 실행 가능한 행동을 제안하는 감정 코칭 모바일 애플리케이션**입니다.  
Gemini API 기반 감정 분석과 데이터 시각화를 결합하여 **사용자가 자신의 감정 패턴을 이해하고 관리할 수 있도록 설계된 Android 앱**입니다.

- **Role**: Frontend Developer (Onboarding, Authentication, Calendar UI)
- **Key Tech**:
  - **AI Emotion Analysis**: Google **Gemini API**를 활용하여 감정 요약, 트리거 분석 및 맞춤형 감정 완화 행동 제안
  - **Emotion Pattern Visualization**: **MPAndroidChart**를 활용하여 월간 감정 흐름과 패턴을 시각화
  - **Interactive Emotion Diary**: 감정 선택 기반 일기 작성 및 **AI 분석 카드 이미지 저장 기능** 제공
  - **Mobile Architecture**: **Android Jetpack (Navigation, Lifecycle, ViewBinding)** 기반 구조 설계
  - **User Experience Design**: 밤하늘 테마 기반 감정 안정 중심 UX 및 **비회원 모드 지원**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![MPAndroidChart](https://img.shields.io/badge/MPAndroidChart-Visualization-blueviolet?style=flat-square)
![OkHttp](https://img.shields.io/badge/OkHttp-Networking-000000?style=flat-square)
---

### 4) 🦁 AI Startup Policy Chatbot: 창업자를 위한 RAG 기반 정책 안내 챗봇

> **SKN AI Camp 20기 — 3차 프로젝트**  
> **Repository**: [🚀 창업자를 위한 AI 정책 안내 챗봇](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN20-3rd-4TEAM.git)


초기 창업자가 겪는 **정부 지원사업·법령·창업 정책 정보 탐색의 어려움**을 해결하기 위해 개발한 **RAG 기반 AI 정책 안내 챗봇**입니다.  
중소벤처기업부 및 K-Startup 데이터를 기반으로 **신뢰 가능한 창업 정책 정보를 검색·요약**하고, Query Transformation과 Multi-Query Retrieval을 통해 **검색 정확도를 개선**했습니다.

- **Role**: Backend & RAG Pipeline Developer

- **Key Tech**:
  - **RAG Architecture**: LangChain + ChromaDB 기반 **7개 데이터 유형 통합 Retrieval 시스템 구축**
  - **Query Optimization**: Query Transformation + Multi-Query Retrieval 적용으로 **검색 정확도 및 문서 재현율 개선**
  - **Prompt Routing**: 질문 유형(추천 / 법령 / 일반 Q&A)에 따라 **프롬프트 자동 라우팅 설계**
  - **Chunking Strategy**: 문서 유형별 **맞춤 Chunk Size 및 Overlap 전략** 적용하여 검색 품질 향상
  - **Hallucination Mitigation**: LLM 응답을 **Context 기반으로 제한하는 프롬프트 설계**

- **Key Features**
  - 📄 창업 지원사업, 창업 공간, 법령, 실패 사례 등 **다중 문서 통합 검색**
  - 🔍 창업 정책 질의응답 **AI 챗봇 인터페이스**
  - 📚 모든 답변에 **참고 문서 출처 자동 표시**
  - 💬 Streamlit 기반 **대화형 사용자 인터페이스**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o--mini-412991?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-VectorDB-blue?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
---

### 5) 🚗 공공 자동차 등록 데이터 & 기업 FAQ 분석 플랫폼
> **Repository**: [🚗 공공 자동차 등록 데이터 & 기업 FAQ 분석 플랫폼](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN20-1ST-2TEAM.git)

국토교통부 자동차등록현황 공공데이터와 현대·기아 자동차 FAQ 데이터를 활용하여  
**자동차 등록 현황 분석과 고객지원 FAQ 구조 개선 방안을 도출한 데이터 분석 프로젝트**입니다.  
공공 통계 데이터 분석과 기업 FAQ 크롤링을 결합하여 **데이터 기반 고객지원 서비스 개선 가능성**을 제시했습니다.

- **Role**: Frontend Developer & Data Processing

- **Key Tech**:
  - **Public Data Pipeline**: 국토교통부 자동차 등록 API를 활용하여 **시도별 차량 등록 데이터를 수집·정규화 후 MySQL DB 구축**
  - **FAQ Crawling System**: Selenium 기반 **현대·기아 자동차 FAQ 데이터 자동 수집 및 텍스트 정제**
  - **Data Modeling**: 자동차 등록 데이터와 FAQ 데이터를 관리하기 위한 **ERD 설계 및 DB 테이블 구조 정의**
  - **Interactive Dashboard**: Streamlit 기반 **자동차 등록 현황 시각화 UI 설계 및 데이터 대시보드 구현**

- **Key Features**
  - 📊 **시도별 자동차 등록 현황 분석** (차종·연도별 데이터 구조화)
  - 🔍 현대·기아 **FAQ 데이터 크롤링 및 분석**
  - 🗂 자동차 등록 데이터 + FAQ 데이터 **통합 DB 구축**
  - 📈 Streamlit 기반 **데이터 분석 대시보드**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
---

### 6) 🎓 Drop Signal Detector: 학생 학업 중도 이탈 예측 시스템
> **Repository**: [🎓 Drop Signal Detector](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN20-2nd-4TEAM.git)

학생의 학적, 학업 성취도, 재정 상태, 가정 배경 등 다양한 데이터를 분석하여 **학업 중도 이탈(Dropout) 가능성을 조기에 예측하는 머신러닝 기반 Early Warning System**을 개발한 프로젝트입니다.  
EDA 기반 변수 분석과 머신러닝 모델 비교를 통해 **학생 이탈 위험을 사전에 감지할 수 있는 예측 모델과 Streamlit 대시보드**를 구축했습니다.

- **Role**: Data Engineer & ML Analysis / Frontend (Streamlit)

- **Key Tech**:
  - **EDA & Feature Analysis**: 상관관계 히트맵과 변수 중요도 분석을 통해 **학업 성취도 및 재정 요인이 Dropout에 미치는 영향 분석**
  - **Machine Learning Modeling**: Logistic Regression, RandomForest, LightGBM, XGBoost 등 **다양한 모델 성능 비교 및 최적 모델 선정**
  - **Imbalanced Data Handling**: `SMOTE` 및 `class_weight='balanced'` 적용하여 **Dropout 데이터 불균형 문제 해결**
  - **Interactive Dashboard**: Streamlit 기반 **학생 데이터 입력 → Dropout 확률 실시간 예측 시스템 구축**

- **Key Features**
  - 📊 **4,424명 × 35개 변수** 학생 데이터 기반 학업 이탈 예측
  - 🔍 학업 성취도, 재정 상태, 부모 학력 등 **주요 변수 영향 분석**
  - 🤖 RandomForest 기반 **Accuracy 0.91 / Recall 0.97 성능 달성**
  - 💻 Streamlit 기반 **Dropout Risk Prediction Dashboard**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

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

- **SK네트웍스 Family AI Camp 최종 프로젝트** | 최우수상 (2026.03)  
  - 주제: FTO 중심 특허·디자인 침해 리스크 판단 AI 에이전트

### 🎓 Education

- **SK Networks Family AI Camp (20기)** | AI/SW 개발자 과정 수료 (2025.09 - 2026.03)
- **LG Aimers** | AI 전문가 양성 과정 Phase 1·2·3 수료
- **Corning AI Challenge** | 키워드 기반 AI 뉴스 추천 시스템 개발
- **광명시 청소년 멘토링 프로그램 (IT 멘토)** | 중·고등학생 대상 IT 기초 교육 및 진로 멘토링 수행
- **서울여자대학교 바롬종합설계프로젝트** | 불법 동영상 유포 및 저작권 침해 방지 캠페인 기획·수행
- **서울여자대학교** | 디지털미디어학과/소프트웨어융합학과 졸업 (학점 /4.5)
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
