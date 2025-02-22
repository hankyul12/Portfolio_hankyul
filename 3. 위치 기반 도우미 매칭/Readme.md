# 헬프미! (Help me!)

## 프로젝트 개요
**프로젝트 명**: 헬프미! (Help me!)  
**프로젝트 기간**: 2025.01.17 - 2025.02.13

### 목표
- 의뢰자의 문제를 빠르게 해결
- 파트너의 수익 창출 기회 제공
- 위치 기반 서비스 제공

### 프로젝트 시나리오

#### 시나리오 1
- **가정**: 혼자 해결하지 못하거나, 시간이 없어 다른 사람에게 도움을 요청
- **대상**: 헬프미 앱을 사용하여 주변 사람들의 도움을 받으려는 사용자 (의뢰자)
- **세부내용**:
  - 의뢰 글 등록 및 조회
  - 카카오 지도 통해 위치 등록
  - 사진 업로드 및 파트너 매칭
  - 마이 페이지에서 활동 정보 확인

#### 시나리오 2
- **가정**: 간단한 용돈벌이를 위해 주변 사람들을 도와주고자 하는 경우
- **대상**: 헬프미 앱을 사용하여 도움을 주고자 하는 사용자 (파트너)
- **세부내용**:
  - 의뢰 글 조회 및 신청
  - 의뢰자와 매칭 후 도움 제공

## 프로젝트 수행 요건
### 서버 설계
- application/json 및 multipart/form-data API 제공
- REST API 라우팅 및 의뢰 글 관리
- 토큰 기반 사용자 인증 처리
- JPA를 활용한 Object-RDB 매핑

### 클라이언트 설계
- 토큰 기반 인증 방식 통합
- Flutter를 사용한 모바일 UI 제공
- 의뢰 정보 관리 기능 구현

### DB 설계
- 상태 변경에 대한 인덱스 처리
- Native Query를 통한 쿼리 최적화

## 프로젝트 팀
### 프로젝트 참여 인력
| 성명     | 소속          | 역할                | 담당 업무                         |
|----------|---------------|---------------------|----------------------------------|
| 하동우   | 한국정보교육원 | Project Leader      | Front-end (UI 개발)              |
| 김규택   | 한국정보교육원 | Project Assistant   | Back-End (서버 구성, DB 설계)     |
| 김지학   | 한국정보교육원 | Project Assistant   | Front-end (UI 개발)              |
| 이한결   | 한국정보교육원 | Project Assistant   | Back-End (서버 연동, DB 설계)     |

## 기능 설명

### 회원
- 구글 소셜 로그인 기능

### 의뢰
- 의뢰 등록, 정보 입력, 사진 업로드, 위치 설정 가능

### 의뢰 신청
- 다른 사용자(예비 파트너)가 의뢰자에게 도움을 주겠다고 신청

### 마이페이지
- 의뢰/파트너 활동 내역, 신청 내역, 자신의 글 수정 및 삭제 기능

### 요청 알림
- 의뢰자와 파트너가 신청/수락/거절을 수행할 때 상대방에게 푸시 알림을 전송
- 의뢰자는 의뢰 신청한 사람의 정보를 확인 후 수락 또는 거절 선택 가능

### 매칭
- 의뢰자가 파트너 신청을 수락한 경우, 서로의 간략한 위치 정보를 표시
- 의뢰가 정상적으로 마무리(완료)되거나 도중에 문제가 발생한 경우(중단)를 처리

### 위치 서비스 제공
- 모바일 기기의 GPS를 활용한 위치 서비스 기능
- 앱 사용자와의 위치를 계산하고 표기
- 지도 활용 정보 제공


## 기술 스택
- **Backend**: Spring Boot (REST API)
- **Frontend**: Flutter
- **Database**: MySQL
- **Collaboration**: Swagger, GitHub
- **Dev-Tools**: IntelliJ IDEA, Android Studio
- **Push Notifications**: Firebase
- **OAuth**: Google Cloud로 구글 소셜 로그인 기능 사용
- **Map Integration**: KakaoMap API를 사용하여 지도 출력

## 화면
<p align="center">
  <img src="https://github.com/user-attachments/assets/2788e360-69aa-4ba9-a53f-6297d574bf7e" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/a7def966-f9b3-4b33-afc1-c3bbafbd63be" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/7d64300c-ae9a-4faa-aa58-dda14fa5e2d5" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/79c264c4-5b4d-4be4-86e0-33dea64eedb1" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/043d06c4-fc12-4bc4-a6fb-257aea2337bc" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/467c4222-e21e-4fd2-8c96-3acccfbab13e" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/558cfaf9-3cca-4b73-9ede-311ffe27983e" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/af7868ae-3a9c-43f8-9961-d461fdcdd604" width="32%" height="150px">
</p>


## 나의 역할 기여
- **DB 설계**
- **SQL문 작성**
- **클라이언트와 서버 연결 작업 (REST API 사용)**
- **마이페이지, 매칭 화면, 수락/거절기능 클라이언트 구성에 도움**
- **문서작성 (계획보고서, 결과보고서)**

