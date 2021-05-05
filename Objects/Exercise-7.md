/*


Add a qux property with value 3 to the myObj object we created in the previous exercise. Now, examine the following code snippets:



let myProtoObj = {
  foo: 1,
  bar: 2,
};

let myObj = Object.create(myProtoObj);


let objKeys = Object.keys(myObj);
objKeys.forEach(function(key) {
  console.log(key);
});


for (let key in myObj) {
  console.log(key);
}


*/




**Both snippets iterate over the keys of myObj. However, for..in iterates over all of the object's keys, including those in the prototype object, myProtoObj. Thus, snippet 2 logs:

qux
foo
bar


Snippet 1 iterates solely over myObj's "own" properties - that is, those defined directly on the object, not its prototype. Thus, it logs:

qux


We can add a conditional to snippet 2 to get the same output from for..in: all we need to do is check whether the key is myObj's own property:

for (let key in myObj) {
  if (myObj.hasOwnProperty(key)) {
    console.log(key);
  }
}

