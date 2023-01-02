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



##### 12. Write function to calc area of a rectangle

```js
function findPerimeter(height, width){
      //Write Your solution Here
};


console.log(findPerimeter(20, 50)); // 140
console.log(findPerimeter(80, 30)); // 220
console.log(findPerimeter(10, 40)); // 100

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function findPerimeter(height, width){
    let perimeter = 2*(height + width);
    return (perimeter)
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 13. Add up all the numbers from 1 to the number you passed to the function.

```js
function addUp(num){
      //Write Your solution Here
};


console.log(addUp(10)); // 55
console.log(addUp(40)); // 820
console.log(addUp(15)); // 120

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function addUp(num) {
    let sum = 0;
    for (i = 0; i <= num; i++){
        sum += i;
            }
    return(sum)
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 14. Create a function that takes in three arguments (prob, prize, pay) and returns true if prob * prize > pay; otherwise return false.

```js
function profitableGamble(prob, prize, pay){
      //Write Your solution Here
};


console.log(profitableGamble(2, 10, 20)); // false
console.log(profitableGamble(5, 10, 40)); // true
console.log(profitableGamble(6, 3, 30)); // false

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function profitableGamble(prob, prize, pay){
    if (prob*prize > pay) {
        return (true)
    }
    else {
        return (false)
    }
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 15. Takes an array of numbers, returns both the minimum and maximum numbers, in that order.

```js
function minMax(arr){
      //Write Your solution Here
};


console.log(minMax([2, -1, 5])); // [ -1, 5 ]
console.log(minMax([0, 5, 2])); // [ 0, 5 ]
console.log(minMax([2, -5, -1])); // [ -5, 2 ]

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function minMax(arr){
    arr.sort(function(a, b){return(a - b)})
    return [arr[0], arr[arr.length - 1]]
};
```  

</details>

---
**[⬆ Back to Top](#header)**



##### 16. Create a function that returns true if the first array can be nested inside the second.
###### arr1 can be nested inside arr2 if:
###### arr1's min is greater than arr2's min.
###### arr1's max is less than arr2's max.

```js
function minMax(arr){
      //Write Your solution Here
};


console.log(canNest([3, 1], [4, 0])); // true
console.log(canNest([9, 9, 8], [8, 9])); // false
console.log(canNest([1, 2, 3, 4], [0, 6])); // true

```

<details><summary style="cursor:pointer">Solution</summary>

```js
function canNest(arr1, arr2) {
    arr1.sort(function(a,b){return(a - b)});
    arr2.sort(function(a,b){return(a - b)});
    let arr1MinMax = [arr1[0], arr1[arr1.length -1]];
    let arr2MinMax = [arr2[0], arr2[arr2.length -1]];
    if (arr1MinMax[0] > arr2MinMax[0] && arr1MinMax[1] < arr2MinMax[1]){
        return true
    }
    else{
        return false
        }
};
```  

</details>

---
**[⬆ Back to Top](#header)**
