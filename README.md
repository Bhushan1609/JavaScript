# Learning JavaScript

Welcome to my JavaScript learning repository! This repository contains my notes, code examples, and exercises as I progress through learning JavaScript. I hope you find it useful, whether you are also learning JavaScript or just looking for some reference material.


1.Declaring a Vector in JavaScript<br>
2.Declaring a 2D Vector in JavaScript<br>\
3.Pair in JavaScript<br\>


# 1.Declaring a Vector in JavaScript
```javascript
let arr=new Array(n).fill(0);
```
# 2.Declaring a 2D Vector in JavaScript
```javascript
let matrix=new Array( n).fill(0).map(() => new Array(m).fill(1));
```
# 3.Pair in JavaScript
Declaration :
let variable = new pair(16 , Bhushan);

console.log(variable.fi());

console.log(variable.se());

```javascript
class pair {
    constructor(first, second) {
        this.first = first;
        this.second = second;
    }
    fi() {
        return this.first;
    }
    se() {
        return this.second;
    }
    setFirst(first) {
        this.first = first;
    }
    setSecond(second) {
        this.second = second;
    }
}
```
