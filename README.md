# 🍶 술렁술렁
* 전통주 정보공유 웹 플랫폼
* 팀명 : Just one more drink
* 주소 : http://roalwh.iptime.org:20108/ (정상 배포 중)
![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/1d779411-921f-476b-95ca-155dca37e758)

<br/>
* 퍼블릭 게시용이므로 설정파일은 되도록 삭제되어있습니다.


## 술렁술렁 - 프로젝트 목차
- [프로젝트 소개](#프로젝트-소개)
  - [프로젝트 목표](#1--솔렁술렁-소개)
  - [프로젝트 팀원](#2--collaborators--팀원-소개)
  - [프로젝트 수행기간](#3--프로젝트-수행기간)
  - [사용기술](#4--사용기술)
    - [백엔드](#4-1-백엔드)
    - [프론트엔드](#4-2-프론트엔드)
  - [프로젝트 시연 화면](#5-프로젝트-시연-화면)
    - [프로젝트_화면](#5-1-메인화면)
    - [프로젝트_시연영상](#5-2--시연-영상)
- [구조 및 설계](#구조-및-설계)
  - [화면설계](#1-화면-설계)
  - [DB설계](#2-db-설계)
  - [기능 설계](#3-기능-설계)
  - [API](#4-api)
- [개발 내용](#개발-내용)
- [후기](#후기)
  - [프로젝트 보완사항](#1프로젝트-보완사항)
  - [후기](#2후기)


## 프로젝트 소개
 
### 1. 😀 술렁술렁 소개
우리술 웹 커뮤니티 플랫폼
우리술에 관심있고 우리술을 좋아하는 모든 사람들이 모인 커뮤니티<br>
소주 맥주 말고도 더 맛있고 다양한 전통주에 대한 정보와 술꾼들의 집합소 <br>
취향에 맞는 전통주도 추천 및 국내 여행할 때 마시면 좋을 지역별 전통주도 추천해드립니다. <br>

### 2. 👨‍👩‍👦‍👦 Collaborators : 팀원 소개
| 이름       | 역할           | GitHub 프로필                               |Email                               |
|------------|----------------|---------------------------------------------|---------------------------------------------|
| 원영호     | 팀장, 서버관리자, 풀스택 | [roalwh](https://github.com/roalwh) | nmnmnmlk6248@gmail.com, roalwh1@naver.com |
| 김세은     | 프론트엔드      | [senique-dev](https://github.com/senique-dev) | minirose42@gmail.com |
| 문상혁     | 풀스택          | [m960626](https://github.com/m960626) | m960626@naver.com |
| 서영은     | 풀스택          | [YOUNGEUN100](https://github.com/YOUNGEUN100) | westzerosilver@gmail.com |
| 최진주     | 프론트엔드      | [pearl1233333](https://github.com/pearl1233333) | ddch4747@naver.com |


### 3. 📑 프로젝트 수행기간
- 총 개발기간 8/1 ~ 9/1
- 8/1 ~ 8/3 프로젝트 기획 및 주제선정
- 8/4 ~ 8/7 화면설계, DB설계, 데이터 수집
- 8/7 ~ 8/27 서비스 구축, 테스트
- 8/27 ~ 9/1 서버 배포

### 4. 🛠 사용기술
<img src="https://github.com/roalwh/Project-OMDB-Public/assets/121986519/d519589a-a3f5-40c8-87e3-296f8f80596e" />

#### 4-1. 백엔드

<div style="display: flex; flex-direction: row;">
  <img src="https://img.shields.io/badge/Python-3DDC84?style=flat-square&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JDK17-3DDC84?style=flat-square&logo=openJDK&logoColor=white"/>
  <img src="https://img.shields.io/badge/mariaDB-3DDC84?style=flat-square&logo=mariaDB&logoColor=white"/>
  <img src="https://img.shields.io/badge/SpringBoot-3DDC84?style=flat-square&logo=SpringBoot&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-3DDC84?style=flat-square&logo=JWT&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-3DDC84?style=flat-square&logo=JPA&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradle-3DDC84?style=flat-square&logo=Gradle&logoColor=white"/>
</div>

##### 주요 프레임워크 / 라이브러리
- Python 3.11.4
- JDK 17
- Spring Boot 3.1.2
- Spring Security
- Oauth 2.0
- jsonwebtoken(JWT) 0.9.1
  
##### Build Tool
- Gradle-8.2.1 

##### DataBase
- MariaDB 10.3.38

#### 4-2. 프론트엔드

<div style="display: flex; flex-direction: row;">
  <img src="https://img.shields.io/badge/Node.JS-3DDC84?style=flat-square&logo=Node.JS&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-3DDC84?style=flat-square&logo=JavaScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/npm-3DDC84?style=flat-square&logo=npm&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-3DDC84?style=flat-square&logo=HTML5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-3DDC84?style=flat-square&logo=CSS3&logoColor=white"/>
  <img src="https://img.shields.io/badge/SASS-3DDC84?style=flat-square&logo=SASS&logoColor=white"/>
  <img src="https://img.shields.io/badge/REACT-3DDC84?style=flat-square&logo=REACT&logoColor=white"/>
</div>

##### 주요 프레임워크 / 라이브러리
- JavaScript 
- HTML/CSS
- REACT
- Bootstrap 4.3.1
- axios
  
##### Build Tool
- Node.js 18.16.0

### 5. 프로젝트 시연 화면

#### 5-1. 메인화면
![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/1d779411-921f-476b-95ca-155dca37e758) 

#### 5-2. 🎞 시연 영상
- 사용자 : https://www.youtube.com/watch?v=N9YjAZHWraE
- 관리자 : https://www.youtube.com/watch?v=9p1A91r_M4w



## 구조 및 설계

### 1. 화면 설계
#### 1-1. 주요 화면 설계 이미지
![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/b0f4183e-cbff-45f3-a9fb-d3ad8a0f43d1)


Figma [https://url.kr/6t7ejs](https://www.figma.com/file/xR6V0dH4JPPIpAuKUuzfHI/%ED%8C%8C%EC%9D%B4%EB%84%90-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8(%EC%98%88%EC%B9%AD-%EC%88%A0%EB%A0%81%EC%88%A0%EB%A0%81)?type=design&node-id=0%3A1&mode=design&t=zhi5r3z6lGj34GMZ-1)

### 2. DB 설계
#### 2-1. ERD 이미지
<img src="https://github.com/roalwh/Project-OMDB-Public/assets/121986519/cc4d2924-af5f-4bd4-8946-ab14051bf127" />

#### 2-2. DB 테이블

<details>
  <summary>DB 테이블 (클릭시 리스트) </summary> 

  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/e7ae7e95-4790-4894-a28a-45f04aead679)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/8343a6ba-a0fa-4616-b49c-b90407a0ee39)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/2868cde7-8413-4133-86bf-650dc41b24c3)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/bb5d4ce9-9dcb-4d60-b4aa-6af851328d64)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/554921b9-1751-47b3-9c61-908595656072)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/24d6dddc-0b1c-45d0-830d-534103d0bddb)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/ee6aeea1-8645-4460-b3b7-174f18153170)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/2c666cd1-791e-43ed-a646-426ceb437c44)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/5b727755-dc4d-4dec-b1bd-4314cea5529a)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/8d7f1225-2fea-468c-a9f2-4abec8615915)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/e3289a4a-1709-4ae8-8b41-009c63120ea3)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/78402e3b-0381-4c27-a6c3-4be1013d9365)
  ![image](https://github.com/roalwh/Project-OMDB-Public/assets/83705507/5f95f4ed-2f2b-4cbb-aa74-67c16368f093)

 </details>

### 3. 기능 설계

#### 3-1. 사용자 관리
- JWT 기반 로그인
- 패스워드 암호화(BCrypt)
- 이메일 인증
- 관리자/일반사용자 권한 분리
- 마이페이지

#### 3-2. 정보 제공
- 전통주 검색
- 전통주 정보 제공
- 검색 정렬 기능
- 리뷰 작성, 수정, 삭제

#### 3-3. 취향 파악
- 5가지 질문을 통해 취향 검색
- 질문 기준으로 전통주 추천

#### 3-4. 지역별 안내
- 지도를 이용한 지역 검색
- 지역별 전통주 표시

#### 3-5. 커뮤니티
- 공지글, 자유글, 맛집 추천 글 작성, 수정, 삭제
- 검색 정렬 기능
- 댓글 작성, 수정, 삭제


### 4. API

#### 4-1. 관리자(admin)   API

기능 | Method | URL
-- | -- | --
관리자 리스트 조회 | GET | /admin/adminlist
사용자 리스트 조회 | GET | /admin/userlist
userFlag 수정 | PUT | /admin/userset
관리자 등록 | POST | /admin/signup
처음 관리자 등록 | POST | /admin/signup/new

#### 4-2. 게시글(board)   + 댓글(comment) API

기능 | Method | URL
-- | -- | --
게시글등록 + 파일등록   add | POST | /board/add
게시글 파일 가져오기 | GET | /board/files/{board_id}
게시글수정 update | PUT | /board/update/{board_id}
게시글삭제 inactive   board | PUT | /board/inactive/{board_id}
전체 게시글 보기 all   view | GET | /board/view/all
게시판 종류별 글보기 이름   검색  kind title orderby | GET | /board/view?kind={kind_no}&orderby={정렬할   컬럼}
게시글 상세보기 + 댓글   보기 | GET | /board/view/{board_id}
댓글 조회 view | GET | /board/comment/no/{comment_id}
댓글 수정 update | PUT | /board/comment/update/{comment_id}
댓글 삭제 inactive | PUT | /board/comment/inactive/{comment_id}
댓글 등록 add | POST | /board/comment/add

#### 4-2, 전통주 검색(cate) + 전통주 상세 리뷰(review) API

기능 | Method | URL
-- | -- | --
전통주 검색 | GET | /cate/search?name={drink_name}
전통주 정보 | GET | /cate/info/{drink_id}
전통주 정보 리뷰조회 | GET | /cate/review/{drink_id}
전체 전통주 정보 | GET | /cate/all
리뷰 이미지 호출 | GET | /rimg/{dirnk_id}/{rimg_id}/review_{dirnk_id}_{rimg_id}.png
리뷰 등록 | POST | /cate/reviewin
리뷰 수정 | PUT | /cate/reviewedit/{review_id}
리뷰 삭제 | DEL | /admin/reviewdel/{review_id}


#### 4-3. 전통주(drink) 정보

기능 | Method | URL
-- | -- | --
전통주 정보 검색 | GET | /dri/{drink_id}
카테고리 or 이름 검색 | GET | /dri/search?name={drink_name}
전통주 이미지 호출 | GET | /dimg/{drink_id}/drink_{dimg_id}.png
전통주 좋아요 조회 | GET | /dlike/userList?uid={user_id}
술정보 등록 | POST | /dri/drinkIn
술정보 수정 | PUT | /dri/drinkedit/{drink_id}
전통주 좋아요 등록 | POST | /dlike/add

#### 4-4. 회원(member) API

기능 | Method | URL
-- | -- | --
회원가입 | POST | /auth/signup
로그인 | POT | /auth/login
회원정보 가져오기 | GET | /member/me
아이디 찾기 | POST | /auth/find-id
비밀번호 찾기 전 계정   확인 | POST | /auth/find-pw
비밀번호 변경 | PUT | /auth/change-pw/{user_id}
회원정보 수정 | PUT | /member/change-info
회원 탈퇴 | PUT | /auth/change-pw/{user_id}
이메일 발송 | POST | /auth/email
이메일 번호 확인 | GET | /auth/check-email/{number}

#### 4-5. 마이페이지(myPage) API

기능 | Method | URL
-- | -- | --
회원 게시글 가져오기 | GET | /member/board/{user_id}
회원 댓글 가져오기 | GET | /member/comment/{user_id}
회원 리뷰 가져오기 | GET | /member/review/{user_id}

## 개발 내용
 - [술렁술렁 프로젝트 - 개인 백엔드 작업, 전통주 데이터 크롤링,DB 데이터 삽입](https://roalwh.tistory.com/17)
 - [술렁술렁 프로젝트 - 개인 백엔드 작업, 카테고리API](https://roalwh.tistory.com/14)
 - [술렁술렁 프로젝트 - 개인 백엔드 작업, 이미지 호출 API](https://roalwh.tistory.com/16)
 - [술렁술렁 프로젝트 - 개인 백엔드 작업, 전통주 정보 API](https://roalwh.tistory.com/15)
 - [술렁술렁 프로젝트 - DB 구축, 벡엔드 배포, 프론트 배포](https://roalwh.tistory.com/18)

## 후기
### 1.프로젝트 보완사항
   - 중복된 API 정리 필요
   - 테스트로 작성한 불필요 print문 제거
   - 파일 업로드 좀더 나은 방법이 있는지 찾아보기
   - 구글 로그인시 사용자 정보 추가 입력 처리
   - 회원가입 이메일 중복체크(구글로그인과 기존등록된 이메일 충돌로인한 에러)
   - 비밀번호 변경 시 기존 비밀번호 재사용 불가 처리
   - yml, env 파일 등을 암호화나 spring cloud 를 이용한 암호화 처리
   - 공유기 사용으로 인한 https 미적용 -> 개인서버 os재설치가 필요한 부분이라 진행 못함






