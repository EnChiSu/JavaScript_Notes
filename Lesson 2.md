# Lesson 2: Basics of Data Types and Variable Declaration

## Declare Variables
In JavaScript, to name a variable you have to type "var" first, then put the name of the variable you want. You can further assign value to the variable with "=" sign.<br/>
For example, name a variable MyVar with value 5 should look like:<br/>
`var MyVar = 5;`<br/>
or declare a string variable<br/>
`var MyName = "EnChiSu";`<br/>
**Note:** <br/>
1. Every command line should follow with a semicolon `;`.
2. Escaping literal quotes in strings you can place a backslash (\) in front of the quote. For example, <br/>
`var sampleStr = "Steve said, \"Andrew is learning JavaScript\".";`
3. Escape sequences in strings<br/>
   `\'`	single quote<br/>
   `\"`	double quote<br/>
   `\\`	backslash<br/>
   `\n`	newline<br/>
   `\r`	carriage return<br/>
   `\t`	tab<br/>
   `\b`	word boundary<br/>
   `\f`	form feed<br/>

## Data Types
There are also various data types, which are "undefined", "null", "boolean", "string", "symbol", "bigint, "number", and "object". <br/>
**Note:** <br/>
1. In JavaScript, you can concatenate strings with `+`. For example, <br/>
`var MyVar = "I am a "` <br/>
`MyVar = MyVar + "String!"` <br/>
The new MyVar would be "I am a String!".*

2. Capitalization matters <br/>
For example, `MYVAR` is not the same as `MyVar` nor `myvar`. <br/>
There is one naming convention called "camelCase", which means the multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized. (變數的第一個字母小寫，接續的變數名中，如果有英文字詞則該字詞的第一個字母大寫) For example, <br/>
`var someVariable;`<br/>
`var anotherVariableName;`<br/>
`var thisVariableNameIsSoLong;`<br/>

## Variable Types
1. array
Array can store several pieces of data in one place. To declare an array, you can simply use bracket to include all the elements you want to contain.  <br/>
e.g. <br/>
`var sandwich = ["peanut butter", 10, "USD"]`<br/>
**Note:**<br/>
1. You can nest one array within another array, which also called a multi-dimensional array.<br/>
   e.g.<br/>
   `var myArray = [["Bulls", 23], ["White Sox", 45]];`<br/>
2. You can access element in an array with indexs. <br/>
   e.g.<br/>
   `var myArray = [["Bulls", 23], ["White Sox", 45]];`<br/>
   `myArray[0][1] // 23`
3. You can append an element to an array with function `.push()`<br/>
   e.g.<br/>
   `var arr1 = [1,2,3];`<br/>
   `arr1.push(4); // arr1 is now [1,2,3,4]`
4. `.pop()` removes the last element from an array and returns that element.<br/>
   e.g. <br/>
   `var threeArr = [1, 4, 6];`<br/>
   `var oneDown = threeArr.pop();`<br/>
   `console.log(oneDown); // Returns 6`<br/>
   `console.log(threeArr); // Returns [1, 4]`

