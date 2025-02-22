# 멀티룸 예약 관리 플랫폼 개발

## 프로젝트 개요
**프로젝트 명**: 멀티룸 예약 관리 플랫폼 SW 개발  
**프로젝트 기간**: 2024-08-26 ~ 2024-09-25

### 목표
- 멀티룸 대여를 원하는 사용자를 타겟으로 진행
- 기존의 '회의실 닷컴' 어플에서 불편한 점 개선
- 사용자에게 직관적인 인터페이스 제공
- 관리자의 관리용이성 증가
- 공간 대여의 상용화

## 프로젝트 참여 인력

### 프로젝트 총괄표

| 성명     | 소속          | 역할                | 담당 업무                    |
|----------|---------------|---------------------|-----------------------------|
| 하동우   | 한국정보교육원 | Project Leader      | 클라이언트 개발 (고객용), 프로젝트 발표 |
| 김규택   | 한국정보교육원 | Project Assistant   | 서버 설계, 유효성 검사       |
| 김지학   | 한국정보교육원 | Project Assistant   | 클라이언트 개발 (관리자용), 클라이언트와 서버 연결 |
| 이한결   | 한국정보교육원 | Project Assistant   | DB 설계, 클라이언트와 서버 연결 |


## 프로젝트 시나리오

### 시나리오 1: 멀티룸 대여 플랫폼 (사용자)
#### 가정
- 멀티룸을 대여하여 사용하고자 하는 사용자를 대상으로 한 플랫폼 개발

#### 세부 내용
- **서버 안정성 및 보안성**:
  - 비밀번호 암호화 및 커넥션 풀 사용으로 보안성 향상
  - RSA와 AES 암호화 방식 적용
  - 세션 관리 및 사용자 인증 구현
- **기능**:
  - 원하는 조건(참석인원, 위치, 날짜, 시간)에 맞는 멀티룸 검색
  - 멀티룸 예약 및 예약 취소 기능
  - 예약한 멀티룸 확인 기능
  - 사용자 정보 수정 기능

### 시나리오 2: 멀티룸 대여 플랫폼 관리 (관리자)
#### 가정
- 멀티룸 대여 플랫폼을 관리하고자 하는 관리자 대상

#### 세부 내용
- **회원 관리**:
  - 사용자 정보 조회, 추가, 삭제
- **멀티룸 등록**:
  - 새로운 멀티룸 등록(이름, 수용인원, 상세정보 등)
  - 서버에 사진 업로드
- **멀티룸 관리**:
  - 등록된 멀티룸 정보 조회, 수정, 삭제
- **매출 관리**:
  - 추후 개발 예정

## 기술 스택
- **프론트엔드**: JavaFX (GUI 개발)
- **백엔드**: Java, 서버 설계 및 구현
- **DB**: JDBC, DAO 패턴, 정규화된 데이터베이스 설계
- **통신**: JSON 방식의 클라이언트-서버 통신
- **암호화**: RSA, AES (세션키 전달 및 양방향 데이터 통신 암호화)
## 결과
<p align="center">
  <img src="https://github.com/user-attachments/assets/1bcba072-4df0-4f77-8049-111efbe8b762" width="32%">
  <img src="https://github.com/user-attachments/assets/aef4f4da-73d9-4bbf-b695-92f36f306e7f" width="32%">
  <img src="https://github.com/user-attachments/assets/ba8acdea-498b-444e-a962-fbeacaf4c64e" width="32%">
  <img src="https://github.com/user-attachments/assets/958c4b6e-e55e-492f-b7c5-73078ad007da" width="32%">
  <img src="https://github.com/user-attachments/assets/63703927-13ba-4f7f-add6-d15e4cd393ba" width="32%">
  <img src="https://github.com/user-attachments/assets/caae3790-0de9-4538-a83a-fe409f0bb897" width="32%">
  <img src="https://github.com/user-attachments/assets/eaef6f30-b99c-4032-a29d-423c22294869" width="32%">
  <img src="https://github.com/user-attachments/assets/1a18d361-4702-4ba9-a53d-00e969d6f5a4" width="32%">
  <img src="https://github.com/user-attachments/assets/4a3b6c80-c051-4541-aaed-4384dde644fc" width="32%">
</p>


## 나의 역할 기여
- **DB 설계**
- **SQL문 작성**
- **클라이언트와 서버 연결**
- **로그인 메인화면, 마이페이지, 검색, 예약, 결제 화면 클라이언트 구성에 도움**
- **문서작성 (WBS, ER다이어그램, DD, 테이블명세서, SQL문)**
- **팀원들의 WBS관리**

