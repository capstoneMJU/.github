# 🧪 Capstone 4조 - 제로픽 (ZeroPick)

> **제로음식, 스마트하게 픽(Pick)하자!**  
> 사진 한 장으로 원재료와 영양성분까지 분석해주는 AI 기반 제로식품 탐지 프로젝트

---

## 👨‍👩‍👧‍👦 팀 소개 - 캡스톤디자인 4조

## 👨‍💻 프론트엔드

| 이름 | 담당 영역 |
|------|------------|
| 👤 김규리 | OCR, 레시피, 유저 , 프론트엔드 팀장|
| 👤 임용진 | 커뮤니티  |

## 🖥️ 백엔드

| 이름 | 담당 영역 |
|------|------------|
| 👤 배석현 | 식품 DB 관리, 커뮤니티,뉴스, 이미지검색 |
| 👤 백가현 | 레시피, 유저 관리 |
| 👤 이지수 | OCR, AWS 관리 |

> 🔁 역할은 프로젝트 상황에 따라 유동적으로 변경될 수 있습니다.

---

## 📌 프로젝트 소개

제로픽(ZeroPick)은 제로음식의  
**사진을 찍으면 OCR이 인식하여 식품 정보를 가져와서 영양성분과 원재료 정보를 분석**해주는 프로젝트입니다.  

이를 통해 사용자에게 **더 나은 식품 선택**을 돕고,  
**제로식품 시장의 성장**에 기여하고자 합니다.

---

## 🔍 주요 기능

- 📸 음식 사진 촬영 및 업로드
- 🧠 AI 기반 제로식품 인식 및 성분 분석
- 🍽️ 영양 성분 정보 시각화
- 🏷️ 제로 식품 여부 판별 및 추천

---

## 🛠️ 기술 스택

| 분야 | 기술 |
|------|------|
| Frontend | React |
| Backend | Spring Boot, JPA, MySQL |
| Infra | GitHub Actions,  AWS|

---

## 🌱 프로젝트 목표

- ✅ 영양성분 및 성분 자동 분석 정확도 90% 이상 달성
- ✅ 사용자 친화적인 제로음식 탐색 UI 제공
- ✅ 오픈데이터 기반의 영양정보 DB 구축

---

## 📂 레포지토리 구조

## 📂 레포지토리 구조

```plaintext
backend/
└── domain/
    ├── auth/
    │   ├── controller/
    │   ├── dto/
    │   ├── repository/
    │   └── service/
    ├── board/
    │   ├── controller/
    │   ├── dto/
    │   ├── entity/
    │   └── service/
    ├── common/
    │   ├── error/
    │   ├── exception/
    │   ├── BaseEntity.java
    │   └── ResponseDto.java
    ├── imagesearch/
    │   ├── controller/
    │   └── service/
    ├── news/
    │   ├── config/
    │   ├── controller/
    │   ├── dto/
    │   └── service/
    ├── nutrition/
    │   ├── config/
    │   ├── controller/
    │   ├── dto/
    │   ├── entity/
    │   └── service/
    ├── ocr/
    │   ├── controller/
    │   ├── dto/
    │   ├── entity/
    │   └── service/
    ├── recipe/
    │   ├── controller/
    │   ├── domain/
    │   ├── dto/
    │   ├── repository/
    │   └── service/
    ├── sugarsubstitute/
    │   ├── dto/
    │   └── entity/
    └── user/
        ├── controller/
        ├── domain/
        ├── dto/
        ├── repository/
        └── service/

global/
├── auth/
├── config/
└── s3/


