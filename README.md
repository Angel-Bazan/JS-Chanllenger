

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
