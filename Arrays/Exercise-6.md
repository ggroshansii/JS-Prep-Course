/*

Use map and filter to first determine the lengths of all the elements in an array of string values, then discard the even values (keep the odd values).


let arr = ['a', 'abcd', 'abcde', 'abc', 'ab'];
console.log(oddLengths(arr)); // => [1, 5, 3]


*/

let arr = ['a', 'abcd', 'abcde', 'abc', 'ab'];

let newArr = arr.map(element => {
  return element.length;
}).filter(element => {
  if (element % 2 !== 0){
    return element;
  }
})