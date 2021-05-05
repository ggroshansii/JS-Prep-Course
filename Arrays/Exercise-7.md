/*

Use reduce to compute the sum of the squares of all of the numbers in an array:

let array = [3, 5, 7];
console.log(sumOfSquares(array)); // => 83

*/

let array = [3, 5, 7];

let arr2 = array.reduce((accum, element) => {
  let square = element * element;
  accum = accum + square;
  return accum;
}, 0);