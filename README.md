
# NxPlatform Requiment
**Next Platform**

## 핵심도출과제
   - **개발생산성 확보방안**      
      - 인수인계성 제시
        - 신규 멤버가 빠르게 개발 Performance를 보일 수 있는 지에 대한 Factor
      
      
   - **운영편의성 확보방안**
      - 변경용이성 제시
        - 운영 중 쉽고 빠르게 요건 대응 가능한지에 대한 Factor
      
      
   - **기능안정성 식별방안**      
      - 견고성 제시
        - 변경으로 인한 장애/오류 발생 가능성을 식별 가능 Factor
      
      
   - **처리성능 식별방안**      
      - 효율성 제시
        - 코드 내의 성능 저하 요소 식별 및 해소 Factor
      
      
   - **취약 보안(취약성)성 대응 방안**
      - 보안성 제시
        - 보안 위험이 있는 아키텍쳐 식별 및 해소 Factor
        - 보안 위험이 있는 소스코드 식별 및 해소 Factor
        - 보안 위험이 있는 서버 취약성 식별 및 해소 Factor
        - SSL/TLS1.3 적용
        - 시큐어코딩/모의해킹 대응     

---

# NxPlatform Layer

## Client (Presentation / Bot App) Layer
### 주요요건  
   - **인증 및 자격증명**
      - SSO/SLO 인증 연계 
      - HR / Account / Role / Permission 검증  
      - 인증토큰 유지
      
   - **UI 프레임워크**
     - PROGRAM DOSSIER 삽입
     - URL REWRITE
     - PARAMETER INJECTION     
     
   - **UX 패턴**     
     - Single / Mulity Data CRUD UX FLOW   
     
   - **UI 컴퍼넌트 코드 라이브러리** 
     - Usage Guide
       - Best Practice 
       - Case Study 
       

### 주요구성요소
  - **UI Launcher**
    - Navigation  
      - System 
      - ApplicationBar 
      - NavBar 
      - Program/DossierArea
         
  - **UI Frame Layout**  
    - [ ] Top Driven 방식
    - [ ] Side Driven방식
    - [ ] Top & Side Driven 방식

  - **UI Component Wrapper**
    - Win
      - [ ] Telerik
      - [ ] Devexpress
    - Web
      - [ ] IBSheet 기본 적용      
    - Mob
      - IOS
      - Android
      
  - **UI Component Design**
    - [ ] 구성 및 디자인 가이드
    
  - **UX Behavior Patern*    
    - [ ] 사용자 경험 조작 동선
    
  - **DEVOPS TOOL**
    - DataAccess Management Tool
      - Grouping 
      - Editing
      - Running
      - Debugging
      - Watching
    - PlayBook Management Tool
      - Grouping 
      - Editing
      - Running
      - Debugging
      - Watching
      
    - EventSignal Definition Tool
    
  
### 주요형태
  - **WebApp (Cross Browser App)**
    - [ ] C# ASP.NET WebForm
    - [ ] C# ASP.NET MVC 
    - [ ] C# ASP.NET Blazor Server 
    - [ ] Javascript Nexacro 
    - [ ] Javascript WebSquare
  - **WinApp (Windows App)**
    - [ ] C# WinForm
    - [ ] C# WPF
  - **MobApp (Hybrid NativeApp / Hybrid MobWebApp)**
    - [ ] C# ASP.NET Blazor WASM
    - [ ] Swift IOS Native Wrapper
    - [ ] Kotlin Android Native Wrapper
  - **DaemonApp (CrossOS Active Agent App)**
    - [ ] C# Windows Service
    - [ ] C# Linux Daemon
  - **AdaptorApp (Windows Server Passive App)**
    - [ ] C# Console

    
### 필수산출물
  - **Coding Pattern**   
    - Do & Not Do
  - **Naming Convention**
    - Do & Not Do
  - **Secure Coding** 
    - Do & Not Do 
    
---

## FrontEnd (Presentation Controller / GateWay) Layer
### 주요요건  
  - **DOCKER Container**  
  
  - **인증 및 자격증명**  
  
  - **External GateWay 서비스**
    - Load Balancing Avail
    - Stateless
    - Service Aggregate
    
  - **Auth Token**
  
  - **메시지규격**
    - POCO & DataSet

  - **메시지전송포맷**    
    - [ ] XML
    - [ ] JSON
    - [ ] Protobuf
    - [ ] Binary  
    
  - **메시지전송채널**        
    - HTTPS
    
  - **디버깅 및 추적 방안**
  
  - **Unit Test**         
  
### 주요구성요소
  - Data Access Aggregation
  - Static Business Logic Aggregation
  - Dynamic Playbook Aggregation

### 주요형태
  - **C# Client Controller**
  - **C# Service Gateway**
  
  - **기타**
    - **Nexacro Controller**
    - ~**WebSquare Controller**~ 계획없음

### 필수산출물
  - **Coding Pattern**   
    - Do & Not Do
  - **Naming Convention**
    - Do & Not Do
  - **Secure Coding** 
    - Do & Not Do 

  
---  

## BackEnd  (비지니스 서비스) Layer
### 주요요건 
  - **DOCKER 컨테이너 기반**
  - **함수형 프로그래밍 패턴**
  - **Service Mashup**
  - **Service Router**
  - **Load Balancing Avail**
    - Stateless  
  - **Platform API**
  - **Auth Token**
  - **메시지규격**
    - POCO & DataSet
  - **메시지전송포맷**
    - ProtoBuf
  - **메시지전송채널**
    - NET.TCP BINARY    
  - **디버깅 및 추적 방안**  
  - **Unit Test**         

### 주요구성요소
  - **Core Service**    
    - Role & Permission
  - **DomainBiz Service**
  - **Signal Service**
  - **Command Service**  
  - **Playbook Service**   
    - Center Agent
    - Pylon Agent

### 주요형태
  - **WCF**
  - **ASP.NET WebAPI**
  - **ASP.NET Core gRPC**
  - **ASP.NET SignalR**  

### 필수산출물
  - **Coding Pattern**   
    - Do & Not Do
  - **Naming Convention**
    - Do & Not Do
  - **Secure Coding** 
    - Do & Not Do 

---    


## Persistence (데이터 영속) Layer
### 주요요건 
  - **Microsoft and Windows Server Familiar Platform****
  - **모델링**  
  - **파일처리**      
  - **이중화**
  - **성능 검증안**  
  - **디버깅 및 추적**
  

### 주요구성요소  
  - **관계형 데이터베이스**
    - 업무 도메인 모델링
  - **도큐먼트형 데이터베스**
    - 처리 로그 모델링
  - **인메모리키밸류 데이터베이스**
      - 토큰 모델링
        
  - **필수제공인프라서비스**
    - ID Generator
    - Dialog
    - Role & Permission  
    - Tenant / Subsidiary / Dept / Emp
    - User & UserGroup
    - System 
    - Application
    - Navigation   
  
  
### 주요형태
  - **RDBMS**
    - [ ] MSSQL 2019 on Windows
  - **NOSQL**
    - [ ] MongoDB on Windows
    - [ ] REDIS on Windows
  - **STORAGE**  
    - [ ] NAS
    - [ ] SAN
    - [ ] SMB
    - [ ] iSCSI

### 필수산출물
  - **업무 모델 정의**
  - **Object Convention 정의**
  - **Query Pattern & Templete**
  - **Query  UseCase**
  
---


# NxPlatform Core Inside
**플랫폼핵심구동요소**

## Common Service
### 주요요건 
### 주요구성요소 
### 주요형태

---  

## Common Adpator
### 주요요건 
### 주요구성요소 
### 주요형태


---  

## Business Process Playbook ( Coded & Play 방식 업무 처리)
### 주요요건 
  * 함수형 프로그래밍
    
### 주요구성요소
  * [ ] Process Mesh

### 주요형태
  * DataAccess
  * Business Process 
  * CLI / API / UI Execute
  

---  
  
## RealTime MessageQue (실 이벤트 메시지 교환)
### 주요요건 
  - **BroadCast**
  - **Bi-Direction**
### 주요구성요소 
### 주요형태
  - **SignalR**
    

---

## BatchJob  (배치 업무 처리)
### 주요요건 
  - **스케쥴링**
  - **큐잉**  
  - **병렬처리**
  
### 주요구성요소 
  - **작업등록**  
  - **작업모니터링**
  - **작업리포트**
  
### 주요형태  
  - **SSIS**
  
 

---


##  Interface (연계 인터페이스)
### 주요요건 
  - 기도입 EAI 활용 
  
### 주요구성요소 
  - **Pre-Processor**
  - **In Processor**
  - **Post-Proccesser**
  - **Logging / Debugging / Monitoring**

### 주요형태
  - **동작주기**
    - BATCH / ONLINE
    
  - **처리방식**
    - SYNC / ASYNC

  - **호출방식**
    - DB to DB
    - DB to RFC
    - DB to API (SOAP / REST) 

  - **트랜젝션**

 
---

## 리포팅 서비스 
### 주요요건 
  - SSRS  혹은 기도입 리포트 제품 활용 
### 주요구성요소 
### 주요형태
    

---

# NxPlatform DEVOPS
**플랫폼 개발 운영 라이프사이클 관리**

## DEVOPS TOOL 
### 주요요건 
  - **타입아이템관리** 
  - **배치업무관리**   
  - **DataAccess 서비스/코드 관리 도구**
  - **플레이북/코드 관리도구** 
  - **모니터링** 
    - 성능 
    - 동작 
    - 에러     
  
### 주요구성요소 
### 주요형태

---

## CI/CD Automation 
### 주요요건 
  - JENKINS  혹은 기도입 제품 활용 
  
### 주요구성요소 
  - **CLIENT 빌드/배포자동화**
  - **FRONT-END 빌드/배포자동화**
  - **BACK-END 빌드/배포자동화**  
  
### 주요형태


---

# NxPlatform 아키텍처
## 아키텍처 기술 문서
  - **Database Schemas**: this is very useful for quickly understanding the relation between many entities of your software.
  - **Software Architecture Schemas**: which explains how different parts of your software interact together.
  - **Sequence Diagram**: it displays the successive stages of a complex flow
  - **Technical decision logs**


---
# NxPlatform 코어 제공 비지니스
## 레거시시스템(EAI 연동) 마이크로서비스
  - FI RFC 
  - EWF  
  - HR 

## 인증/자격증명 마이크로서비스
  - LDAP, SSO, TOKEN 
  - ROLE, AUTH, PERM

## 인사/조직정보 연동
  - 실시간 / 배치 
  - 처리 로그 
  - 동적 역할 / 그룹  


## 어플리케이션 런처
  - 윈도우 
  - 웹 
  - 모바일

### 프로그램등록관리
  - 메뉴네비게이션관리

### 역할관리
  - 고정역할 / 동적역할
  
### 네비게이션 제공 권한
  - 프로그램 조회/사용 권한

### 사용자관리
  - 인사변동자 역할/권한 자동 인수/인계/회수

### 사용자그룹관리
  - 고정사용자그룹 / 동적사용자그룹

### 화면도움말
  - 온라인문서뷰어

### 파일업로드
  - 파일 라이프사이클 관리

### 파일다운로드
  - 파일다운로드통제

### 시스템활용현황
  - 업무별 접속 / 사용패턴  

## 처리업무별 화면패턴코드
  - 그리드
  - 탭
  - 폼


## .Net Framework 버전 호환 요건
  * [ ] .NET FRAMEWORK 4.X ~ 4.8
  * [ ] .NET Core 3.1
  * [ ] .NET 5
  
## 인프라 요건
  * OS   
    * [ ] Windows Server 201X
  * DBMS 
    * [ ] MSSQL 201X
  * IDE  
    * [ ] VisualStudio 201X

## 형상관리 요건
  * GIT
    * [ ] GITHUB 
    * [ ] TFS
  
## 빌드/배포 자동화 방안
  * JENKINS CI/CD 



