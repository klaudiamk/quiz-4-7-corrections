#Quiz 4-7 Corrections

##Quiz 4

01. Question 6) The second answer was correct (in addition to the one I selected) because it gets the html by the provided id and displays the greeting. The only difference I see from the other correct answer is that it does not store the greeting in the variable "p".
02. Question 11) 
```
function askedAndAnswered(){
  let x = prompt("Please enter your name: ");
  let y = prompt("Please enter your age: ");
  z = y++;
  let a = prompt("Hello, " + x + ". When do you turn " + z + "?");
}
 ```
 ```
 function classTrip() { 
    let y = prompt("How many students will be attending the trip?");
    let z = prompt("How many chaperones (including teachers) will be attending the trip?");
    let busMax = prompt("What is the maximum capacity of each bus(not including the bus driver?");
    
    let x = (y +z)/busMax;
    x = Math.round(x);
    
    console.log(x + "busses are required to accomodate " + y + "students and " + z + "chaperones.")
 }
 ```
 
 ##Quiz 5
 
 01. Question 1) The "x === y ; x !== y" is correct because the first part compares both the value and the type, while the second one compares only the value. It fits the code because the == will diplay true even if the types are not the same.
 02. Question 3) The !== and != are also relational operators because they compare values or variables. The !== means the value and type needs to be correct, while in the != only the value needs to be correct.
 03. Question 7) The if statement is the simplest way to achieve the goal because it evaluates the value and goes to the appropriate if. The switch operator is not the simplest because it is a case by case basis. 
 04. Question 11) The correct order for the for loop is setup, expression, loop body, update, and return to step 2. The is correct because after the variable is set up, the expression is evaulated and looped. The variable is then updated and the process is repeated until the statement is statesfied.
 05. Question 13) The correct for loop that will execute at least once is (let i=0; i>5; i++) because the i will need to reach  6 or greater to satisfiy the expression. The given code will in fact execute more than once.
 06. Question 15) The x--; is correct because it will take one away from x=123 until the x is less than 100. This will run at least once (24 times) and will terminiate.

##Quiz 6

01. Question )
02. Question )
03. Question )
04. Question )
05. Question )

##Quiz 7

01. Question )
02. Question )
03. Question )
