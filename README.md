## 🚀 프로젝트 소개

모던 애자일 11기 메인 프로젝트 "점메추(lunchmate)"의 백엔드 리포지토리입니다.

> "오늘 점심 누구랑 먹지?"

점메추는 같이 점심 먹을 사람을 찾는 **밥약 방**, 맛집과 일상을 나누는 **커뮤니티**, 오늘의 **학식 정보**를 한곳에서 제공하는 서비스입니다.
혼자 밥 먹기 애매한 순간, 방을 만들거나 빠르게 참여해 함께 식사할 사람을 모을 수 있습니다.

### 📅 개발 기간

2026.04 ~ 2026.08

### ✨ 주요 기능

- **밥약 방**: 방 생성 · 참여 · 나가기 · 빠른 참여, 방장 강제퇴장, 약속 시간이 지난 방 자동 정리
- **실시간 동기화**: Socket.io로 방 멤버 입장 · 퇴장을 실시간 반영
- **커뮤니티**: 카테고리별 게시글 · 댓글 작성, 익명 작성, 좋아요, 조회수
- **학식**: 학식 메뉴와 구성 정보 조회, 좋아요 · 싫어요 반응과 랭킹
- **친구**: 유저 검색, 친구 신청 · 수락 · 거절
- **인증**: Google · Kakao 소셜 로그인, 역할 기반 권한 관리

### 🏗️ 인프라

GitHub Actions에서 테스트를 통과하면 Docker 이미지를 빌드해 ECR에 올리고 EC2에 자동 배포합니다.
Nginx + Certbot으로 HTTPS를 적용하고, 개발 / 운영 환경을 분리해 운영합니다.

## 🛠️ 기술 스택

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

## 🫱🏻‍🫲🏻 멤버

<table>
  <tr>
    <td align="center" width="200px">
      <img src="https://github.com/imdongyoung.png" />
      임동영<br/>
      <b>imdongyoung</b><br/>
      <a href="https://github.com/imdongyoung">@imdongyoung</a>
    </td>
    <td align="center" width="200px">
      <img src="https://github.com/hawon6691.png" />
      서하원<br/>
      <b>hawon6691</b><br/>
      <a href="https://github.com/hawon6691">@hawon6691</a>
    </td>
  </tr>
</table>
