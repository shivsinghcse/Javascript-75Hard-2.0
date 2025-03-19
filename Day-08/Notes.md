# Day - 07 (Variable Scope | Argument vs Parameter)


### Variable Scope
- There are two type of scope
    - Global Scope | Global variable
    - Local Scope | Local variable

### Arguments and Parameter    

- Arguments : When we pass any value at the time of calling function is called Arguments.
- These are the values passed to a function when it is called.
- Also called call by value.
```js
greet('Shiv Singh');
```
Parameter: A parameter is a variable used in the function definition to receive data when the function is called.
```js
function demo(x, y){
    return x + y;
}
```

- Optional Parameter / default parameter
```js
function demo(x, y, z = 0){
    return x + y + z;
}
```
