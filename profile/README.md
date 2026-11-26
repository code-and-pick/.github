<div align="center">

[동성인재개발교육원](https://www.dshrd.or.kr/)<br>
교과과정: [클라우드 AI기반 마이크로서비스 풀스택(리액트/자바) 개발](https://www.work24.go.kr/hr/a/a/3100/selectTracseDetl.do?tracseId=AIG20250000501497&tracseTme=2&cstmConsTme=&crseTracseSe=C0061&trainstCstmrId=&tracseReqstsCd=&focusId=)

<br>

<img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/logo.webp" width="420" alt="PMart 로고">

# PMart

**우리 동네 MFC 재고로 주문받아, 라이더가 바로 가져다주는 퀵 커머스 서비스**

고객 앱 · 라이더 앱 · MFC 앱 · DC/운영 백오피스, 그리고 그 뒤의 Spring Boot 마이크로서비스까지 직접 만들었습니다.

**[팀원 · 담당](#팀)** &nbsp;|&nbsp; **개발 기간** 2026.10.23 ~ 진행 중

</div>

<br>

<!-- [미리보기] 사진·영상이 생기면 이 블록의 주석(맨 위·맨 아래 줄)을 풀고 이미지 주소를 맞춘다. 파일은 profile/images/ (절대 주소로 넣는다)
## 미리보기

▶ 시연 영상: https://youtu.be/영상주소

| 고객 앱 | 라이더 앱 | MFC 앱 |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/customer-home.png" width="220"> | <img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/rider-offer.png" width="220"> | <img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/mfc-picking.png" width="220"> |

| DC 백오피스 | 통합 백오피스 |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/dc-backoffice.png" width="400"> | <img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/backoffice-dashboard.png" width="400"> |
-->

## 주요 기능

- **고객 앱**: 소셜 로그인(Google·카카오·네이버), 상품 검색, 장바구니·쿠폰, 토스페이먼츠 결제, 주문·배송 조회, 리뷰, AI 상담
- **라이더 앱**: 출근·배차 수락, MFC에서 QR로 상품 인계, 길 안내, 배달 완료 사진, 정산
- **MFC 앱 (PDA 앱)**: 피킹·포장, 라이더 인계, 입고·적치, 재고 실사
- **DC 백오피스**: 중앙 물류센터 입고·보충, 출고 작업, 재고·품질 관리
- **운영 백오피스**: 주문·고객·상품·승인·문의 관리, 대시보드 (통합·MFC·CDC·라이더·인사 웹을 한 번 로그인으로 오감)

## 기술 스택

| 분야 | 사용 기술 |
|---|---|
| Backend | <img src="https://img.shields.io/badge/Java-21-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21"> <img src="https://img.shields.io/badge/Spring_Boot-4.0.9-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot 4.0.9"> <img src="https://img.shields.io/badge/Spring_Cloud-2025.1-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Cloud 2025.1"> <img src="https://img.shields.io/badge/Google_OR--Tools-9.15-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google OR-Tools 9.15"> |
| Data · Messaging | <img src="https://img.shields.io/badge/PostgreSQL-17-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL 17"> <img src="https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis 7"> <img src="https://img.shields.io/badge/Apache_Kafka-4.1-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka 4.1"> <img src="https://img.shields.io/badge/Elasticsearch-8.18-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch 8.18"> <img src="https://img.shields.io/badge/Debezium-CDC-91D443?style=flat-square&logo=debezium&logoColor=white" alt="Debezium CDC"> |
| Client | <img src="https://img.shields.io/badge/Flutter-3.47-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter 3.47"> <img src="https://img.shields.io/badge/React-19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19"> <img src="https://img.shields.io/badge/TypeScript-7-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript 7"> <img src="https://img.shields.io/badge/Vite-8-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite 8"> |
| AI | <img src="https://img.shields.io/badge/Ollama-local_LLM-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama local LLM"> <img src="https://img.shields.io/badge/pgvector-RAG-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector RAG"> |
| Infra · 관측 | <img src="https://img.shields.io/badge/Docker-Jib-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Jib"> <img src="https://img.shields.io/badge/Keycloak-SSO-4D4D4D?style=flat-square&logo=keycloak&logoColor=white" alt="Keycloak SSO"> <img src="https://img.shields.io/badge/Prometheus-metrics-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus metrics"> <img src="https://img.shields.io/badge/Grafana-dashboard-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana dashboard"> <img src="https://img.shields.io/badge/Elastic_Stack-logs-005571?style=flat-square&logo=elastic&logoColor=white" alt="Elastic Stack logs"> |
| 협업 | <img src="https://img.shields.io/badge/GitHub-PR-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub PR"> <img src="https://img.shields.io/badge/Gradle-Kotlin_DSL-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle Kotlin DSL"> |

## 프로젝트 구조

```
앱(고객·라이더·MFC) · 백오피스 웹
        │
   API Gateway (인증 · 요청 제한)
        │
   업무 서비스 41개 ── Kafka(이벤트) ── PostgreSQL(서비스마다 따로)
   커머스 · 주문/결제 · MFC · CDC · 배송 · 플랫폼
```

| 저장소 | 내용 |
|---|---|
| [pmart-backend](https://github.com/code-and-pick/pmart-backend) | 백엔드 서비스, 공통 라이브러리, API·이벤트 계약, 설계 문서, 배포 스크립트 |
| [pmart-clients](https://github.com/code-and-pick/pmart-clients) | Flutter 앱(고객·라이더·MFC)과 React 백오피스 웹 5종 |
| [pmart-config](https://github.com/code-and-pick/pmart-config) | 서비스 설정(Spring Cloud Config) |
| [pmart-mfc-simulation](https://github.com/code-and-pick/pmart-mfc-simulation) | MFC 현장 시뮬레이터 |
| [pmart-cdc-simulation](https://github.com/code-and-pick/pmart-cdc-simulation) | 중앙 물류센터(CDC) 시뮬레이터 |
| [pmart-rider-simulation](https://github.com/code-and-pick/pmart-rider-simulation) | 라이더 배달 시뮬레이터 |

## 시작하기

필요한 것: JDK 21, Docker, Flutter 3.47 이상, Node.js 22.12 이상

```bash
# 백엔드
git clone https://github.com/code-and-pick/pmart-backend.git && cd pmart-backend
git clone https://github.com/code-and-pick/pmart-config.git deploy/lan/.config-repo   # 설정
docker compose -f deploy/local/docker-compose.yml up -d                              # PostgreSQL·Kafka·Redis 등
./gradlew :platform-services:config-server:bootRun --args='--spring.profiles.active=local'
./gradlew :services:order-service:bootRun --args='--spring.profiles.active=local'   # 띄울 서비스마다

# 앱 (서버 없이 목 데이터로)
git clone https://github.com/code-and-pick/pmart-clients.git && cd pmart-clients
cd apps/customer_app && flutter run --dart-define=PMART_ENV=mock
npm install && npm run dev -w web/backoffice
```

자세한 내용은 각 저장소 README를 봐 주세요.

## 협업 규칙

- 브랜치는 `<영역>/<주제>` (예: `mfc/picking-queue`)로 만들고 PR로 합칩니다. main에 바로 올리지 않습니다.
- API·이벤트를 바꿀 때는 계약(`contracts/`)부터 고치고 코드를 맞춥니다.
- 커밋 메시지는 `feat(order-service): …`, `fix(…)`, `docs(…)` 처럼 씁니다.
- 다른 영역에 필요한 것은 요청서(`docs/architecture/service-requests/`)로 남깁니다.
<!-- 문의 채널이 정해지면 여기에 한 줄: - 문의: (채널 링크) -->

## 팀

<!-- [사진 자리 5] 팀 사진(선택) — profile/images/team.png 를 올린 뒤 아래 줄의 주석을 푼다 -->
<!-- <p align="center"><img src="https://raw.githubusercontent.com/code-and-pick/.github/main/profile/images/team.png" width="820" alt="팀 사진"></p> -->

### 비즈니스 로직

| 이름 | 담당 |
|---|---|
| 배희지 | Commerce |
| 오화실 | SCM |
| 윤서영 | Delivery, TMS, MFC·DC 규모 |
| 이유현 | MFC |
| 이종근 | WMS |
| 전소영 | OMS |

### 개발

| 이름 | 담당 |
|---|---|
| 배희지 | 플랫폼(로그인·인증, 인사, 승인, API 게이트웨이, 공통 라이브러리, LAN 배포)과 커머스·주문·결제·검색 서비스, 고객 앱 |
| 오화실 | AI 상담(RAG): 운영자·고객 상담 서비스, 지식 색인과 평가 |
| 윤서영 | 라스트마일 배송(배송 지역·배차·배송·추적·라이더) 서비스, 라이더 앱·라이더 백오피스 웹, CDC(중앙 물류센터) 서비스, MFC 시뮬레이터 |
| 이유현 | MFC 서비스(재고·피킹/포장·입고·작업 배정·위치·품질), MFC 앱, MFC 백오피스 웹 |
| 이종근 | 백오피스 서버(backoffice-bff)·상담/사건 서비스, 통합·인사 백오피스 웹, 웹 공통 코드 |
| 전소영 | AI 상담(RAG): 운영자·고객 상담 서비스, 지식 색인과 평가 |


---

<div align="center">

지도: 서성원 훈련 교사

</div>
