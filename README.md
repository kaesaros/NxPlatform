
# NxPlatform ( Next .Net Platform) 
## .Net Framework 버전 호환
  * [ ] .NET FRAMEWORK 4.X ~ 4.8
  * [ ] .NET Core 3.1
  * [ ] .NET 5
  
## 인프라
  * OS   
    * [ ] Windows Server 201X
  * DBMS 
    * [ ] MSSQL 201X
  * IDE  
    * [ ] VisualStudio 201X

## 형상관리 
  * GIT
    * [ ] GITHUB 
    * [ ] TFS
  
## 빌드/배포 자동화
  * JENKINS CI/CD 

## 5대 방안
   - **개발생산성 확보방안**      
      - 인수인계성 제시
        - 신규 멤버가 빠르게 개발 Performance를 보일 수 있는 지에 대한 Factor
      - [상세보기]()
      
   - **운영편의성 확보방안**
      - 변경용이성 제시
        - 운영 중 쉽고 빠르게 요건 대응 가능한지에 대한 Factor
      - [상세보기]()
      
   - **기능안정성 식별방안**      
      - 견고성 제시
        - 변경으로 인한 장애/오류 발생 가능성을 식별 가능 방안
      - [상세보기]()         
      
   - **처리성능 식별방안**      
      - 효율성 제시
        - 코드 내의 성능 저하 요소 식별 및 해소 방안
      - [상세보기]()
      
   - **취약 보안(취약성)성 대응 방안**
      - 보안성 제시
        - 보안 위험이 있는 아키텍쳐 식별 및 해소 방안
        - 보안 위험이 있는 소스코드 식별 및 해소 방안
        - 보안 위험이 있는 서버 취약성 식별 및 해소 방안
      - [상세보기]()         
        - SSL/TLS1.3 적용
        - 시큐어코딩/모의해킹 대응     
---

## Client (Presentation / Bot App)
### 공통요건  
   - **인증 및 자격증명**
      -  SSO/SLO 인증 연계 
      -  HR / Account / Role / Permission 검증 
 
      
   - **UI 프레임워크**
     - VIEW 삽입
     - URL REWRITE
     - PARAMETER INJECTION
     - Single / Mulity Data CRUD 처리 UX
     - [상세보기]()
     
   - **UI 컴퍼넌트 코드 라이브러리** 
      - Best Practice 
      - Case Study 
      - Usage Guide
      - [상세보기]()   


### 공통구성
  *  #### UI Launcher    
      *  ##### Navigation  
         * System Definition
         * ApplicationBar Definition
         * NavBar Definition
         * ProgramArea Definition
  *  #### UI Frame Layout  
      * [ ] Top Driven 방식
      * [ ] Side Driven방식
      * [ ] Top & Side Driven 방식
  *  #### UI Component Design
  *  #### UX Behavior PATTERN    
  *  #### UI Component (Win/Web/Mob)
      * [ ] IBSheet 기본 적용

  
### 어플리케이션타입
  * #### WebApp (Cross Browser App)
      * [ ] C# ASP.NET WebForm
      * [ ] C# ASP.NET MVC 
      * [ ] C# ASP.NET Blazor Server 
      * [ ] Javascript Nexacro 
      * [ ] Javascript WebSquare
  * #### WinApp (Windows App)
       * [ ] C# WinForm
       * [ ] C# WPF
  * #### MobApp (Hybrid NativeApp / Hybrid MobWebApp)
       * [ ] C# ASP.NET Blazor WASM
       * [ ] Swift IOS Native Wrapper
       * [ ] Kotlin Android Native Wrapper
  * ### DaemonApp (Cross OS Agent App)
      * #### C# Windows Service
      * #### C# Linux Daemon
  * ### AdaptorApp ()
      * #### C# Windows Console

  * ### DEVOPS AUTOMATION 
      * [ ]  UPDATER
      * [ ]  DEPLOY
      * [ ]  INSTALLER 
    
### Code Qualify  & Secure
 [상세보기](https://github.com/kaesaros/NxPlatform/blob/master/CodeQualify.txt)  
 * [ ] Coding Pattern   
 * [ ] Naming Convention  
 * [ ] Secure Coding 
 * [ ] Do & Not Do



---

## FrontEnd (Presentation Controller)
### 공통요건  
  * #### External GateWay 서비스
    * [ ] Load Balancing Avail
  * #### Session
    * [ ] Stateless
    * [ ] State full
  * #### Auth Token
  * #### Message Format
    * [ ] JSON
    * [ ] XML
    * [ ] Protocol buffer
    * [ ] Message Pack
    * [ ] Binary Stream
    
### 공통구성
   * Data Access Execution
   * Business Logic  Execution
   * Playbook Execution

### 컨트롤러타입
  * #### C# Application Controller
  * #### Nexacro Controller
  * #### WebSquare Controller

### Code Qualify  & Secure
  * [ ] Contoller API Unit Test
  * [ ] Coding Pattern   
  * [ ] Naming Convention  
  * [ ] Secure Coding 
  * [ ] Do & Not Do

  
---  

## BackEnd  (비지니스 서비스)
### 공통요건 
  * DOCKER 컨테이너 기반
  * 함수형 프로그래밍 패턴 
  * Service Mashup
  * Service Router
  * Load Balancing Avail
    * [ ] Stateless  
  * Platform API  
  * Auth Token
  * 메시지
    * 직렬화타입
  * 메시지전송타입
  * 메시지전송프로토콜
  * 디버깅 및 추적 방안

### 공통구성
*  #### Role & Permission 

### 서비스타입
*  #### WCF API
*  #### gRPC API
*  #### SignalR API

  

### Code Qualify  & Secure
  * [ ] Core API Unit Test
  * [ ] Coding Pattern   
  * [ ] Naming Convention  
  * [ ] Secure Coding 
  * [ ] Do & Not Do
  
---  
  


## Persistence (데이터 영속)
### 공통요건 
* #### Microsoft and Windows Server Familiar Platform
* #### 업무 모델 정의
* #### Object Convention  정의
* #### Query Pattern & Templete
* #### Query  UseCase
* #### 이중화 방안
* #### 디버깅 및 추적 방안
* 
### 공통구성
*  ### 모델링
    * #### 관계형 
        * [ ] 업무 모델링
    * #### 도큐먼트형
        * [ ] 처리로그 모델링
    * #### 키밸류형
        * [ ] 토큰 모델링
        *
*  #### 핵심서비스
    *  [ ]  ID Generator
    *  [ ]  Dialog
    *  [ ]  Role & Permission  
    *  [ ]  Tenant / Subsidiary / Dept / Emp
    *  [ ]  User & UserGroup
    *  [ ]  System 
    *  [ ]  Application
    *  [ ]  Navigation
  
### 저장소타입
* ####  RDBMS
    * [ ] MSSQL 2019 on Windows
* ####  NOSQL
    * [ ] MongoDB on Windows
    * [ ] REDIS on Windows
* #### STORAGE  
    * [ ] NAS
    * [ ] SAN
    * [ ] SMB
    * [ ] iSCSI

---

## Business Process  Playbook ( Coded & Play 방식 업무 처리)
### 공통요건 
    * 함수형 프로그래밍
    

### 공통구성
    * [ ] Process Mesh

### 플레이북타입
    * DataAccess
    * Business Process 
    * CLI / API / UI Execute

### Code Qualify  & Secure
  * [ ] Unit Test
  * [ ] Coding Pattern   
  * [ ] Naming Convention  
  * [ ] Secure Coding 
  * [ ] Do & Not Do
  
  
## RealTimeMessageQue (실 이벤트 메시지 교환)
### 공통요건 
* #### BroadCast  
* #### Bi-Direction
### 공통구성

### 메시지큐타입
* #### SignalR
### Code Qualify  & Secure

  
### Code Qualify  & Secure
  * [ ] Core API Unit Test
  * [ ] Coding Pattern   
  * [ ] Naming Convention  
  * [ ] Secure Coding 
  * [ ] Do & Not Do
  

---

## BatchJob  (배치 업무 처리)
  ### SSIS
  ### 작업등록  
  ### 스케쥴링  
  ### 큐잉  
  ### 병렬처리
  #### Coding Pattern   
  #### Coding Convention  
  #### Secure Coding Guide  
  #### Do / Not Do Guide   

---

## Interface (인터페이스)
  ### EAI (SolutionName)  
  ### PEAR
*  #### SAP RFC
*  #### DB 
*  #### WebService
*  #### WebApi

 ###  BATCH / ONLINE
 ### SYNC / ASYNC

 
---

## 리포팅 서비스 

---

## CI/CD Automation 

   



*  [ ] VIEW 삽입\
