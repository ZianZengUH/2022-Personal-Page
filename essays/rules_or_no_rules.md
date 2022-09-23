---
layout: essay
type: essay
title: "Rules or No Rules?"
# All dates must be YYYY-MM-DD format!
date: 2022-09-22
published: true
labels:
  -  Coding Standards
  -  ESLints
  - 
---

<img width="400px" class="rounded float-start pe-4" src="../img/essays/ESLint.jpeg">

# Rules Are Painful

Have you ever gotten bothered by some rules and thought that why do I have to follow them? Following rules is always a hard and sometimes even painful thing to do. Also, rules are everywhere in our lives and we follow many of them every day. It is not an exception in the world of software engineering and it has a name called “code standards”. For example, the following piece of code (from Module 10 - Experience 25) contains 28 errors according to a code analysis tool - ESlint:

```js
var foo = 3;
const car = "Toyota";
const obj = {
 car: car,
 'foo': 3,
 bar: 'this' + 'is' + this.car,
 baz: 'b\az'
};
const zumba = obj['car'];
const stuff = new Array();

function f(){};
function zob(param) {
 param = 2;
 let foob=4+param;
 if (param == 4) {
   return foob;
 }
}
[1, 2, 3].map(function (x) {
 const y = x + 1;
 return x * y;
});
class MyClass {
 constructor() {}
 getName() {
   return this.name;
 }
 getName() {
   return this.name;
 }
}
const TheTitle = 'The Title';

export default {  obj, stuff, zumba, f, zob, MyClass, TheTitle };
```

That’s so many errors that we need to fix! In addition, from my own experience, I got some errors when I was writing the code even though my code actually run correctly as what I wanted. The errors are mostly code style issues like string variables need to use single quotes instead of double quotes, and there need to be space after parentheses etc. Try to fix these errors may be time consuming and tedious. If these rules are complicated and painful to follow, why do we have these rules in the first place and why should we still obey them? 

# Why Should We Follow Rules?

Let’s talk about what is rule first, specifically it is coding standards in the world of software engineering. According to *Geeks for Geeks*, coding standards are the rules that good software development organizations developed to enable their programmers to maintain a well-defined and standard style of coding. There are four main reasons to maintain such a style of coding: 
A coding standard gives a uniform appearance to the codes written by different engineers.
It improves the readability, and maintainability of the code and it reduces complexity also.
It helps in code reuse and helps to detect errors easily.
It promotes sound programming practices and increases the efficiency of the programmers. 
[Coding Standards and Guidelines](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)

If these reasons are too broad for you, let’s imagine a world without implementing coding standards. There are typos all over the place, semicolons are missing from certain places, variables are named randomly without any meaning, lines are not aligned properly, functions are half-finished and missing curly brackets, and so on. For many big companies who have millions of codes, how can the new software engineers who just get on the project able to understand what’s going on, how can the software engineers fix and maintain the program when they can’t even read what their co-workers’ or even themselves’ codes? Simply attempting to understand the code may take hours and hours that may be even longer than rewriting the program. For example, can you read and understand the codes we mentioned earlier easily? For most people, it is probably not very easy to understand what’s going on because the code doesn’t follow the code standard. How about the following piece of code after we modified it to follow the ESlint code standard:

```js
const car = 'Toyota';
const obj = {
 car,
 foo: 3,
 bar: `this is ${this.car}`,
 baz: 'baz',
};

const zumba = obj.car;
const stuff = [];

function zob(param) {
 const foob = 4 + param;
 if (param === 4) {
   return foob;
 }
 return foob + 3;
}

[1, 2, 3].map(function (x) {
 const y = x + 1;
 return x * y;
});

class MyClass {
 getName() {
   return this.name;
 }
}
const TheTitle = 'The Title';

export default {
 obj, stuff, zumba, zob, MyClass, TheTitle,
};
```

I believe for most people this modified code is much easier to read than the original code, and this is the power of code standard. 

Some may argue that their own style of coding is easy to understand as well, but if there is not a universal standard for everyone, everyone can write things very differently despite the fact that the codes are correct and not very hard to read. Using code standards like the AirBnB style implemented in ESlint can make the codes in a standard format that everyone can read the code and every knows where to look for things. This method accomplish the goals of improving the readability and maintainability of the code, reducing the complexity, helping in code reuse and errors detection, and lastly increasing the efficiency of the programmers! Thus, the small amount of time spent in maintaining the code style will prevent the huge amount of time spent from  poor written code. Let’s embrace the code standards while writing our codes!
