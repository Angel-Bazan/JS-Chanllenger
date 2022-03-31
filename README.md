
# JS-Chanllenger

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
