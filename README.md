# dev-interview
- 주니어 백엔드 기술 면접 질문을 공유하는 repository입니다.
- 스터디에서 진행한 내용을 기록합니다.

# 스터디 소개
- 스터디명 : 백엔드 모의 면접 스터디(운영체제, 네트워크, 데이터베이스, Java, Spring)
- 스터디 기간 : 2-3개월
- 스터디 일정 : 주 1회 온라인 화상 회의 1-2시간 매주 월요일 22시
- 인원 : 4명
- 스터디 방식 :
    - 과목은 운영체제, 네트워크, 데이터베이스, Java, Spring
    - 한 주에 한 과목씩 면접관 2명, 지원자 2명으로 모의 면접 & 피드백
    - 모의 면접 전 미리 예상 질문 List 작성
    - 과목당 두 번 로테이션하는 것을 목표로 진행(5과목 X 2 = 10주)

# 스터디 진행 기록
|주차|일시|주제|
|:---:|:---|:---:|
|1주차|2022.12.19|[운영체제](https://github.com/happy-developers/dev-interview/issues/17)|
|2주차|2022.12.26|네트워크|
|3주차|2023.1.2|데이터베이스|
|4주차|2023.1.9|Java|
|5주차|2023.1.16|Spring|
|6주차|2023.1.23|운영체제|
|7주차|2023.1.30|네트워크|
|8주차|2023.2.6|데이터베이스|
|9주차|2023.2.13|Java|
|10주차|2023.2.20|Spring|

# Repository 작성 Rule
키워드에 해당하는 질문을 면접 리스트에 추가, 질문을 issue에 추가 및 링크, Comment로 답변

# 질문 리스트
<details>
<summary>운영체제</summary>
<div markdown="1">

### 핵심 키워드
- 프로세스 & 스레드
    - [프로세스의 메모리 구조에 대해서 설명해주세요](https://github.com/happy-developers/dev-interview/issues/3)
    - [프로세스와 스레드의 차이점은 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/4)
    - [멀티스레드와 멀티프로세스의 차이는 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/5)
    - [사용자 스레드와 커널 스레드의 차이점은 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/6)
    - [Context Switch에 대해서 설명해주세요.](https://github.com/happy-developers/dev-interview/issues/2)
- CPU 스케줄링
- 프로세스 동기화
    - [Race Condition에 대해서 설명해주세요](https://github.com/happy-developers/dev-interview/issues/7)
- deadlock
- 물리 메모리 관리
- 가상 메모리 관리
    - [가상 메모리 관리 전략에 대해서 설명해주세요](https://github.com/happy-developers/dev-interview/issues/8)

</div>
</details>

<details>
<summary>네트워크</summary>
<div markdown="1">

### 핵심 키워드
- Read Timeout / Connection Timeout
- 비잔틴문제
- http
    - [http란 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/20)
    - [GET 메서드와 POST 메서드의 차이는 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/21)
    - [HTTP 보안 공격에는 무엇이 있나요?](https://github.com/happy-developers/dev-interview/issues/22)
    - [http 버전별 바뀐 점은 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/23)
    - [https에 대해서 설명해주세요](https://github.com/happy-developers/dev-interview/issues/24)
- TCP/IP 계층 구조
- vpn
    - ipsec
- TCP
    - [TCP 프로토콜은 무엇이고, 왜 사용하는 것일까요?](https://github.com/happy-developers/dev-interview/issues/12)
    - Active Closer / Passive Closer
    - Piggyback, sliding window
    - Sequence Number, SYN / ACK 등
    - 3way handshake, 4way handshake
- UDP, QUIC
- SSL의 동작 방식
- [웹사이트 접속 흐름](https://github.com/happy-developers/dev-interview/issues/14)
- [DNS](https://github.com/happy-developers/dev-interview/issues/10)

</div>
</details>

<details>
<summary>데이터베이스</summary>
<div markdown="1">

### 핵심 키워드
- 정규화
- 스토리지 엔진
- 트랜잭션
    - ACID
- lock
    - s-lock, x-lock
    - gap lock
    - 낙관적/비관적 락
- mvcc
- 갱신손실
- 쓰기스큐
- isolation level
- 인덱스
    - BTree
    - 왜 ArrayList가 아닌 B-Tree?
    - Rebalancing
    - 복합 인덱스 설정 시 정렬되는 순서는?
- 옵티마이저
    - 옵티마이저 힌트
    - sql 힌트
- 페이징
- DB Buffer cache
- Block size
- Execution plan
- 왜 DB에서 열거형은 VARCHAR2가 아닌 Int를 쓸까?

</div>
</details>

<details>
<summary>Java</summary>
<div markdown="1">


</div>
</details>

<details>
<summary>Spring</summary>
<div markdown="1">


</div>
</details>
