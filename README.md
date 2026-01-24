# cs-study
cs 스터디 용 리포지토리입니다!

# 기본 학습 목차 내용입니다!!

# DB

## DB-1. 데이터 모델링과 설계

- ERD, 정규화/비정규화
- 키(Primary/Foreign/Unique), 제약조건
- 관계(1:1, 1:N, N:M), 조인 설계

## DB-2. SQL 기초와 쿼리 사고

- SELECT/WHERE/GROUP BY/HAVING/ORDER BY
- JOIN(Inner/Left), Subquery, CTE
- Window Function(OVER, PARTITION BY)

## DB-3. 인덱스와 실행 계획

- B-Tree 인덱스 구조, 카디널리티
- Composite index, covering index
- 실행계획(Explain), 인덱스가 안 타는 케이스

## DB-4. 트랜잭션과 동시성

- ACID, commit/rollback
- 격리수준(Read Committed, Repeatable Read, Serializable)
- Lock(Shared/Exclusive), MVCC, Deadlock

## DB-5. 저장구조와 성능 튜닝

- 페이지/버퍼풀, WAL/Redo log
- I/O 병목, 쿼리 튜닝 패턴
- 파티셔닝/샤딩(개념 레벨)

## DB-6. 분산/운영 관점

- Replication(비동기/동기), Failover
- 백업/복구 전략
- 데이터 마이그레이션(dual write/backfill 개념)

# OS

## OS-1. 프로세스와 스레드

- 프로세스/스레드 차이
- 컨텍스트 스위칭
- 사용자/커널 모드

## OS-2. CPU 스케줄링

- FCFS, SJF, RR, Priority
- Throughput/Latency/Starvation
- 멀티코어/캐시 관점(개념)

## OS-3. 동기화와 경쟁 상태

- Race condition, Critical section
- Mutex/Semaphore/Monitor/Condition Variable
- Deadlock(조건, 예방/회피/탐지)

## OS-4. 메모리 관리

- 주소공간, 스택/힙
- 페이징/세그먼테이션
- 가상메모리, 페이지 폴트, TLB

## OS-5. 파일 시스템과 I/O

- 파일/디렉터리, inode 개념
- 버퍼/캐시, 동기/비동기 I/O
- 디스크 스케줄링(개념)

## OS-6. 시스템 콜과 인터럽트

- 시스템 콜 흐름
- 인터럽트/트랩/시그널
- 타이머, 컨텍스트 전환 연결

# 네트워크

## NET-1. 네트워크 기초 뼈대

- OSI 7계층 vs TCP/IP
- 캡슐화/역캡슐화
- MTU, MSS

## NET-2. IP와 라우팅

- IPv4/IPv6, 서브넷/라우팅
- NAT, 공인/사설 IP
- ICMP(ping), traceroute 개념

## NET-3. TCP

- 3-way handshake / 4-way termination
- 흐름제어/혼잡제어
- 재전송(Timeout/Fast retransmit), RTT

## NET-4. UDP

- UDP 특성/사용처(DNS, 스트리밍 등)
- 신뢰성은 어디서 보장하는가(애플리케이션 레벨)

## NET-5. DNS / HTTP

- DNS 질의 과정, 캐시
- HTTP/1.1 keep-alive, 쿠키/세션
- HTTPS(TLS) 개념, 인증서

## NET-6. 실무 트러블슈팅/운영

- 로드밸런서(L4/L7)
- CORS, 프록시/리버스 프록시
- 장애 패턴(타임아웃, 커넥션 고갈)

# 자료구조와 알고리즘

## DSA-1. 빅오와 기본기

- 시간/공간 복잡도, 상한/평균
- 재귀/스택 프레임 이해
- 정렬/탐색 기본 감각

## DSA-2. 선형 자료구조

- 배열/리스트
- 스택/큐/덱
- 해시(충돌, 체이닝/오픈어드레싱)

## DSA-3. 트리

- 이진트리/이진탐색트리(BST)
- 힙/우선순위큐
- 트리 순회, LCA(선택)

## DSA-4. 그래프

- 표현(인접리스트/행렬)
- BFS/DFS, 위상정렬
- 최단경로(Dijkstra, BFS), MST(선택)

## DSA-5. 알고리즘 패턴

- 투포인터/슬라이딩 윈도우
- 그리디
- 분할정복/백트래킹

## DSA-6. DP / 문자열 / 기타

- DP(상태 정의/점화식/메모이제이션)
- KMP/트라이(선택)
- Union-Find(선택)

