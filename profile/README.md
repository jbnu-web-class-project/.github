# 웹서비스 설계 프로젝트

## 프로젝트 개요
- **시작일**: 2024년 10월 9일
- **요구사항**: 기능 및 비기능 요구사항, Use Case (정의서), Class Diagram, Sequence Diagram, UI 정의서, Activity Diagram

## 프로젝트 목표
 저희는 울산 HD 축구팀과 기아 타이거즈 야구팀을 좋아하는 팀원들이 함께 모여, 축구와 야구를 비롯한 프로스포츠 팬들을 위한 쇼핑몰을 만들게 되었습니다.

이 쇼핑몰은 사용자가 응원하는 팀을 선택하면 그 팀에 맞는 맞춤형 홈페이지를 제공하고, 쇼핑은 물론 중고거래와 커뮤니티 활동까지 한곳에서 즐길 수 있도록 설계하였습니다.

당근마켓이 이웃 간의 중고거래를 중심으로 한다면, 저희는 같은 팀을 응원하는 팬들끼리의 중고거래와 소통에 초점을 맞췄습니다.

가입 시 응원팀을 설정하면 홈페이지가 자동으로 사용자 취향에 맞게 꾸며지고, 쇼핑, 중고거래, 커뮤니티 기능을 통해 같은 팀 팬들과 더 가까워질 수 있는 공간을 제공합니다. 저희는 팬들이 함께 어울리고, 팀을 응원하며, 다양한 활동을 즐길 수 있는 특별한 플랫폼을 만들어가고자 합니다.

## 프로젝트 관리
- **프로세스**: Agile
- **회의**: 정기 회의 진행
- **참여자**
  - **허완**
  - **엄성혁**

## 기술 스택

### 🖥️ 프론트엔드 (Frontend)
| 기술       | 설명                   |
|------------|------------------------|
| ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white) | 사용자 인터페이스 구축 |
| ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) | UI/UX 디자인 도구 |

### ⚙️ 백엔드 (Backend)
| 기술       | 설명                   |
|------------|------------------------|
| ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) | 서버 사이드 프레임워크 |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) | 데이터베이스 관리 시스템 |

### ☁️ 인프라 (Infrastructure)
| 기술         | 설명                        |
|--------------|-----------------------------|
| ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) | 컨테이너 오케스트레이션 |
| ![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat&logo=istio&logoColor=white) | 서비스 메시 설정 |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) | 컨테이너 관리 도구 |
| ![Harbor](https://img.shields.io/badge/Harbor-60B932?style=flat&logo=harbor&logoColor=white) | 컨테이너 이미지 저장소 |

### 🛠️ CI/CD 및 관리
| 기술          | 설명                 |
|---------------|----------------------|
| ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) | 버전 관리 시스템 |
| ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) | CI/CD 자동화 도구 |
| ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white) | GitOps 기반 배포 도구 |
| ![ERD Cloud](https://img.shields.io/badge/ERD%20Cloud-FF6F00?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij4KICAgIDxwYXRoIGQ9Ik04Ni4xMTQgMTUuMzc3QzgwLjE2IDkuNDI2IDcxLjk4MyA2IDYzLjUgNmMtOC40ODMgMC0xNi42NiAzLjQyNi0yMi42MTEgOS4zNzdsLTEuMTg5IDEuMTg5IDE5LjI2NyAxOS4yNjdMNDQuNCAyNS4zNDVjNC4zOTUtNC4zOTUgMTAuMjgzLTYuODU1IDE2LjA5OS02Ljg1NSAzLjc2MiAwIDcuMzM5IDEuMDE5IDEwLjQ4MSAyLjk0OUw2Ni4xMSAzOC4wOTVsLTMwLjcxNiAzMC43MTZhMzYuMTEzIDM2LjExMyAwIDAwMTEuMTQ0IDUuNzZsNDYuMDY5IDQ2LjA3YzQuMzQ4IDQuMzQ4IDkuOTY1IDYuNzI2IDE1Ljk2NiA2LjcyNiA2LjA1MSAwIDExLjc1OS0yLjQ3NyAxNi4xNzEtNi44NTVsMS4xODktMS4xODktMTkuMjY3LTE5LjI2N2w5LjgxOC05LjgxOGM1Ljk0OCA1Ljk0OCA1LjQ4MiAxNS4zOTctLTEuMTk4IDIxLjA3NWwtNDYuMDY5IDQ2LjA3Yy0zLjEyMyAzLjEyMy03LjI0MSA0LjY4OC0xMS40MzEgNC42ODgtNC4xODkgMC04LjMwOC0xLjU2NC0xMS40MzEtNC42ODhsLTQ2LjA3LTQ2LjA3Yy01Ljk0OC01Ljk0OC01LjQ4Mi0xNS4zOTcgMS4xOTgtMjEuMDc1bDIxLjA3NS0yMS4wNzUtMTkuMjY3LTE5LjI2N0wxNC4wOTIgMTUuMzc3QzUuNTg5IDIzLjg4IDAuNSAzNC4xMTYgMCA0My41YzAgOS4zODIgNS42MzkgMTkuNjczIDE1LjM3NSAyOS40MTNsNDYuMDcgNDYuMDdjOS43MzYgOS43MzYgMjAuMDMxIDE1LjM3NSAyOS40MTMgMTUuMzczIDkuMzgyIDAgMTkuNjc1LTUuNjM5IDI5LjQxMy0xNS4zNzNsNDYuMDctNDYuMDdjOS43My05LjczNiAxNS4zNzMtMjAuMDMxIDE1LjM3My0yOS40MTMgMC05LjM4Mi01LjYzOS0xOS42NzMtMTUuMzczLTI5LjQxM3oiIGZpbGw9IiNGRkYiLz4KPC9zdmc+) | ERD 설계 도구 |

### 📜 참고 링크
#### 웹사이트 도메인 : http://heim.hwys.xyz/
#### 노션 링크 : https://www.notion.so/hodu26/bf9f047b08594d61b0cfdf7187ff0054
#### 피그마 링크 : https://www.figma.com/design/94VkK2AepmfsD0JAo5iRKm/shop?t=pB0jxT7VeIulyMfZ-0
#### 정리 문서 : https://docs.google.com/document/d/1Bb5gr8THt_E3g8s91y0ZwCa6x4rw_odxzHxnKjOiB3o/edit?tab=t.0

## 프로젝트 구성
### 주요 기능
- **상품관리 서비스**: 상품 관련 데이터 처리 및 관리
- **주문관리 서비스**: 주문 데이터 처리 및 관리
- **회원관리 서비스**: 사용자 데이터 처리 및 관리
- **경매관리 서비스**: 경매 기능 지원

### 인프라
- **CI/CD 구축**: Jenkins, ArgoCD 사용
- **보안**: Kubernetes Security 설정
- **모니터링**: 서비스 메시 설정

## UI 구성 (FIgma)
<div align="left">
  <img src="https://github.com/user-attachments/assets/d8e7dba6-06fb-4ef4-b184-15d3b36641b8" width="70%" alt="Image 1">
</div>

## DB 구성 (ERD CLOUD)
<div align="left">
  <img src="https://github.com/user-attachments/assets/fa3a7f6a-6db8-4559-ae6a-3088faa09708" width="70%" alt="Image 1">
</div>

## CICD 및 MSA 구상도
<div align="left">
  <img src="https://github.com/user-attachments/assets/ceb9d4c8-6ba5-4ae3-ab58-f296dbd0474e" width="70%" alt="Image 1">
</div>
<div align="left">
  <img src="https://github.com/user-attachments/assets/c607f19a-f7d0-4623-8ca7-08b010d7da59" width="70%" alt="Image 2">
</div>


## Sprint 계획
<div align="left">
  <img src="https://github.com/user-attachments/assets/164101bb-628b-4001-b731-00e28e7feaee" width="70%" alt="Sprint Plan Image 1">
</div>
<div align="left">
  <img src="https://github.com/user-attachments/assets/90c58818-f9db-45f0-ac0b-df787aa75e15" width="70%" alt="Sprint Plan Image 2">
</div>

### 플랜 (Plan)
- **주제 선정**: 완료 (2024/10/10 - 2024/10/12)
- **프로젝트 구상도 작성**: 진행 중 (2024/10/13)
- **Figma 디자인 작성**: 진행 중 (2024/10/23 - 2024/10/28)

### 프론트엔드 (Frontend)
- **프론트엔드 개발 (React)**: 진행 중 (2024/10/24 - 2024/10/28)

### 백엔드 (Backend)
- **상품관리 서비스 개발 (Nest.js)**: 진행 중 (2024/10/28)
- **주문관리 서비스 개발 (Nest.js)**: 진행 중 (2024/10/28)
- **회원관리 서비스 개발 (Nest.js)**: 완료 (2024/10/28)
- **경매관리 서비스 개발 (Nest.js)**: 진행 중 (2024/10/28)
- **DB 서버 구축**: 완료 (2024/10/10 - 2024/10/27)

### 인프라 (Infra)
- **CI/CD 구축**: 완료 (2024/10/10 - 2024/10/12)
- **K8S 보안 설정**: 완료 (2024/10/11 - 2024/10/12)
- **서비스 메시 설정**: 완료 (2024/10/26 - 2024/10/27)

## 타임라인
- 전체 일정은 스프린트 단위로 관리하며, 주요 일정은 다음과 같습니다.
  - 2024/10/10 ~ 2024/10/12: 주제 선정 및 CI/CD 구축
  - 2024/10/10 ~ 2024/10/27: DB 서버 구축
  - 2024/10/13: 프로젝트 구상도 작성
  - 2024/10/24 ~ 2024/10/28: 프론트엔드 및 백엔드 서비스 개발
  - 

## 기타 참고사항
- **ERD Cloud**: 데이터베이스 설계
- **GitHub**: 버전 관리 및 코드 리뷰
- **기타 문서**: 프로젝트 관련 문서 관리

---

프로젝트와 관련한 질문이 있다면, 언제든지 문의해 주세요!

