# Lesson 01

a website usually contains the 3 basics:
1. HTML - the structure of the page. 
2. CSS - the design of the page.
3. JavaScript - make the website dynamic. 

## JavaScript:
Is a programming language. 
* OOP - Object Oriented Programming lang. 
* Event driven. 
* Dynamicly typed. 

## Visual studio VS visual studio code:
Visual studio is IDE (Integrated development environment) and compiler (C/C++, Java, C#). 
visual studio code is text editor - is interpreter. (python, JS, HTML)


### Alert
alert - popup to user. 
```js
alert("Hello");
```
### Console.log()
Console.log() - prints to the console (behind the schenes) data. 
```js
console.log("Hello");
```
### prompt()
prompt() - gets input from the user. 
> note: input from user (in any language) comes as string. if we need a number - we must convert it.  
```js
var res = prompt("Enter res");
var res = Number(prompt("Enter res"));
```

### Typeof

will return the type of a variable

```js
console.log(typeof {a:1}); // Object
```

### if - else

check the value inside () - and return boolean expression. case true - will enter. 

```js
if(){
    // code to execute
}
else if(){

}
else{

}
```

### interpolation - שרבוב
allow us to put inside the string variables. 
```js
var str = `2 + 2 = ${2 + 2}`
var str = `Hello user, your age: ${age}`
```

### Switch-case
```js
switch(){
    case: // code to execute
    break;

    default: // code to execute
}
```
