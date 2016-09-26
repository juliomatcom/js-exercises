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
  this.grow = (years) => this.age += years;
  this.rejuvenate = function (years) {
    this.age -= years;
  }
}

var juan = Person(18)
juan.grow(2)
juan.rejuvenete(3)

console.log(juan.age) // ?
```
