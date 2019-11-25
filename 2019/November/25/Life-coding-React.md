# 리액트 - 생활코딩

## * 리액트 : 페이스북에서 페이스북의 UI를 잘 만들기 위한 라이브러리

### 리액트의 장점

1. 가독성
2. 재사용성
3. 유지보수

### 리액트 - 생활코딩에서 할 것

* coding
* run
* deploy

NPM : Node.js를 이용하여 만들어진 앱들을 손쉽게 만들 수 있는 도구

### NPM 설치 방법

1. [https://nodejs.org](https://nodejs.org)
    * LTS : 안정적인 버전
    * Current : 최신 버전
2. Node.js 설치
3. Window키 + R -> cmd 입력
4. npm install -g create-react-app@2.1.8

### NPM 사용 방법

1. 폴더 생성
2. Window키 + R -> cmd 입력
3. cd 폴더경로 입력
4. react-app 입력
5. npm start
    * 만약 ENOENT 에러가 날 경우
        1. Window키 + R -> cmd 입력
        2. npm install nconf 입력

**index.js**에서  App.js를 import 하는데, 이 App을 통해 태그를 생성한 것으로 작성함.  
즉, App.js에서 작성한 코드를 index.js에서 받음

### Component 만들기

``` JavaScript
class Classname extends Component{
    render(){
        return(
            <div>
            </div>
        );
    }
}
```

Component 생성시, `Classname`이라는 클래스를 통해 만들게 되는데, Classname은 대문자로 시작한다. 이 클래스는 *Component*를 상속받는다.
그 후, `render()`라는 함수를 만드는데. class 속의 함수는 function을 붙이지 않는다. 이 render() 함수는 return 속에 HTML 코드를 반환하는데. 이때, HTML 코드는 최상위 태크가 하나만 존재해야 한다.

``` JavaScript
import React, { Component } from 'react';
```

React와 Component를 임포트 해 주는 코드이다.

### by CutyApple
