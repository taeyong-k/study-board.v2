# 📝 Study Board Project

## 📌 프로젝트 개요
Spring Boot 기반의 게시판 시스템을 학습 목적으로 제작하였습니다.  
게시글 작성, 조회, 수정, 삭제 기능과 함께 조회수 카운트, 검색, 페이지네이션 기능을 구현하였으며, MVC 패턴 구조로 개발하였습니다.

---

## 🚀 주요 기능

- ✍️ 게시글 작성 (닉네임, 비밀번호 확인 포함)
- 📖 게시글 조회 (조회수 자동 증가)
- 🛠 게시글 수정 (비밀번호 입력 후 수정)
- ❌ 게시글 삭제 (비밀번호 입력 후 삭제)
- 📄 게시글 목록 (5개씩 페이징 처리)
- 🔍 검색 기능 (제목, 작성자, 내용 포함 검색)

---

## 🛠 사용 기술

- **IDE**: IntelliJ IDEA
- **Language**: Java 17
- **Framework**: Spring Boot 3.4.4  
  - ✅ Spring Web  
  - ✅ Spring Boot DevTools  
  - ✅ Lombok  
  - ✅ Thymeleaf (Template Engine)
- **Database**: MariaDB
- **ORM/DB 연동**:  
  - ✅ Spring Data JDBC  
  - ✅ JDBC API  
  - ✅ MyBatis Framework
- **Frontend**: HTML, CSS, JavaScript (모두 외부 파일 분리)
- **Build Tool**: Maven (WAR 패키지)

---

## 📚 학습 포인트

- RESTful API 설계 및 HTTP Method별 처리 (GET, POST, PATCH, DELETE)
- `XMLHttpRequest` + `FormData`를 통한 비동기 통신 처리
- 사용자 입력 검증 및 클라이언트 경고 처리 (`alert`)
- 페이지네이션 & 검색 필터링 구현
- Entity, DTO, Controller, Mapper 구조 분리
- Lombok을 활용한 코드 간결화
- Thymeleaf를 활용한 SSR 방식 View 구성

---

## ▶ 실행 방법

1. MariaDB에 테이블 생성  
   (제공된 `.sql` 파일 또는 쿼리 이용)

2. `application.properties` 또는 `application.yml`에 DB 연결 정보 작성
   ```properties
   spring.datasource.url=jdbc:mariadb://localhost:3306/your_db
   spring.datasource.username=your_username
   spring.datasource.password=your_password
