<div align="center">

# 🎬 모두의 플리 (Mople)

**대규모 트래픽이 예상되는 글로벌 콘텐츠 평점 플랫폼**

영화·드라마·스포츠 등 다양한 콘텐츠를 큐레이팅하고 공유하며,<br/>
실시간 같이 보기 기능까지 제공하는 소셜 콘텐츠 서비스입니다.

<br/>

![Coverage](https://img.shields.io/badge/coverage-line%2080%25-brightgreen?style=flat-square)
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.16-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-9.5.1-02303A?style=flat-square&logo=gradle&logoColor=white)
![License](https://img.shields.io/badge/team-6%20backend-blue?style=flat-square)

<br/>

<img width="1200" height="1310" alt="4컷(4)" src="https://github.com/user-attachments/assets/c019b2d2-0649-4375-aeb3-2f4f608fd27b" />

<br/><br/>

[프로젝트 소개](#-프로젝트-소개) · [팀원](#-팀원-소개) · [기술 스택](#-기술-스택) · [브랜치 전략](#-브랜치-전략--커밋-컨벤션)<br/>
[프로젝트 구조](#-프로젝트-구조) · [주요 기능](#-주요-기능) · [API](#-api) · [CI/CD](#️-cicd--테스트) · [문서](#-문서)

</div>

<br/>

---

## 📌 프로젝트 소개

<table>
<tr><td width="140"><b>프로젝트명</b></td><td>모두의 플리 (Mople)</td></tr>
<tr><td><b>진행 기간</b></td><td>2026.07.27 ~ 2026.08.28 (4.5주)</td></tr>
<tr><td><b>팀 구성</b></td><td>6인 (Backend)</td></tr>
<tr><td><b>저장소</b></td><td><code>dkegldh/sb11-mople-team2</code></td></tr>
<tr><td><b>프로젝트 목표</b></td><td>인증/인가 설계 · 복잡한 DB 설계 · 실시간 통신 구현 · 분산 환경 설계 · 안정성 확보</td></tr>
</table>

<br/>

---

## 👥 팀원 소개

<table>
<tr>
  <td align="center" width="150">
    <a href="https://github.com/dkegldh"><img src="https://github.com/dkegldh.png" width="90"/><br/><b>김진혁</b></a><br/>
    <sub>@dkegldh</sub>
  </td>
  <td align="center" width="150">
    <a href="https://github.com/jsKim1219"><img src="https://github.com/jsKim1219.png" width="90"/><br/><b>김지성</b></a><br/>
    <sub>@jsKim1219</sub>
  </td>
  <td align="center" width="150">
    <a href="https://github.com/eomoff"><img src="https://github.com/eomoff.png" width="90"/><br/><b>엄주혁</b></a><br/>
    <sub>@eomoff</sub>
  </td>
  <td align="center" width="150">
    <a href="https://github.com/DonToong2"><img src="https://github.com/DonToong2.png" width="90"/><br/><b>김명근</b></a><br/>
    <sub>@DonToong2</sub>
  </td>
  <td align="center" width="150">
    <a href="https://github.com/seongmin0244"><img src="https://github.com/seongmin0244.png" width="90"/><br/><b>강성민</b></a><br/>
    <sub>@seongmin0244</sub>
  </td>
  <td align="center" width="150">
    <a href="https://github.com/vincent865"><img src="https://github.com/vincent865.png" width="90"/><br/><b>노정빈</b></a><br/>
    <sub>@vincent865</sub>
  </td>
</tr>
<tr>
  <td align="center"><sub>인증·인가<br/>JWT · OAuth2<br/>사용자<br/>ECS · CD 인프라</sub></td>
  <td align="center"><sub>콘텐츠<br/>외부 API 연동<br/>수집 배치<br/>실시간 같이 보기</sub></td>
  <td align="center"><sub>팔로우<br/>플레이리스트<br/>Kafka 발행·소비<br/>Redis 락·캐시</sub></td>
  <td align="center"><sub>리뷰<br/>플레이리스트<br/>Kafka 발행·소비<br/>Elasticsearch 매핑</sub></td>
  <td align="center"><sub>DM 대화방<br/>다이렉트 메시지<br/>WebSocket<br/>SSE</sub></td>
  <td align="center"><sub>사용자 관리<br/>어드민<br/>알림<br/>SSE</sub></td>
</tr>
</table>

<br/>

---

## 🛠 기술 스택

| 분류 | 기술 |
|:---|:---|
| **Language & Framework** | ![Java](https://img.shields.io/badge/Java%2017-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) ![Spring Batch](https://img.shields.io/badge/Spring%20Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white) |
| **Database & ORM** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL%2016-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![JPA](https://img.shields.io/badge/Spring%20Data%20JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=for-the-badge) ![Redis](https://img.shields.io/badge/Redis%207-FF4438?style=for-the-badge&logo=redis&logoColor=white) |
| **Real-time & Messaging** | ![WebSocket](https://img.shields.io/badge/WebSocket%20(STOMP)-010101?style=for-the-badge) ![SSE](https://img.shields.io/badge/SSE-FF6C37?style=for-the-badge) ![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch%208-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) |
| **Auth & External** | ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2%20(Google·Kakao)-4285F4?style=for-the-badge&logo=google&logoColor=white) ![TMDB](https://img.shields.io/badge/TMDB-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white) ![OpenFeign](https://img.shields.io/badge/OpenFeign-6DB33F?style=for-the-badge&logo=spring&logoColor=white) |
| **Infra & Deploy** | ![AWS](https://img.shields.io/badge/AWS%20ECS%20·%20ECR%20·%20S3-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Test & Docs** | ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white) ![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3E?style=for-the-badge&logo=testcontainers&logoColor=white) ![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) |

<br/>

---

## 🌿 브랜치 전략 & 커밋 컨벤션

```
main (production)
└── develop (staging)
    └── {type}/{#이슈번호}-{기능명}
        예) feature/#5-user-register, fix/#12-login-bug
```

| 항목 | 규칙 |
|:---|:---|
| **type** | `feature` `fix` `refactor` `docs` `test` `chore` `batch` `deploy` |
| **push** | `develop` · `main` 직접 push 금지 — fork에서 작업 후 upstream `develop`으로 PR |
| **머지** | **2인 이상** 리뷰 승인 후 **Squash and Merge** (PR 제목 = squash 커밋 메시지) |
| **이슈 제목** | `[FEAT] 팔로우 생성 구현` |
| **커밋 메시지** | `feat: 팔로우 생성 구현` · `fix: 중복 구독 방지 버그 수정` |

<br/>

---

## 📁 프로젝트 구조

```
com.codeit.mople
├── domain
│   ├── auth              # 로그인·토큰 재발급·비밀번호 초기화·OAuth2
│   ├── user              # 회원가입·프로필·어드민(권한/잠금)
│   ├── content           # 콘텐츠 CRUD + TMDB·SportsDB 수집 배치
│   ├── review            # 평점·의견
│   ├── playlist          # 플레이리스트·콘텐츠 연결·구독
│   ├── follow            # 팔로우
│   ├── conversation      # DM 대화방
│   ├── directmessage     # 다이렉트 메시지
│   ├── notification      # 알림 (이벤트 기반, SSE 전달)
│   └── watchingsession   # 실시간 같이 보기 · 콘텐츠 채팅
├── realtime              # WebSocket 세션 레지스트리 · 강제 종료
└── global                # config · error · event · jwt · sse · storage …
```

각 도메인은 `controller → service → repository` 레이어와
`controller/api`(Swagger 인터페이스) · `dto`(record) · `entity` · `exception` 서브패키지로 구성합니다.

<br/>

---

## ✨ 주요 기능

| 도메인 | 기능 |
|:---|:---|
| **인증** | JWT 로그인·토큰 재발급, Google/Kakao 소셜 로그인, 비밀번호 초기화(메일), 재로그인 시 기존 기기 세션 무효화 |
| **사용자** | 회원가입, 프로필 수정(S3 이미지), 어드민 권한 변경·계정 잠금 |
| **콘텐츠** | 콘텐츠 CRUD(어드민), TMDB·SportsDB 수집 배치, Elasticsearch 검색 |
| **평가** | 평점·의견 CRUD, 콘텐츠 평균 평점·리뷰 수 집계 |
| **큐레이팅** | 플레이리스트 CRUD, 콘텐츠 추가/삭제, 구독 |
| **소셜** | 팔로우·팔로우 취소, 팔로우 알림 |
| **같이 보기** | 시청 세션 입장/퇴장 브로드캐스트, 콘텐츠 실시간 채팅 |
| **DM** | WebSocket 실시간 전송 + SSE 대화 목록 갱신, Redis 읽음 워터마크 |
| **알림** | 권한 변경·구독·팔로우·DM 이벤트를 SSE로 실시간 전달 |

> 배치 Job은 `tmdbCollectJob`(TMDB 영화·시리즈), `sportsContentJob`(스포츠) 두 개입니다.

<br/>

---

## 📋 API

| 항목 | 내용 |

| **인증** | `Authorization: Bearer {accessToken}` + CSRF(`XSRF-TOKEN` 쿠키 → `X-XSRF-TOKEN` 헤더)<br/>리프레시 토큰은 `REFRESH_TOKEN` 쿠키 |
| **목록 조회** | `cursor` + `idAfter` 복합 커서 페이지네이션 |
| **에러 응답** | `{ "success": false, "error": { "code": "FOLLOW-002", "message": "..." } }`<br/>성공 응답은 DTO를 그대로 반환 |
| **SSE** | `GET /api/sse` — `notifications`, `direct-messages` 이벤트 |
| **WebSocket** | `/ws` (STOMP over SockJS) — 구독 `/sub/...`, 발행 `/pub/...` |

<br/>

---

## ⚙️ CI/CD & 테스트

| 워크플로우 | 트리거 | 내용 |
|:---|:---|:---|
| `ci.yml` | `main`·`develop` PR / push | 빌드 + 테스트 + 커버리지 검증 |
| `cd.yml` | CI 성공 후 `main` push | 이미지 빌드 → ECR → ECS Fargate 배포 |
| `promote-to-main.yml` | `develop` 머지 | 검증된 커밋만 `main`으로 승격 |

테스트는 `service/`(Mockito) · `repository/`(`@DataJpaTest`) · `controller/`(`@WebMvcTest`) · `batch/`(`@SpringBatchTest`)로 나뉘고,
실시간·Redis 통합 테스트는 Testcontainers를 씁니다.
커버리지는 `domain/**/service/**`의 **클래스별 라인 80%** 미만이면 `check`가 실패합니다.

<br/>

---

## 📚 문서

| 문서 | 내용 |
|:---|:---|
| [`doc.md`](./doc.md) | 프로젝트 요구사항 |
| [`api.md`](./api.md) | API 명세 — **계약의 기준** |
| [`erd.md`](./erd.md) | ERD 다이어그램 및 컬럼 정의 |
| [`conventions.md`](./conventions.md) | 팀 개발 컨벤션 |
