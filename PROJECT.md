## 증권 투자 서비스

  

### 관련 사이트

- [efriend 홈페이지](https://efriendexpert.com/)
- EFriend Service
  - [EFriendService GitHub](https://github.com/pnuskgh/EFriendService)
    - [프로젝트 개요](https://github.com/pnuskgh/EFriendService/blob/main/PROJECT.md)
- 카카오톡
  - [블루스톤 오픈채팅방](https://open.kakao.com/o/gZKGWq0f)
- 렛플: [한국투자증권 Node.js 라이브러리](https://letspl.me/project/900)
- 증권사 REST API
  - [한국투자증권](https://apiportal.koreainvestment.com/apiservice/)
  - [이베스트투자증권](https://openapi.ebestsec.co.kr/apiservice) : 미지원

​     

  

### 시작 동기

  

한국투자증권에서 제공하는 REST API를 사용하여 node에서 사용할 수 있는 라이브러리를 만들어 배포 하였습니다.

- [efriend 홈페이지](https://efriendexpert.com/)
  
- efriend 라이브러리

  - [efriend NPM 라이브러리](https://www.npmjs.com/package/efriend)
  - [EFriendExpert GitHub](https://github.com/pnuskgh/EFriendExpert)
    - [프로젝트 개요](https://github.com/pnuskgh/EFriendExpert/blob/main/PROJECT.md)
  - [한국투자증권 KIS Developers](https://apiportal.koreainvestment.com/apiservice/oauth2)

- 카카오톡

  - [EFriendExpert 오픈 채팅방](https://open.kakao.com/o/gZbStqsf)
  - [EFriendExpert 1:1 채팅방](https://open.kakao.com/o/snBRsqsf)

- 렛플: [증권 투자 서비스](https://letspl.me/project/1336)

- 증권사 REST API

  - [한국투자증권](https://apiportal.koreainvestment.com/apiservice/)
  - [이베스트투자증권](https://openapi.ebestsec.co.kr/apiservice) : 미지원

  

다음 단계로, **해당 라이브러리를 사용하여 투자 자동화 서비스**를 같이 만들려고 합니다.

증권 투자에 관심이 있거나 아이디어가 있는 분은 지원해 주세요.

한국투자증권에서 제공하는 API를 사용하여 자동매매를 구현하고자 하는 사용자 대상 입니다.

  

아이디어만 있는 분도 많이 지원해 주세요.

프로젝트의 방향은 2가지 입니다.

  

- 첫째. 여러 사람의 아이디어를 결합한 Web Service
- 둘째. 개인의 독자적인 아이디어를 구현할 Application




### 진행 방식 

   

- Zoom을 사용하여 1주일에 1회 정기적으로 회의 합니다.
- [블루스톤 오픈채팅방](https://open.kakao.com/o/gZKGWq0f)에 zoom 링크를 공유 합니다.
  - 각자가 가진 아이디어를 공유 하거나 주제를 정하여 발표 하고 다음 1주일간 진행할 사항을 정하여 역할을 분담 합니다.
  

​    

### 기간

  

1단계 : 2024년 1월 1일부터 2024년 6월 30일까지

- 제1차 온라인 미팅 : 2024년 1월 8일 월요일 오후 7시 예정 (미확정)
  - [블루스톤 오픈채팅방](https://open.kakao.com/o/gZKGWq0f)에서 zoom 링크 배포
  - 참석자 소개
  - 프로젝트 개요 소개
  - 향후 프로젝트 진행 방향 협의

  

2단계 : 추후 협의

   

### **사용 서비스**

  

- [Zoom](https://zoom.us/) : 온라인 미팅

- [카카오톡](https://www.kakaocorp.com/) : 공지 등 알림과 일정 조율
- [Discord](https://discord.com/) : 커뮤니케이션
- [GitHub](https://github.com/) : 소스와 문서 관리
  
  - 기존 사용 언어 : [TypeScript](https://www.typescriptlang.org/)와 [JavaScript](https://developer.mozilla.org/ko/docs/Web/JavaScript)
- 기본 문서 포맷 : [Markdown](https://gparkkii.github.io/tech/markdown/) (~.md)
  
  

### **개발 환경**

  

- 개발 언어 : [TypeScript](https://www.typescriptlang.org/)와 [JavaScript](https://developer.mozilla.org/ko/docs/Web/JavaScript)
  
  - [efriend 라이브러리](https://www.npmjs.com/package/efriend) 사용
- 테스트 : [Mocha](https://mochajs.org/) with [Chai](https://www.chaijs.com/), [Sinon](https://sinonjs.org/)
  - 후보
    - [Mocha](https://mochajs.org/) : Test Framework
    - [Chai](https://www.chaijs.com/) : Assertion library
    - [Sinon](https://sinonjs.org/) : Test double
    - [istanbul](https://istanbul.js.org/) : Code Coverage
    - [Vitest](https://vitest.dev/) : Unit Test Framework

- Software
  - Web Server : [Nginx](https://nginx.org/)
  - Application
    - [Node.js](https://nodejs.org/) (Web과 Desktop Application용)
    - [Electron](https://www.electronjs.org/) (Desktop Application용)
  - Database : [MariaDB](https://mariadb.org/)
  - Cache : [Redis](https://redis.com/)
  - MQTT : [Mosquitto](https://mosquitto.org/)
  - Chart : [D3](https://d3js.org/), [Trading View](https://tradegnview.com/), [AnyChart](https://www.anychart.com/) 등
  - Notification
    - Email ([Gmail](https://mail.google.com/) 등)
    - SMS ([알리고](https://smartsms.aligo.in/) 등)
    - [Telegram](https://telegram.org/) 등
  - OS : [Window](https://www.microsoft.com/ko-kr/windows), [Mac](https://www.apple.com/kr/mac/), [CentOS](https://www.centos.org/) 등

  



### Git Convention

  

- 형상 관리를 위한 branch 전략
  - master : 제품으로 출시될 수 있는 브랜치
  - develop : 다음 출시 버전을 개발하는 브랜치
  - feature : 기능을 개발하는 브랜치
  - release : 이번 출시 버전을 준비하는 브랜치
  - hotfix : 출시 버전에서 발생한 버그를 수정 하는 브랜치
- Merge process
  - Merge Request
  - 동료 Review
  - Merge
- Commit message 규칙
  - [Type] commit message
  - type 종류
    - feature : 새로운 기능 추가
    - fix : 버그 수정
    - docs : 문서 업데이트
    - style : frontend의 style 수정
    - refactor : 코드의 리팩토링
    - test : 테스트 코드 업데이트
    - env : 환경 구축

​    

### **Code Convention**

  

- ESLint 사용
- Prettier 사용

    

 투자에 관심이 있는 분의 많은 지원 바랍니다.

  

  
