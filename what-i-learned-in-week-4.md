What I learned in week 4 
### Monday
****
Boleans

Deals with true false'

&& = both statements have to be followed

|| = either statement has to be true

! is the opposite signal


only use === not ==

Can also incorporate math like symbols like greater than(>), less than (<), greater and less than or equal to (<,>=)

Visual Studio Code Tools
Quokka

```python npm 
1. init -y
2. npm i
3. npm test
``` 

For inequality ranges format is important. 

Make sure you chose relevant and concise names for parameters so its easier to understand the code later on.

```javascript 
function isInDanger(grade) {
return grade>=60 && grade<=71;
}
```

### Tuesday
****
Make sure you chose relevant and concise names for parameters so its easier to understand the code later on.    

```javascript 
function hello(name) {
    return 'Hello' + name;
}
```

**If else functions**

These functions allow you to add alternatives to your code.

```javascript
function grader(score) {
    let response = ' ';
    
    if(score >= 90){
        response = response + ' You got an A.';
    }
    else if(score >= 80){
        response = response + ' You got an B.';}

    return response;
}
```
Exercise to practice if else:

FIZZBUZZ

If divisable by:

3->FIZZ

5->Buzz

3&5->FizzBuzz

Neither->Num

### Wednesday

****
**Unary Operator** 
const userInput= true;
console.log(typeof userInput); 

!true

Binary operator
===
%
!===
||
&&&

The ternary operator    

```javascript

const greeting = 'hello';
const response = (greeting === hello) ? 'hello back': 'salutations'

//same as 

let response = ' '
if (greeting === 'hello'){
response = 'hello back';
} else {
  response = 'salutations';
}
```

Incorrect Side effects - Shouldn't have '=' after the ? because it is not supposed to behave like a function

let height = 70;
let answer= ' ':
Correct -> answer = (height > 72) ? 'You are tall' : 'You are short'; 
Incorrect-> (height > 72) ? answer = 'You are tall' : answer = 'You are short';

### Thursday

Switch statements are alternatives to if else when only using '==='

