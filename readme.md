## 📘 교과목명: FastAPI와 Streamlit을 활용한 AI 웹 애플리케이션 개발

### 강의 개요
FastAPI와 Streamlit을 활용해 머신러닝 모델을 포함한 웹 서비스를 개발하고 배포하는 기술을 습득한다.  
FastAPI로 API 서버를 만들고, Streamlit으로 시각적 인터페이스를 제공하며, LLM 및 외부 API와 연계하여 실전 웹 서비스를 구현한다.

---

| 주차 | 주제 | 이론 (40분) | 실습 (110분) |
|------|------|-------------|--------------|
| 1주차 | 전체 구조 소개 및 웹앱 개요 | Web Framework 비교, API vs UI | Python 환경 세팅, FastAPI/Streamlit Hello App |
| 2주차 | FastAPI 기초 | FastAPI 라우팅, Path/Query 이해 | `/predict`, `/status` 엔드포인트 실습 |
| 3주차 | Streamlit 기초 | UI 구성요소 소개, `st.write`, `st.button` 등 | 기본 입력 → 출력 앱 실습 |
| 4주차 | FastAPI + ML 모델 서빙 | 모델 로딩 및 추론 API 설계 | Iris 분류기 API 구축 (`1126_05_fastapi_iris_server.ipynb`) |
| 5주차 | Streamlit + ML 모델 시각화 | Pandas, Matplotlib 연동 | 파일 업로드 + 시각화 앱 (`Ch_03_그래프와_워드클라우드.ipynb`) |
| 6주차 | FastAPI 비동기 처리 및 상태 관리 | `async`, BackgroundTask, CORS | 비동기 응답, 로깅 기능 실습 |
| 7주차 | Streamlit 멀티페이지 앱 설계 | 앱 구조 분할, session_state | 시각화 + 모델 예측 멀티탭 구성 |
| 8주차 | FastAPI-Streamlit 통합 I | REST API → Streamlit 연결 | FastAPI 결과를 Streamlit에 표시 |
| 9주차 | FastAPI-Streamlit 통합 II | 내부 API 호출 최적화, 에러 핸들링 | 모델 결과 시각화 통합 앱 완성 |
| 10주차 | 외부 API 연동 (OpenWeather 등) | FastAPI + 외부 API 연계 구조 | 실시간 날씨 조회 앱 실습 |
| 11주차 | LLM 연동 I: Huggingface & FastAPI | Transformer 모델 서빙 | 감성분석 API 구성 (`huggingface_transformer.ipynb`) |
| 12주차 | LLM 연동 II: Streamlit UI 통합 | LLM 응답 스트리밍, 문장 생성 UI | 실시간 LLM 챗봇 인터페이스 |
| 13주차 | LangChain & RAG 구조 설계 | LLM 응답 강화 기법, 벡터DB 기초 | FastAPI로 LangChain 서버 만들기 (`1210_04_RAG.ipynb`) |
| 14주차 | 종합 프로젝트 개발 | 기획서 발표, 기능 분담 | 팀별 앱 개발, 기능 구현 피드백 |
| 15주차 | 최종 프로젝트 발표 및 시연 | 팀별 발표, 배포 시연 | 데모 시연 및 피드백, 코드 리뷰 |

---

### 📦 주요 실습자료
- FastAPI 관련: `1126_04_FastAPI.ipynb`, `1203_04_FastAPI.ipynb`, `fastapi_iris_server.ipynb`  
- Streamlit 관련: `working_with_text_data.ipynb`, `Ch_03_그래프와_워드클라우드.ipynb`, `huggingface_transformer.ipynb`  
- LLM 관련: `1210_04_RAG.ipynb`, `1210_05_RAG_chatGPT.ipynb`, Gemini 연동 예제

---

### 🎯 학습 목표
- FastAPI를 이용해 AI 기반 REST API 서버를 설계하고 구현할 수 있다.  
- Streamlit을 활용하여 데이터 기반 웹 인터페이스를 구축할 수 있다.  
- 두 기술을 통합하여 상호작용 가능한 웹 서비스를 만들고, 실제 AI 모델 또는 LLM을 연동할 수 있다.  
- 실전 프로젝트를 통해 기획부터 배포까지의 전 과정을 경험할 수 있다.


