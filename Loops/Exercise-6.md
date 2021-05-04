/*

Reimplement the factorial function from exercise 2 using recursion. Once again, you may assume that the argument is always a positive integer.

*/

function factorial(n, product = 1){
  if (n == 1){
    return product
  } else {
    product = product * n;
    return factorial(n - 1, product);
  }
}