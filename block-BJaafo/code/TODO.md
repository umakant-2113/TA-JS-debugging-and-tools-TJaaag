### Write two tests for the following functions

#### Get full name

1. Write a function that takes two input `firstName` and `lastName` and returns full name. You will get the full name by adding first and last name with an space.
2. After writing the function write two tests for above function
3. Make the first test fail and look at the output
4. After making the first test fail do you see the output of the second test?

#### Calculate total amount

1. Write a function that takes two input `amount` and `taxRate` and returns the total amount by `amount + (amount * taxRate) `
2. Write two tests for the above function
3. Make the first test fail and look at the output
4. After making the first test fail do you see the output of the second test?
 
let firstName = "umakant ";
let lastName = "rajput"
function fullName(){
   
   let result =  return firstName+lastName;
}
fullName();

let expected= "umakant rajput ";
if(result !==expected){
    throw error(`${result} is not equal to ${expected}`)
}

let amount = 1000
let tax= 12%
function totalAmount(){
    return amount+amount*12/100
}
totalAmount();