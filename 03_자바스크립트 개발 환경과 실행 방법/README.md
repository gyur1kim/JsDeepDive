# 3.1 자바스크립트 실행 환경

- 자바스크립트 엔진을 내장한 것
  
  - 브라우저
    
    - HTML, CSS, 자바스크립트를 실행해 웹페이지를 브라우저 화면에 렌더링하는 것이 주된 목적
    
    - ECMAScript + 클라이언트 사이트 Web API 실행
  
  - Node.js
    
    - 브라우저 외부에서 자바스크립트 실행 환경을 제공하는 것이 주된 목적
    
    - ECMAScript + Node.js 고유 API 실행





# 3.2 웹 브라우저

## 3.2.3 브라우저에서 자바스크립트 실행

- 브라우저는 HTML 파일을 로드하면 script 태그에 포함된 자바스크립트 코드를 실행

## 3.2.4 디버깅

- `F12` -> `Source` 패널

- 에러가 발생한 위치에 빨간 밑줄

ㄴ



# 3.3 Node.js

- `Node.js`
  
  - 2009년 라이언 달이 발표
  
  - 크롬 V8 자바스크립트 엔진으로 빌드된 자바스크립트 런타임 환경
  
  - 브라우저에서만 동작하던 자바스크립트를 브라우저 이외의 환경에서 동작시킬 수 있는 자바스크립트 실행 환경
  
  - `node index.js` (.js 생략 가능) 의 커맨드라인으로 파일 실행

- `npm` (node package manager)
  
  - 자바스크립트 패키지 매니저
  
  - Node.js에서 사용할 수 있는 **모듈들**을 **패키지화**해서 모아둔 저장소 역할
  
  - 패키지 설치 및 관리를 위한 CLI를 제공


