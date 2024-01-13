# 💸 Account_System

spring/java로 결제시스템을 구성해보는 프로젝트

<br/><br/><br/>

### 1. 제작기간 & 참여인원
---
- 2024.01.15 ~ 
- 개인 프로젝트
- 



## 2. 기술 스택

Language
- Java

Library/framework
- Spring boot
- Spring data jpa
- Spring Security
- Gradle
- JWT
- Swagger
- Junit

Infrastructure
- MySQL
- Redis
- H2 Database
- docker



## 3. ERD 설계



## 4. 핵심 기능

Account 시스템은 사용자와 계좌의 정보를 저장해서, 외부 시스템에서 거래 요청시, 거래 정보를 받아서 계좌에서 잔액을 결제, 결제금액을 취소하는 거래 관리 기능을 제공합니다.

사용자, 계좌, 거래 정보를 제공합니다.

사용자는 신규 등록, 해지, 중지 등을 제공합니다.
계좌는 계좌추가, 해지, 확인 기능을 제공합니다. 
한 사용자는 최대 3개의 계좌를 가질 수 있고, 그 이상의 계좌는 생성할 수 업습니다.

계좌 번호는 10자리의 정수로 이루어져있으며 중복이 불가능합니다. 

거래는 잔액 사용, 잔액 사용 취소, 거래 확인 기능을 제공합니다.



## 5. 핵심 트러블 슈팅




## 6. 회고





