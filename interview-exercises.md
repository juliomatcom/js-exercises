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
What is the result of the following code? Explain your answer.

```javascript
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
```

How old is Juan ?

```javascript

function new Person(age) {
  this.age = age
  this.grow = function () { 
    this.age++;
  }
  this.rejuvenate = function () {
    this.age-- ;
  }
}

var juan = new Person(18)
$button.on('click', juan.grow);
$button.click();

juan.rejuvenete();

console.log(juan.age) // ?
```
