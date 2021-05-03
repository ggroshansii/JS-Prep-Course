/*

Use the arithmetic operators to determine the individual digits of a 4-digit number like 4936:

1) thousands place is 4
2) hundreds place is 9
3) tens place is 3
4) ones place is 6

*/

let number = 4936;

let onesPlace = number % 10;
number = (number - onesPlace) / 10;

let tensPlace = number % 10;
number = (number - tensPlace) / 10;

let hundredsPlace = number % 10; 
number = (number - hundredsPlace) / 10; 

thousandsPlace = number;