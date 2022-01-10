# Class 9 Reading
---

Reading
Here are the chapters to read/skim before class:

From the Duckett HTML book:

Chapter 7: “Forms” (p.144-175)
Chapter 14: “Lists, Tables & Forms” (pp.330-357)
From the Duckett JS book:

Chapter 6: “Events” (pp.243-292)


## Chapter 7: “Forms” (p.144-175)

---

### What is the best known form on the web?

- google search box


### Several different types of form controls

- Adding text
- Making choices
- Submiting forms

### Summary
- Whenever you need to collect infomration from visitors you will need a form, which lives inside the form element
- information from a form is sent in name/value pairs
- Html5 has new form elements which make it easier to fill in forms


## Chapter 14: “Lists, Tables & Forms” (pp.330-357)

---

### Several CSS properties to work with layout of tables
- list-style-types


### Summary
- Forms are easier to use if the form controls are vertically aligned using CSS
- Form benefit from styles that make them feel more interactive
- you can customize different borders and spacing in different browsers


## Review 2d arrays
--- 

Arrys can be made into 2 dimensions. Usually writing a for loop inside of another for loop can access differnt indexs of the 2d array.


### Example code of 2d array

> ` 'use strict';
let students = ['Micahel', 'Rae', 'Josh', 'Kevin', 'Chuck', 'Cesar', 'JT'];

>const introducer = function(){
  // outer for loop // slower
  for (let i = 0; i < students.length; i++){
    console.log(`${students[i]} stands and greets everyone.`);

    // inner loop // fast loop
    for (let j = 0; j < students.length; j++){
      if (i !== j){
        console.log(`${students[i]} says hello to ${students[j]}`);
      }
    }
  }
};

> let numsArr = [
  [1, 2, 3], // 6
  [4, 5, 6], // 15
  [7, 8, 9]  // 24
];
//12, 15, 18
for (let i =  0; i < numsArr.length; i++){
  let total = 0;
  for (let j = 0; j  <  numsArr[i].length; j++){
    total += numsArr[j][i];
  }
  console.log(total);
}
console.table(numsArr);`


## Chapter 6: “Events” (pp.243-292)

---


### What is an Event?

1. interations create events
2. Events trigger code
3. code responds to users

### Terminology

- events fire or are raised
- events trigger scripts

### Event flow

- html elements nest inside other elements. If you hover or click on a link you will also be clicking on its parent elements
- Flow only matters when your code has event handlers and one of its ancestor elements


### Summary

- Binding is the process of stating which event you are waiting to happen and which element you are waiting for that event to happen upon
- when events occur, it can trigger a JS function. When this function changes the web in some way. 
- You can use event delegation to monitor for events that happen on all of the children of an element.





