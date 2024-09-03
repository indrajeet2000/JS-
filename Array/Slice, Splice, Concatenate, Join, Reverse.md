
<ins>Arr.slice(from,to)</ins> <br>
Don't mutate, parameters given to show from to elements, it resturns copy of array
here 'to' is not included, to is external parameter
It's similar to rest operator
The only usecase of slice over spread is when we have to call it multiple times.

1. The slice() method returns selected elements in an array, as a new array.
2. The slice() method selects from a given start, up to a (not inclusive) given end.
3. The slice() method does not change the original array.
 
<ins>Arr.splice(from,to: number of elements we want to delete)</ins> <br> 
Mutate, parameters given which should be eliminated
In console.log - splice will return which elements are being eliminated
In orginal array it'll remove the elements

1. The splice() method adds and/or removes array elements.
2. The splice() method overwrites the original array.
 
<ins> Arr.Reverse </ins> <br>
Mutate and reverse the array
 
<ins> Arr.concat(arr2) </ins> <br>
Concatenate in arr mutate
 
<ins> Arr.join('-') </ins> <br>
Add - in between
