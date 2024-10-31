# Javascript

#### Destructuring Objects

This is very simple. We can take an object like this:

```
const details = { student: "Fred", results: [3, 2, 4, 1, 5] };
```

We can assign the components of the object to separate variables:

```
const { student, results } = details;

console.log(student); // outputs "Fred"
console.log(results); // outputs [3, 2, 4, 1, 5]
```

### Asynchronous Javascript

#### Callbacks

```
setTimeout(() => {
    console.log("5 second wait");
},5000);
```

```
const callbackFunction = () => console.log("5 second wait");

setTimeout(callbackFunction,5000);
```

Callbacks are often used in event handlers:

```
const btn;
btn.addEventListener('click', () => {
    alert('Button clicked!')
})
```

The disadvantage of callback functions is that they can become deeply nested, creating what is known as 'callback hell'.
