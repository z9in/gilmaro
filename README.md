# 쇼핑몰 길마로

# 팀프로젝트 : GILMARO 스마트 웹앱 구현 
담당 업무) 백엔드/프론트엔드
### 기존 길마로 홈페이지를 참고하여 프로젝트를 진행 하였음
#### 프로젝트 기간 : 2023.01.09~2023.01.18
#### 기본 업체 홈페이지 : www.gilmaro.co.kr/
#### 배포 : https://port-0-gilmaro-422t024lbonwoan.gksl2.cloudtype.app/index
#### 서버운영 : https://cloudtype.io
##### 📌개발환경 : 운영체제 윈도우10 chrome✅
##### 📌사용 코드에디터 : vs code
##### 📌개발언어: HTML, CSS, JavaScript 
##### 📌사용 모듈: node.js, express, sqlite3, sequelize, cookie-parse 활용 

# 제작 목표
#### 1. 기존 홈페이지를 참고하되. 상품의 간결화
#### 2. 실제 회원가입, 로그인 정보수정 등 기능 구현
#### 3. 장바구니, 찜목록등 session 과 cookie 등 브라우저의 기능 활용

# 주요 기능 구현 방법
#### 1. ejs템플릿을 활용한 SSR 구현
#### 2. local storege를 활용하여 제품 찜목록 구형
#### 3. session storege를 활용하여 로그인 전 장바구니 담기 구현
#### 4. 로그인 후 session storege의 내용을 db에 저장하고, 로그인 후 장바구니 담기는 db에 저장
#### 5. 로그인 상태는 쿠키 발행을 통해 관리 진행

# 향후 발전 방향
#### 1. 로그인과 관련하여 토큰 방식, websession의 활용 및 암호화 방식으로 보안을 강화할 수 있음
#### 2. db설계 시 회원 개인정보와, 회원의 관심 상품 목록을 이원화 하여 관리, 데이터 관리를 더욱 효율적으로 가능할 것임



# 사이트 페이지📰
![image 1](https://user-images.githubusercontent.com/113665619/215364470-2fba01d8-990c-4806-902f-ea947a69a95a.png)
![image 2](https://user-images.githubusercontent.com/113665619/215364441-34c91393-d807-4c56-b0b6-a34798e1b65a.png)
![image 3](https://user-images.githubusercontent.com/113665619/215364443-8c24b996-e6a3-4972-bd99-2a8656f85d23.png)






