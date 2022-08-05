# assignment4

1. print odd number in a array:

let arr = [1,2,3,4,5,6,7,8,9,10,11,12]
let odds = arr. filter(n => n%2)
console. log(odds)

2. sum of all numbers in array :

   var arr = [4, 8, 7, 13, 12]
    var sum = 0
    for (let i = 0; i < arr.length; i++) {
        sum += arr[i];
    }
    document.write("Sum is " + sum)

 3.return all the prime numbers in an array:

 function checkPrime(number) {
  if (number <= 1) {
    return false;
  } else {
    for (let i = 2; i < number; i++) {
      if (number % i == 0) {
        return false;
      }
    }
  }
}   
