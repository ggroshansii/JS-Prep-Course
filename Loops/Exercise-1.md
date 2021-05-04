/*

Modify the age.js program you wrote in the exercises for the Input/Output chapter. The updated code should use a for loop to display the future ages.

*/


let age = prompt("How old are you? \n");
let futureYears = 10;
console.log(`You are ${age} years old`);

for (let i = 0; i < 4; i++){
if (Number(age) !== 'NaN'){
    console.log(`In ${futureYears} years, you will be ${Number(age)} years old`);
    futureYears = futureYears + 10;
    age = Number(age) + 10;
} 
}