## 휴먼스온 사전과제 제출

### 지원자 : 최용락 (c1.yrkk@gmail.com)
### 프로젝트명
**humanson**

### ⚙개발 환경
- JAVA 17
- **IDE** : Intellij   
- **Framework** : Spring boot 3.3.4
  
### 📌클래스 다이어그램

![다이어그램](https://github.com/user-attachments/assets/3649248a-3c44-4fdd-b964-f6f4575c24df)


* 상품 리스트 ("/main")

  - DB에 등록된 상품리스트를 노출 : 대표이미지, 원가(할인 전 가격), 할인가, 할인율(%)
  - 찜 기능

    **로그인 유저** : UI 클릭으로 상품별 찜 등록/취소

    **비로그인** : UI 클릭 로그인 페이지 이동
    
  - 상품 10개씩 페이지네이션

* 상품 상세 ("/productView")
