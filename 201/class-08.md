# Class 8 Reading
---

From the Duckett HTML book:

HTML/CSS book, Ch. 15, “Layout” (again; repeat of Class 4 reading)



## Chapter 15 CSS Layout

---

### Review of Tables

- thead = heading of table should sit inside this element
- tbody = The body element of table
- tfoot = the footer of the table 
- tr = tr tag to indicate start of new row
- td = each cell of a table is represented using a td tag
- th = header of each column or row


### Key concepts in positioning elements
- Building blocks - CSS treates html elements as if it is in its own box. This box will either be block-level or inline.
- Examples of block level elements include; h1 ,p, ul,li.
- Examples of inline elements include; img, b, i


### Common Layouts

- Fixed width layouts - do not change size as the user increase or decreasd the size of thier window.
- Liquid Layouts - stretch and contract, tend to use percentages
- You can use some CSS prebuilt layouts for better composition of page. 

## Review of previous day (day 7)

---

### what is a Constructor?
- it is a FUNCTION
- creates object INSTANCES
- use parameters to assign UNIQUE property values
- important diff betwwen this and object literal:
- NO OBJECT EXISTS.... yet


### we've create a Student "factory"

`let allStudents = [],`

`function Student(name, pronouns){
  this.studentName = name;
  this.pronouns = pronouns;
  this.currentClass = '201d81';
  allStudents.push(this); (pushes informatino into array)
}`

- at this point in code, THIS refers to the instance that WILL BE created

let kendrah = new Student('Kendrah', 'she/her');
let shane = new Student('Shane', 'he/him');
let chuck = new Student('Chuck', 'he/him');
let jallow = new Student('Jallow', 'he/him');


`//  protoype === inherits
Student.prototype.greetsClass = function(){
    console.log(`Hello ${this.currentClass}! I'm ${this.studentName}! I use ${this.pronouns} pronoouns.`)
  }`

`Student.prototype.greeting = function(){
  console.log('hello!');
};`

`// console.log(kendrah);
// kendrah.greetsClass();`

---

### Object Literals 

>let instructor = {
  name: 'Ryan',
  age: 46,
  isDev: true,
  faveNumbers: [42, 7, 144, 206],
  multiplesOfFive: [],
}

console.log(instructor);

### What are two different ways you could add a property to this object.  maybe one inside and one outside?

// TODO add the property eyeColor with a  value of brown one way and the property hairColor with a value of brown the other way.  then run the console.log below to confirm success




// console.log(instructor);

// TODO write a method method for the instrutor object that iterates thru the faveNumbers array, multiplies EACH element by five, and pushes that product into the multiplesOfFive Array.


