/*

Write a function that logs whether a number is between 0 and 50 (inclusive), between 51 and 100 (inclusive), greater than 100, or less than 0.

*/

function interval(number){
    if (number >= 0 && number <= 50){
        console.log(`${number} is between 0 and 50`)
    } else if (number >= 51 && number <= 100){
        console.log(`${number} is between 51 and 100`)
    } else if (number > 100){
        console.log(`${number} is greater than 100`) 
    } else if (number < 0 ){
        console.log(`${number} less than 0`) 
    }
}
