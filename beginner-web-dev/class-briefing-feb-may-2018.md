# Class Briefing

## Week 1

### Class Recap 02/06/18
Format of the class was as follows:
* Instructors and teachers gave quick introductions
* How and why we use Slack
* Went over Slack features
* Introduction to CodePen
* Introduction to Medium
* Introduction to web development
* Assignment: Medium Blog Post - How they feel about getting into web development. Due on Thursday 2/8/18

Resources:
* Intro to web dev slides: http://slides.com/mellanie/intro-to-web-dev

### Class Recap 02/08/18
Format of the class was as follows:
* Explained what GitHub is
  - Online open source repository for storing projects
  - Most widely used online host for source code used by programmers
  - How to find repositories
  - File structure of repositories: README.md, folders, and files
  - How to find assignment repositories in junior-devleague-educators organization
  - For the purpose of this class, we will be using GitHub for assignment instructions only
* Explained what Git is
  - Open source version control software used in the command line
* Explained difference between remote and local repositories
  - Remote is anything online, servers and files in the cloud on the internet
  - Local is anything on your machine
* Explained what web content is
  - Everything from words, pictures, videos inside of tags
* Explained HTML Syntax
  - Opening tags w/ closing tags
  - Self closing tags
* Explained Importance of indentation when writing code
  - Easier readability
  - Easier way to differentiate between code and content
Live coded the following:
* Creating a HTML Structure, also called "HTML skeleton"
* HTML tags
  - Created divs, paragraphs, headers, ordered lists, unordered lists, links, and images
* HTML attributes
  - Used as labels or to provide additional information
* CodePen shortcuts
  - When using shortcuts you must type bang symbol or element name and immediately press tab
  - Explained that using shortcuts eliminate the possibility of forgetting a closing tag, and auto indents code for you.
  - Auto-create an HTML skeleton, example: ! _tab_
  - Auto-create opening and closing tags, example: div _tab_
  - Creating mulitple elements, example: li*3 _tab_ to create 3 list elements
* Live code example created during class: https://codepen.io/msoriano/pen/JpEeLb

Assignment:
fan-page - https://github.com/junior-devleague-educators/fan-page

Resources:
* HTML Slides: http://slides.com/mellanie/html
* HTML Elements: https://www.w3schools.com/html/html_elements.asp

## Week 2

### Class Recap 02/13/18
Format of the class was as follows:
* Reviewed some of the feature of zoom.us 
* Open discussion about HTML
* Had Jenn and Miki live code fan-page solution so that they could practice talking about code
* Live-Code: Intro to CSS
  - Explained what CSS does
  - Why we use CSS and explained about cascading 
  - Went over basic syntax
    - Selectors, delcartion, property, value
  - Explained why we use ID's and Classes
  
Resources:
* CSS Slides: http://slides.com/jasonsewell/css-yes#/
* W3Schools CSS: https://www.w3schools.com/css/

### Class Recap 02/15/18
Format of the class was as follows:
* Reviewed how CSS works
  - Style cascades from top to bottom like a waterfall
  - Explanation of inheritance; parent vs child
* CSS Syntax
  - How to use selectors to style elements by tag name, id, and classes.
  - How to use properties like width, background-color, font-family, etc and set values to add styling to HTML elements.
* Live-Code: HTML
  - Teachers navigated instructor on creating a basic HTML page with h1, links, images, divs, and paragraphs.
* Live-Code: CSS
  - Element selector, state the element itself
  - ID selector, use # to select and id
  - Class selector, use . to select classes
  - Multiple styles for a single element
  - Pseudo classes
    - Hover effect to links
    - Change color of links if it was visited
  - Sizing content with px, pt, and %
  - Adding background images
  - How to use colors
    - CSS color names
    - Hex code
    - Showed teachers ColorZilla extension to grab any color on the web
  - Using fonts
    - How to import fonts from google fonts
    
Assignment:
Style fan-pag with CSS - https://github.com/junior-devleague-educators/fan-page
  
Resources:
* CSS Slides: http://slides.com/jasonsewell/css-yes#/
* W3Schools CSS: https://www.w3schools.com/css/
* ColorZilla Chrome Extension: https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=en

## Week 3

### Class Recap 02/20/18
Format of the class was as follows:
* Every teacher presented their fan-page project, and answered the following questions:
  - What makes that artist your favorite?
  - Was there any parts of the project that was tricky to solve?
  - On a scale of 1-5 (1 being low, 5 being high) how confident are you about moving on from HTML & CSS?
  - Is there anything you would like us to go over before moving on?
* After each presentation, instructors helped debug and clarify the biggest issue(s) each teacher had.
* Reviewed how to resize images
  - How to select elements with a class selector ( . )
  - How to select elements with a element selector ( img )
* Reviewed importing fonts from google
* Reviewed centering elements
  - Using margin: auto;
  - Using text-align: center;
* Reviewed lists
  - difference between ol, ul, and li
    - ol represents an ordered list, and within the tags they hold list elements (li)
    - ul represents an unordered list, and within the tags they hold list elements (li)
    - ol's and ul's have li elements within them
* Live coded some of the solutions for the CSS part of the fan-page project

Assignment:
Medium Blog Post - What advice would you give your students about the struggles you had with html & css?

### Class Recap 2/22/18
Format of the class was as follows:
* Teachers took the first 10 minutes to do an html & css assessment
* Went over solutions for the most commonly missed questions
  - Went over selecting and styling only elements within a div. Example: div p { color: orange; }
  - Went over the difference between tags and attributes
  - Reviewed the different selectors: element selectors use tag names, id selectors use #, and class selectors use .
  - Went over linking external stylesheets to html
  - Went over border-width property in CSS. The first value is the top border, second value is the right border, third value is the bottom border, and fourth value is the left border.
* Live coded debugging exercise: https://codepen.io/msoriano/pen/EQRKyE?editors=1100

Assignment:
Debug html & css: https://codepen.io/msoriano/pen/EQRKyE?editors=1100
IG Profile: https://github.com/junior-devleague-educators/ig-profile-educators/blob/master/README.md

Resources:
HTML & CSS for Beginners: https://css-tricks.com/guides/beginner/

## Week 4

### Class Recap 2/27/18
Format of the class was as follows:
* Teachers presented their ig-profile project, and answered the following questions:
  - What did you enjoy about the project?
  - What was the most challenging part of the project?
  - At this point, would you be comfortable teaching your students the basics of html & css?
* Live-coded how to make images larger on hover
  - Used the `.images:hover` pseudo-selector to target an image only on hover
  - Used the `width` and `height` property to make images larger
  - Also showed another way using `transform: scale(1.5)`
* Live-coded how to move div's into specific areas of a webpage
  - Gave a quick introduction to flexbox
    - Flexbox is a layout method
    - Use `display: flex` on the parent div/element to activate flexbox
    - Must target parent div/element in order for children elements to move around
    - Used `display: row` to make elements align in a row
  - Adjusted margin and padding to position divs containing a number count right above images, followers, and following section of ig-profile
* Quick reviewed of html & css debugging exercise
  - Used one of the teacher's project to debug
  - Explained that the `:nth-child()` pseudo-selector targets the child element specified inside the parenthesis.
    - example: `p:nth-child(2)` will target the 2nd p element

Resources:
CSS-Tricks Flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

### Class Recap 3/1/18
Format of the class was as follows:
* Live-code and lecture introduction to JavaScript
  - Variables
    - Syntax for creating a variable includes `var` followed by the name of the variable followed by the assignment operator (=), followed by the value, which should be a JavaScript datatype. example: `var firstName = "Jay"`
    - Declare a variable using the keyword `var`
    - Initialize a variable by using `=` and setting a value.
    - Explained that keywords in JavaScript are reserved for a specific purpose and can only be used for that purpose. Example: `var` is to indicate that you are creating a variable 
    - Re-assigning variables does not require the keyword var, because the variable name is already stored in memory. Example: `var firstName = "Jay"` can be reassigned by doing: `firstName = "Mel"`
    - Variable names can include letters and numbers. It must start with a letter, but can not start with a number. Example: Acceptable: `var num1 = 10` Not Acceptable: `var 1num = 10`
  - How to use `console.log()`
    - We use `console.log()` to check code as it gives us instant feedback
    - You can pass in variable names or any data type between parentheses. Example:
      ```
      var num1 = 99;
      console.log(num1); // returns 99
      
      console.log(50); // returns 50
      ```
    - Reading errors in console. Example errors we encountered: undefined and illegal (syntax error)
    - console.log() should always go below the code you are checking. Example:
      ```
      Correct way:
      var firstName = "Mel";
      console.log(firstName); // returns "Mel"
      
      Wrong way:
      console.log(lastName); // returns undefined
      var lastName = "Soriano";
      ```
  - Writing comments
    - Use 2 forward slashes for single line comments. Example: `// single line comment`
    - Use 1 forward slash follwed by an asterisk for the opening of a mult-line comment and an asterisk followed by a forward slash to close multi-line comments. Example:
    ```
    /* use this
    for multi-line
    comments. */
    ```
        
  - String Data Type
    - Syntax for strings should be wrapped between double or single quotes
    - Concatenating more than 1 string with space. Example: `"Taco " + "Cat"` will result in `"Mellanie Soriano"`
    - Concatenating more than 1 string without space. Example: `"Taco" + "Cat"` will result in "TacoCat"
  - Number Data Type
    - Syntax for numbers should just be typed as is, no quotes
    - Number data types can be positive (1,2,3, etc) or negative integers (-1, -2, -3, etc), and floating points (1.1, 2.345, 3.456, etc).
  - Boolean Data Type
    - true or false values
  - Null Data Type
    - Has only 1 value, `null`. Example: `var tomorrowsWeather = null`
    - Used as a placeholder when we don't know what the value is at the moment
  - Undefined Data Type
    - When a variable doesn't exist
    - When a variable hasn’t been set or assigned to a value. Example: `var kittenName;`
  - Expressions
    - Produces a value. Example: `2 + 3` will produce 5 as it’s value
  - Arithmetic Operators
    - How to use arithmetic operators: Add `+`, Subtract `-`, Multiply `*`, Divide `/`, Increment `++` increases integer by 1, Decrement `--` decreases integer by 1, Modulus `%` will divide 2 numbers and return the remainder.
    ```
    var add = 1 + 1; // produces 2 as it's value
    var subtract = 2 - 1; // produces 1 as it's value
    var multiply = 5 * 5 // produces 25 as it's value
    var divide = 10 / 5; // produces 2 as it's value
    
    var increment = 1; // produces 1 as it's value
    increment++ // produces 2 as it's value
    increment++ // produces 3 as it's value
    
    var decrement = 5; // produces 5 as it's value
    decrement-- // produces 4 as it's value
    decrement-- // produces 3 as it's value
    ```
  - Comparison & Logic Operators
    - Greater than ( > )
    - Less than ( < )
    - Greater than or equal to ( >= )
    - Less than or equal to ( <= )
    - Loose equality ( == )
    - Must be same value, does not have to be same data type. Example: `“5” == 5` will result in true
    - Strict equality ( === ) Must be same value and same data type. Example: `“5” === 5` will return false. `“5” === “5”` will return true
    - Loose inequality ( != ) Must not be same value, can be same data type. `5 != 5` will result in false. `5 != 4` will result in true
    - Strict inequality ( !== ) Must NOT be same value and same data type. `“5” !== 5` will return true. `“5” !== “5”` will return false
    - Logical AND ( && ) Expressions on both sides of the and ( && ) must evaluate to true in order for code to run. Example: `5 > 2 && `
    - Logical OR ( || ) Also known as ‘pipe’. Expression on either side of the pipe ( || ) will evaluate to true if either side of the expression is true, otherwise it will produce false. Example: `5 >= 5 || 5 === 6` produces true. `5 < 5 || 5 === 6` produces false
* Assigned: js-variables-datatypes: https://github.com/junior-devleague-educators/js-variables-datatypes

## Week 5

### Class Recap 3/1/18
* Reviewed and live-coded a couple exercises from the js-variables-datatypes assignment
  - Explained the difference between `"5" and 5`
* Went over some JavaScript caveats
* Difference between “5” and 5, "5" is a String data type and 5 is a number datatype
  - When you `console.log("5" + 5); // outputs "55"`
* Difference between console.log(hello); and console.log(“hello”);
  - `console.log(hello); // outputs hello is not defined`
  - `console.log("hello"); // outputs "hello"`
* Review re-assigning variables:
```
var x = 5;
console.log(x); // outputs 5
x = 10;
console.log(x); // outputs 10
```
* Explained that JavaScript runs top to bottom. Example:
```
console.log(name); // outputs not defined
var name = "Mel";
console.log(name) // outputs "Mel"
```
* Teachers took a variables and datatypes pop quiz
* Went over solutions that people got wrong
  - Reviewed strict equals. Datatype and value must be the same in order for this expression to be true. `"3 === 3 // produces false`
  - Reviewed incrementing and decrementing
* Assigned: Medium Blog Post - Explain Like I'm 5: Variables

### Class Recap 3/8/2018
Format of class was as follows:

Introduction to Arrays
- An array is another data type like strings, numbers, boolean, etc
- Arrays are like “lists” - you can store all data types in an array.
- Items in an array should be wrapped in square brackets.
- Each item in the array should be separated by a comma.
= Each item in the array is assigned an index, starting from 0.
- To get the length of an array you can use .length
Live Code Array Examples
- Create an array of strings containing Hogwarts student names
  `var students = [“Hermoine”, “Ron”, “Harry”, “Luna”];`
  `var schoolSubjects = [“Potions”, “Alchemy”, “Defense Against The Dark Arts”, “Charms”];`
- Create an array of numbers
  `var numbers = [10, 2, 9, 200, 56];`
- Show an example of subarrays within an array
  `var subarrays = [[“Severus Snape”, “Dolores Umbridge”], [true, false], [“hello”, “9 ¾”, false]]`
- To get the length of an array we use .length
- .length can be useful when we don’t know how many items are within an array.
  Example: `subarrays.length will produce 3`
  
Accessing Arrays
- To access specific items in an array you would use bracket notation.
- Bracket notation is a property accessor. It gives the ability to access arrays.
- We use bracket notation by writing the array name followed by the index of the item we want to get.
- Reiterate that array indexes start from 0

EXERCISES: Create the following sentences:
  - “Hermoine’s favorite subject is Charms”
    - To access “Hermoine” we would do `students[0]`
    - You can do `students[0]` as-is or store it in a variable
  - “The Alchemy class is located in Room 200, next to the Potion’s class.”
    - To access “Alchemy” we would do `schoolSubjects[1]`
    - To access 300 we would do 1numbers[3]1
    - To access “Potion” we would do `schoolSubjects[0]`
  - “Harry got lost looking for the Defense of Dark Arts class taught by Dolores Umbridge”
    - To access “Harry” we would do `students[2]`
    - To access “Defence of Dark Arts” we would do `schoolSubjects[2]`
    - To access “Severus Snape” we can do this two ways.
      - Store `subarrays[0]` in a variable to get the first item in the array. Then use the newly created variable and do `subarrays[1]`
      - OR `subarrays[0][1]` works too
  - “Ron and Luna is taking 4 subjects this semester.”
    - To access “Ron” we would do `students[1]`
    - To access “Luna” we would do `students[3]`
    - Get the length of subjects by doing `schoolSubjects.length`
Assigned: js-arrays - https://github.com/junior-devleague-educators/js-arrays

## Week 6

### Class Recap 3/13/18
Format of the class was as follows:
Arrays Homework Review
- Review an exercise from each section of js-arrays assignment
  - js-arrays: https://github.com/junior-devleague-educators/js-arrays
MadLib Story
- Explain that MadLib story is one way they can bring coding into the classroom.
- They can create a fill in the blank story with any subject Math, Literature, History, Science, etc.
- Call on a teacher to create an array with the instructions on madlib-arrays.
  - madlib-arrays: https://github.com/junior-devleague/madlib-arrays
- When arrays are created, call on teachers again to fill in the blanks.
- Console log the results

### Class Recap 3/15/18
Format of the class was as follows:
Introduction to JavaScript Objects
- Objects are thought of as “collections” that have key-value pairs.
- Variables can store objects
Live Code Objects
- Objects are wrapped in curly braces {...}
- Explain that var fileCabinet = {}; is an empty object
- To add key-value pairs we do the following:
```
var fileCabinet = {
   taxes: “2017 Tax Return”
};
```
- The KEY will come first, followed by a colon, followed by the value
- To add more key-value pairs we do the following:
```
var fileCabinet = {
   taxes: “2017 Tax Return”,
   insurance: “Geico”,
   receipts: [“MacBook Pro”, “School Tuition”]
};
```
- Properties should be separated by commas NOT semicolons
- Show that if you use a semicolon to separate properties you will get a syntax error
Accessing Objects
- Dot Notation
```
fileCabinet.insurance // produces “Geico”
fileCabinet.receipts // produces [“MacBook Pro, “School Tuition”]
```
Bracket Notation
```
fileCabinet["insurance"] // produces “Geico”
fileCabinet["receipts"] // produces [“MacBook Pro, “School Tuition”]
fileCabinet[insurance] // will return an error, insurance not defined
```
Have teachers create “person” object and add properties
```
var person = {
  name: "mel",
  favoriteColor: "orange"
};

// add a property with dot notation
person.languages = ["english", "javascript"]

// add a property with bracket notation
person["hairColor"] = "black";


// what the object looks like now that you've added new properties:
var person = {
  name: "mel",
  favoriteColor: "orange"
  languages: ["english", "javascript"],
  hairColor: "black"
}
```

## Week 7

### Class Recap 3/20/18
Format of the class was as follows:
JS-Objects Assignment Review
- Review an exercise from each section of js-objects assignment
  - js-objects: https://github.com/junior-devleague-educators/js-objects
  - had each teach live-code a section from the assignment
Objects and Array Quiz
- After the quiz we reviewed some tricky questions as a class, mostly syntax erros
- Teachers found that Question #4 had no correct answer which was a good sign
Objects and Array Quiz
- Spent remainder of class working on debugging objects and arrays assignment
 - debug-arrays-and-objects: https://github.com/junior-devleague-educators/debug-arrays-and-objects
 - Had teachers work on each number and slack their solution

### Class Recap 3/22/18
Format of the class was as follows:
Quick review of debug-array-and-objects
- Explained why console logging nested objects don't fully show in codepen or jsbin
- Showed that we can see object nesting in chrome dev tools
Intro to functions live-code
- Please see lesson plan for live-code steps
  - https://docs.google.com/document/d/1DH_r_5vwfk0fX5uAdRsnGyzk24TpZDiupOISswlY6mQ/edit#
    1. Started functions with no parameters and only console.log
    1. Explained difference between parameters and arguments
    1. Explained the purpose of `return`
    1. Had teachers create add, substract, multiply, and divide functions during session 
- Assigned js-functions
  - https://github.com/junior-devleague-educators/js-functions
  
## Week 8

### Class Recap 3/27/18
Format of the class was as follows:
Function Review
- Syntax for writing a function
  - Start with the keyword `function`
  - Followed by the function name
  - Immediately followed by parenthesis
  - Parameters are optional within the parenthesis
  - Followed by curly braces
  - Your code should go within the curly braces, this area is called the `function body`
- How to write a function without parameters:
  ```
  function nameOfFunction(){
    // code in here
  };
  ```
- Write a function with 1 parameter and invoke the function with 1 parameter:
  ```
  function nameOfFunction(parameter1){
    // code in here
  };
  
  nameOfFunction(argument1);
  ```
- Write a function with 2 parameters and invoke the function with 2 parameters:
  ```
  function nameOfFunction(parameter1, parameter2){
    // code in here
  };
  
  nameOfFunction(argument1, argument2);
  ```
- Storing a function in a variable to use when console logging
  ```
  function nameOfFunction(parameter1, parameter2){
    // code in here
  };
  
  var myFunction = nameOfFunction(argument1, argument2);
  console.log(myFunction);
  ```
Review parameters
- What are function parameters?
  - Parameters are used as “placeholders” that will be replaced with values when you invoke your function and pass arguments
  - Parameters are used when we want to pass different values so we can reuse the function.
  - Parameters give us the ability to invoke the function many times and pass different arguments.

Review returns in a function
  - The return is used to specifically return a value
  ```
  function pizza(topping1){
    return topping1; // this will return 'cheese' because I invoked it below with 'cheese' as the argument
  };
  
  pizza('cheese');
  ```
  - If we do not return inside of a function we will get an undefined.
  ```
  function pizza(topping1){
    console.log(topping1); // this will print 'cheese' in the console, followed by undefined
  };
  
  pizza('cheese'); 
  ```
  - The return should be the last line of code in the function body, anything after the return statement will not be executed because the return keyword basically tells JavaScript “this is the end, give me the final value”.
  ```
  function pizza(topping1){
    return topping1; // will return 'cheese'
    console.log(topping); // this will not be exectued
  };
  ```
  
Invoking functions and passing arguments
  - In order for our function to actually execute, we have to invoke or call it
  - To invoke or call a function we use the function name followed by parenthesis
  Example: `myFunction()`;
  - Arguments should be passed when invoking a function when you have parameters
  ```
  function nameOfFunction(parameter1){
    // code in here
  };
  
  // invoking function below:
  nameOfFunction(argument1);
  ```
  
In-class function exercise
Each teacher wrote a function called createStudent with 1 parameter
  ```
  function createStudent(firstName) {
      return firstName
  };
  var student1 = 'Mellanie'
  
  // storing function to a variable
  var studentFunction = createStudent(student1);
  
  console.log(studentFunction);
  ```
### Class Recap 3/29
Format of class was as follows:
- Went over js-function solutions: https://codepen.io/msoriano/pen/NYzMdN
- Reviewed functions:
  * How to invoke a function
  * How to pass arguments
  * Difference between parameters vs arguments
  
## Week 9

### Class Recap 4/3
Format of class was as follows:
Mid-program Quiz & Review
  * Correct way of invoking the following function:
  ```
  function doSomething() {
      return "hello world";
  }

  // ** ANSWER
  // HOW TO INVOKE A FUNCTION:
  doSomething() // returns "hello world"
  ```
  * What are the two ways you can access an object?
    1. Dot Notation
    2. Bracket Notation
  * How would you invoke the following function and pass "chocolate" as an argument?
  ```
  function makeIceCream(flavor);
    return flavor;
  }
  ```
  * Assign the following function to a variable called `myFavoriteDance` and pass in the argument `salsa`.
  ```
  function letsDance(dance) {
    return dance;
  }
  
  // *** ANSWER
  var myFavoriteDance = letsDance('salsa');
  ```
  * Add a property called `name` and set it's value to `Fido` to the following object:
  ```
  var dog = {};
  
  // *** ANSWER
  // Using dot notation
  dog.name = 'Fido';
  
  // Using bracket notation
  dog['name'] = 'Fido';
  ```
  * How would you invoke the following function and pass “chocolate” as an argument?
  ```
  function makeIceCream(flavor);
    return flavor;
  }
  
  // *** ANSWER
  makeIceCream('chocolate');
  ```
  * What is the value that will be console logged in the following:
  ```
  var decrement = 5;
  decrement--;
  console.log(decrement); // *** ANSWER: 4
  decrement = 2;
  ```
  * Open discussion & feedback about learning coding and program
    - Teachers would like to see and learn how html, css, javascript work together
    
 ### Class Recap 4/5
Format of class was as follows:
- HTML Review
  - Use `! <tab>` to generate a HTML skeleton
  - Create a div with the id “container”: `<div id="container"></div>`
  - Add an image `<img src="url">`
  - Create a paragraph `<p>some text in here</p>`
  
- Introduction to DOM
Slides: http://devleague.slides.com/jasonsewell/dom-dom-dom-dom#/

What is DOM?
- DOM is an acronym for Document Model Object
- The DOM is an API, or Application Programming Interface for interacting with the browser
- The DOM is a dynamic, in-memory representation of an HTML document
- We can use DOM to manipulate the structure of a document


What DOM isn’t?
- The DOM is NOT JavaScript, we use JavaScript to interact with the DOM
- The DOM is NOT your HTML document that you write in your editor  (although it starts that way)

How does DOM work?
- Browser requests HTML document from web server
- File downloads to the browser via the internet as plain text
- Browser parses the HTML text to create the DOM
- An in-memory replica of the HTML downloaded is created in memory
- We can change the DOM not the source file


Accessing HTML Elements
- Example of accessing an element by tag name
`var getDivs = document.getElementsByTagName(div);`
- Example of accessing an element by ID
`var mainContainer = document.getElementById(‘container’);`
- Console log to check if you targeted the right element 

How to set or return text
- The innerHTML property sets or returns the HTML content (inner HTML) of an element
- The property value should always be a string/text
- Syntax for using innerHTML to add text to our container div:
```
var mainContainer = document.getElementById(‘container’);
mainContainer.innerHTML = ‘hello world’;
```

How to change an image
- The src property sets or returns the value of the src attribute of an image
- The required src attribute specifies the URL of an image
```
var grumps = document.getElementById(“grumpy-cat”);
grumps.src = “replace-with-image-url”;
```

Create a new HTML element:
`var newDiv = document.createElement(‘div’);`

Assign an id to the newly created div:
`newDiv.id = (‘about-me-container’);`


Add text to the newly created div:
`newDiv.innerHTML = “My name is Grumpy Cat.”`

Appending the newly created div to an existing element:
`mainContainer.appendChild(newDiv);`


Style property
- Change the background color
  `mainContainer.style.backgroundColor = ‘orange’;`
- Change font family
  `mainContainer.style.fontFamily = ‘comic sans’;`
- Change font size
  `mainContainer.style.fontSize = ‘60px’;`
 
## Week 10
 
### Class Recap 4/10
 Format of class was as follows:
- Live-coded DOM-all-stars assignment
- Teachers guided instructor to the solutions
- Went over how to access elements by class name
  - Explained that they would need to access the classes using square brackets and the index number
 ```
 Example:
 
 // this gets the first element with the same class name
 var changeProfile = document.getElementsByClassName('profile')[0];
 // this changes the text content
 changeProfile.innerHTML = 'My name is Hello Kitty';
 ```
 - Solution to assignment:
  codepen: https://codepen.io/msoriano/pen/jzeBmN
 
 
### Class Recap 4/12
 Format of class was as follows:
 - Introduced events with addEventListener method
 - Had teachers code along on their end which was very beneficial to help them understand concepts
 - Had more practice with `createElement()` method
 
What is an “event”?
- Events are sent to notify code of things that have taken place.
- There are many different categories of events
- Reference: https://developer.mozilla.org/en-US/docs/Web/Events
- We will be working with mouse events

What is the addEventListener() method?
- Sets up a function to be called whenever the specified event is delivered to the target.
- High-level syntax:
```
target.addEventListener(‘type’, function(){})
```

- Live-code example
  codepen: https://codepen.io/jhoun/pen/rdgymd

- Assignment
  Intro to DOM events: https://codepen.io/msoriano/pen/yKrMVp
  
  
## Week 10

### Class Recap 4/17
Format of class was as follows:
 - Spent entire class reviewing Intro to DOM events assignment
 - Live-coded problems from #1 - #7
 - Some students weren't able to get button events working, so we debugged their assignment as a class, which was very effective
 
 - Solution to assignment
   codepen: https://codepen.io/jhoun/pen/xjxbmX?editors=1011

### Class Recap 4/19
Format of class was as follows:
Introduction to JS Conditionals
- What are conditionals?
  - A conditional says “If something is true, do this… Otherwise, do that”
- If statements
  - An if statement is used to execute a piece of code if something is true.
  - The piece of code will only run if the condition is true
  - Structure of an if statement
  ```
  if (condition statement) {
    // code to be executed if statement is true
  }
  ```
- If/else statements
  - Same rules apply for the if statement
  - Else is added to statement if the condition in the if statement is false
  - Structure of an if/else statement
  ```
  if (condition statement) {
    // code to be executed if statement is true
  } else {
    // code to be executed if statement is false
  }
  ```
- If, else if, and else statements
  - We can check for multiple conditions
  ```
  if (condition statement) {
    // code to be executed if statement is true
  } else if (other condition statement) {
    // code to be executed if statement is false
  } else {
    // code to be executed if none of the statements are true
  }
  ```
Live code examples
- Write a conditional statement that checks if num1 is greater than num2, if truthy return num1 + “is greater than” + num2.
    ```
    if (10 > 5) {
        console.log(“I am greater than!”);
    }
    ```
- Explain that if we only have an if statement and we don’t control what happens if something is false, the code will not be executed.
- Add an else to the already made if statement
  ```
  if (10 > 5) {
    console.log(“I am greater than!”);
  } else {
    console.log(“I am not greater than!”);
  }
  ```
- Create a function called greeting with one parameter called name. Inside the function, write a conditional statement that returns “Hi” + name if truthy, otherwise return “You are not” + name. Create two variables and assign one of the variables to your name and the other variable to another name.
```
function greeting(name){
  if (name === “mellanie”) {
    return “Hi “ + name + “ !”;
  } else {
    return “You are not “ + name + “ !”;
  }
}
```
- Create a variable and assign it to your favorite food. Next, create a function called favoriteFood with one parameter called food. Inside the function write a conditional statement that checks if food equals pizza and an else if statement if food equals sushi.
```
function favoriteFood(food){
  if (food === “pizza”) {
    return “Pizza is my favorite!”;
  } else if (food === “sushi”) {
    return “Sushi is my favorite!”;
  }
  else {
    return “Pizza is NOT my favorite. I prefer ” + food;
    }
}
```
Assignment
- Js-conditonals: https://github.com/junior-devleague-educators/js-conditionals

Resources:
- W3 Schools Conditionals - https://www.w3schools.com/js/js_if_else.asp
- W3 Schools Comparison and Logical Operators - https://www.w3schools.com/js/js_comparisons.asp


## Week 11

### Class Recap 4/24
Format of class was as follows:
* Conditionals Review
  * Each teacher was assigned an exercise from js-conditionals to live code and teach us the solution like we were their students.
  
### Class Recap 4/26
Format of class was as follows:
* What is a for loop used for?
  *  Loops can execute blocks of code a number of times
  * Loops are handy when you want to run the same code over and over again, each time with a different value
  * For loops are used to iterate through arrays and strings
  * A for loop is comprised of 3 pieces separated by semicolons
    * Initialization - used to initialize the variable before the code block is executed and tracks how far through the loop you are: `for ( var i = 0 )`
    * Condition - used to evaluate the condition for running the loop (how many times to run the loop): `for ( var i = 0; i < array.length )`
    * Expression - is executed each time after the code block has been executed 
      ```
      for ( var i = 0; i < array.length; i++ ) {
      // block of code goes in here
      }
      ```
* Live code for loops example
```
var nameArray = [‘mel’, ‘jay’, ‘alana’, ‘traci’];
for (var i = 0; i < nameArray.length; i++) {
	console.log(‘name: ’ +  nameArray[i] + ' is at index: ' + i);
}

outputs:
name: mel is at index: 0
name: jay is at index: 1
name: alana is at index: 2
name: traci is at index: 3
```
* The loop starts at index 0 of the nameArray array.
* The loop will only iterate through the array one less than the array length
* After each iteration, the count of i will go to the next value
* When i is 0 nameArray[i] is 'mel', when i is 1 nameArray[i] is 'jay', and so on..

```
var name = “Mellanie”
for (var i = 0; i < name.length; i++) {
	console.log(‘My name contains the letter: ‘ + name[i]);
}

outputs:
My name contains the letter: M
My name contains the letter: e
My name contains the letter: l
My name contains the letter: l
My name contains the letter: a
My name contains the letter: n
My name contains the letter: i
My name contains the letter: e
```

* Using a for loop in a function
  * Key things to note:
    * You should not return within a loop, returning in a loop will only output the last iteration.
    * You need a variable to set the result in order to see the looped result.

* Greeting Example:
```
var greetingList = ['aloha', 'hola', 'ciao'];

function saySomething(greeting){
	var result = '';
	for (var i = 0; i < greeting.length; i++) {
		result += greeting[i] + " mel! ";
	}
	 return result;
}
var greetMel = saySomething(greetingList);
console.log(greetMel); // "aloha mel! hola mel! ciao mel! "
```

Odd Numbers Example:
```
var numberList = [9,8,7,6,5];

function findOddNums(numArr){
	var result = '';
	for (var i = 0; i < numArr.length; i++) {
		if (numArr[i] % 2 !== 0) {
			result += numArr[i] + ‘ ‘;
	}
	 return result;
}
var displayOddNums = findOddNums(numberList);
console.log(displayOddNums); // "9 7 5 "
```

HOW TO ADD ODD NUMBERS:
```
var numberList = [9,8,7,6,5];

function findOddNums(numArr){
	var result = 0; // if you want to do math operations set the value to an integer
	for (var i = 0; i < numArr.length; i++) {
		if (numArr[i] % 2 !== 0) {
			result += numArr[i];
	}
	 return result;
}
var displayOddNums = findOddNums(numberList);
console.log(displayOddNums); // "9 7 5 "
```

## Week 12

### Class Recap 5/1
Format of class was as follows:
- Had each teachers live-code and teach a problem from js-for-loops assignment.

### Class Recap 5/3
Format of class was as follows:
- Assigned whack-a-mole https://github.com/junior-devleague/whack-a-mole
- Introduced 
  - setInterval method https://www.w3schools.com/jsref/met_win_setinterval.asp
  - Math.random() https://www.w3schools.com/jsref/jsref_random.asp
  - Math.floor() https://www.w3schools.com/jsref/jsref_floor.asp
  - Flexbox https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- Provided teachers with CSS code snippet to pract CSS Flexbox

## Week 13

### Class Recap 5/8
Format of class was as follows:
- Teachers presented a mini lesson on their given topic
- Topics covered: Functions, Loops, Conditionals
- Live-coded how to add an event listener to multiple elements with the same class using a for loop
Example:
```
for(let i = 0; i < boxes.length; i++) {
	boxes[i].addEventListener('click', function() {
		alert('Hello!');
	});
}
```
- Live-coded how to add text to a random div
```
function addRandomText() {
  var newDiv = document.createElement('div');
  newDiv.setAttribute('class', 'newDiv');
  newDiv.innerHTML = 'hello';
  
  // this creates a random number based on the number of elements in the specified array
  var randomNumber = Math.floor((Math.random() * boxes.length) + 0);
  
  if(boxes[randomNumber].innerHTML === '') {
    boxes[randomNumber].appendChild(newDiv);
  }
}
});
```
- Reviewed how to create a random number
```
var randomNum = Math.floor((Math.random() * boxes.length) + 0);
```
