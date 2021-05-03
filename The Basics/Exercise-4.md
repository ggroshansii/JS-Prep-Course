/*

Explain why this code logs '510' instead of 15.

console.log('5' + 10);

*/

Implicit coercion converts the Number data type of 10 to a string and then concatenates the string ‘5’ to the string ‘10’

**The code logs 510 since every + expression that has a string operand produces a string result no matter what the other operand is. In other words, the Number 10 gets coerced to a String and then gets concatenated to the String '5', which produces '510'.