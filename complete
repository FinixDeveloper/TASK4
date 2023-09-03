//1(a). Print odd numbers in an array

//anonymous

const argArr = [1, 2, 3, 4, 5, 6, 7];
function printodd(array){
    for(let i = 0; i< array.length; i++){
          if(array[i]%2!=0){
             console.log(array[i]);
          } 
     }
  }
printodd(argArr);

//IIFE

const printOddOn=function(array){
    for(var i = 0 ; i< array.length ; i++){
               if(array[i]%2!=0){
                  console.log(array[i])
               } 
          }
    }
printOddOn(argArr);

// 2(a) arrow function

const printOddARR = (array) => {
    for(var i = 0 ; i< array.length ; i++){
         if(array[i]%2!=0){
            console.log(array[i])
         } 
    }
    }
printOddARR(argArr);



//1(b) Convert all the strings to title caps in a string array

//anonymous : 
let str = function () {
    let arr = "hello there how are you"
    let titlecase = arr.toLowerCase().replace(/\b(\w)/g, s => s.toUpperCase());
    console.log(titlecase)
  }
  str();

//IIFE

  const value = "hello there how are you";
   function printans(str) {
    str = str.toLowerCase().split(' ');
    for (var i = 0; i < str.length; i++){
      str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1);
    }
    console.log(str.join(' '));
    }
    printans(value);

//2.(b) ARROW Function

    const titleCase = (str) => {
        str = str.toLowerCase().split(' ');
        for (var i = 0; i < str.length; i++) {
          str[i] = str[i].charAt(0).toUpperCase() + str[i].slice(1); 
        } 
        console.log(str.join(' '));
      }   
      titleCase(value);


//1(c).Sum of all numbers in an array


//Anonymous :

  const value=[1, 2, 3, 4, 5];
  function printarr(array){
    var sum = 0;
    for(var i = 0 ; i< array.length ; i++){
       sum = sum + array[i];
     }
     console.log(sum);
  }
  printarr(value);

//IIFE:

const printarry=function(array){
    var sum = 0;
         for(var i = 0 ; i< array.length ; i++){
            sum = sum + array[i];
          }
          console.log(sum);
    }
    printarry(value);

// 2(c) Arrow function.

const sum = (array)=>{
    var sum = 0;
         for(var i = 0 ; i< array.length ; i++){
            sum = sum + array[i];
          }
          console.log(sum);
          }
sum(value);


//1(d).Return all the prime numbers in an array

//Anonymous:

  const value=[7, 16, 9, 3];

  function prime(numArray){
    numArray = numArray.filter((number) => {
      for (var i = 2; i <= Math.sqrt(number); i++) {
        if (number % i === 0) return false;
      }
      return true;
    });
    console.log(numArray);
}
prime(value);

//IIFE

   const primeadd=function(numArray){
       numArray = numArray.filter((number) => {
         for (var i = 2; i <= Math.sqrt(number); i++) {
           if (number % i === 0) return false;
         }
         return true;
       });
       console.log(numArray);
   }
   primeadd(value);

//2(d) ARROW Function:

primeNumber = (numArray) => {
    numArray = numArray.filter((number) => {
      for (var i = 2; i <= Math.sqrt(number); i++) {
        if (number % i === 0) return false;
      }
      return true;
    });
    console.log(numArray);
}
primeNumber(value);


//1(e). Return all the palindromes in an array

//Anonymous :
const value=['viicc', 'racecar', 'honda', 'malayalam'];
function palindromew(arr) {
    var arr = arr.filter(function ( c, d) {
      var palindrome = c.split('').reverse().join('');
      if (c == palindrome) {
        console.log(arr[d]);
      }
    });
  }
  palindromew(value);


//IIFE:

const palindromet = function(arr) {
    var arr = arr.filter(function ( c, d) {
      var palindrome = c.split('').reverse().join('');
      if (c == palindrome) {
        console.log(arr[d]);
      }
    });
  }
  palindromet(value);

//Arrow Function:

palindromes = (arr) => {
    var arr = arr.filter(function ( c, d) {
      var palindrome = c.split('').reverse().join('');
      if (c == palindrome) {
        console.log(arr[d]);
      }
    });
  }
  palindromes(value);


