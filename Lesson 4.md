# Lesson 4: Build-in Function

1. .length<br/>
e.g. `"Alan Peter".length; // 10`

2. use bracket behind variable as index to call the element you want<br/>
e.g. <br/>
`var firstName = "Charles";`
`var firstLetter = firstName[0] // firstLetter is "C"`<br/>
Note: <br/>
JavaScript, like Python, also start counting at 0.

3. String values are immutable.<br/>
**False** Demo: <br/>
`var myStr = "Bob";`<br/>
`myStr[0] = "J";`<br/>

4. You can append an element to an array with function `.push()`<br/>
   e.g.<br/>
   `var arr1 = [1,2,3];`<br/>
   `arr1.push(4); // arr1 is now [1,2,3,4]`
5. `.pop()` removes the last element from an array and returns that element.<br/>
   e.g. <br/>
   `var threeArr = [1, 4, 6];`<br/>
   `var oneDown = threeArr.pop();`<br/>
   `console.log(oneDown); // Returns 6`<br/>
   `console.log(threeArr); // Returns [1, 4]`
6. `.shift()` removes the first element from an array and returns that element.<br/>
   e.g.<br/>
   `var threeArr = [1, 4, 6];`<br/>
   `var oneDown = threeArr.shift();`<br/>
   `console.log(oneDown); // Returns 1`<br/>
   `console.log(threeArr); // Returns [4, 6]`
7. Instead of append an element at the last of an array, you can also append an element in front of your array.<br/>
   e.g.<br/>
   `var ourArray = ["Stimpson", "J", "cat"];`<br/>
   `ourArray.shift(); // ourArray now equals ["J", "cat"]`<br/>
   `ourArray.unshift("Happy"); // ourArray now equals ["Happy", "J", "cat"]`
   
