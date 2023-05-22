# Account_Service

- Spring WEB MVC를 이용해서 계좌 시스템의 기본적인 비즈니스 로직과 API 기능을 개발한 토이프로젝트입니다. 이 토이프로젝트를 통해 Spring MVC의 Model-View-Controller의 기본적인 아키텍쳐를 구현해 볼 수 있었고, TDD 방식을 적용하여 개발을 진행하면서 테스트 코드의 중요성 또한 알게되었다. 마지막으로 다양한 에러상황에 대한 예외처리를 다루면서 
예외처리가 어플리케이션의 안정성을 높이고 오류가 일어났을때 디버깅에 대한 이점을 제공해 준다는 것을 알게되었다.

## 활용 기술 스택
- Spring WEB MVC
- Junit5
- JPA
- H2 DataBase
- Redis
- Lombok
- Mockito
- Intellij IDE 

## ERD
<img width="502" alt="AccountERD" src="https://github.com/devhongsa/Account_Service/assets/100022877/67aa767c-7336-4226-ab56-fff33e64cecd">


## API 기능
계좌 관련 기능
1. 계좌생성
2. 계좌해지
3. 계좌확인

거래 관련 기능
1. 잔액 사용(거래 생성)
2. 잔액 사용 취소(거래 취소)
3. 거래확인


