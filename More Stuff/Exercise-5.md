/*

What does the following function do?

function doSomething(string) {
  return string.split(' ').reverse().map((value) => value.length);
}

*/


**This code converts a string into an array of words, reverses that array, and then returns a new array that contains the lengths of the words. It assumes that a single space character delimits the words in the original string.

console.log(doSomething("Pursuit of happiness")); // => [ 9, 2, 7 ]