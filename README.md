## 휴머스온 사전과제 제출

### 지원자 : 최용락 (c1.yrkk@gmail.com)
### 프로젝트명
**humanson**

### ⚙개발 환경
- JAVA 17
- **IDE** : Intellij   
- **Framework** : Spring boot 3.3.4
  
### 📌클래스 다이어그램

![다이어그램](https://github.com/user-attachments/assets/3649248a-3c44-4fdd-b964-f6f4575c24df)


* DTO
  Order : 주문ID, 고객명, 주문 날짜, 주문 상태 등 속성 데이터

* Controller
  OrderController : 외부 시스템에서 주문 수집, 주문 조회, 주문 리스트 조회 를 호출하여 사용
* Service
  OrderRepository : 주문 데이터 CRUD 구현을 위한 클래스
  OrderService : 외부 시스템 데이터 연동 담당 인터페이스
* Config
  RestTemplateConfig : RestTemplate를 사용한 Http 통신을 위한 설정 
