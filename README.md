
# JavaScript Basics 

## Write a function that takes two strings (a and b) as arguments.If a contains b, append b to the beginning of a If not, append it to the end.Return the concatenation


```jsx
function myFunction
(a, b)
{

return a.includes(b) ? b + a : a + b

}
```

## Write a function that takes two numbers (a and b) as arguments.If a is smaller than b, divide a by b.Otherwise, multiply both numbers.Return the resulting value

```jsx 
function myFunction(a, b)
{

return a < b ? a/b : a * b
}
```

## Write a function that takes a number (a) as argument.If a is a whole number (has no decimal place), return true.Otherwise, return false

```jsx 
function myFunction(a)
{
return Number.isInteger(a);
}
```

## Write a function that takes two strings (a and b) as arguments.Return the number of times a occurs in b

```jsx 
functionmyFunction(a, b)
{
let newB = b.split('');
let count = 0;
for (let i = 0; i < newB.length; i++) {
  if (a === newB[i]) {
    count += 1;
  }
}
return count
}
``` 
#### or 

```jsx 
functionmyFunction(a, b)
{

return b.split(a).length - 1

}
```

## Write a function that takes 6 values (a,b,c,d,e,f) as arguments.Sum a and b.Then substract by c.Then multiply by d and divide by e.Finally raise to the power of f and return the result

```jsx 
function myFunction
(a, b, c, d, e, f)
{

return (((a + b)- c) * d / e )**f
}

```

## Write a function that takes a string (a) as argument.Remove the last 3 characters of a.Return the result

```jsx 
function myFunction(a)
{
return a.slice(0,-3)
}
```

##  Write a function that takes a string (a) as argument.Extract the first half a.Return the result

```jsx 
function myFunction(a)
{

return a.slice(0,a.length/2)
}
```

##  Write a function that takes a string (a) and a number (n) as argument Return the nth character of 'a'


```jsx 
function myFunction(a, n)
{
return a[n-1]
}
```

## Write a function that takes a string (a) as argument Remove the first 3 characters of a.Return the result

```jsx
function myFunction(a)
{

return a.slice(3)
}
```

## Write a function that takes a string as argument.Extract the last 3 characters from the string.Return the result

```jsx
function myFunction(str)
{

return str.slice(-3)
}

```

## Write a function that takes a string (a) as argument.Get the first 3 characters of a.Return the result

```jsx
functionmyFunction(a)
{
return a.slice(0,3)
}
```

## Write a function that takes a number as argument.If the number is even, return true.Otherwise, return false

```jsx 
function myFunction(a)
{
return a % 2 === 0 
}
 ```

# JavaScript Arrays 


##  Write a function that takes an array (a) and a value (n) as argument Return the nth element of 'a'

```jsx 
function myFunction(a, n){
return a[n-1]
}

```

## Write a function that takes an array of numbers as argument It should return the average of the numbers

```jsx 
function myFunction(arr){
return arr.reduce((a,b) => a + b, 0 ) / arr.length 
}

```

## Write a function that takes an array as argument It should return true if all elements in the array are equal It should return false otherwise 

```jsx 
function
myFunction(arr)
{
return arr.every(element => element === arr[0]) ? true : false 
}
```

## Write a function that takes arguments an arbitrary number of arrays.It should return an array containing the values of all arrays

```jsx 
function myFunction(...arrays)
{
let newArr = [];
return newArr.concat(...arrays)
}
```

## Write a function that takes an array of objects as argument.Sort the array by property b in ascending order.Return the sorted array 

```jsx 
function myFunction(arr)
{
return arr.sort((a,b) => (a.b < b.b) ? -1 : 1 )
}
```
