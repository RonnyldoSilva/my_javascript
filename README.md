# My Javascript

## Numbers:
```javascript
0.1 + 0.2 == 0.30000000000000004

Math.sin(3.5);
var d = Math.PI * r * r;

> parseInt("123", 10)
123

> parseInt("11", 2)
3

> + "42"
42 

> parseInt("hello", 10)
NaN

> NaN + 5
NaN

> isNaN(NaN)
true
```

## Never Declare Number, String, or Boolean Objects
```javascript
var x = "John";             
var y = new String("John");
(x === y) // is false because x is a string and y is an object. 
```
