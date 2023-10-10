---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: 기술 상세
permalink: /tech/
---

## 프로그래밍 언어

---

### C# - 상  [oldest]
- 마비노기 영웅전 게임 서버의 인 하우스 프레임워크 언어
- asp.net core를 이용한 API 서비스 개발
- GC의 동작 원리/IL code 분석/dump 분석까지 가능하며 최적화와 안정화 경험
- DB 연결을 위한 Linq 문법, 동작 원리를 숙지
- 멀티 스레딩(+lock free), 네트워크 프로그래밍(tcp) 경험
- 간단한 내용은 구글링 없이 구현 가능

### C++ - 중상
- 마비노기 영웅전 게임 클라이언트의 기반 언어 (source engine)
- 멀티 스레딩, 네트워크 프로그래밍(tcp) 경험 (windows iocp base, hole punching 데모 개발)

### Java/Scala - 중  [newest]
- apache flink를 사용하기 위해 입문하여 +1 year 사용
- akka와 백그라운드 스레드 를 이용한 초단위 스케쥴러 구현
- 공식 flink 에서 지원하지 않는 드라이버 자체 개발
- sqs source, mysql sink process function, dynamodb sink, http call sink
- GC 동작 원리/heap & native memory dump 등 jmap, gdb를 이용하여 OOM 해결 경험

### Python - 중하
- 편의/자동화 툴을 만드는 데에 사용

### 기타 스크립트 - 하
- terraform
  - 개발 머신, 프로토타이핑 시 코드 재활용
- flash action script
- informatica (data management solution)

<br />

## 이론/개념
---

### Data streaming processing (apache flink) - 중상
- checkpoint를 이용한 스트리밍 데이터의 무결성 보장 방법을 이해
- state의 활용과 관리 방법 이해
- flink sql 을 이용하여 sql 문으로 실행하는 개념 이해

### 공학 지식 - 중
- aws, gcp 경험
- network programming
- OOP
- tcp, udp, http, https 등 구현 및 서비스 경험
- windows os iocp, rio 이해와 r-udp 방식 이해
- multi-thread programming

<br />

## 데이터베이스 활용
---

### MSSQL/mysql - 중
- RDBMS의 구조를 개인적으로 학습하여 내부구조 개념을 숙지 
- index, stored procedure, execution plan
- 게임 개발 시, 유저의 정보를 담아 OLTP 서비스 경험
- openapi/상품추천 등 분석 서비스 제공 시, 데이터를 저장하고 서빙하는 용도로 사용

### redis - 중
- single instance를 복제하여 사용
- sp 활용 가능하며 redis의 atomic transaction에 대해 이해하고 있음

### hbase - 중
- hbase의 구조(mem table(region server), hdfs)를 이해
- 상품추천 개발 시, 유저의 정보를 담는 용도로 사용

