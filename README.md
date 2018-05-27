# Function Problems With Scope


# 1 

Write a function `printCool` that accepts one parameter, `name` as an argument. The function should print the name and a message saying that that person is cool.

```javascript
console.log(printCool("Captain Reynolds"));
```

> => "Captain Reynolds is cool";

My Solution:

```javascript
const printCool = (name) => {
  return(name + " is cool");
} 

printCool('Jim')
```

# 2

Write a function `calculateCube` that takes a single number and prints the volume of a cube made from that number.

```javascript
console.log(calculateCube(5));
```

> => 125

My Solution: 

```javascript
const calculateCube = (num) => {
  return Math.pow(num, 3);
}

calculateCube(2);
```
# 3

Write a function `isAVowel` that takes a character (i.e. a string of length 1) and returns true if it is a vowel, false otherwise. The vowel could be upper or lower case.

```javascript
console.log(isAVowel("a"));
```

> => true

My Solution: 
```javascript
const isAVowel = (str) => {
  const character = (str.toLowerCase());
  if (character === "a") {
    return "true";
  } else if (character === "e") {
    return "true";
  } else if (character === "i") {
    return "true";
  } else if (character === "o") {
    return "true"; 
  } else if (character === "u") {
    return "true";
  } else {
    return "false";
  }
}

console.log(isAVowel("I"));
console.log(isAVowel("t"));
```
# 4

Write a function `getTwoLengths` that accepts two parameters (strings). The function should return an _array_ of numbers where each number is the length of the corresponding string.

```javascript
console.log(getTwoLengths("Hank", "Hippopopalous"));
```

> => [4, 13]

My Solution:
```javascript
const getTwoLengths = (string1, string2) => {
  return [string1.split("").length, string2.split("").length];
}

console.log(getTwoLengths("Hank", "Hippopopalous"));
```
# 5 

Write a function `getMultipleLengths` that accepts a single parameter as an argument: an **array** of **strings**. The function should return an array of **numbers** where each number is the length of the corresponding string.


```javascript
console.log(getMultipleLengths(["hello", "what", "is", "up", "dude"]));
```

> => [5, 4, 2, 2, 4]


# 6

Define a function `maxOfThree` that takes three numbers as arguments and returns the largest of them. If all numbers are the same, it doesn't matter which one is returned. If the two largest numbers are the same, one of them should be returned.

```javascript
console.log(maxOfThree(6, 9, 1));
```

> => 9


# 7

Write a function `printLongestWord` that accepts a single argument, an **array** of **strings**. The method should return the longest word in the array. In case of a tie, the method should return the word that appears first in the array.

```javascript
console.log(printLongestWord(["BoJack", "Princess", "Diane", "a", "Max", "Peanutbutter", "big", "Todd"]));
```

> => "Peanutbutter"


# 8

Write a Javascript function called `transmogrify`. This function should accept three arguments, which you can assume will be numbers. Your function should return the "transmogrified" result.

The transmogrified result of three numbers is the product of the first two numbers, raised to the power of the third number.

For example, the transmogrified result of 5, 3, and 2 is `(5 times 3) to the
power of 2` is 225.

```javascript
console.log(transmogrify(5, 3, 2));
```

> => 225


# 9

[Project Euler problem #2](https://projecteuler.net/problem=2)

* Write a function that takes a parameter, a number. The function should print the Fibonacci sequence up to that number.

* Adjust the function to push the **even numbered** values into an array.

* Adjust the function to return the summed value of the array.

* Find the sum of the even numbered values that do not exceed four million.


<br>
<hr>
