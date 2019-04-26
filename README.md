# Study ReAct by LossCut

## About

React 기본 작업 환경
- babel 을 통한 ES6 변환
- webpack-dev-server 사용
- react-hot-loader 를 통한 Hot Module Reload 사용

React CodeLab 에서 작업환경 설정을 할 때 사용 된 코드 입니다.


## 설치하기

```sh
npm install -g webpack webpack-dev-server
npm init
npm install --save react react-dom
npm install --save redux
npm install --save-dev babel-core babel-loader@7 babel-preset-es2015 babel-preset-react 
npm install --save-dev react-hot-loader webpack webpack-dev-server
npm install --save-dev webpack-cli
npm install --save react-redux
Global Dependency 설치
npm install -g babel-cli nodemon cross-env
Local Dependency 설치
npm install --save express body-parser
```

## 실행하기

```
개발 환경 : npm run dev
배포 빌드 : npm run build
```

서버는 포트 8080 으로 실행됩니다. 변경은 webpack.config.js 에서 할 수 있습니다.


 ## Markdown PreView
 ```
 EXTENSIONS 추가
  - markdown All in One, Markdown Preview Enhanced
  - 단축키 : Ctrl + k, v
 ```

## Snippets
```
EXTENSIONS 추가
Reactjs code snippets
ex) rcc
```

## WEBSITE
```
 - https://faith79.github.io/udeme02/public/
 ```


