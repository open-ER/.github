# 🍷 openER

**openER**는 다양한 조건을 기반으로 와인을 탐색하고 비교할 수 있는 웹 서비스입니다.  
사용자가 맛 프로필, 가격, 국가, 품종 등의 필터를 통해 원하는 와인을 쉽게 찾고, 여러 와인을 한눈에 비교할 수 있도록 설계된 프로젝트입니다.

https://open-er-lake.vercel.app/

<img width=50% alt="Screenshot 2026-02-09 at 2 28 00 PM" src="https://github.com/user-attachments/assets/1e1af72a-050c-4c35-8656-2d42a5cf1a92" />
<img width=50% alt="Screenshot 2026-02-09 at 2 28 19 PM" src="https://github.com/user-attachments/assets/c851311e-dd66-42fc-bad6-658faee24309" />
<img width=50% alt="Screenshot 2026-02-09 at 2 29 12 PM" src="https://github.com/user-attachments/assets/aafbcc74-0835-486b-a2fa-87a0ef279294" />
<img width=50% alt="Screenshot 2026-02-09 at 2 29 26 PM" src="https://github.com/user-attachments/assets/7bfbfe68-d66b-4587-897a-a826fa60b3ff" />
<img width=50% alt="Screenshot 2026-02-09 at 2 29 42 PM" src="https://github.com/user-attachments/assets/5d079525-abec-4947-a9dd-92411c411dda" />
<img width=50% alt="Screenshot 2026-02-09 at 2 29 49 PM" src="https://github.com/user-attachments/assets/80173491-93f5-44ed-9ad9-b08adf6b3142" />
<img width=50% alt="Screenshot 2026-02-09 at 2 29 58 PM" src="https://github.com/user-attachments/assets/cf26bf1d-0355-47f0-8f5f-322af43de1f2" />
<img width=50% alt="Screenshot 2026-02-09 at 2 30 09 PM" src="https://github.com/user-attachments/assets/36397b9a-bd5a-454f-ab8e-68fec8f54f67" />


## 🌐 서비스 개요

- 다양한 조건 기반 와인 검색 및 탐색
- 실시간 필터링을 통한 맞춤형 결과 제공
- 여러 와인을 선택하여 비교 가능
- 직관적인 UI를 통한 사용자 경험 중심 설계


## 🧩 Repository 구성

이 Organization은 프론트엔드와 백엔드를 분리하여 관리합니다.

### 📦 Frontend
React 기반 사용자 인터페이스를 담당합니다.

주요 역할:
- 와인 목록 화면 구성
- 필터 UI 및 실시간 검색 UX 구현
- 와인 비교 페이지
- 반응형 UI 설계

기술 스택:
- React
- TypeScript
- Vite

### ⚙️ Backend
와인 데이터 조회 및 필터링을 처리하는 API 서버입니다.

주요 역할:
- 전체 와인 목록 조회
- 조건 기반 필터링 API
- 키워드 검색 API
- 와인 비교 API
- 필터 옵션 제공 API

기술 스택:
- Node.js
- Express
- MongoDB Atlas
- Mongoose
- Swagger
- Render (배포)


## 🏗 아키텍처 구조
```
[ React Frontend ]
       ↓
  REST API 통신
       ↓
[ Node.js Backend ]
       ↓
[ MongoDB Atlas ]
```
- 프론트엔드는 사용자 인터페이스 및 상태 관리를 담당
- 백엔드는 데이터 처리 및 API 제공
- MongoDB는 와인 데이터를 저장하는 DB 역할



## 🚀 주요 기능

- 🍷 전체 와인 카탈로그 조회
- 🎛 다양한 필터 기반 탐색
- 🔍 키워드 검색 (이름, 국가, 품종, 향 등)
- 📊 와인 비교 기능
- 📄 페이지네이션 기반 데이터 로딩 (더보기 방식)


## 🎯 프로젝트 목표

- 사용자 중심의 와인 탐색 경험 제공
- 다양한 조건을 조합한 동적 필터링 시스템 구현
- 프론트엔드–백엔드 협업 구조 설계 경험
- 실제 서비스 배포 경험 축적


## 🧠 구현 포인트

- 동적 필터 쿼리를 통한 맞춤형 데이터 조회
- 페이지네이션 기반 성능 최적화
- 실시간 검색 UX 지원
- API 문서 자동화 (Swagger)
- 클라우드 DB 및 서버 배포 경험


## 📌 향후 확장 아이디어

- 추천 와인 기능
- 정렬 옵션 추가 (가격 / 평점 등)
- 사용자 리뷰 기능
- 개인화된 와인 추천 시스템


## 👥 Team

- Frontend: UI/UX 및 사용자 인터페이스 구현
- Backend: API 설계 및 데이터 처리
- Database: MongoDB Atlas 기반 데이터 관리

| 나현우 | 조성래 | 한여진 | 서다솜 |
|:--------:|:--------:|:--------:|:--------:|
| [@HyeonWooNa0861](https://github.com/HyeonWooNa0861) |  [@Sungrae24](https://github.com/Sungrae24) |[@hanyj0317](https://github.com/hanyj0317) |[@dasom040819](https://github.com/dasom040819) |
| 국민대학교<br>인공지능전공 | 국민대학교<br>소프트웨어전공 |국민대학교<br>소프트웨어전공 |국민대학교<br>소프트웨어전공 |
| UI/UX Design<br>Frontend | UI/UX Design<br>Frontend | Database <br>Backend|Data Processing |

openER는 협업을 기반으로 설계된 프로젝트이며,  
실제 서비스 구조를 경험하고 확장 가능성을 고려하여 개발되었습니다.
