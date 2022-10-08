## Ways to browse an array
### O(N)

```JavaScript
const printEvenNumbersVersionOne = () => {
  let number = 2;

  while (number <= 100) {
    if (number % 2 === 0) {
      console.log(number);
    }
    number += 1;
  }
};
```

### O(N/2)
```JavaScript
const printEvenNumbersVersionTwo = () => {
  let number = 2;

  while (number <= 100) {
    console.log(number);
    number += 2;
  }
};
```

## Exercises
  1. **For an array containing 100 elements, give number of steps**
     1. > Reading : *1 step*
     2. > Searching a not contained value : *100 steps*
     3. > Insertion at the beginning of an array : *100 steps to move data to the right + 1 step to insert new data*
     4. > Insertion at the end of an array : *1 step to insert new data*
     5. > Deletion at the beginning of an array : *100 steps = 1 step to delete + 99 steps to move data to the left*
     6. > Deletion at the end of an array : *1 step to delete*
  2.  **For an array-based set containing 100 elements**
      1. > Reading : *1 step*
      2. > Searching a not contained value : *100 steps*
      3. > Insertion at the beginning of an array : *100 steps to move data to the right + 1 step to insert new data*
      4. > Insertion at the end of an array : *1 step to insert new data*
      5. > Deletion at the beginning of an array : *100 steps = 1 step to delete + 99 steps to move data to the left*
      6. > Deletion at the end of an array : *1 step to delete*
   3. **To count how many times there's an instance of value "apple" found in an array. How many steps ?**
      > *N steps*
