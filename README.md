# Spring Boot Developer Study

[스프링 부트 백엔드 개발자 만들기](https://ebook-product.kyobobook.co.kr/dig/epd/sam/E000012835012?tabType=SAM) 교재를 기반으로 진행하는 백엔드 스터디 리포지토리입니다. 

## 스터디 개요
- **목표:** 스프링 부트의 핵심 원리를 이해하고, 게시판 및 RESTful API 개발, 시큐리티, 배포까지 백엔드 개발의 전 과정을 직접 구현합니다.
- **참고 도서:** [해당 교보문고 도서 링크](https://ebook-product.kyobobook.co.kr/dig/epd/sam/E000012835012?tabType=SAM)

## 기술 스택 (Tech Stack)
- **Language:** Java 17 
- **Framework:** Spring Boot 3.x
- **Database:** H2 Database (개발용) / MySQL (운영용)
- **ORM:** Spring Data JPA
- **Build Tool:** Gradle
- **Template Engine:** Thymeleaf

## 📖 학습 진도 및 목차 (Curriculum)
학습을 완료한 챕터는 `[x]`로 표시하여 진도를 관리합니다. 교재의 상세 목차에 맞춰 유동적으로 수정하여 사용하세요.

- [x] **Chapter 1~2:** 스프링 부트 시작하기 및 환경 설정 (JDK, IDE, Postman)
- [x] **Chapter 3:** 스프링 부트 핵심 원리와 구조 이해
- [x] **Chapter 4:** 테스트 코드 작성하기 (JUnit5, AssertJ)
- [x] **Chapter 5:** 데이터베이스 연동 및 JPA의 이해 (엔티티 매핑, 영속성 컨텍스트)
- [x] **Chapter 6:** 블로그 API 만들기 (REST API, CRUD 구현)
- [ ] **Chapter 7:** 블로그 화면 구성하기 (Thymeleaf 활용)
- [ ] **Chapter 8:** 스프링 시큐리티로 폼 로그인 및 회원가입 구현
- [ ] **Chapter 9:** JWT 토큰 기반 API 인증 구현
- [ ] **Chapter 10:** OAuth2를 활용한 구글 소셜 로그인 구현
- [ ] **Chapter 11~12:** AWS EC2 배포 및 GitHub Actions 기반 CI/CD 구축

## 커밋 컨벤션 (Commit Rules)
커밋 메시지는 직관적으로 작업 내용을 알 수 있도록 아래의 태그를 활용합니다.

- `feat`: 새로운 기능 추가, 실습 코드 작성
- `fix`: 버그 수정
- `docs`: README 등 문서 수정
- `refactor`: 코드 리팩토링
- `chore`: 설정 파일 수정, 패키지 추가

**커밋 예시:**
> `feat: Chapter 6 - 블로그 게시글 생성 API 구현`

## 📁 디렉토리 구조
```text
📦 springboot-developer-study
 ┣ 📂 src
 ┃ ┣ 📂 main
 ┃ ┃ ┣ 📂 java/com/example/springbootdeveloper
 ┃ ┃ ┃ ┣ 📂 controller
 ┃ ┃ ┃ ┣ 📂 domain
 ┃ ┃ ┃ ┣ 📂 dto
 ┃ ┃ ┃ ┣ 📂 repository
 ┃ ┃ ┃ ┗ 📂 service
 ┃ ┃ ┗ 📂 resources
 ┃ ┗ 📂 test
 ┗ 📜 build.gradle
