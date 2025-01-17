# CloverWebtoon 🍀
네이버 웹툰을 벤치마킹하여 제작한 웹툰 플랫폼 프로젝트입니다.
교육 과정에서 학습한 기술 스택을 바탕으로 개발된 프로젝트로, 사용자와 관리자 페이지를 포함한 다양한 기능을 구현하였습니다.


<hr>


## 📌 프로젝트 소개
CloverWebtoon은 웹툰을 탐색, 열람, 업로드 및 관리할 수 있는 웹 기반 플랫폼입니다.
네이버 웹툰의 주요 기능을 참고하여 사용자가 친숙하게 느낄 수 있는 UI/UX를 제공하며, 교육 과정에서 배운 기술을 활용하여 기능을 구현하였습니다.


<hr>


## 📋 주요 기능
- **메인 페이지**: 카테고리별 웹툰 탐색 및 추천 웹툰 열람
- **웹툰 뷰 페이지**: 웹툰 회차 열람 및 댓글 작성 (로그인 필요)
- **웹툰 업로드 페이지**: 관리자 페이지에서 새로운 웹툰 및 회차 업로드
- **관리자 페이지**: 방문자 통계, 사용자 관리, 댓글 관리, 매출 관리
- **로그인 및 회원가입**: 사용자 인증 및 회원 관리 기능
- **내 정보 페이지**: 사용자 정보 수정, 비밀번호 변경, 회원 탈퇴
- **공지사항 페이지**: 플랫폼 공지사항 열람 및 작성


<hr>


## 🛠️ 기술 스택
### Front-end
<div> 
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" height="30"> 
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" height="30"> 
  <img src="https://img.shields.io/badge/ECMAScript-323330?style=flat&logo=javascript&logoColor=white" height="30"> 
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white" height="30"> 
</div>

### Back-end
<div> 
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white" height="30"> 
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white" height="30"> 
  <img src="https://img.shields.io/badge/JSP-3776AB?style=flat&logo=java&logoColor=white" height="30"> 
</div>

### Database
<div> 
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" height="30"> 
  <img src="https://img.shields.io/badge/MySQL_Workbench-4479A1?style=flat&logo=mysql&logoColor=white" height="30"> 
</div>

### Tools
<div> 
  <img src="https://img.shields.io/badge/STS4-6DB33F?style=flat&logo=spring&logoColor=white" height="30"> 
</div>


<hr>

## 💡 시스템 설계: 와이어프레임
와이어프레임은 프로젝트 초기 설계 단계에서 작성되었으며, 사용자 동선 및 레이아웃 구상을 기반으로 개발이 진행되었습니다.
| **메인 페이지**           | **웹툰 회차 페이지 1**         |
|---------------------------|---------------------------|
| ![메인 페이지](./images/main_page_wireframe.png) | ![웹툰 회차 페이지](./images/webtoon_episode.png) |

| **웹툰 페이지 1**         | **웹툰 페이지 2**      |
|---------------------------|---------------------------|
| ![웹툰 페이지 1](./images/webtoon_page1.png)     | ![웹툰 페이지 2](./images/webtoon_page2.png) |

| **마이 페이지**           | **관리자 페이지**         |
|---------------------------|---------------------------|
| ![마이 페이지](./images/my_page.png)             | ![관리자 페이지](./images/admin_page.png)       |

| **로그인 페이지**         | **회원가입 동의 페이지**  |
|---------------------------|---------------------------|
| ![로그인 페이지](./images/login_page.png)         | ![회원가입 동의 페이지](./images/signup_page.png) |



<hr>


## 🖥️ 시스템 구현: 주요 페이지
구현된 주요 페이지를 통해 설계와 실제 구현된 화면의 결과를 확인할 수 있습니다.

### **1. 웹툰 관련 페이지**
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 메인 페이지             | ![메인 페이지](./images/웹툰메인페이지.png)       |
| 웹툰 페이지             | ![웹툰 페이지](./images/웹툰페이지.png)    |
| 주간 웹툰 페이지        | ![주간 웹툰 페이지](./images/주간웹툰페이지.png) |
| 웹툰 리스트 페이지      | ![웹툰 리스트 페이지](./images/웹툰리스트페이지.png) |
| 웹툰 뷰 페이지 & 댓글   | ![웹툰 뷰 페이지](./images/웹툰뷰페이지&댓글.png) |
<br>

### **2. 업로드 관련 페이지**
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 웹툰 업로드             | ![웹툰 업로드](./images/웹툰업로드.png) |
| 회차 업로드             | ![회차 업로드](./images/회차업로드.png) |
<br>

### **3. 마이 페이지**
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 관심 웹툰               | ![관심 웹툰](./images/관심웹툰.png) |
<br>

### **4. 관리자 페이지**
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 방문자 수               | ![방문자 수](./images/방문자수.png)    |
| 회원 정보 관리          | ![회원 정보](./images/회원정보.png)    |
| 조회수 관리             | ![조회수 관리](./images/조회수.png)    |
| 웹툰 관리               | ![웹툰 관리](./images/웹툰관리.png)    |
| 매출 관리               | ![매출 관리](./images/매출.png)    |
| 관리/업로드             | ![관리/업로드](./images/관리및업로드.png)   |
<br>

### **5. 공지사항 페이지**
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 공지사항 목록               | ![공지사항 목록](./images/공지사항목록.png)    |
| 공지사항 상세          | ![공지사항 상세](./images/공지사항상세페이지.png)    |
| 공지사항 작성             | ![공지사항 작성](./images/공지사항작성.png)    |
<br>

### **6. 인증 및 회원 페이지**
#### 인증 페이지 요약
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 로그인 페이지           | ![로그인 페이지](./images/로그인페이지.png)   |
| 회원가입 동의 페이지     | ![회원가입 동의](./images/회원가입동의페이지.png) |
| 회원가입 입력 페이지     | ![회원가입 입력](./images/회원가입입력페이지.png) |

#### 내정보 관리 페이지
| **페이지**         | **화면**                                    |
|-------------------------|---------------------------------------------|
| 내정보 수정          | ![회원 정보 수정](./images/회원정보수정.png) |
| 비밀번호 변경하기       | ![비밀번호 변경](./images/비밀번호변경하기.png) |


<hr>


## 🔄 페이지 플로우 차트
페이지별 플로우 차트는 사용자의 동선과 기능 흐름을 시각적으로 설명합니다.

### 1. 웹툰 페이지 플로우 차트
![웹툰 페이지 플로우 차트](./images/웹툰페이지플로우차트.png)
<br><br>

### 2. 공지사항 페이지 플로우 차트
![공지사항 페이지 플로우 차트](./images/공지사항페이지플로우차트.png)
<br><br>

### 3. 관리자 업로드 페이지 플로우 차트
![관리자 업로드 페이지 플로우 차트](./images/관리자업로드페이지플로우차트.png)
<br><br>

### 4. 관리자 페이지 플로우 차트
![관리자 페이지 플로우 차트](./images/관리자페이지플로우차트.png)
<br><br>

### 5. 내정보 페이지 플로우 차트
![내정보 페이지 플로우 차트](./images/내정보플로우차트.png)
<br><br>

### 6. 로그인 페이지 플로우 차트
![로그인 페이지 플로우 차트](./images/로그인플로우차트.png)
<br><br>

### 7. 회원가입 페이지 플로우 차트
![회원가입 페이지 플로우 차트](./images/회원가입플로우차트.png)


<hr>


## 🚀 설치 및 실행 방법
### 1. 저장소를 클론합니다:
```bash
git clone https://github.com/your-username/CloverWebtoon.git
```
<br>

### 2. 프로젝트를 IntelliJ IDEA 혹은 STS4에 가져옵니다.
#### 1) IntelliJ IDEA
- File → Open → 프로젝트 폴더 선택 → 열기.
- Maven을 사용하는 경우, IntelliJ에서 자동으로 pom.xml 파일을 읽어 의존성을 설정합니다.
#### 2) STS4
- File → Import → Existing Maven Project 선택 → 프로젝트 폴더 선택 → Finish.
<br>

### 3. 데이터베이스 설정
#### 1) 스키마 생성
- schema.sql 파일을 사용해 MySQL 데이터베이스에 필요한 테이블 및 초기 데이터를 생성합니다.
  ```bash
  mysql -u [username] -p [database_name] < schema.sql
  ```
#### 2) application.properties 설정
- src/main/resources/application.properties 파일을 열어 데이터베이스 연결 정보를 수정합니다.
  ```bash
  spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
  spring.datasource.username=your_username
  spring.datasource.password=your_password
  ```
  <br>

### 4. Spring Boot 애플리케이션 실행
#### 아래 두 가지 방법 중 하나를 선택하여 실행합니다:

#### 방법 1: IntelliJ IDEA 또는 STS4에서 실행
① src/main/java 디렉토리에서 @SpringBootApplication이 붙은 메인 클래스(예: Application.java)를 찾습니다. <br>
② 해당 파일을 오른쪽 클릭 → Run 'Application' 또는 Run As > Spring Boot App을 선택합니다.<br>

#### 방법 2: 터미널에서 실행
① 프로젝트 루트 디렉토리에서 아래 명령어를 실행합니다.
```bash
./mvnw spring-boot:run
```
<br> ② Maven이 설치되어 있다면 아래 명령어도 가능합니다.
```bash
mvn spring-boot:run
```
<br>

### 5. 브라우저에서 애플리케이션에 접근
브라우저를 열고 아래 URL로 이동합니다.
```bash
http://localhost:8080
```


<hr>


### 👥 팀 구성 및 역할
| 이름       | 역할                                    |
|------------|-----------------------------------------|
| 양성호     | 팀장, 프로젝트 종합 정리                  |
| 권용우     | 메인페이지 구현                           |
| 손정훈     | 뷰 & 업로드 페이지                        |
| 윤정인     | 관리자페이지 & 와이어프레임 제작           |
| 장혜지     | 로그인 & 회원가입 & 내정보페이지           |
| 차인균     | 공지사항페이지                            |


<hr>


### 📢 프로젝트 후기
이 프로젝트는 교육 과정에서 학습한 기술 스택을 기반으로 팀원들과 협업하며 완성된 결과물입니다. 
네이버 웹툰의 기능을 벤치마킹하며 개발 과정 전반에 걸쳐 설계, 구현, 테스트를 경험할 수 있었습니다. 
이를 통해 실무에 적용 가능한 풀스택 개발 경험을 쌓을 수 있었습니다.

#### 🤔 아쉬운 점과 느낀 점
- **관리자 페이지** : 화면 구성은 완료했지만, 데이터를 실질적으로 관리하거나 분석하는 기능은 구현하지 못했습니다. 단순한 UI 구현만으로는 프로젝트 완성도를 높이기에 부족하다는 점을 깨달았습니다.
- **로그인 및 회원가입** : 인증 및 보안적인 부분이 없이 단순히 DB에 정보를 저장하는 기능만 구현되었습니다. 사용자의 데이터를 다룰 때는 보안적인 측면이 중요하다는 점을 실감했습니다.
- **테스트 부족** : 테스트 과정을 충분히 거치지 못해 일부 기능이 불안정할 수 있음을 느꼈습니다. 테스트의 중요성을 다시 한 번 깨닫게 되었습니다.
- **UI/UX 설계** : 사용자의 경험을 충분히 고려하지 못한 부분이 아쉬웠습니다. 프로젝트 초기 단계에서 UI/UX 설계에 더 많은 시간을 투자해야 한다는 점을 배웠습니다.









