# 🛟 SwapClass : 수강신청을 구조하는 간편하고 안전한 강의 교환 플랫폼
<img width="1098" height="619" alt="image" src="https://github.com/user-attachments/assets/481222fa-62db-4f74-9ddb-8f8e08f9af45" />  

  
> 2026-1 SOLUX | Team SongWalks <br>
> 기간: 2026.03.29 ~ 2026.08.09

<br></br>
## 🔥 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄

**SwapClass**

기존 익명 커뮤니티 강의 교환의 피로도와 불안감을 해결하기 위해,
교환 매칭부터 실시간 채팅, 강의 보유 자동 인증까지 지원하는 서비스입니다.
<br></br>
### 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗦𝗰𝗵𝗲𝗱𝘂𝗹𝗲

| 🚩 단계 | ⌛ 기간 |
| --- | --- |
| 기획 및 디자인 | 2026.04 ~ 2026.05 |
| 개발 | 2026.06 ~ 2026.08.09 |
| 최종 발표 | 2026.08.10 |

</br></br>
### 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗠𝗼𝘁𝗶𝘃𝗮𝘁𝗶𝗼𝗻

❗ 기존 강의 교환(에브리타임 등)에서 발생하는 문제점

```
- 조건에 맞는 상대를 찾기 위해 게시판을 수시로 확인해야 함 (시간 낭비)
- 쪽지를 주고받으며 강의와 교환 조건을 일일이 확인해야 함 (소통의 피로도)
- 익명 거래 특성상 상대가 약속대로 진행할지 알 수 없어 불안함 (신뢰도의 부재)

```

❗ 이에 대한 해결책

```
- 자동 추천 매칭 시스템
   - 희망 과목 1~3순위와 버릴 과목을 기반으로 최적의 상대 자동 추천
- 묻고 답하는 과정을 줄이는 간편한 교환
   - 실시간 채팅방 내에서 교환 시간 조율 및 상태 머신(예약/인증/카운트다운) 동기화
- 교환 전후를 확인하는 거래 안전 장치
   - 화면 공유를 통한 수강 내역 및 QR 코드 자동 캡처·검증
   - 양측 인증 완료 시 10초 동기화 카운트다운을 통한 동시 교환 지원

```
<br></br>
## 📊 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗗𝗶𝗮𝗴𝗿𝗮𝗺𝘀
### 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗔𝗿𝗰𝗵𝗶𝘁𝗲𝗰𝘁𝘂𝗿𝗲
<img width="2667" height="1500" alt="image" src="https://github.com/user-attachments/assets/c51cdf88-d025-486a-a4c6-f669c52a6c9d" />

<br></br>
### 𝗘𝘅𝗰𝗵𝗮𝗻𝗴𝗲 𝗙𝗹𝗼𝘄 & 𝗦𝘁𝗮𝘁𝗲 𝗠𝗮𝗰𝗵𝗶𝗻𝗲

```
게시글 등록 (버릴 과목 + 희망 과목 1~3순위)
    ↓
추천 매칭 및 교환 요청 (매칭 대기)
    ↓
[CHATTING] 실시간 채팅 및 시간 조율
    ↓
[SCHEDULED] 교환 시간 확정 (상태 동기화)
    ↓
[VERIFYING] 교환 5분 전 화면 공유 QR 인증 시작
    ↓
[COUNTDOWN] 양측 인증 완료 시 10초 동기화 카운트다운
    ↓
[DONE] 교환 완료 (또는 거래 파기 시 CANCELED 전환)

```
<br></br>
## 💡 𝗞𝗲𝘆 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀

| 기능 | 설명 |
| --- | --- |
| 🔍 자동 추천 매칭 | 등록된 버릴 과목과 타겟 과목 데이터를 분석하여 최적의 교환 대상자를 추천 |
| 💬 실시간 교환 채팅 | WebSocket(STOMP) 기반 지연 없는 실시간 1:1 채팅 및 상태 동기화 UI 제공 |
| 🛡️ 화면 공유 QR 인증 | 화면 공유로 수강 내역과 발급된 QR 코드를 동시 캡처하여 허위 매물 방지 |
| ⏱️ 동기화 카운트다운 | 양측 유저 인증 완료 시 10초 타이머 오버레이로 안전한 동시 교환(취소/신청) 지원 |
| 🔔 동적 알림 배너 | 교환 약속 시간에 맞춰 홈 화면에 동적 디데이(D-Day) 및 알림 배너 제공 |
| ☕ 라운지 커뮤니티 | 강의 꿀팁, 폐강 정보 등을 자유롭게 공유할 수 있는 소통 공간 |
| 🎓 졸업 요건 관리 | 졸업에 필요한 과목을 미리 등록하고 이수 여부를 체계적으로 관리 |
| 🚨 신고 및 분쟁 조정 | 교환 실패 시 수강 취소 내역을 재인증받아 잘잘못을 가려내는 분쟁 조정 시스템 |

<br></br>
## 🛠️ 𝗧𝗲𝗰𝗵 𝗦𝘁𝗮𝗰𝗸

### 💻 Frontend
| 분류 | 기술 |
|---|---|
| Language | TypeScript |
| Library | React |
| State | TanStack Query |
| Styling | Tailwind CSS |
| Build | Vite |
| Runtime | Node.js |
| HTTP | Axios |

### ⚙️ Backend
| 분류 | 기술 |
|---|---|
| Language | Java 17 |
| Framework | Spring Boot 3 |
| ORM | Spring Data JPA |
| Database | MySQL |
| Cache | Redis |
| Auth | Spring Security · JWT |
| Realtime | WebSocket (STOMP) |
| Storage | AWS S3 |
| Infra | AWS EC2 · Nginx |
| CI/CD | GitHub Actions |
| Push | FCM (Firebase Cloud Messaging) |

</br></br>
## 🎥 𝗗𝗲𝗺𝗼 𝗩𝗶𝗱𝗲𝗼
[![Demo Video](https://img.youtube.com/vi/ThDeejwzZzE/maxresdefault.jpg)](https://youtu.be/ThDeejwzZzE)

</br></br>
## 📷 𝗦𝗰𝗿𝗲𝗲𝗻𝘀𝗵𝗼𝘁𝘀

| 로그인/회원가입 | 홈 화면 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/713bf9c7-1c75-4d88-8d73-ce06893e7b1e" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/28dbc0a6-fc05-414a-85fc-a39cf69882f7" width="190" /> | <img src="https://github.com/user-attachments/assets/b95a0e67-8a22-42e4-bc97-e408f741e97c" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/73c5854a-337b-4b52-8836-7628ba7e87a7" width="190" /> |
| 숙명 이메일 인증 기반<br>회원가입 및 로그인 | D-Day 배너, 추천 매칭 피드,<br>수강 교환 요청 내역 |

<br>

| 교환 채팅방 | QR 자동 인증 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/20518cd2-a4bf-4590-b653-e13801bd4f7e" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/c0da9ecb-1526-4a88-8035-264807afa39e" width="190" /> | <img src="https://github.com/user-attachments/assets/a4030660-9e28-4b5f-ae7d-bfe0f6abd446" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/204136bb-4feb-4344-ac60-85d00f6b893d" width="190" /> |
| 실시간 시간 조율, 거래 파기,<br>상태 머신 동기화 UI | PC 화면 공유 기반 수강 내역 및<br>QR 캡처, 동기화 카운트다운 |

<br>

| 게시판 | 라운지 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/01a7b462-8adb-4844-9ddc-f4f9e73f4bf5" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/17c0edcc-0278-40d8-b701-de039bb3ab7c" width="190" /> | <img src="https://github.com/user-attachments/assets/e096f803-6e25-4642-a45d-1daa1a9c44f1" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/348cebf6-9cce-4e4d-9f72-e7479a9dbf6b" width="190" /> |
| 내 타겟/버릴 과목 필터링,<br>희망 순위 지정 교환글 작성 | 강의 꿀팁 및 폐강 정보<br>공유 커뮤니티 |

<br>

| 마이페이지 |
| :---: |
| <img src="https://github.com/user-attachments/assets/8d5baa32-3df9-4c96-bc5d-717b5bb53fd4" width="190" />&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/68729956-c538-4ee4-94ef-3f4553e29491" width="190" /> |
| 교환 활동 내역, 북마크,<br>계정 설정 및 알림 관리 |

<br></br>
## 👥 𝗧𝗲𝗮𝗺

| 이름 | 담당 |
| --- | --- |
| 인영서 | 서비스 기획, 사용자 플로우 설계 (팀장) |
| 정현서 | Design - 로고, 서비스 디자인 |
| 강유나 | Frontend - 마이페이지, 게시글, 교환요청함, 교환 추천 매칭함 |
| 박지아 | Frontend - 계정 관련, 교환채팅방, 알림함 |
| 송유진 | Frontend - 라운지, 홈화면, 신고 화면 |
| 이지현 | Backend - 알림/FCM, 신고/차단, QR 인증, 상태머신, 스케줄러 |
| 이지민 | Backend - 인증/회원, 게시글, 교환요청, 마이페이지, 라운지 |

<br></br>
## 🔗 𝗥𝗲𝘀𝗼𝘂𝗿𝗰𝗲𝘀

* [Frontend Repository](https://github.com/SongWalks/31th_1_songwalks_swapclass_front.git)
* [Backend Repository](https://github.com/SongWalks/31th_1_songwalks_swapclass_back.git)
* [서비스 배포 링크](https://soo-frontend-brown.vercel.app)
