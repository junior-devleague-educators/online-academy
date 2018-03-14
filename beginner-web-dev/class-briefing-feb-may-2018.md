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
