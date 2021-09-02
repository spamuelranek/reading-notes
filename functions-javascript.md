#### i can define the universe around me

# CAN YOU BEND IT TO YOUR WILL?

#### well, no. is there a way to do that?

# OF COURSE TINY BEING.
## You will need to learn about Functions
### We will be applying those definitions you have started and start combining them

### [Creation starts with a Declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
 - Defining Functions
   - Names are important `function`
   - Space needs to be defined `{}`
 ``` javascript
 function square(X){
    return number * number;
 }
 ```
 - Function(al) Expression
   - can be with out names
   ``` javascript
   const square = function(number) {return number * number}
   ```
   - can not be called later
 - Definition not action
  - A function does not run because it is written
  -__It Must Be Invoked__
 - What variables can talk to which (Scope)
    - Global variables can talk to any variable
    - Variables defined in a function can only interact through that function
    ``` javascript
    var num1 = 20,
        num2 = 3,
        name = "chamakh"

    function multiply() {
        return num1 *num2;
    }

    multiply(); // returns 60

    fuction getScore(){
        var num1 = 2,
        var num2 = 3;
        function add() {
            return name + "scored" + (num1 + num2);
        }
        return add ();
    }

    getScore(); //Returns "Chamakh scored 5"
    ```
    - The above example shows num 1 and num2 have different values. Inside getScore it maintains 2 and 3 respectatively. If function add was run outside of getScore it would have returned scored 23 not five.
    - `function add` is a nested function
      - These functions can access all the variables in the total function 
    ### [Operators (lots'o'forms and options)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

    
