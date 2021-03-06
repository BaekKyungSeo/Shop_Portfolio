# Shop_Portfolio

<웹 마켓 프로젝트> 는 웹 서비스에 대한 기초적인 이해, 직접 서버를 운용해보는 경험을 해보고자 JSP로 만들어본 사이트입니다.
기본적인것은 수업 내용을 참고해서 만들어 보았습니다.

## 사용기술
● 언어 : JSP, HTML, JS, CSS

● 운영체제 : Windows

● 데이터베이스 : Oracle 11g

● 웹 서버 : Apache 9.0.55

● JDK 버전 : JAVA SE 11

## 주요기능
1. 회원가입 & 로그인 & 회원정보 수정 & 회원탈퇴

2. 게시판(질문등록,답변)

3. 상품목록 & 상품상세 페이지

4. 상품관리기능(Admin 아이디를 활용하여 상품등록,수정,삭제)

## 회원가입
![회원가입](https://user-images.githubusercontent.com/88361809/158541006-75f6c93b-e226-421a-becf-d490d83810ba.gif)

회원가입에 js를 걸어 특정한 조건이 만족되도록 한 후에 회원가입 , 로그인 화면을 통해 세션값을 저장하여 회원아이디를 저장상태로 등록 회원수정 탭을 이용하여 회원수정 및 탈퇴가 가능하도록 하였습니다.

## 게시판
![게시판](https://user-images.githubusercontent.com/88361809/158541247-95db92e2-c8ac-4d9b-84a9-08005b16b453.gif)

로그인이 된 아이디로 게시판에 글을 작성하고 수정 및 삭제가 가능하도록 만들었습니다. 자신이 로그인한 아이디로만 수정 및 삭제가 가능하도록 하였으며 후에 나올 ADMIN아이디는 모든 게시판의 글들을 삭제할 수 있도록 하였습니다.

## 상품목록 & 상품상세 페이지
![상품목록   상품상세 페이지](https://user-images.githubusercontent.com/88361809/158541355-c97930cb-4736-49a4-9115-2850a75512cf.gif)

상품목록 창에서 상품들을 살펴볼 수 있도록 하였으며 , 상품정보를 누르고는 주문하기와 장바구니를 이용하여 상품을 구매하도록 만들었습니다.

## 관리자기능(상품등록,삭제,수정)
![관리자기능(상품등록,삭제,수정)](https://user-images.githubusercontent.com/88361809/158541430-df27c6d4-fd69-49db-bcae-d24c01391376.gif)

관리자 (admin) 아이디를 이용하여 관리자 상태에서만 상품등록,삭제,수정이 가능하도록 구현하였습니다.
