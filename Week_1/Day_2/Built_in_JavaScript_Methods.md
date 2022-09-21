# Built-in JavaScript Methods (e.g. ".includes()", ".indexOf(), etc.)

## .includes() - a number
``` javascript
const nums = [ 1, 3, 5, 7];
console.log(nums.includes(3));
// true
```

## .includes() - a string
``` javascript
const nums = [ 1, 3, "hello", "world"];
console.log(nums.includes("world"));
// true
```

## .indexOf()
``` javascript
const beasts = ['ant', 'bison', 'camel', 'duck', 'bison'];
console.log(beasts.indexOf('bison'));
// output: 1
```

## .concat() - returns a combined array
### does not change the original arrays
``` javascript
const arr1 = ["Cecilie", "Lone"];
const arr2 = ["Emil", "Tobias", "Linus"];
const arr3 = ["Robin"];
const children = arr1.concat(arr2, arr3);
console.log(children);
// output: [ 'Cecilie', 'Lone', 'Emil', 'Tobias', 'Linus', 'Robin' ]
```

## .join() 
### returns a combined string, where you can specify the separator in between the original elements
``` javascript
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let text = fruits.join(" + ");
console.log(text);
// output: "Banana + Orange + Apple + Mango"
```