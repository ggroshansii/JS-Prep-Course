/*

Write a program that uses a multiply function to multiply two numbers and returns the result. Ask the user to enter the two numbers, then output the numbers and result as a simple equation.

*/

function multiply (num1, num2){
    return num1 * num2;
}

let numberOne = prompt("Enter a number: ");
let numberTwo = prompt("Enter a number: ");
console.log(`${numberOne} multiplied by ${numberTwo} equals ${multiply(numberOne, numberTwo)}.`)