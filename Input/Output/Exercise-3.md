/*

Modify the age.js program you wrote in the exercises for the Variables chapter. The updated code should ask the user to enter their age instead of hard-coding the age in the program. Here's an example run:

How old are you? 22
You are 22 years old.
In 10 years, you will be 32 years old.
In 20 years, you will be 42 years old.
In 30 years, you will be 52 years old.
In 40 years, you will be 62 years old.

*/

let age = prompt("How old are you? \n");

if (Number(age) !== 'NaN'){
    console.log(`You are ${age} years old`);
    console.log(`In 10 years, you will be ${Number(age) + 10} years old`)
    console.log(`In 20 years, you will be ${Number(age) + 20} years old`)
    console.log(`In 30 years, you will be ${Number(age) + 30} years old`)
    console.log(`In 40 years, you will be ${Number(age) + 40} years old`)
} 