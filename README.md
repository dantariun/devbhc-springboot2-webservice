# devbhc-springboot2-webservice

"스프링 부트와 AWS로 혼자 구현하는 웹 서비스" 도서를 따라 구현한 학습용 Spring Boot 2.x 웹 서비스.

## Stack

- Java 8 · Spring Boot 2.1.7
- JPA · H2 (dev) · MariaDB (prod)
- Mustache · OAuth2 (Google 소셜 로그인)
- Travis CI

## Features

- 게시글 CRUD (Posts API)
- Google OAuth2 소셜 로그인
- Spring Session JDBC 기반 세션 관리
- Travis CI 자동 빌드

## Run

```bash
./gradlew clean build
./gradlew bootRun
```
