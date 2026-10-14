# ayushkumar.js


// Write a program to perform arithmetic operations on two numbers.

let num1 = 20;
let num2 = 10;

console.log("Addition: " + (num1 + num2));
console.log("Subtraction: " + (num1 - num2));
console.log("Multiplication: " + (num1 * num2));
console.log("Division: " + (num1 / num2));
console.log("Modulus: " + (num1 % num2));

// Write a program to compare two numbers using comparison operators.

let a = 15;
let b = 25;

console.log(a > b);  // false
console.log(a < b);  // true
console.log(a >= b); // false
console.log(a <= b); // true
console.log(a === b); // false
console.log(a !== b); // true


// Write a program to demonstrate logical operators (&&, ||, !).

let x = true;
let y = false;

console.log(x && y); // false (AND)
console.log(x || y); // true (OR)
console.log(!x);     // false (NOT)


// Write a program to check whether a number is positive.

let num = 10;

if (num > 0) {
        console.log("The number is positive.");
}


// Write a program to check whether a number is even or odd.

let num = 7;

if (num % 2 === 0) {
        console.log("The number is even.");
} else {
        console.log("The number is odd.");
}

// Write a program to check voting eligibility using if-else. 

let age = 18;

if (age >= 18) {
        console.log("Eligible to vote.");
} else {
        console.log("Not eligible to vote.");
}


// Write a program to check whether a number is positive, negative, or zero. 

let num = -5;

if (num > 0) {
        console.log("Positive");
} else if (num < 0) {
        console.log("Negative");
} else {
        console.log("Zero");
}


// Write a program to calculate grades based on marks using else-if.

let marks = 85;

if (marks >= 90) {
        console.log("Grade: A");
} else if (marks >= 75) {
        console.log("Grade: B");
} else if (marks >= 50) {
        console.log("Grade: C");
} else {
        console.log("Grade: Fail");
}


// Write a program to find the largest of two numbers.

let num1 = 45;
let num2 = 30;

if (num1 > num2) {
        console.log(num1 + " is the largest.");
} else {
        console.log(num2 + " is the largest.");
}


// Write a program to check whether a year is a leap year.

let year = 2024;

if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)) {
        console.log(year + " is a leap year.");
} else {
        console.log(year + " is not a leap year.");
}


// Write a program to print numbers from 1 to 10 using a for loop.

for (let i = 1; i <= 10; i++) {
        console.log(i);
}


// Write a program to print the multiplication table of a given number.

let n = 5;

for (let i = 1; i <= 10; i++) {
        console.log(n + " x " + i + " = " + (n * i));
}


// Write a program to calculate the sum of the first N natural numbers.

let N = 10;
let sum = 0;

for (let i = 1; i <= N; i++) {
        sum += i;
}

console.log("Sum: " + sum);


// Write a program to print all even numbers between 1 and 50.

for (let i = 1; i <= 50; i++) {
        if (i % 2 === 0) {
                    console.log(i);
        }
}

        
// Write a program to count numbers divisible by 3 between 1 and 100. 

let count = 0;

for (let i = 1; i <= 100; i++) {
        if (i % 3 === 0) {
                    count++;
        }
}

console.log("Count: " + count);

        
// Write a program to find the largest of three numbers. 

let a = 12;
let b = 45;
let c = 25;

if (a >= b && a >= c) {
        console.log(a + " is the largest.");
} else if (b >= a && b >= c) {
        console.log(b + " is the largest.");
} else {
        console.log(c + " is the largest.");
}


// Write a program to check whether a number is divisible by both 3 and 5. 

let num = 15;

if (num % 3 === 0 && num % 5 === 0) {
        console.log("Divisible by both 3 and 5.");
} else {
        console.log("Not divisible by both 3 and 5.");
}


// Write a program to calculate the factorial of a number using a for loop. 

let num = 5;
let factorial = 1;

for (let i = 1; i <= num; i++) {
        factorial *= i;
}

console.log("Factorial: " + factorial);


// Write a program to print numbers from 50 to 1 in reverse order.

for (let i = 50; i >= 1; i--) {
        console.log(i);
}


// Write a program to calculate the sum of all odd numbers between 1 and 100. 

let sum = 0;

for (let i = 1; i <= 100; i++) {
        if (i % 2 !== 0) {
                    sum += i;
        }
}

console.log("Sum of odd numbers: " + sum);

        
