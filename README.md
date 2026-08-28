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

<img width="1200" height="1310" alt="4컷(4)" src="https://github.com/user-attachments/assets/3694bc6e-d3a9-4364-b568-25eba69dc692" />

<br/><br/>

[프로젝트 소개](#-프로젝트-소개) · [팀원](#-팀원-소개) · [기술 스택](#-기술-스택)<br/>
[브랜치 전략](#-브랜치-전략--커밋-컨벤션) · [프로젝트 구조](#-프로젝트-구조) · [주요 기능](#-주요-기능) · [CI/CD](#️-cicd--테스트)

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
  <td align="center"><sub>콘텐츠<br/>외부 API(SportDB)<br/>수집 배치<br/>실시간 같이 보기</sub></td>
  <td align="center"><sub>팔로우<br/>플레이리스트<br/>외부 API(TMDB)<br/>Kafka 발행·소비<br/>Redis 락·캐시</sub></td>
  <td align="center"><sub>리뷰<br/>플레이리스트<br/>Kafka 발행·소비<br/>Elasticsearch 매핑</sub></td>
  <td align="center"><sub>DM 대화방<br/>다이렉트 메시지<br/>WebSocket<br/>SSE</sub></td>
  <td align="center"><sub>사용자 관리<br/>어드민<br/>알림<br/>SSE</sub></td>
</tr>
</table>

<br/>

---

## 🛠 기술 스택

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,gradle,postgres,redis,kafka,elasticsearch,docker,aws,nginx,githubactions,prometheus&perline=6" alt="기술 스택"/>

</div>

<br/>

| 분류 | 상세 |
|:---|:---|
| **Language & Framework** | Java 17 · Spring Boot 3.5.16 · Spring Security · Spring Batch · Spring Cloud 2025.0.1 |
| **Database & ORM** | PostgreSQL 16 · Spring Data JPA · QueryDSL 5.0.0 · Redis 7 · H2(테스트) |
| **Real-time & Messaging** | WebSocket(STOMP over SockJS) · SSE · Apache Kafka 3.9.0 · Elasticsearch 8.18.8 |
| **Auth & External API** | JWT(jjwt) · OAuth2(Google · Kakao) · TMDB · The Sports DB · OpenFeign |
| **Infra & Deploy** | AWS ECS Fargate · ECR · S3 · Docker · Docker Compose · Nginx · GitHub Actions |
| **Test & Monitoring** | JUnit 5 · Mockito · Testcontainers · JaCoCo · k6 · Actuator · Prometheus · Swagger |

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

| 도메인        | 기능 |
|:--------------|:---|
| **인증**      | JWT 로그인·토큰 재발급, Google/Kakao 소셜 로그인, 비밀번호 초기화(메일), 재로그인 시 기존 기기 세션 무효화 |
| **사용자**    | 회원가입, 프로필 수정(S3 이미지), 어드민 권한 변경·계정 잠금 |
| **콘텐츠**    | 콘텐츠 CRUD(어드민), TMDB·SportsDB 수집 배치, Elasticsearch 검색 |
| **평가**      | 평점·의견 CRUD, 콘텐츠 평균 평점·리뷰 수 집계 |
| **큐레이팅**  | 플레이리스트 CRUD, 콘텐츠 추가/삭제, 구독 |
| **소셜**      | 팔로우·팔로우 취소, 팔로우 알림 |
| **같이 보기** | 시청 세션 입장/퇴장 브로드캐스트, 콘텐츠 실시간 채팅 |
| **DM**        | WebSocket 실시간 전송 + SSE 대화 목록 갱신, Redis 읽음 워터마크 |
| **알림**      | 권한 변경·구독·팔로우·DM 이벤트를 SSE로 실시간 전달 |

> 배치 Job은 `tmdbCollectJob`(TMDB 영화·시리즈), `sportsContentJob`(스포츠) 두 개입니다.

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
