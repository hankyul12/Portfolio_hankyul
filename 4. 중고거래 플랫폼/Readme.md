# RUR – ReUse Rover

## 프로젝트 개요
**프로젝트 명**: RUR – ReUse Rover  
**프로젝트 기간**: 2023.11.21 - 2023.12.19.

### 목표
- 중고 거래를 위한 데이터 관리 체계 구축
- 사용자에게 편리한 UI 제공으로 거래의 안정성 증대
- 흥정 가능한 중고 거래 사이트 개발

### 프로젝트 시나리오

#### 시나리오 1
- **가정**: 중고 제품을 판매하고자 하는 판매자가 물품 정보를 등록
- **대상**: 중고 거래를 원하는 사용자 (판매자)
- **세부내용**:
  - 판매 물품 등록 및 정보 입력
  - 사진 업로드 및 가격 설정
  - 등록한 물품 목록 조회

#### 시나리오 2
- **가정**: 중고 물품을 구매하고자 하는 구매자가 검색 및 구매
- **대상**: 중고 거래를 원하는 사용자 (구매자)
- **세부내용**:
  - 물품 검색 기능 제공
  - 물품 구매 및 흥정 기능 지원
  - 마이 페이지에서 거래 내역 확인


## 프로젝트 팀
### 프로젝트 참여 인력
| 성명       | 역할                | 담당 업무                      |
|------------|---------------------|-------------------------------|
| 김태호     |  Project Leader      | Front-end(UI 개발, 발표)           |
| 이한결     |  Project Assistant   | Front-end,Back-End (UI개발, DB 설계) |
| 이한음     |  Project Assistant   | Front-end (CSS, 문서작성)            |

## 기능 설명

### 회원
- 회원가입 기능

### 물품 등록
- 판매자가 물품 등록을 위한 정보 입력 및 사진 업로드 가능

### 검색
- 게시글 제목 검색 기능 제공

### 물품 구매
- 구매자가 물품 구매 버튼 클릭 시 거래 진행

### 물품 흥정
- 구매자가 판매자에게 흥정 요청 가능

### 마이페이지
- 사용자가 등록한 물품 정보 확인 및 수정, 삭제 기능 제공

### 시스템 설계
- **회원 가입**: 계정이 없는 사용자가 회원가입을 진행
- **물품 등록**: 로그인한 사용자가 물품 정보를 입력하여 등록
- **물품 검색**: 사용자가 입력한 키워드를 기반으로 물품 검색
- **물품 구매**: 사용자가 선택한 물품을 구매
- **물품 흥정**: 구매자가 원하는 가격으로 흥정 요청

## 기술 스택
- **Backend**: tomcat 8.5
- **Frontend**: HTML5, CSS, JSP
- **Database**: MySQL
- **Collaboration**: GitHub
- **Dev-Tools**: Eclipse IDE, Chrome, Tomcat
- **Data Handling**: JDBC

## 결과
<p align="center">
  <img src="https://github.com/user-attachments/assets/1cdda9cd-073b-439c-8b8d-463ecd9e2317" width="32%" >
  <img src="https://github.com/user-attachments/assets/7ddc831e-9d2a-4f74-a5b1-edf647b6782f" width="32%" height="150px">
  <img src="https://github.com/user-attachments/assets/023fd40d-f092-4cf9-a411-7c9483055e71" width="32%">
  <img src="https://github.com/user-attachments/assets/de5334a0-de76-4bb2-8025-99219fbecd77" width="32%" >
</p>

## 나의 역할 기여
- DB 설계, 연결
- AJAX 사용한 JSP 개발
- cos.jar로 톰캣 서버에 이미지 업로드 방법 확립
- 물품등록, 검색, 흥정 / 마이페이지 위주 개발
