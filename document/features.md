# 프로젝트 기능

## 1. 상품 관리 (Product Management)
- **설명**: 상품 정보를 관리합니다.
- **구성 요소**:
    - `ProductController`: 상품 목록 조회, 생성, 수정 요청을 처리합니다.
    - `ProductService`: 상품 작업을 위한 비즈니스 로직입니다.
    - `ProductDAO`: 상품에 대한 데이터베이스 작업입니다.
    - `ProductDTO`: 상품 상세 정보를 위한 데이터 구조입니다.
- **뷰 (View)**: `product.html`

## 2. 재고 관리 (Inventory Management - In/Out)
- **설명**: 재고의 입고 및 출고 기록을 추적합니다.
- **구성 요소**:
    - `InoutDTO`: 재고 거래를 위한 데이터 구조입니다.
- **뷰 (View)**: `inout.html`

## 3. 판매 관리 (Sales Management)
- **설명**: 판매 기록을 관리합니다.
- **구성 요소**:
    - `SalesDTO`: 판매 정보를 위한 데이터 구조입니다.
- **뷰 (View)**: `sales.html`

## 4. 상세 보기 (Detail View)
- **설명**: 특정 항목(상품 또는 주문 등)에 대한 상세 정보를 조회합니다.
- **구성 요소**:
    - `DetailDTO`: 상세 보기를 위한 데이터 구조입니다.
- **뷰 (View)**: `detail.html`

## 5. 대시보드 / 홈 (Dashboard / Home)
- **설명**: 애플리케이션의 메인 랜딩 페이지입니다.
- **뷰 (View)**: `index.html`

## 6. 레이아웃 (Layout)
- **설명**: Thymeleaf Layout Dialect를 사용한 애플리케이션의 공통 레이아웃입니다.
- **뷰 (View)**: `layout.html`
