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

01. Question 1) The correct answer was prompt and Math.random because they both return a value. When the user is asked for an input, using one of these methods, the response is then stored. Console.log was not a correct answer because it only prints the value to console.
02. Question 2) The code below is the correct answer because it uses the values which the prompt specified. The function os defined as 'power' because it will raise the base to the power of the exponent.
```
function power(base, exponent) {
  /* implementation not shown */
 }
```
03. Question 4) The function below is named mystery and is not designed to accept parameters because the () are empty. It is unknown if it can return a value b/c the implementation details are not shown. 
```
function mystery () {
  /* not shown */
 }
```
04. Question 6) One of the statements that would come from the given function was "I need to do chores, homework, and undefined ... So busy!" because the last variable was not given. The function parameters called for three statements, but one example only provided two so the undefined is sort of like a placeholder for the value.
05. Question 7) Math.random is not correct because it cannot accept parameters, unlike console.log, prompt, and alert. It can only randomly generate a number and print it to the given place.
06. Question 8) Console.log(subtract(x,y)) is correct, unlike my option of console.log(subtract), because it shows the values which need to be subtracted. In this case, it is x and y and the difference will then be printed to the console.

##Quiz 7

01. Question )
02. Question )
03. Question )
