# 도서 관리 어플리케이션

이 프로젝트는 **Spring Boot**와 **JPA**를 활용하여 간단한 도서 관리 어플리케이션을 구현한 저장소입니다.  
**AWS EC2**에 수동으로 배포하는 과정을 테스트하기 위해 제작되었습니다.

## 주요 기술 스택
- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **MySQL** (테스트용 내장 DB)

## 기능
- 도서 목록 조회
- 도서 등록, 수정, 삭제
- 기본적인 웹 기반의 CRUD 기능 제공

## 배포 환경
- **AWS EC2**: Amazon Linux 2
- **Gradle**: 프로젝트 빌드 및 의존성 관리
- **MySQL** 또는 **H2 Database** 사용 가능

## 실행 방법
1. **프로젝트 빌드**
   ```bash
   ./gradlew build
   ```

2. **JAR 파일 실행**
   ```bash
   java -jar build/libs/library-app.jar
   ```

3. **브라우저에서 접속**
   - 기본 포트: `http://<EC2-IP>:8080`

## 참고
- 이 저장소는 개인 학습 및 배포 테스트를 목적으로 합니다.
- 프로젝트 개선 및 확장 가능성 고려하여 설계되었습니다.
