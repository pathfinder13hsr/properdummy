# ProperDummy

---

- **Naming**
  - Dummy - 가짜
  - Proper - 참된, 제대로 된
  - Proper Dummy - 참된 가짜 ㅋ 제대로 된 더미데이터 생성기 (를 만들고 싶다는 개발자의 바람)

---

- **Key Features**
  - 흔히 사용하는 데이터(이름, 전화번호, 주소, ipv4, ipv6, port, ...)를 무작위로 생성한다
  - row 또는 json 단위로 지정한 갯수만큼 생성한다
  - 지정한 포맷(.json 파일, .csv 파일, java 객체, sql insert문, ..)으로 출력한다

---

- **Target Users**
  - 시작 단게의 SI 프로젝트에 투입된 개발자
  - 새로 구성된 stg 환경에서 테스트를 해야하하는 QA 엔지니어
  - 간단한 더미데이터가 필요한 모든 사람

---

- **Development**
  - Java 17 (8 ~ 21 사이 타협점, SI라고 할지라도 새로 시작하는 프로젝트라면 이제는 17버전 정도는 쓸 것이라고 가정)
  - 순수 Java 라이브러리 형태로 배포 예정(spring boot starter는 현재는 고려하고 있지 않음)
  - TDD를 시도해볼 예정

