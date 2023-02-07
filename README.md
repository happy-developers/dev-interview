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
|2주차|2022.12.26|[네트워크](https://github.com/happy-developers/dev-interview/issues/19)|
|3주차|2023.1.2|[데이터베이스](https://github.com/happy-developers/dev-interview/issues/33)|
|4주차|2023.1.9|[Java](https://github.com/happy-developers/dev-interview/issues/50)|
|5주차|2023.1.16|[Spring](https://github.com/happy-developers/dev-interview/issues/56)|
|6주차|2023.1.30|운영체제|
|7주차|2023.2.6|[네트워크](https://github.com/happy-developers/dev-interview/issues/66)|
|8주차|2023.2.13|데이터베이스|
|9주차|2023.2.20|Java|
|10주차|2023.2.27|Spring|

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
- Active close Passive close
- readtimeout connectiontimeout
- ssl
- 비잔틴문제
- http
    - [http란 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/20)
    - [GET 메서드와 POST 메서드의 차이는 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/21)
    - [HTTP 보안 공격에는 무엇이 있나요?](https://github.com/happy-developers/dev-interview/issues/22)
    - [http 버전별 바뀐 점은 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/23)
    - [https에 대해서 설명해주세요](https://github.com/happy-developers/dev-interview/issues/24)
- TCP/IP 계층 구조
- 웹사이트 접속 흐름
- vpn
    - ipsec
- TCP
    - Active Closer / Passive Closer
    - Piggyback, sliding window
    - Sequence Number, SYN / ACK 등
    - 3way handshake, 4way handshake
    - [TCP 헤더에 대해서 설명해주세요.](https://github.com/happy-developers/dev-interview/issues/69)
- UDP, QUIC
    - [TCP와 UDP의 차이는 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/67)
- SSL의 동작 방식
- 웹사이트 접속 흐름
- DNS
    - [DNS가 UDP 통신을 사용하는 이유는 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/68)
- [proxy 서버는 무엇이고 왜 사용하는 걸까요?](https://github.com/happy-developers/dev-interview/issues/70)

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
    - [인덱스란 무엇인가요?](https://github.com/happy-developers/dev-interview/issues/34)
    - [cluster index 와 non-cluster index 의 차이점에 대해서 설명해주세요](https://github.com/happy-developers/dev-interview/issues/35)
    - [복합 인덱스 설정 시 정렬되는 순서는?](https://github.com/happy-developers/dev-interview/issues/36)
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

### 핵심 키워드
- checked exception vs unchecked exception
- transient
- overriding vs overloading
- 동등성 vs 동일성
- interface vs abstract class
- Pass by value / reference
- Java Hashmap
- Concurrent package
- volatile
- equals, hashcode
- String이 final일까
- StringBuilder vs StringBuffer
- synchronized
- GC
- 자바 메모리 영역
- String 과 리터럴
- 리플렉션
- 제네릭
- 타입 이레이저
- Type token Super Type token
- serializable
- JVM

</div>
</details>

<details>
<summary>Spring</summary>
<div markdown="1">

### 핵심 키워드
- di 방식 비교: 생성자, setter, field
    - [DI란 무엇이고 의존성 주입 방법에 대해서 설명해주세요.](https://github.com/happy-developers/dev-interview/issues/57)
- di 어노테이션 비교: @Autowired, @Resource, @Inject
- [스프링 MVC 패턴과 클라이언트 요청이 처리되는 순서에 대해서 설명해주세요.](https://github.com/happy-developers/dev-interview/issues/58)
- 스프링 빈의 스코프
- AutoConfigure 작동 방식 (@ComponentScan, @EnableAutoConfiguration)
- 스프링 트라이앵글
- IOC/DI
- AOP
    - aop의 단점
    - 어노테이션 동작 방식
- self invocation 문제
- 순환 참조 문제
- interceptor vs filter
    - [클라이언트 요청 앞단에 요구사항이 추가된다면 어떻게 구현하겠습니까?](https://github.com/happy-developers/dev-interview/issues/59)
- AOP
    - [self-invocation에 대해서 설명해주세요.](https://github.com/happy-developers/dev-interview/issues/60)
- @Transactional 동작방식
    - AOP와 함께
    - 과연 Rollback이 되는 조건이 정해져 있는 걸까?
    - 언제 동작하지 않을까?
- @Autowired
- PSA
    - PlatformTransactionManager
    - JDBCTrasactionManager(?)
    - HibernateTransactionManager
    - MyBatis(?)TransactionManager
- DynamicProxy, CGLib
- HttpMessageConverter, @ResponseBody는 어떻게 동작할까요?
- Proxy
- CGLIB
- springboot

</div>
</details>
