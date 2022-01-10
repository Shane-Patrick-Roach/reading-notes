# Reading 13 

Local Storage:

http://diveinto.html5doctor.com/storage.html


---

## Problems with cookies:
- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


## What we want in storage

1. a lot of storage space
2. on the client
3. that persists beyond a page refresh
4. and isn’t transmitted to the server

## What is HTML5 Storage? 

- Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser.



## Review 

### Javascript object
`const john = {
  first: "John",
  last: "Cokos",
  lastName: "Cookoo",
  age: 50
}`

### Function 

`function sayHi(name) {
  console.log('Hi', name);
}`

### Constructor

`function Person(name) {
  this.fullName = name;
}`

`Person.prototype.sayMyName = function() {
  console.log( this.fullName.toUpperCase() );
}`

### CSS selecors

- '#' = selects id
- '.' = selects class
- '*' = selects all elements
- ':hover' = selects links on mouseover

