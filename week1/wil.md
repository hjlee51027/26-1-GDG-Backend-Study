# 📌 Week1 WIL (What I Learned)

## 1️⃣ 1주차에 학습한 내용

* 웹의 소통 방식, HTTP와 REST API
* Spring Boot, Intellij를 이용한 개발 환경 설정

---

## 2️⃣ Whitelabel Error Page 스크린샷


![Whitelabel Error Page](hw1%20screenshot.png)


---

## 3️⃣ 온라인 쇼핑몰 프로젝트 API 명세서

### 📦 상품(Product) API

| 기능       | HTTP Method | URI                   |
| -------- | ----------- | --------------------- |
| 상품 등록    | POST        | /products             |
| 상품 목록 조회 | GET         | /products             |
| 상품 상세 조회 | GET         | /products/{productId} |
| 상품 수정    | PUT         | /products/{productId} |
| 상품 삭제    | DELETE      | /products/{productId} |

---

### 🧾 주문(Order) API

| 기능       | HTTP Method | URI               |
| -------- | ----------- | ----------------- |
| 주문 생성    | POST        | /orders           |
| 주문 목록 조회 | GET         | /orders           |
| 주문 상세 조회 | GET         | /orders/{orderId} |
| 주문 취소    | DELETE      | /orders/{orderId} |

---
