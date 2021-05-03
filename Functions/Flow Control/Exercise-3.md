/*

Let's improve our previous implementation of evenOrOdd. Add a validation check to ensure that the argument is an integer. If it isn't, the function should issue an error message and return.

*/

function evenOrOdd(number){
    if (Number.isNaN(number) === false){
        if (number % 2 == 0 ){
        return 'even';
        } else{
        return 'odd';
    }
} else{
    console.error("Input is not a number.");
}
}
