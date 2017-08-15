---
title: "JavaScript大闯关..."
date: 2017-08-11
tags: [细节]
categories: [JavaScript]
---
原Repo地址:[JavaScript Quiz](https://github.com/everget/javascript-quiz)  
下面记录一些...自己觉得很有意思的地方，暴露基础了:joy:

1.
```javascript
false % 1; // 0
1 / ''; // Infinity
```
这两个例子说明一般算数运算符(除了`+`)之外，都会先将操作数转成`Number`;

2.
```js
+'  -12'; // -12
```
说明`+`作为单目运算符时会将操作数转为`Number`;

3.
```js

