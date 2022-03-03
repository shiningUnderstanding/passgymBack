# passGym
passgymBack

## [What is PassGym?](#what-is-passgym)
PassGym 프로젝트는 사용자와 피트니스, 헬스장 등을 연결해주는 플랫폼 프로젝트입니다.

#### 1. [Project planning(Project topic selection, functional design, water fall) 프로젝트 기획](#project-planning)
#### 2. [Layout Design 화면설계](#layout-design)
#### 3. [Data Base design(from requirements specification) 데이터 베이스 설계](#data-base-design)
#### 4. [Functional Specification 기능명세서](#functional-specification)
#### 5. [Create eclipse project with github 이클립스 프로젝트 생성 및 깃헙 연동](#create-eclipse-project-with-github)
#### 6. [VO(Value Object) Class](#value-object-class)
#### 7. [Development implementation (frontend, backend, unit test) 개발 구현](#development-implementation)
#### 8. [Integration test(통합테스트)](integration-test)

---------------------------------------------------------
## What is PassGym       

- 프로젝트 소개
  PassGym 프로젝트는 사용자와 피트니스, 헬스장을 연결해주는 플랫폼 프로젝트입니다.  
  사용자는 자신의 위치와 가까운 헬스장, 본인이 찜한 헬스장 등을 한눈에 파악할 수 있습니다. 사용자는 각 헬스장의 상세페이지에 접속하여 해당 헬스장의 상세정보를 확인하고 회원권을 결제하고 맘에 드는 헬스장을 본인의 찜목록에 추가할 수 있습니다. 이렇게 찜하고 결제한 목록은 마이페이지에서 확인이 가능합니다.  
  헬스장측은 사업자 회원가입이라는 다른 경로로 회원가입을 하며 회원가입시에 헬스장에 관한 정보를 등록하도록합니다. 헬스장에 관한 정보는 이용권의 종류와 상세설명, 보유기구, 헬스장 사용 정보 등이 있습니다. 회원가입 후 사업자로 로그인을 하게 되면 판매자 전용페이지로 접속이 됩니다. 회원권 조회를 통해 각 회원권을 이용하는 회원들의 목록을 확인할 수 있습니다.
  
- 프로젝트에 사용한 기술
   - JAVA SpringBoot
   - JPA
   - Oracle Data Base
   - React JS
   - jQuery
   - HTML/CSS
   - github(프로젝트 버전 관리)

- 프로젝트에 사용한 디자인 패턴
  - MVC 패턴 사용
   
- 프로젝트에 사용된 Open API
  - 카카오맵 API 
  - 사업자번호 인증 API

- 추후 추가될 사항들
  - 사용자의 위치를 입력하여 가까운 순서대로 헬스장을 보여줌
  - 결제 API 사용
  - 회원권 일시정지, 연장기능
  - 헬스장 정보 수정 페이지
  - 핸드폰번호 입력시 인증번호 발송 및 입력 
  - SNS아이디를 통한 빠른 로그인, 회원가입

---------------------------------------------------------
## Project planning   

- 프로젝트 계획 과정
  총 프로젝트 기간 30일  프로젝트 기획 4일 요구사항 정의 3일 데이터베이스 설계 7일 기술명세서 작성 7일
  
  ---------------------------------------------------------
## Layout Design
- 판매자와 사용자가 사용하는 화면이 다르므로 이용자에 맞는 화면을 설계
- 사용자 화면
 ![image]()
- 판매자 화면
  ![image]()
  
---------------------------------------------------------
## Data Base design

- 데이터베이스 설계 과정  
  Has a 관계에 중점을 두고 설계를 진행하였습니다. Owner와 User는 서로 다른 정보를 필요로 하지만 서로 완벽하게 독립적인 관계는 아니기 때문에 각 테이블간의 연결성을 우선적으로 고려하였습니다.
  
- initial DB design
![디비 설계]()

- DB ERD
![DB-ERD]()

--------------------------------------------------------
## Functional Specification

- 기술명세서 작성
  - https://docs.google.com/spreadsheets/d/1KWoKs7q8w8CywX_KmKA10uDT3iW2dMSPw1QK_EhPTA8/edit#gid=0
--------------------------------------------------------
## Create eclipse project with github

--------------------------------------------------------
## Value Object Class

--------------------------------------------------------
## Development implementation

--------------------------------------------------------
## Integration test