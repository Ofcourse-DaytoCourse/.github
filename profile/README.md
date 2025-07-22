# DayToCourse
**AI 기반 데이트 코스 추천 생성 서비스**

멀티 에이전트와 RAG 기반의 AI 챗봇 시스템으로, 사용자에게 맞춤형 데이트 코스를 추천해주는 서비스입니다.

---

## 📌 소개

**DayToCourse**는 자연어 기반 대화를 통해 사용자로부터 정보를 추출하고, 위치·날씨·관계·취향에 따른 최적의 데이트 코스를 제안하는 **개인화 추천 서비스**입니다.

> 데이트 계획이 막막한 연애 초보부터, 색다른 장소를 찾는 커플까지 모두를 위한 챗봇!

---

## 🧠 핵심 기능

- 🧾 **Main Service**: 사용자 입력을 구조화하고 전체 흐름을 조율
- 📍 **Place Service**: 지역/카테고리 기반 핫플 수집 및 좌표 추출
- 📚 **RAG**: 벡터 유사도 검색으로 추천 정확도 향상
- 💬 **자연어 인터페이스**: 설정 없이 자유롭게 대화로 정보 입력
- 💑 **코스 관리 및 공유 기능**: 커플 단위의 저장, 피드백, 공유 지원

---

## ⚙️ 기술 스택

| 영역 | 기술 |
|------|------|
| Backend | FastAPI, WebSocket |
| Frontend | next.js, Tailwind |
| AI | GPT-4, LangChain |
| DB | PostgreSQL |
| Vector DB | Qdrant |
| Data | Kakao API, 한국관광공사API |
| Infra | Docker, RunPod, Vercel |

---

## 📊 시스템 구조

- Service 아키텍처 (Main / Place / RAG )
- 구조화된 정보 추출 → 검색용 문장 생성 → 유사 장소 검색 → 최적 코스 구성


<img width="2529" height="1581" alt="image" src="https://github.com/user-attachments/assets/13b9051f-5817-4252-a3e0-7313ffe6689e" />


---

## 🚀 프로젝트 진행 상황

- [x] 시스템 설계 및 데이터 수집 완료
- [x] 서비스별 단위 구현 완료
- [x] 프론트/백 통합 완료
- [ ] 서비스 최종 테스트 진행 중
- [ ] 실시간 알림, BM 구축 진행 중

---

