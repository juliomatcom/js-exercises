
```javascript

(function() {
   var a = b = 5;
})();

console.log(b);
```

What will be printed on the console?


What’s the result of executing this code and why.

```javascript
function test() {
   console.log(a);
   console.log(foo());
   
   var a = 1;
   function foo() {
      return 2;
   }
}

test();
```

