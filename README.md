# 🥟 Mando

안녕하세요. 지속 가능하고 유지보수가 용이한 소프트웨어 개발을 추구하는 백엔드 개발자 김수민입니다.

## 👩‍💻 About Me

* 체계적인 설계와 문서화를 바탕으로 가독성 높고 유지보수가 쉬운 코드 구조를 만들고자 노력합니다.
* 50명 규모의 실사용자 서비스 운영 경험을 통해 확장성과 유지보수성의 중요성을 체감했습니다.
* Java 언어에 대한 깊은 이해를 바탕으로 객체지향 프로그래밍, 함수형 프로그래밍에 관심이 있습니다.

## 🔥 History
* 크래프톤 Publishing Platform Div. Web Back-End Developer Intern(2024.10 ~ 2025.01)

### 교육
* 크래프톤 정글 5기 (2024.03 ~ 2024.07)
  * OS의 핵심을 직접 구현하는 핀토스 과정 수료
  * Thread, System Call, Virtual Memory 구현
* 카카오테크캠퍼스 1기 2단계 우수 수료 (2023.04 ~ 2023.11)
* 전남대학교 컴퓨터정보통신공학과 (2020.03 ~ 2024.08)

### 프로젝트
* EEOS - 동아리 행사 관리 서비스 (2023.09 ~ 2024.02)
  * EEOS - 동아리 행사 관리 서비스 (2023.09 ~ 2024.02)
  * 50명 규모의 실사용자 대상 서비스 운영
  
  #### 테스트 코드 실행 속도 개선
  * 문제: @MockBean, @SpyBean 사용으로 인한 테스트 컨텍스트 오염 및 재생성으로 실행 속도 저하
  * 해결: 필요한 대리 객체를 미리 테스트 컨텍스트에 로드하고 테스트 클래스들이 상속받아 사용하는 구조로 개선
  * 결과: 컨텍스트 캐싱을 통한 테스트 실행 속도 향상

  #### DB Connection Pool 한계 극복
  * 문제: 트랜잭션 내 외부 API 호출로 인한 DB Connection 장기 점유 및 Pool 고갈 위험
  * 해결: 퍼사드 패턴을 활용하여 트랜잭션과 외부 API 호출 로직 분리
  * 결과: DB Connection 사용 시간 최적화 및 리소스 효율성 증가

  #### 활성 팀빌딩 개수 제한 기능 개선
  * 문제: Java Atomic 변수 사용 시 서버 재시작으로 인한 초기화 문제 발생
  * 해결: DB 낙관적 락(Optimistic Lock) 도입으로 동시성 제어
  * 결과: 서버 재시작과 무관하게 안정적인 팀빌딩 개수 제한 기능 구현

  #### 출석 정보 조회 성능 최적화
  * 문제: 출석 정보 조회 API의 빈번한 호출로 인한 서버 부하
  * 해결: 
    * Cache-Control 헤더를 통한 클라이언트 캐싱 구현
    * ETag를 도입하여 정보 변경 시 캐시 무효화 및 최신 정보 반영
  * 결과: 서버 부하 감소 및 응답 속도 개선

  #### Refresh Token 관리 개선
  * 문제: MySQL에 저장된 Refresh Token의 수동 만료 처리 필요
  * 해결: Redis의 TTL 기능을 활용한 토큰 저장소 마이그레이션
  * 결과: Refresh Token의 자동 만료 처리 구현으로 관리 효율성 향상
* PIXELLER - 중고 물품 거래 서비스 (2023.09 ~ 2024.02)
  * DB 쿼리 최적화 (Index range search 도입)
  * 웹소켓 통신 개선 및 인증 프로세스 최적화
  * RabbitMQ를 활용한 비동기 메시지 처리 시스템 구축

## 🛠 Tech Stack

### Backend
* Java, Spring Boot, JPA
* JUnit5, Mockito

### Database
* MySQL, Redis
* Flyway

### DevOps
* Docker, Docker Compose
* AWS, Nginx

### Tools
* Git, GitHub
* IntelliJ IDEA

## 📫 Contact
* Email: ksoomin25@gmail.com
* Blog: [Mando.log](https://velog.io/@kssumin)
* Github: [@kssumin](https://github.com/kssumin)

## 📝 Projects & Experience

각 프로젝트에 대한 자세한 내용은 아래 링크에서 확인하실 수 있습니다:
* [EEOS](https://github.com/kssumin/EEOS-BE)
* [PIXELLER](https://github.com/Jungle-Team3-Olympus/pixeller)
