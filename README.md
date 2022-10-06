# Javascript-Output-related-questions

Question 1: (Strings, Numbers, Boolean)
var num = 8;
var num = 10;
console.log(num);
Answer 10 **Explanation — **With the var keyword, you can declare multiple variables with the same name. The variable will then hold the latest value. You cannot do this with let or const since they're block-scoped.

Question 2:
function sayHi() {
  console.log(name);
  console.log(age);
  var name = 'Ayush';
  let age = 21;
}

sayHi();
