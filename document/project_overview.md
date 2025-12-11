# 프로젝트 개요

## 프로젝트명
WMS (창고 관리 시스템)

## 설명
이 프로젝트는 Spring Boot와 Thymeleaf로 구축된 창고 관리 시스템(Warehouse Management System)입니다. 상품, 판매, 재고 입출고 관리를 담당합니다.

## 기술 스택
- **언어**: Java 17
- **프레임워크**: Spring Boot 3.5.5
- **빌드 도구**: Gradle
- **데이터베이스**: MySQL
- **ORM**: MyBatis
- **템플릿 엔진**: Thymeleaf
- **프론트엔드**: HTML, CSS, JavaScript (Thymeleaf Layout Dialect)

## 설정
- **애플리케이션 이름**: wms
- **인코딩**: UTF-8
- **포트**: 8090 (로컬)
- **데이터베이스**: `localhost:3306`의 `wms` 스키마

## 의존성 (Dependencies)
- Spring Boot Starter Web
- Spring Boot Starter Data JDBC
- MyBatis Spring Boot Starter
- MySQL Connector J
- Spring Boot Starter Thymeleaf
- Thymeleaf Layout Dialect
- Spring Boot DevTools
