# Server 1주차 워크북

## 서버와 서비스
    - 주된 정보의 제공이나 작업을 수행하는 컴퓨터 시스템. **서버**는 클라이언트 시스템이 요청한 작업이나 정보의 수행 결과를 돌려준다.
    - **서비스**는 서버가 클라이언트에게 제공하는 것.
## 클라이언트 - 서버 관계
    - 클라이언트가 서버에게 request를 보낸다.
    - 서버는 클라이언트에게 response를 보낸다.
## 서버의 동작 방식과 순서 (요청이 들어왔을 때 서비스가 어떻게 처리되는가?)
    ![Untitled](https://user-images.githubusercontent.com/74655780/198918957-1ebb268b-b6fa-4f3a-b336-b662242ac595.png)
    [[Web] Web Server와 WAS의 차이와 웹 서비스 구조 - Heee's Development Blog](https://gmlwjd9405.github.io/2018/10/27/webserver-vs-was.html)
## 서버의 구조
    - Server Program
        - 웹서버
            - Nginx
            - Apache
    - Backend Language(ex : Java, Javascript…)
        - Was Server
            - Spring
            - node, express
            - django
    - DB, DBMS
        - SQL
            - MySQL
            - MSSSQL
            - ORACLE
        - NoSQL
            - MongoDB
            - Redis
            - Cassandra
## APM
    - Apache
    - Php
    - MySQL
## 로컬 호스트 (localhost)
    컴퓨터 네트워크에서 사용하는 루프백 호스트명 (자신의 컴퓨터)
    IPv4         |         IPv6
    127.0.0.1    |         ::1
    테스트 목적으로 사용
## 가상머신 (Virtual Machine)
    컴퓨터 환경을 소프트웨어로 구현한 것. 가상의 컴퓨터.
    - Virtual Box        
    - VMware        
## Linux, Ubuntu
    - Linux: 커뮤니티 기반으로 개발된 오픈소스 컴퓨터 운영체제(OS) 또는 커널
    - Ubuntu: 컴퓨터 운영체제. 데비안 리눅스를 포크해 개발된다.
## 리눅스 명령어
    [[Linux] 리눅스 기본 명령어 정리](https://cocoon1787.tistory.com/717)
## 리눅스 디렉토리 구조
    [[LINUX] 📚 리눅스 디렉토리 구조 - 💯 한눈에 정리](https://inpa.tistory.com/entry/LINUX-%F0%9F%93%9A-%EB%A6%AC%EB%88%85%EC%8A%A4-%EB%94%94%EB%A0%89%ED%86%A0%EB%A6%AC-%EA%B5%AC%EC%A1%B0)
## vi(vim) 편집기 사용법
    [[Linux] vi 편집기 사용법 및 명령어](https://velog.io/@zeesoo/Linux-vi-%ED%8E%B8%EC%A7%91%EA%B8%B0-%EC%82%AC%EC%9A%A9%EB%B2%95-%EB%B0%8F-%EB%AA%85%EB%A0%B9%EC%96%B4)
## Web Server(WS)와 Web Application Server(WAS)
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f082bf5b-d0b8-4fbc-868e-2e7d2105ed3c/Untitled.png)
## 운영체제 (OS)
    - 운영체제
        **Operating System.**
        사용자의 하드웨어, 시스템 리소스를 제어하고 프로그램에 대한 일반적 서비스를 지원하는 **시스템 소프트웨어**이다.
    - Window, MacOS
        - Window: 마이크로소프트가 개발한 운영체제
        - MacOS: 애플이 개발한 유닉스 기반 운영체제
## CLI와 GUI
    - 인터페이스
        - GUI
            
            Graphic User Interface
            
            사용자가 그래픽을 통해 컴퓨터와 정보를 교환하는 방식
            
        - CLI
            
            Command Line Interface
            
            text terminal을 통해 사용자와 컴퓨터가 상호 작용하는 방식
            
## HTTP
    
    HyperText Transfer Protocol
    
    브라우저와 서버가 대화할 때 사용하는 것
    
    WWW 상에서 정보를 주고받을 수 있는 프로토콜
    
## 패키지 설치와 컴파일 설치
    - 패키지 매니저
        컴퓨터의 운영 체제를 위해 일정한 방식으로 컴퓨터 프로그램의 설치, 업그레이드, 구성, 제거 과정을 자동화하는 소프트웨어 도구들의 모임
    - 컴파일 
