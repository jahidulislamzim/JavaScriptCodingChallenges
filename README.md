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
