# SpringMVCBoard
java spring framework에 mvc 패턴을 적용해서 만든 게시판입니다.


## zip파일
- 1_JSP게시판.zip  
JSP로만 만든 기본 게시판
- 2_MVC_Board_MAV.zip  
mvc패턴의 게시판, view에서 jstl태그 이용
- 3_MVC_Board_Business_View.zip  
비즈니스와 view단을 분리하여 만든 게시판  
비즈니스단은 restful하게 구현했으며 view단은 jquery로 구현하였습니다.  
jquery를 이용해서 Ajax통신을 하고, 서버에 특정 url로 요청을 보내면 JSON 데이터를 응답 받도록 구현하였습니다.


## 기능
- 기본 CRUD : 게시판 목록보기, 게시글상세보기, 게시글 쓰기, 게시글 수정, 게시글 삭제
- 댓글 기능
- 페이징
- 파일 업로드/다운로드

## 개발환경
Server OS : Windows10  
Language : JAVA 1.8  
Framework : Spring 5.2.2  
WEB Server : Apache  
WAS Server : Tomcat 8.5  
build tool : maven 3.6.3  
Database : Mysql 5.7
