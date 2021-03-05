# Course-code

FIZZBUZZ CHALLENGE

// Create function that add a number everytime called when it is a multiple of 3 fizz is pushed instad of number when multiple of 5 is pushed when multiple of 3 and five fizzbuzz is pushed//

var output = [];

function fizzBuzz() {
  var add1 = output.length + 1;

  if (add1 % 3 === 0 && add1 % 5 === 0 ) {
    add1 = "fizzBuzz"  
  }
 
  if (add1 % 3 === 0) {
    add1 = "fizz"  
  }
  if (add1 % 5 === 0 ) {
    add1 = "Buzz"
  }
  output.push(add1);
  console.log(output);
}



WHO IS PAYING CHALLENGE

//Create function that pick random item in array //

function whosPaying(names) {
  
  var NumberOfName = names.length;
  var randomName = Math.floor(Math.random() * NumberOfName);
  var pickName = names[randomName]
  console.log(pickName)
}


FIBONACCI CHALLENGE

// ForLoop, Array , .Push //

function fibonacciGenerator(n){
  
   var output = [];

  if (n === 1){
    output = [0]
  } 
  else if (n === 2){
    output = [0, 1]
  }
  else if (n > 2) {
    for(output = [0, 1, 1]; output.length < n; output.push(output[output.length -2] + output[output.length -1])){
   }
  }
   
console.log(output)
}
   
HIGHER ORDER FUNCTION 
 // FUCTION //
 
function add(num1, num2){
return num1 + num2
}
function multiply(num1, num2){
return num1 * num2
}
function substraction(num1, num2){
return num1 - num2
}
function divide(num1, num2){
return num1 / num2
}

function calculator(num1, num2, operator){
    return operator(num1, num2)
}


