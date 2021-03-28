### INTRO TO Core Node JS debugger:
### Node.js provides built-in non-graphic debugging tool that can be used on all platforms. It provides different commands for debugging Node.js application.

:desert_island: Now, considering an example where we add two numbers
``````
 const add= (a, b) => {
    return a+b;
    
 }
 const result = add(3,4)
 console.log(result) 
   ```````
  :violin: store this file as add.js , Now in command promt type
   > node debug add.js
   
 :violin:  This command start debugging and stops at the first line as shown below:
   
 <img src="https://github.com/catherinekennedy/images/blob/main/debug2.png" >
 
:bulb: Command used in core debugger:

* cont, c - Continue execution
* next, n - Step next
* step, s - Step in
* out, o - Step out
* watchers -	See the value of all expressions and variables added into watch.
* Pause -	Pause running code.
* watch().


###  :old_key: now by using watch command it will return the result 
> watch('result')

   <img src="https://github.com/catherinekennedy/images/blob/main/debug3.png" >
   
 :pill: In this output it shows undefined as it is executed before the result is defined.  
 
   ## :old_key: Thus the final output :
   <img src="https://github.com/catherinekennedy/images/blob/main/debug4.png" >
