# Node.JS

 - 브라우저에서만 실행되던 javascript를 로컬 pc에서도 작동하게 하는 것.
    - Javascript는 브라우저에 종속되어있던 언어였다.

# What is a Server
 - 인터넷에 연결된 컴퓨터이다.
 - 물리적으로 늘 켜져있는 접속 요청에 응답하는 컴퓨터

# What is a Express
 - node.js에서 작동하는 프레임워크
 - Super 엄청나게 유명하다.
 - 매우 안정적이다.
 
 ## package.json
  - scripts안에 "start": "node index.js" 를 등록하면 npm start명령어로 실행이가능하다.

# Babel
 - 최신의javascript코드를 무난했던 javascript코드로 변환해준다.

# Nodemon
 - node명령어로 일일이 실행시켜야하는 서버를 저장할때마다 자동으로 재실행 시켜주는 모듈

 # ArrowFunction
  - ES6에서 제공하는 함수형태
 ``` javascript
 function Test(){
     console.log("Hello world");
 }

 ->

 const Test = () =>{
     console.log("Hello world");
 }
```

# MVC
 - Model View Controller
 - M : data
 - V : how does the data look
 - C : function that looks for data