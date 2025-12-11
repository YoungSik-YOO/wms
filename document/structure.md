# 프로젝트 구조

## 디렉토리 구조
```
/
├── build.gradle          # Gradle 빌드 설정
├── settings.gradle       # Gradle 설정
├── gradlew               # Gradle 래퍼 스크립트
├── src
│   ├── main
│   │   ├── java          # Java 소스 코드
│   │   │   └── com.koreait.wms
│   │   │       ├── controller  # 웹 컨트롤러
│   │   │       ├── dao         # 데이터 접근 객체 (MyBatis 매퍼)
│   │   │       ├── dto         # 데이터 전송 객체
│   │   │       ├── service     # 비즈니스 로직 서비스
│   │   │       └── WmsApplication.java # 메인 애플리케이션 클래스
│   │   └── resources     # 리소스
│   │       ├── application.properties      # 전역 설정
│   │       ├── application-local.properties # 로컬 환경 설정
│   │       ├── static    # 정적 자산 (CSS, JS, 이미지)
│   │       └── templates # Thymeleaf 템플릿 (HTML)
│   └── test              # 테스트 코드
└── document              # 프로젝트 문서
```

## 패키지 구조
- **com.koreait.wms**
    - **controller**: HTTP 요청을 처리하고 뷰를 반환합니다.
        - `ProductController`: 상품 관련 요청 관리.
    - **dao**: 데이터베이스 작업을 위한 인터페이스입니다.
        - `ProductDAO`: 상품에 대한 데이터베이스 접근.
    - **dto**: 계층 간 데이터 전송을 위한 객체입니다.
        - `ProductDTO`: 상품 데이터.
        - `DetailDTO`: 상세 보기 데이터.
        - `InoutDTO`: 재고 입출고 데이터.
        - `SalesDTO`: 판매 데이터.
    - **service**: 비즈니스 로직을 포함합니다.
        - `ProductService`: 상품 관리를 위한 로직.
