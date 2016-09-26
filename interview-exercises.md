### Scope

```javascript

(function() {
   var a = b = 5;
})();

console.log(b);
```

What will be printed on the console?

### Hoisting

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
### this

var fullname = 'John Doe';
var obj = {
   fullname: 'Colin Ihrig',
   prop: {
      fullname: 'Aurelio De Rosa',
      getFullname: function() {
         return this.fullname;
      }
   }
};
