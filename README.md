
### 커뮤니티 기능을 강화한 여행 사이트입니다.

사이트 URL : http://13.125.213.74:8080/roaming/userboard/mainPage

## 📦 개발 환경

- **editor** : <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white">
- **language** : <img src="https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/>
- **database** : <img src="https://img.shields.io/badge/oracle-F80000?style=flat-square&logo=oracle&logoColor=white">
- **기타** : <img src="https://img.shields.io/badge/bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/aws-232F3E?style=flat-square&logo=aws&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=white">
<br/><br/>
## 로밍 사이트
![001](https://user-images.githubusercontent.com/131675760/261490289-adddcd82-df6f-41ff-b682-2b5128c43871.png)

## 메인 페이지
![002](https://user-images.githubusercontent.com/131675760/261490308-5830faf0-c5fb-4ae4-9da9-8d242151ad8d.png)
### 먼저 로그인을 하지 않은 채 메인 페이지를 들어가면 동행찾기, 커뮤니티, 숙소예약, 짐서비스, 포인트샵 순으로 보여줍니다.
### 로그인을 하면 상세 보기를 눌러 각 기능 페이지에 들어갈 수 있습니다.
<br/><br/>

## 로그인 기능
![003](https://user-images.githubusercontent.com/131675760/261490419-0c90a7d1-1aa7-41d2-9e85-540d1389f80f.png)
### 로밍의 아이디 또는 카카오 토큰을 이용한 아이디를 이용해서 로그인 할 수 있습니다.
<br/><br/>

## 회원가입 기능
![004](https://user-images.githubusercontent.com/131675760/261490381-f742727c-33ca-4661-b3df-3f4ad72ba587.png)
### 계정을 생성해주는 회원가입 기능입니다.<br/>
### 유효성 검사 항목들
* 이미 존재하는 아디이 검사
* 비밀번호 재입력이 일치하는지 검사
* 필수 약관 내용에 동의하는지 검사
<br/><br/>

## 커뮤니티 들어가기
![005](https://user-images.githubusercontent.com/131675760/261494443-fd0045d1-ddd4-4452-9b81-7c3ebc1fe7f4.png)
### 제가 구현한 커뮤니티를 들어갑니다.
<br/><br/>

## 홈
![006](https://user-images.githubusercontent.com/131675760/261494491-c4cb123b-5134-4623-a577-12c5d1ddf099.png)
### 홈에서는 UNOIN 쿼리를 이용하여 모든 게시물을 한번에 확인할 수 있습니다.
<br/><br/>

![007](https://user-images.githubusercontent.com/131675760/261494782-5591689f-1c75-42ec-acc9-1fd1b458ea0b.png)
### 각각의 게시물에 대해 모든 기능을 수행할 수 있습니다.
<br/><br/>

![008](https://user-images.githubusercontent.com/131675760/261494795-a66040a3-70d1-44d5-9791-f015c2efbfd1.png)
### 더보기를 누르거나 댓글 아이콘을 누르면 모달로 크게 보여줍니다.
<br/><br/>

## 업로드
![009](https://user-images.githubusercontent.com/131675760/261494535-253e5248-720d-4ba6-b0e8-0b27d42ab9d1.png)
![010](https://user-images.githubusercontent.com/131675760/261494554-b3cbc119-4567-4df1-9091-28125da8961e.png)
### 사진, 영상을 업로드에 올리면 파일리더로 미리볼 수 있습니다.
### 업로드 기능은 자바스크립트와 Ajax를 이용하여 비동기로 구현하였습니다.
### 입력하는 항목들
* 게시물에 대한 제목(사진만 영상은 NULL)
* 게시물에 대한 내용
* 게시물에 대한 위치
<br/><br/>

## 피드(사진 게시물)
![011](https://user-images.githubusercontent.com/131675760/261497992-7ca80035-27c8-4231-a363-b1cd5d7c2cc3.png)
### 여러 사진들을 나열하고 마우스 오버를 하면 게시물에 대한 좋아요 수와 제목을 미리 볼 수 있습니다.
### 게시물을 클릭하면 피드 상세 페이지로 넘어갑니다.
<br/><br/>

![012](https://user-images.githubusercontent.com/131675760/261494864-9419442b-257b-472a-9755-bc2efafe2857.png)
![013](https://user-images.githubusercontent.com/131675760/261494882-ea8fb0dd-0dbc-4ae6-b9d8-c911dc03051a.png)
### 사진이 여러장 일 때 옆으로 가기 버튼을 눌러 모두 확인할 수 있습니다.
### 게시물에 대해 댓글을 달고 수정, 삭제도 가능합니다.
### 하트 이모티콘을 누르면 좋아요와 싫어요를 표현할 수 있습니다.
### 아래로 스크롤하면 다른 피드를 바로 확인할 수 있습니다.
<br/><br/>

## 릴스(영상 게시물)
![014](https://user-images.githubusercontent.com/131675760/261494926-1fd8d028-3cae-4e09-83ca-0515789db3e4.png)
### 영상에 대해 좋아요, 댓글이 가능하고 댓글 아이콘이나 더보기를 눌렀을 때 모달로 댓글을 모두 확인할 수 있습니다.
<br/><br/>

## 검색
![015](https://user-images.githubusercontent.com/131675760/261495052-1caed7a2-9985-4f60-9a10-805668fbe475.png)
### 검색창에 단어를 검색하면 게시물의 내용, 제목, 유저 아이디, 닉네임 중 하나가 포함된다면 유저 정보로 검색됩니다.
### 검색 후 유저를 클릭하면 유저 페이지로 넘어갑니다.
<br/><br/>

## 유저 페이지(어느 페이지에서든 유저 사진을 클릭하면 됩니다)
![016](https://user-images.githubusercontent.com/131675760/261495166-a544430d-f8e2-4f39-bf77-07eec51f3a0a.png)
### 팔로우를 클릭하면 비동기로 바로 팔로잉으로 바뀝니다.
### 메세지 보내기를 누르면 메세지 페이지로 넘어갑니다.(네비바에서 메세지를 클릭해도 동일)
### 피드, 릴스를 따로 볼 수 있습니다.
<br/><br/>

## 메세지
![017](https://user-images.githubusercontent.com/131675760/261495081-5049499b-3905-4ae5-8662-b30081d8d950.png)
### 1:1 채팅을 할 수 있습니다.
### 나에게 온 채팅 목록을 확인 할 수 있습니다.
<br/><br/>

## 알림
![018](https://user-images.githubusercontent.com/131675760/261495103-a9ddfd38-90ce-4b16-8de2-d7e90acfc087.png)
### 나를 팔로워한 유저가 있으면 바로 알림이 옵니다.
<br/><br/>

## 프로필
![019](https://user-images.githubusercontent.com/131675760/261495150-da43c667-4c8f-42ce-951e-79379b624c0c.png)
### 프로필 설정에 들어가 프로필 사진을 변경할 수 있습니다.
<br/><br/>

## erd 다이어그램
![020](https://user-images.githubusercontent.com/131675760/261490348-ef5c64dd-19b5-4a3f-a3c1-232c82dec7b1.png)
### 테이블 명세서
* R_user : 회원
* R_message_p : 메세지
* R_follow : 팔로우
* R_save_spot : 저장소
* R_save_category : 저장소 카테고리
* R_alerts : 인스타 알림
* R_hash_tag : 해시태그
* R_reels : 릴스
* R_block_users : 차단
* R_tags : 태그
* R_reels_likes : 릴스 좋아요
* R_feed : 피드
* R_feed_likes : 피드 좋아요
* R_reels_comment : 릴스 댓글
* R_feed_comment : 피드 댓글
* R_feed_category : 피드 좋아요 카테고리
* R_feed_image : 피드 상세 이미지
<br/><br/>
