<p align="center">
LLM의 답변을 그대로 신뢰하지 않고, <b>검증 가능한 파이프라인</b>으로 설계하는 데 집중합니다.<br/>
AI/LLM 백엔드 개발 직무로 합류할 팀을 찾고 있습니다.
</p>

<p align="center">
  <a href="https://shrub-scaffold-39b.notion.site/RAG-AI-296d540ee62580d0a968ee9d21142157">
    <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/진성-김-7a14b0392">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## 🛠 기술 스택

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![Embedding Models](https://img.shields.io/badge/Embedding%20Models-4051B5?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-000000?style=flat-square)
![Librosa](https://img.shields.io/badge/Librosa-4051B5?style=flat-square)

**Data Analysis**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square)

**Backend**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 🚀 Featured Project

### 💻 [PC 견적 추천 AI 시스템](https://github.com/Kimooooooo/pc_assembly)

> LangGraph + OpenAI API + ChromaDB RAG 기반, 예산·용도 맞춤형 PC 부품 견적 추천 시스템

사용자가 예산·용도·자유형식 참고사항을 입력하면 **가성비형 · 밸런스형 · 최고스펙형** 3종 견적을 실시간 생성합니다.

- **LangGraph 6노드 파이프라인**: 분석 → 예산 배분 조정 → 벡터 검색 → 견적 생성 → **환각 검증** → 포맷의 상태 기반 오케스트레이션
- **검증 레이어 설계**: LLM이 생성한 견적을 메타데이터 기준으로 Python이 재검증하고, 신뢰도 0.6 미만이면 LLM 폴백 + 재시도(최대 2회)까지 태우는 구조 → LLM 출력을 그대로 믿지 않는다는 원칙을 코드로 구현
- **한국어 특화 임베딩**: `dragonkue/snowflake-arctic-embed-l-v2.0-ko` (1024-dim) 채택 이유를 벤치마킹 후 문서화
- **서버 사이드 가격 재계산**: 총액·이미지 주입을 LLM이 아닌 서버 로직에서 처리해 환각으로 인한 금액 오류를 원천 차단

`Django` `LangGraph` `LangChain` `ChromaDB` `OpenAI GPT-4o-mini` `Tailwind CSS` `Chart.js`

---

## 📂 Other Projects

### 🎤 [AI 면접 피드백 시스템](https://github.com/Kimooooooo/Ai_interview) (팀 프로젝트)

실시간 멀티모달 면접 분석 서비스. 음성 감정(CNN-BiLSTM)·영상 자세/표정(DeepFace + MLP)을 분석해 LLM이 종합 리포트를 생성합니다.

**담당**: LLM 기반 피드백 엔진 및 시스템 통합
- 채용공고 URL 분석 기반 맞춤형 질문 동적 생성
- 음성·영상 멀티모달 데이터를 LLM 평가 컨텍스트로 변환하는 파이프라인 구축
- STAR 기법을 적용한 구조화된 JSON 피드백 리포트 생성

`FastAPI` `MySQL` `JWT` `WebSocket` `OpenAI API` `NAVER CLOVA STT` `React`


### 🦾 로봇 에이전트 시스템 (팀 프로젝트)

로봇 에이전트의 판단·행동 로직에 검증 계층을 설계해 신뢰도를 확보하는 데 집중한 프로젝트입니다. *(저장소 정리 후 링크 추가 예정)*

### 🦺 산업 안전 챗봇 (팀 프로젝트, Private)

현장 안전 규정 기반 챗봇으로, LLM 응답의 사실 검증 레이어를 설계했습니다. *(비공개 레포지토리)*

---
📊 GitHub 통계
<p align="center"> <img src="https://img.shields.io/github/stars/Kimooooooo?style=flat-square&label=Stars" /> <img src="https://img.shields.io/github/followers/Kimooooooo?style=flat-square&label=Followers" /> </p>
