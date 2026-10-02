## Practice Problems — JavaScript Fundamentals

Wrap-up day for Week 4 — no new concepts, just applying everything so far: variables, operators, conditionals, loops, functions, arrays, objects. Mix of difficulty, meant to be solved hands-on.

---

**1. Even or odd**

```jsx
// Write a function that takes a number and returns "Even" or "Odd"
function checkEvenOdd(num) {
  // your code
}
```

**2. Largest of three numbers**

```jsx
// Given three numbers, return the largest one — no built-in Math.max, use if/else
function largest(a, b, c) {
  // your code
}
```**3. FizzBuzz — classic**

```jsx
// Loop from 1 to 30:
// - print "Fizz" if divisible by 3
// - print "Buzz" if divisible by 5
// - print "FizzBuzz" if divisible by both
// - otherwise print the number
```

**4. Reverse a string**

```jsx
// Without using .reverse() — loop through it manually
function reverseString(str) {
  // your code
}
reverseString("hello");   // should return "olleh"
```

**5. Count vowels**

```jsx
// Count how many vowels (a, e, i, o, u) are in a given string
function countVowels(str) {
  // your code
``````jsx
}
countVowels("javascript");   // 3
```

**6. Sum of an array**

```jsx
// Without using .reduce() (not covered yet) — use a loop
function sumArray(arr) {
  // your code
}
sumArray([1, 2, 3, 4, 5]);   // 15
```

**7. Find the maximum in an array**

```jsx
function findMax(arr) {
  // your code — loop through, track the largest seen so far
}
findMax([4, 9, 2, 7, 1]);   // 9
```

**8. Remove duplicates from an array**

```jsx
// Given an array with repeated values, return a new array with only unique values
function removeDuplicates(arr) {
  // your code — hint: use .includes() while building a new array
}
removeDuplicates([1, 2, 2, 3, 4, 4, 5]);   // [1, 2, 3
``````jsx
 4, 5]
```

**9. Object practice — student record**

```jsx
// Create an object "student" with name, age, and an array of marks: [85, 90, 78]
// Write a function that calculates and returns the average of the marks array
```

**10. Array of objects — filter manually**

```jsx
let products = [
  { name: "Pen", price: 10 },
  { name: "Notebook", price: 50 },
  { name: "Bag", price: 500 },
  { name: "Bottle", price: 150 }
];

// Without using .filter() (not covered yet) — loop through and print
// only products with price above 100
```

**11. Multiplication table**

```jsx
// Take a number, print its multiplication table from 1 to 10
function printTable(num) {
  // your code
}
```

**12. Palindrome check**

```jsx
// Check if a string reads the same forwards and backwards
function isPalindrome(str) {
  // your code
}
isPalindrome("madam");   // true
isPalindrome("hello");   // false
```

**13. Count occurrences**

```jsx
// Count how many times each word appears in this sentence, store result in an object
let sentence = "the cat sat on the mat the cat ran";
// expected output shape: { the: 3, cat: 2, sat: 1, on: 1, mat: 1, ran: 1 }
```

**14. Simple calculator using a function**

```jsx
// Write a function "calculate" that takes two numbers and an operator ("+", "-", "*", "/")
// and returns the correct result using conditionals/switch
calculate(10, 5, "+");   // 15
calculate(10, 5, "*");   // 50
``````jsx




---

**How to approach these**

- Don't jump to Google/AI for every problem — struggle with it for at least 10–15 minutes first, that's where the actual learning happens
- Write the logic out in plain words/comments before writing code, if stuck
- Test each function with 2–3 different inputs, not just the example given
- These map directly to interview-style questions later — FizzBuzz, palindrome, and array manipulation especially come up a lot

```jsx
14
let sent = "the cat sat on the mat the cat ran"

let ans = sent.split(" ")
let count = {}

for(let word of ans) {
    count[word] = (count[word] || 0) + 1
}

console.log(count)
```# Day-28
js 7 Practice Problems — JavaScript Fundamentals
