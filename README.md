# JPA Core

Spring Boot와 JPA의 핵심 개념을 학습하기 위한 프로젝트입니다.
엔티티(Entity) 매핑부터 영속성 컨텍스트(Persistence Context), EntityManager 사용법, CRUD 기능 구현까지 JPA의 기본 동작 원리를 실습하며 이해하는 것을 목표로 합니다.

---

# 프로젝트 소개

JPA(Java Persistence API)의 핵심 개념을 실습 중심으로 학습하기 위해 제작한 프로젝트입니다.

Spring Boot 환경에서 Entity와 테이블 매핑, 영속성 컨텍스트, EntityManager를 활용한 데이터 관리, CRUD 기능 등을 구현하며 JPA의 동작 방식을 익혔습니다.

---

# 기술 스택

* Java 21
* Spring Boot
* Spring Data JPA
* Hibernate
* H2 Database / MySQL
* Gradle
* Lombok
* IntelliJ IDEA

---

# 프로젝트 구조

```text
src
 ├── entity
 ├── repository
 ├── service
 ├── controller
 └── test
```

---

# 학습 내용

* JPA(Entity) 매핑
* @Entity, @Table
* @Id
* @Column
* EntityManager 사용
* Persistence Context
* CRUD 구현
* Repository 활용
* Spring Data JPA 기초
* JUnit 테스트

---

# 주요 기능

## Entity 생성

JPA Entity를 생성하고 데이터베이스 테이블과 매핑합니다.

---

## 데이터 저장

EntityManager를 이용하여 데이터를 저장합니다.

---

## 데이터 조회

기본 키(ID)를 이용한 조회와 전체 조회를 수행합니다.

---

## 데이터 수정

영속성 컨텍스트의 변경 감지(Dirty Checking)를 이용하여 데이터를 수정합니다.

---

## 데이터 삭제

Entity를 삭제하여 데이터베이스에서 제거합니다.

---

# 실행 방법

### 프로젝트 실행

```bash
./gradlew bootRun
```

또는 IntelliJ IDEA에서 실행 버튼을 눌러 실행할 수 있습니다.

---

# 테스트 실행

```bash
./gradlew test
```

---

# 프로젝트 목적

Spring Boot와 JPA를 활용하여 ORM(Object Relational Mapping)의 개념을 이해하고, EntityManager와 영속성 컨텍스트를 직접 다루며 JPA의 내부 동작 원리를 학습하기 위한 프로젝트입니다.

---

# 향후 학습 계획

* 연관관계 매핑
* 양방향 관계
* Cascade
* Fetch 전략
* JPQL
* QueryDSL
* Spring Data JPA 심화
* 실무 프로젝트 적용
