# Lesson 5: Edit your own function
You can create your own function with function name like below:<br/>
e.g.<br/>
function functionName() {<br/>
  console.log("Hello World");<br/>
}<br/>
functionName() // "Hello World"<br/>

**Note:**
Inside function, to create a "global" variable you don's have to add `var` in front of your new variable. ("global" variable means it can be applied to all the environment of your program. <br/>
e.g.<br/>
`var myGlobal = 10 // Normal way to name a global variable.`<br/>
vs<br/>
`function fun1() {` <br/>
  `oopsGlobal = 5`<br/>
`}`<br/>

However, if you just want to create a "local" variable for the use of the specific function, you have to add `var` in front of your new variable.<br/>
e.g.<br/>
`function myTest() {<br/>`
`  var loc = "foo";<br/>`
`  console.log(loc);<br/>`
`}`<br/>
`myTest(); // logs "foo"`<br/>
`console.log(loc); // loc is not defined`<br/>
