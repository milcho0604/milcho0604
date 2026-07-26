<div align="center">

# Changhyun Kim

### Backend Engineer · Reliability · Observability

“누군가 하겠지”를 기다리지 않습니다. 문제를 재현하고, 측정하고, 직접 해결합니다.<br>
I don’t wait for someone else to solve it. I reproduce the problem, measure it, and build the solution myself.

[![GitHub](https://img.shields.io/badge/GitHub-milcho0604-181717?style=flat-square&logo=github)](https://github.com/milcho0604)
[![Email](https://img.shields.io/badge/Email-milcho0604%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:milcho0604@gmail.com)
[![Velog](https://img.shields.io/badge/Velog-Technical_Writing-20C997?style=flat-square&logo=velog&logoColor=white)](https://velog.io/@milcho0604/posts)

</div>

## About me

협업툴 **FLOW**의 백엔드 개발자로 일하며, 메시징 신뢰성·성능·관측 가능성과 운영 자동화에 관심이 많습니다.<br>
불편을 발견하면 재현 가능한 증거를 만들고, 코드와 도구로 끝까지 해결하는 편입니다.

I am a backend engineer working on **FLOW**, a collaboration platform. My interests include messaging reliability, performance, observability, and operational automation. I enjoy turning hard-to-reproduce production problems into measurable evidence and maintainable solutions.

## Featured project — [모일까? (moilga)](https://moilga.com)

> 친구들이 모일 날짜를 회원가입 없이 링크 하나로 정하는 실시간 일정 투표 서비스<br>
> A real-time group scheduling app that works with one link and no sign-up.

[**Live service**](https://moilga.com) · [**Source code**](https://github.com/milcho0604/daypoll)

<p align="center">
  <img src="assets/moilga-main.png" alt="moilga latest main screen" width="320">
  &nbsp;
  <img src="assets/moilga-results.png" alt="moilga live poll results with ranked dates" width="320">
</p>

- 날짜별·사람별 실시간 투표, 동률 순위, 불참 표시, 일정 확정과 `.ics` 내보내기를 제공합니다.
- 닉네임과 선택형 PIN만 사용하며, 같은 사용자의 여러 기기 복원과 실시간 동기화를 지원합니다.
- API·DB·백업은 Docker로 직접 운영하고, Cloudflare Tunnel을 통해 외부 인바운드 포트 없이 공개합니다.
- CI, 배포, 인증서 만료 확인, uptime 점검, DB 백업과 오래된 데이터 정리를 자동화했습니다.
- Built with **Next.js 16, NestJS 11, PostgreSQL 16, Socket.IO, Docker, Cloudflare, Vercel, and GitHub Actions**.

## Open source contributions

| Project | Contribution | Link |
|---|---|---|
| **VeXell/pm2-prom-module** | Fixed stale dynamic metric snapshots when a metric becomes an empty series. | [Merged PR #16](https://github.com/VeXell/pm2-prom-module/pull/16) |
| **VeXell/pm2-prom-module-client** | Replaced an `any` IPC metrics payload with a type inferred from `prom-client`. | [Merged PR #1](https://github.com/VeXell/pm2-prom-module-client/pull/1) |
| **prometheus/client_js** | Exported public metric types and added TypeScript consumer coverage. | [Approved PR #786](https://github.com/prometheus/client_js/pull/786) |
| **Microsoft TypeScript Website** | Documented implicit export visibility in declaration-file modules with verified examples. | [PR #3615 · review pending](https://github.com/microsoft/TypeScript-Website/pull/3615) |

## Selected projects

| Project | What I built | Stack |
|---|---|---|
| [**TODAKTODAK**](https://github.com/milcho0604/TodakTodak_backend) | 병원 예약·관리 플랫폼 / Hospital reservation and management platform ([Frontend](https://github.com/milcho0604/TodakTodak_frontend)) | Spring, Vue.js, Kubernetes, Kafka, Prometheus, Grafana |
| [**MealPlan**](https://github.com/milcho0604/MealPlanning) | 식단 계획 모바일 앱 / Mobile meal-planning app | React Native, NestJS, Turborepo, Supabase |
| **Published Chrome Extensions** | [Universal Decoder](https://github.com/milcho0604/universal-decoder): 인코딩 자동 감지·디코딩 · [Emoji Pocket](https://github.com/milcho0604/EMOJI-POCKET): 빠른 이모지 검색 | Chrome Extension, TypeScript |

## Tech I work with

| Area | Technologies |
|---|---|
| **Backend** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Data & messaging** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) |
| **Platform & operations** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) |
| **Frontend & mobile** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=000) |

<details>
<summary>More activity</summary>

<br>

[![Solved.ac profile](http://mazassumnida.wtf/api/generate_badge?boj=golf1585)](https://solved.ac/golf1585)

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/milcho0604" width="600" alt="GitAnimals farm">
</a>

</details>
