# 🥂 오늘 한 잔

## 📌 프로젝트 개요

`오늘 한 잔`은 다양한 지역 특산주를 홍보하거나 리뷰하며 
국내 지역 특산주 소비를 촉진하는 플랫폼 입니다.

- 지역별 다양한 특산주 리뷰와 홍보를 통해 국내 술에 대한 알찬 정보와 유용한 커뮤니티 경험을 할 수 있도록 도와줍니다.
- 특산주 정보 제공, 시음 리뷰 작성, 사용자 기호에 맞는 추천 등으로 지역 특산주를 더욱 활기차게 경험해보세요!

### ❓이 저장소는

본 README는 제가 담당한 작업 위주로 작성되었습니다.</br>
백엔드 및 전체 프로젝트의 상세 내용은 아래 링크를 참고해 주세요!

### 🔗 [프로젝트 노션 바로가기(상세 설명)](https://develop-growth.notion.site/One-Drink-Today-9ef0f66fc89e4bbe952db9e05e0e6714?pvs=4)
### 🔗 [GitHub 바로가기](https://github.com/coding-bankatgan/Front-end)

<br>

## 🚀 주요 기능

### 📝 게시글 및 댓글 수정
- 사용자가 작성한 게시글과 댓글을 수정할 수 있는 기능 구현
- 상태 관리 (useState, Context API 활용)
- API 연동 및 비동기 데이터 처리

### 🔔 알림 시스템
- 새로운 댓글, 공지 사항 등 주요 이벤트 발생 시 사용자에게 알림 제공
- WebSocket을 활용한 실시간 알림 (적용 여부 확인 필요)
- React Notification 라이브러리 활용 가능

### 👤 마이페이지
- 사용자 프로필 조회 및 수정 기능 제공
- 계정 설정 및 활동 내역 조회 기능 구현
- TypeScript의 Interface를 활용하여 데이터 구조 정의

### 📢 기타 기능
- **공지사항 관리**: 관리자가 공지를 등록, 수정, 삭제 가능
- **특산주 신청**: 신청 폼 개발 및 백엔드 연동
- **신고 기능**: 사용자 신고 기능 추가, API 연동 및 UI 개발

<br>

## 🏗️ Architecture
![아키텍쳐](https://github.com/user-attachments/assets/f82521ed-531b-4e2a-ba49-8ef31549a6d8)

<br>

## 🛠 사용 기술

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

<br>

## 🎥 앱 시연 영상  
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

## ❗ Trouble Shooting 및 회고  
### 🔗 [트러블 슈팅](https://develop-growth.notion.site/a30c421bef1745fc94296595745aa4ff)
### 🔗 [회고](https://develop-growth.notion.site/4d3afdc9157b46ce90e9344c6a1f09f9)
