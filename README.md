<img src='./images/logo.png'  alt='JavaScript Coding Challenges jahidul islam zim' id='header'/>

<h1 align="center" >JavaScript Coding Challenges </h1>


##### 01. Creates a function that takes two numbers as arguments and return their sum.

```js
function addition(a, b) {
    //Write Your solution Here
};

console.log(addition(10, 20)); // 30
console.log(addition(30, 20)); // 50
console.log(addition(10, 90)); // 100

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function addition(a, b) {
    let add = a + b;
    return (add)
};
```  

</details>

---
**[⬆ Back to Top](#header)**




##### 02. Converts hours into seconds.

```js

function howManySeconds(hours) {
    //Write Your solution Here
};


console.log(howManySeconds(12)); // 43200
console.log(howManySeconds(8)); // 28800
console.log(howManySeconds(3)); // 10800

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function howManySeconds(hours) {
    let hoursToSeconds = (hours*3600);
    return(hoursToSeconds)
};
```  

</details>

---
**[⬆ Back to Top](#header)**


##### 03. Converts minutes into seconds.

```js

function convert(minutes){
    //Write Your solution Here
};


console.log(convert(30)); // 1800
console.log(convert(10)); // 600
console.log(convert(20)); // 1200

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function convert(minutes) {
    let seconds = minutes*60;
    return (seconds)
};
```  

</details>

---
**[⬆ Back to Top](#header)**


##### 04. Calculates total points of a team from number of wins(3pts), draws(1pt), and losses(0pt).

```js

function footballPoints(wins, draws, losses){
    //Write Your solution Here
};


console.log(footballPoints(4, 3, 1)); // 15
console.log(footballPoints(10, 5, 0)); // 35
console.log(footballPoints(11, 0, 9)); // 33

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function footballPoints(wins, draws, losses) {
    let points = (wins*3) + (draws*1) + (losses*0)
    return(points)
};
```  

</details>

---
**[⬆ Back to Top](#header)**


##### 05. Write functions to calculate the bitwise AND, bitwise OR and bitwise XOR of two numbers.

```js

function bitwiseAND(n1, n2) {
    //Write Your solution Here
};

function bitwiseOR(n1, n2) {
    //Write Your solution Here
};

function bitwiseXOR(n1, n2) {
    //Write Your solution Here
};


console.log(bitwiseAND(10, 20)); // 0
console.log(bitwiseOR(10, 20)); // 30
console.log(bitwiseXOR(10, 20)); // 30

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function bitwiseAND(n1, n2) {
    let answer = n1 & n2;
    return (answer);
};

function bitwiseOR(n1, n2) {
    let answer = n1 | n2;
    return (answer);
};

function bitwiseXOR(n1, n2) {
    let answer = n1 ^ n2;
    return (answer);
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 06. Write Function to return first value of an array.

```js
function getFirstValue(arr) {
      //Write Your solution Here
};


console.log(getFirstValue(["Saab", "Volvo", "BMW"])); // Saab
console.log(getFirstValue([3, 5, 1])); // 3
console.log(getFirstValue(['hello', 'world', 'welcome'])); // hello

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function getFirstValue(arr) {
    return arr[0];
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 07. Create a function that takes a number as an argument, increments the number by +1 and returns the result.

```js
function addition(num){
      //Write Your solution Here
};


console.log(addition(5)); // 6
console.log(addition(100)); // 101
console.log(addition(99)); // 100

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function addition(num) {
    let numPlusOne = num + 1;
    return(numPlusOne)
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 08. Given two numbers, return true if the sum of both numbers is less than 100. Otherwise return false.

```js
function lessThan100(a, b){
      //Write Your solution Here
};


console.log(lessThan100(10, 20)); // true
console.log(lessThan100(50, 60)); // false
console.log(lessThan100(20, 50)); // true

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function lessThan100(a, b) {
    if (a + b < 100) {
        return true;
    }
    else {
        return false;
    }
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 09. Create a function that returns true when num1 is equal to num2; otherwise return false.

```js
function isSameNum(num1, num2){
      //Write Your solution Here
};


console.log(isSameNum(30, 30)); // true
console.log(isSameNum(20, 40)); // false
console.log(isSameNum(50, 50)); // true

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function isSameNum(num1, num2) {
    if (num1 === num2){
        return true;
    }
    else {
        return false;
    }
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 10. Create a function that takes a number (step) as an argument and returns the amount of matchsticks in that step.

<div align="center">
<img src='./images/matchstick.png'  alt='JavaScript Coding Challenges jahidul islam zim' id='header'/>
</div>

```js
function matchHouses(step){
      //Write Your solution Here
};


console.log(matchHouses(5)); // 26
console.log(matchHouses(0)); // 0
console.log(matchHouses(10)); // 51

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function matchHouses(step){
    if (step > 0) {
        let matchSticks = ((step*6) - (step -1));
    return(matchSticks)
    }
    else {
        let matchSticks = 0;
        return (matchSticks)
    }
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 11. Write function to return the square of a number.

```js
function squared(a){
      //Write Your solution Here
};


console.log(squared(6)); // 36
console.log(squared(9)); // 81
console.log(squared(4)); // 16

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function squared(a) {
    return (a*a);
};
```  

</details>

---
**[⬆ Back to Top](#header)**
