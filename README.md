# Javascript Homework

## Assignment Operator
Without running the following code, try to determine:

```js
let a = 1;
let b = 'bongos';
let c = true;

a = b;
b = c;
c = a;
```

### Your solution here:
1.  What is `a`?
```
a is 'bongos'
```
2.  What is `b`?
```
b is true
```
3.  What is `c`?
```
c is 'bongos'
```


## Concatenation
Use the `+` operator to concatenate these strings together within a `console.log()`: "Red", "Hot", "Chilli", "Peppers". Make sure there are spaces in-between each word.

```js
const firstWord = "Red";
const secondWord = "Hot";
const thirdWord = "Chilli";
const fourthWord = "Peppers";
```
Result should be:
```js
"Red Hot Chilli Peppers"
```

### Your solution here:
4.  Fill in the `console.log()`?
```js
console.log(firstWord + " " + secondWord + " " + thirdWord + " " + fourthWord)

```

Output a console log `The sum of 5 and 10 is 15` where the values for 5 and 10 are saved to variables, and where 15 comes from those variables being summed.
```js
const num1 = 5;
const num2 = 10;
```

### Your solution here:
5.  How can we make `num3` equal to the sum of `num1` and `num2`?
```js
// your solution here
See the answer below.

```
6.  Use variables `num1`, `num2` and `num3` to fill in the `console.log()` to complete the sentence: 

```js 
const num1 = 5;
const num2 = 10;
let num3 = num1 + num2; // answer to the pre-question
console.log("the sum of "+num1+" and "+num2+" is "+num3);
```

```js

```

## Comparisons
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false
```
a) 999 > 999
b) 999 === 999 
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5 
g) 81 / 9 === 9
h) 9 !== 8 + 1
```
### Your solution here:
7.  Write `true` or `false` based on the list above
```
a) F
b) T
c) F
d) F
e) F
f) F
g) T
h) F
```

## Conditionals
Declare a variable equal to a number 0 to 100

Write a conditional statement that...
- If it is a multiple of 3, print “Fizz” instead of the number.
- If it is a multiple of 5, print “Buzz” instead of the number.
- If it is a multiple of both 3 and 5, print “FizzBuzz” instead of the number.
- Otherwise, print the number

### Your solution here:
8.  Write your javascript solution below
```js
// If it is a multiple of both 3 and 5, print “FizzBuzz” instead of the number.
            if (i % (3 * 5) == 0) {
              console.log("FizzBuzz");

// If it is a multiple of 5, print “Buzz” instead of the number.
            else if (i % 5 == 0) {
              console.log("Buzz");
            }

// If it is a multiple of 3, print “Fizz” instead of the number.

            else if (i % 3 == 0) {
            console.log("Fizz");
            }

// Otherwise, print the number
            else {
              console.log(i)
            }
   
```
## Homework Submission
https://github.com/SEI2-jeddah/General/tree/master/homework_submission

# Additional Resources

1.  Variables
    - https://www.youtube.com/watch?v=cXUWYZXru6o (7 min video)
    - https://www.codeanalogies.com/jsconstruction/ (interactive game)

2.  Conditions
    - https://blog.codeanalogies.com/2018/06/18/javascript-booleans-explained-by-going-to-court/ (reading)

For more practice read about...
- https://javascript.info/variables
- https://javascript.info/types
- https://javascript.info/operators
- https://javascript.info/comparison
- https://javascript.info/ifelse
- https://javascript.info/logical-operators
