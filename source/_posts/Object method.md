---
title: Object Methods
date: 2018-05-13 15:17:34
tags: [JavaScript]
---

```
// OBJ
var A = {
  print: function () {
    console.log('hello');
  }
};

// OBJ
var B = Object.create(A);

Object.getPrototypeOf(B) === A // true
B.print() // hello
B.print === A.print // true
```
