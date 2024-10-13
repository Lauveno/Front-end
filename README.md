## 🥂 오늘 한 잔

`오늘 한 잔`은 다양한 지역 특산주를 홍보하거나 리뷰하며 
국내 지역 특산주 소비를 촉진하는 플랫폼 입니다.

- 지역별 다양한 특산주 리뷰와 홍보를 통해 국내 술에 대한 알찬 정보와 유용한 커뮤니티 경험을 할 수 있도록 도와줍니다.
- 특산주 정보 제공, 시음 리뷰 작성, 사용자 기호에 맞는 추천 등으로 지역 특산주를 더욱 활기차게 경험해보세요!

### 🔗 [프로젝트 노션 바로가기(상세 설명)](https://develop-growth.notion.site/One-Drink-Today-9ef0f66fc89e4bbe952db9e05e0e6714?pvs=4)

<br><br>
## 👩‍👩‍👧‍👦 팀원 소개

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/KatsCC"><img src="https://github.com/user-attachments/assets/c9a589eb-ebd0-4f31-b569-c03f048042f3" width="150px;" alt=""/><br /><b>FE 박근영</b></a><br /></td>
      <td align="center"><a href="https://github.com/Lauveno"><img src="https://avatars.githubusercontent.com/u/49627661?v=4" width="150px;" alt=""/><br /><b>FE 정유경</b></a><br /></td>
      <td align="center"><a href="https://github.com/subin114"><img src="https://github.com/user-attachments/assets/03970566-5632-4194-b508-943a3931e1e2" width="150px;" alt=""/><br /><b>FE 황수빈</b></a><br /></td>
     <tr/>
      <td align="center"><a href="https://github.com/gkjm123"><img src="https://avatars.githubusercontent.com/u/47303804?v=4" width="150px;" alt=""/><br /><b>BE 구정은</b></a><br /></td>
      <td align="center"><a href="https://github.com/BigHuni"><img src="https://avatars.githubusercontent.com/u/79084294?v=4" width="150px;" alt=""/><br /><b>BE 허대훈</b></a><br /></td>
      <td align="center"><a href="https://github.com/Hyun-jun-Lee0811"><img src="https://avatars.githubusercontent.com/u/80097977?v=4" width="150px;" alt=""/><br /><b>BE 이현준</b></a><br /></td>
    </tr>
  </tbody>
</table>

<br>

## 1. 목표와 기능

### 1.1 목표
- **지역 특산주 홍보 및 소비 촉진**: 다양한 지역 특산주를 홍보하거나 리뷰하며, 국내 지역 특산주 소비를 촉진하는 플랫폼 제공
- **맞춤형 음주 경험 제공**: 사용자 위치 기반의 맞춤형 특산주 추천을 통해 사용자에게 새로운 음주 경험을 제공
- **커뮤니티 형성**: 특산주에 대한 리뷰와 정보를 공유하며 사용자 간 활발한 소통이 이루어지는 커뮤니티를 형성
- **지역 경제 활성화**: 특산주 인지도를 높여 지역 경제 및 브랜드 인지도를 높이는 데 기여

<br>

### 1.2 기능

#### 1.2.1 회원 관리
- **회원가입 및 로그인**: 일반 및 소셜(구글) 로그인 지원
    - 필수 입력 데이터: 닉네임, 생년월일, 이메일, 패스워드, 선호 주종
- **비밀번호 재설정**: 이메일을 통해 비밀번호 재설정
- **회원 정보 수정 및 탈퇴**:
    - 프로필, 닉네임, 패스워드, 선호 주종 수정 가능
    - 게시글 및 댓글 작성 시 닉네임을 "탈퇴한 사용자"로 변경

#### 1.2.2 게시글 관리
- **게시글 작성 및 수정**: 특산주 리뷰 및 광고 게시글 작성 가능
    - 사진 등록 및 특산주 검색, 태그 추가, 평점 입력 기능 제공
    - 도배 방지 기능 및 좋아요 토글 지원
    - 최신순/조회순으로 게시글 조회 가능
- **댓글 기능**: 리뷰 및 광고 게시글에 댓글 작성, 수정, 삭제 가능. 익명 작성 지원

#### 1.2.3 특산주 및 태그 관리
- **특산주 등록**: 사용자가 특산주 등록 요청 가능
    - 사진, 이름, 지역, 주종, 도수, 당도, 가격 등 특산주 정보 입력
    - 매니저가 등록 요청을 승인 또는 반려
- **태그 팔로우 및 검색**: 게시글에 입력된 태그 팔로우 및 특산주/태그 검색 지원

#### 1.2.4 추천 기능
- **맞춤형 특산주 추천**:
    - **위치 기반 추천**: 사용자의 위치 정보에 따라 특산주 추천(ON/OFF)
    - **생일 및 매월 추천**: 사용자 생일 및 매월 특산주 추천 이메일 전송
    - **인기 태그 및 특산주 추천**: 인기 상위 태그 및 특산주 15개씩 랜덤 추천

#### 1.2.5 알림 및 신고
- **알림 기능**:
    - 팔로우한 태그가 포함된 게시글 작성 시 알림
    - 사용자가 작성한 게시글에 댓글 작성 시 알림(ON/OFF)
    - 신고 승인 및 반려 결과 알림
    - 특산주 등록 승인 알림
- **신고 기능**:
    - 부적절한 게시글 신고 가능. 매니저가 신고 리스트를 검토하고 처리

#### 1.2.6 커뮤니티 관리
- **FAQ**: 애플리케이션 설명과 기능 사용법 안내
- **공지사항**: 매니저는 공지사항 CRUD 기능 제공, 회원은 조회만 가능

<br>

## 2. Architecture
![아키텍쳐](https://github.com/user-attachments/assets/f82521ed-531b-4e2a-ba49-8ef31549a6d8)

<br>

## 3. ERD
![전통주](https://github.com/user-attachments/assets/1b8ad56e-0539-4e24-bc4d-774f05bdb9d0)

<br>

## 4. 기술 스택

### ✨ Front-End

<div align="center">
  <table>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React"><br />React
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"><br />TypeScript
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge" alt="Axios"><br />Axios
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/emotion-DB7093?style=for-the-badge" alt="Emotion"><br />Emotion
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/shadcn%2Fui-%23383838?style=for-the-badge" alt="Shadcn/UI"><br />Shadcn/UI
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/framer--motion-black?style=for-the-badge&logo=framer&logoColor=blue" alt="Framer Motion"><br />Framer Motion
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/redix--ui-FF477E?style=for-the-badge" alt="Redix UI"><br />Redix UI
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/zustand-%23E15151.svg?style=for-the-badge" alt="Zustand"><br />Zustand
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/tanstack--query-%23FF3E00.svg?style=for-the-badge" alt="TanStack Query"><br />TanStack Query
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/msw-007ACC?style=for-the-badge" alt="MSW"><br />MSW
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"><br />Vercel
      </td>
    </tr>
  </table>
</div>

### ✨ Back-End

<div align="center">
  <table>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white" alt="Java"><br />Java
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"><br />Spring Boot
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white" alt="MariaDB"><br />MariaDB
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white" alt="Gradle"><br />Gradle
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/jpa-%23323330.svg?style=for-the-badge" alt="JPA"><br />JPA
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="JWT"><br />JWT
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/spring--security-6DB33F?style=for-the-badge&logo=spring%20security&logoColor=white" alt="Spring Security"><br />Spring Security
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/spring--batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Batch"><br />Spring Batch
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/OAuth2-3A3A3A?style=for-the-badge&logo=oauth" alt="OAuth2 Client"><br />OAuth2 Client
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit"><br />JUnit
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/Mockito-6DB33F?style=for-the-badge&logo=java&logoColor=white" alt="Mockito"><br />Mockito
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"><br />Redis
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch" alt="ElasticSearch"><br />ElasticSearch
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/swagger-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger"><br />Swagger
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"><br />AWS
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS EC2"><br />AWS EC2
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS S3"><br />AWS S3
      </td>
    </tr>
  </table>
</div>
<br>

## 5. API 명세서
### 🔗 [API 명세서](https://develop-growth.notion.site/One-Drink-Today-9ef0f66fc89e4bbe952db9e05e0e6714?pvs=4)

<br>

## 6. 앱 시연 영상  
| **기능**                          | **영상보기 링크** |
|-----------------------------------|-------------------|
| **회원가입 / 일반 & 소셜 로그인** | [영상보기](https://develop-growth.notion.site/11804c4c306b812a8ae8e2f5555fe43f?pvs=4) |
| **비밀번호 찾기**                 | [영상보기](https://develop-growth.notion.site/11804c4c306b81c5ae01df2c6c6c6455?pvs=4) |
| **마이 페이지**                   | [영상보기](https://develop-growth.notion.site/11804c4c306b81ad94e1df4041da766a?pvs=4) |
| **특산주 등록 / 매니저 승인**     | [영상보기](https://develop-growth.notion.site/11804c4c306b8147bb4aea166568428f?pvs=4) |
| **게시글 / 댓글 작성**            | [영상보기](https://develop-growth.notion.site/11804c4c306b81d19907c3009db1c42e?pvs=4) |
| **특산주 & 태그 검색 / 자동완성** | [영상보기](https://develop-growth.notion.site/11804c4c306b81e1be77c749937d6f5c?pvs=4) |
| **태그 팔로우 추가 / 삭제**       | [영상보기](https://develop-growth.notion.site/11804c4c306b8187a781ff38d058e46d?pvs=4) |
| **알림 확인**                     | [영상보기](https://develop-growth.notion.site/11804c4c306b81ac8fdbe3edb3a1b484?pvs=4) |
| **신고 등록 / 승인**              | [영상보기](https://develop-growth.notion.site/11804c4c306b8148965ce612b61d10d6?pvs=4) |
| **특산주 추천 (지역 / 생일 / 매월)** | [영상보기](https://develop-growth.notion.site/11804c4c306b810c84dad88c125caa0c?pvs=4) |

<br>

## 7. Trouble Shooting 및 회고  
### 🔗 [트러블 슈팅](https://develop-growth.notion.site/a30c421bef1745fc94296595745aa4ff)
### 🔗 [회고](https://develop-growth.notion.site/4d3afdc9157b46ce90e9344c6a1f09f9)
