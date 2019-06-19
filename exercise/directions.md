

# Exercises: JavaScript loops

<br>

## Print every number from 0 to 10

    var number = new Array(10);
        for (var i = 0; i < 10; i++) {
            number[i] = i + 1; 
            console.log(number[i]);
        }


## Print every number from 10 to 0
   var number = new Array(10);
        for (var i = 10; i >= 0; i--) {
            number[i] = i; 
            console.log(number[i]);
        }

<br>

## Print every number from 4 to -16


        for (var i =4; i >=-16; i--) {
        
            console.log(i);
        }


## Print every fifth number from 8 to 41


for (var i = 8; i <= 40; i+=5) {
         console.log(i);
        }
        

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"

for (var i= 0; i<=100; i++ ){
  if ((i%3 == 0) && (i%5 ==0)){
    console.log("Fizzybuzz");
  }else if(i%3 == 0){
  console.log("Fizzy");
  }else if(i%5 ==0){
console.log("Buzz");
  }
}


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

for (i =0; i <= 20; i++){
if (i%2 == 0){
  console.log(`${i} is even`);
}else{
    console.log(`${i} is odd`);
  }
}

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).

var multiply=0; 
for ( i =0; i <= 10; i++){
  multiply= i*9;  

  console.log(`${i}*9 = ${multiply}`);
}

## The Grade Assigner

Check the results of assignGrade function from the conditionals exercise for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

function grade(studentGrade){
 if(studentGrade >=90){
   return 'A';
  }else if (studentGrade >= 80){
     return 'B';
   }else if (studentGrade >=70){
       return 'C';
       }else if (studentGrade >= 65){
         return 'D';
         }else{
          return 'F';
         }
       }
for(i = 100; i >= 60; i--){
 console.log(`For ${i}, you got a ${grade(i)}`);
}

## The Rest

Make the rest of the programs you made in the conditional exercises use loops in some way (if possible)
