# PMart

도심 소형 풀필먼트 센터(MFC)를 기반으로 한 **퀵 커머스(즉시·예약 배달) 플랫폼**입니다.
고객 주문부터 중앙 물류센터(CDC) 재고·간선 운송, MFC 피킹·포장, 라이더 배달까지 하나의 흐름으로 다룹니다.

## 저장소
| 저장소 | 내용 |
|---|---|
| [pmart-backend](https://github.com/code-and-pick/pmart-backend) | Spring Boot 마이크로서비스 백엔드 (Java 21, Gradle Multi-Project) — 커머스·주문/결제·CDC WMS·MFC·간선 운송·라스트마일 배송·플랫폼 |
| [pmart-clients](https://github.com/code-and-pick/pmart-clients) | 고객·라이더·MFC 앱과 백오피스 웹 |
| [pmart-config](https://github.com/code-and-pick/pmart-config) | Spring Cloud Config 설정 저장소 (서비스별 local·lan·prod 프로필) |
| [pmart-mfc-simulation](https://github.com/code-and-pick/pmart-mfc-simulation) | MFC 현장 시뮬레이터 — 실제 센터 대신 피킹·포장·입고 작업을 화면으로 재현해 백엔드와 연결 |
| [pmart-cdc-simulation](https://github.com/code-and-pick/pmart-cdc-simulation) | CDC(중앙 물류센터) 시뮬레이터 |
| [pmart-rider-simulation](https://github.com/code-and-pick/pmart-rider-simulation) | 라이더 배달 시뮬레이터 |

## 기술 스택
- **백엔드**: Java 21 · Spring Boot · Spring Cloud Gateway · Spring Security(OAuth2/OIDC) · PostgreSQL · Flyway · Redis · Apache Kafka(KRaft) · Debezium(Outbox)
- **관측**: Micrometer · OpenTelemetry · Zipkin · Prometheus · Grafana · Elastic Stack
- **검색·AI**: Elasticsearch · 의미 검색·AI 상담(RAG)
- **빌드·배포**: Gradle(Kotlin DSL) · Jib · Docker · Testcontainers

---

- 동성인재개발교육원 — https://www.dshrd.or.kr/
- 지도: 서성원 훈련 교사
