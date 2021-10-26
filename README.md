# React Project

## 출력하기(index.js)
```javascript
import React from "react";
import ReactDom from "react-dom";

const name = "imJihyeon";
const hello = <h1>Hello {name}</h1>;

ReactDom.render(hello,document.getElementById("root"));
```