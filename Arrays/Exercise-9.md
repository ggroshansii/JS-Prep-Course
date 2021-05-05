/*


Without using a for, while, or do/while loop, write some code that checks whether the number 3 appears inside these arrays:


> let numbers1 = [1, 3, 5, 7, 9, 11];
> let numbers2 = [];
> let numbers3 = [2, 4, 6, 8];


*/

function checkForThree(arr) {
  if (arr.length > 0) {
    let newArr = arr.reduce((accum, element) => {
      if (element == 3) {
        accum = accum + 1;
      }
      return accum;
    }, 0);
    // console.log(newArr)
    if (newArr > 0) {
      return true;
    } else {
      return false;
    }
  } else {
    return false;
  }
}


************

> numbers1.includes(3);
= true

> numbers2.includes(3);
= false

> numbers3.includes(3);
= false