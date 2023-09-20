# 💁🏻‍♂️ 교환학생 소통 플랫폼
## ⌨️ 구현 목표
- 채팅을 뿌술거야  
- ts로 뿌술거야
## 🛠️ 기능 소개
- 회원(카카오, 애플 로그인)  
    - 국적, 언어, 관심주제 등은 이후 선택
    - JWT 토큰 방식 + OAuth2.0
    - 마이페이지 
- 모임(게시물) CRUD, 조회수
- 댓글, 리뷰 CRUD
- 검색 기능
- 카테고리별 추천 기능
- 찜 기능 CRUD
- 채팅 기능
## 📚 파일 구조  
📦src  
 ┣ 📂@types  
 ┃ ┗ 📜index.d.ts  
 ┣ 📂config  
 ┃ ┗ 📜.env  
 ┣ 📂controllers  
 ┃ ┗ 📜index.ts  
 ┣ 📂middlewares  
 ┃ ┗ 📜index.ts  
 ┣ 📂models  
 ┃ ┗ 📜index.ts  
 ┣ 📂public  
 ┃ ┣ 📜favicon.ico  
 ┃ ┗ 📜index.ts  
 ┣ 📂routes  
 ┃ ┗ 📜index.ts  
 ┣ 📂services  
 ┃ ┗ 📜index.ts  
 ┣ 📂utils  
 ┃ ┗ 📜index.ts  
 ┗ 📜app.ts  
