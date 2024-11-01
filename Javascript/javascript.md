# Javascript

### Destructuring Objects and Arrays

This is very simple. We can take an object like this:

```
const details = { student: "Fred", results: [3, 2, 4, 1, 5] };
```

And then assign the components of the object to separate variables:

```
const { student, results } = details;

console.log(student); // outputs "Fred"
console.log(results); // outputs [3, 2, 4, 1, 5]
```

We can do this with arrays as well (remember to use square brackets):

```
const values = ["John", "Smith", 27]
const [fName, sName] = values;

console.log(fName); // outputs "John"
```

### Destructuring and the Spread Operator

```
const myArray1 = [3, 4, 5, 6, 78];
const [first, second, ...others] = myArray1;

console.log(first); // outputs 3
console.log(others); // outputs [5, 6, 78]
```
