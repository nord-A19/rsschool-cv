# Andrey Kuzma

## Contacts:
1. Phone: +1234567
2. Discord: nord-A19
-----
## About MySelf:  

My name is Andrey. I am from Mozyr.  

-----
## Skills:

1. HTML, CSS
2. JS
3. Git

-----
## Code example:

Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index.
```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
-----
## Courses: 

HTML and CSS Tutorials on the w3schools (completed)

## Languages:
1. English
2. Russian 


