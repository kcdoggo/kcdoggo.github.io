---
layout: post
title:  "react spinner"
categories: React
show_excerpts: true

---
리액트 스피너를 만들기 위해선 npm을 이용하는 게 간편하고 빠르다
<br/>
https://www.npmjs.com/package/react-loader-spinner


```javascript
$ npm install react-loader-spinner --save

import "react-loader-spinner/dist/loader/css/react-spinner-loader.css";
import Loader from "react-loader-spinner";
export default class App extends React.Component {
  //other logic
  render() {
    return (
      <Loader
        type="Puff"
        color="#00BFFF"
        height={100}
        width={100}
        timeout={3000} //3 secs
      />
    );
  }
}

```
