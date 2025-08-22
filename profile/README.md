# DayToCourse
**AI 기반 데이트 코스 추천 생성 서비스**

사용자 요청 기반의 AI 데이트 코스 추천 시스템으로, 사용자에게 맞춤형 데이트 코스를 추천해주는 서비스입니다.

---

## 📌 소개

**DayToCourse**는 자연어 기반 대화를 통해 사용자로부터 정보를 추출하고, 위치·날씨·관계·취향에 따른 최적의 데이트 코스를 제안하는 **개인화 추천 서비스**입니다.


---


## 🧠 핵심 기능

- 🧾 **Main Service**: 사용자와 대화를 통해 데이터 수집 및 흐름 조율
- 📍 **Place Service**: 지역/카테고리 기반 인기 장소 수집 및 좌표 추출
- 📚 **Date-Course Service**: 벡터 유사도 기반으로 추천 근거 생성
- 💬 **자연어 인터페이스**: 설정 없이 자유롭게 대화로 정보 입력
- 💑 **코스 관리 및 공유 기능**: 연인 간의 코스 저장, 피드백, 공유 지원

---

## ⚙️ 기술 스택

| 영역 | 기술 |
|------|------|
| Backend | FastAPI, WebSocket |
| Frontend | next.js, Tailwind |
| AI Model | GPT-4 |
| DB | PostgreSQL |
| Vector DB | Qdrant |
| Infra | Docker, RunPod, Vercel |

---

## 📊 시스템 구조

- Service 아키텍처 (Main / Place / Date-Course )
- 구조화된 정보 추출 → 검색용 문장 생성 → 유사 장소 검색 → 최적 코스 구성


![프레임 3](https://github.com/user-attachments/assets/96c13962-f9b4-437b-9f40-24203d788ccb)


---

## 🚀 프로젝트 진행 상황

- [x] 시스템 설계 및 데이터 수집 완료
- [x] 서비스별 단위 구현 완료
- [x] 프론트/백 통합 완료
- [x] 서비스 최종 테스트 완료
- [x]  BM 구축 완료


---

## 📖 [Wiki](https://github.com/Ofcourse-DaytoCourse/.github/wiki/1.-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B0%9C%EC%9A%94)

- [1. 프로젝트 개요](https://github.com/Ofcourse-DaytoCourse/.github/wiki/1.-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B0%9C%EC%9A%94)
- [2. 시스템 구조](https://github.com/Ofcourse-DaytoCourse/.github/wiki/2.-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EA%B5%AC%EC%A1%B0)
- [3. 기술 스택](https://github.com/Ofcourse-DaytoCourse/.github/wiki/3.-%EA%B8%B0%EC%88%A0-%EC%8A%A4%ED%83%9D)


