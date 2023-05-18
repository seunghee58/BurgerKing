# BurgerKing

>개발 기간: 2023.05.11 ~ 2023.05.18</p>

### 🍔 버거킹 클론코딩
  - 기본 기능
    - 회원가입, 로그인, 로그아웃
    - 카테고리 별 메뉴 조회
    - 메뉴 추가, 삭제, 수정 (ADMIN 권한을 부여하여 메뉴 CRUD 추가)
  - 추가 기능
     - 매장 찾기 (지도 API)
     - 소셜 로그인

## 🍟 S.A
[https://www.notion.so/S-A-afa6ceba07db4022bebde44ccb35807a](https://www.notion.so/S-A-0c13c352a4634d7c9ae4636f22d98e7e)

## 🥤 와이어 프레임
<img width="897" alt="스크린샷 2023-05-18 184506" src="https://github.com/seunghee58/BurgerKing/assets/129656095/869a7515-a0a1-4156-84ca-cf0fafef29ed">
https://www.figma.com/file/IV9Mt2Kw79DDIXyXhDw1Ix/BurgerKing?type=design&node-id=0-1&t=PZdCfBoHayr6a9lG-0

## 📰 ERD
![ERD](https://github.com/seunghee58/BurgerKing/assets/129656095/1b657eda-7ea5-498e-8c3d-90bda5fc6eb0)

## 📖 API 명세서
<details>
  <summary> 펼쳐보기 </summary>
<img width="891" alt="버거킹 API 명세서" src="https://github.com/seunghee58/BurgerKing/assets/129656095/9a6c5619-911e-410e-a65f-570ff3b0b214">
</details>

## 👨‍👩‍👧팀원
|이름|역할|
|------|---|
|이재호 (Reader) </br>(https://github.com/spainclub)|- 메뉴 CRUD </br>- 소셜 로그인 API</br>- 매장 찾기 지도 API</br>- 서버 배포</br>|
|장기웅</br>(https://github.com/Jangkiwoong)|- 회원가입, 로그인, 로그아웃 기능</br>-Security / JWT filter / 토큰</br>|
|이승현</br>(https://github.com/seungheyon)|- 회원가입, 로그인, 로그아웃 기능</br>-Security / JWT filter / 토큰</br>|
|한승희</br>(https://github.com/seunghee58)|- 메뉴 CRUD </br>- 소셜 로그인 API</br>- 매장 찾기 지도 API</br>|

FE git hub : https://github.com/yeonju0318/BurgerKing

## ⚙️ Tech Stack
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <br>
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <br>
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> <br>
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">

## 1️⃣ 회원 관련 기능
  1. 회원 가입 API <br>
    - userId : 크기 4 이상, 10 이하 / 소문자와 숫자만 입력가능, 공백 금지 / 중복 불가
    - userName : 크기 10이하, 공백 금지
    - password : 크기 8 이상, 15 이하 / 대소문자, 숫자, 특수문자 가능, 공백 금지
  2. 로그인 API <br>
    - 로그인 시 access token 발급
  4. 로그아웃 API <br>
    - 로그아웃 시 Redis를 사용하여 access token을 사용하지 못하도록 등록
  
## 2️⃣ 메뉴 CRUD 기능
  1. 메뉴 추가 API <br>
    - ADMIN 권한에 한하여 메뉴 추가 기능
  2. 메뉴 수정 API <br>
    - ADMIN 권한에 한하여 메뉴 수정 기능
  3. 메뉴 삭제 API <br>
    - ADMIN 권한에 한하여 메뉴 삭제 기능
  4. 메뉴 조회 API <br>
    - 카테고리 별 메뉴 조회 기능 

## 3️⃣ 소셜 로그인 기능
  1. 카카오 로그인 API

## 4️⃣ 매장 찾기 기능
  1. 시, 구 별로 매장 찾기 API
    - 카카오 지도 API 사용하여 기능 구현


## 🚩 기능 구현을 위해 고민한 것

