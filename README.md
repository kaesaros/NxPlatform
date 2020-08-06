
# NxPlatform ( Next .Net Platform) 

## Client (Presentation / Bot App)
### 공통요건  
   *  #### 인증
      *  [ ] SSO/SLO 인증 연계     
   *  #### 자격증명
      *  [ ] HR / Account / Role / Permission 검증 

### 공통구성
  *  #### Launcher    
      *  ##### Navigation  
         *  System
         *  ApplicationBar 
         * NavBar
         * ProgramArea
  *  #### UI Frame Layout  
      * [ ] Top Driven 
      * [ ] Side Driven
      * [ ] Top & Side Driven    
  *  #### UI Component Design / Usage Guide
  *  #### UX Behavior PATTERN  
  
### 어플리케이션타입
  * ### WebApp (Cross Browser App)
      * #### C# ASP.NET WebForm
      * #### C# ASP.NET MVC 
        * #### C# ASP.NET Blazor Server 
      * #### Javascript Nexacro 
      * #### Javascript WebSquare
  * ### WinApp (Windows App)
       * #### C# WinForm
       * #### C# WPF
  * ### MobApp (Hybrid NativeApp / Hybrid MobWebApp)
        * #### C# ASP.NET Blazor WASM
        * #### Swift IOS Native Wrapper
        * #### Kotlin Android Native Wrapper
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
 * [ ] Coding Pattern   
 * [ ] Naming Convention  
 * [ ] Secure Coding 
 * [ ] Do & Not Do



---

## FrontEnd (Presentation Controller)
### 공통요건  
  * #### Session
    * [ ] Stateless
    * [ ] State full
* #### Auth Token
* #### Message Format
    * [ ] JSON
    * [ ] XML
    * [ ] Protocol buffer
    * [ ]     Message Pack
    * [ ]     Binary Stream
    
### 공통구성
   * #### Data Access Execution
   * #### Business Logic  Execution
   * #### Playbook Execution

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
  * #### Session
    * [ ] Stateless
    * [ ] State full
* #### Auth Token
* #### 메시지직렬화타입
* #### 메시지전송타입
* #### 메시지전송프로토콜
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
### 공통구성
### 플레이북타입
### Code Qualify  & Secure
  * [ ] Core API Unit Test
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
   


