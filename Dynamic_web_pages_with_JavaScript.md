# Building Dynamic Webpages with JavaScript

*JavaScript* (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions.
> It's a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, 
and declarative (e.g. functional programming) styles.

## JavaScript Identifiers

These unique names are called *identifiers.*

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

1) Names can contain letters, digits, underscores, and dollar signs.
2) Names must begin with a letter
3) Names can also begin with $ and _
4) Names are case sensitive (y and Y are different variables)
5) Reserved words (like JavaScript keywords) cannot be used as names.

## Creating a variable

* `<p id="demo"></p>`

`<script>`
`var carName = "Volvo";`
`document.getElementById("demo").innerHTML = carName;`
`</script>`

* `var person = "John Doe", carName = "Volvo", price = 200;`

* This is a sequence of text known as a *string.* To signify that the value is a string, enclose it in single quote marks.`let myVariable = 'Bob';`

* This is a *number.* Numbers don't have quotes around them.`let myVariable = 10;`

* *Boolean* is a *True/False* value. The words true and false are special keywords that don't need quote marks. `let myVariable = true;`

* *Array* is a structure that allows you to store multiple values in a single reference. `let myVariable = [1,'Bob','Steve',10];
Refer to each member of the array like this:
myVariable[0], myVariable[1], etc.` 

* *Object* can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn. `let myVariable = document.querySelector('h1');
All of the above examples too.` 



**Value = undefined**
In computer programs, variables are often declared without a value. The value can be something that has to be calculated, or something that will be provided later, like user input.

A variable declared without a value will have the value undefined.

The variable carName will have the value undefined after the execution of this statement:


## Remember that JavaScript identifiers (names) must begin with:

A letter (A-Z or a-z)
A dollar sign ($)
Or an underscore (_)

Eample: 
* `var $$$ = "Hello World";`
`var $ = 2;`
`var $myMoney = 5;`

### Comments

Comments are snippets of text can be added along with the code. The browser ignores text marked as comments.
Using `/* Everything in this */` is a comment. Also `//This is a comment` as well. 

### Operators 

*Operator* is a mathematical symbol that produces a result based on two values or varibles.
Here are a couple of ideas how it works.

1) Addition just adding two numbers together example is `6 + 9;` `Hello` + `world!`;
2) Subtraction, Multiplication, Division example `9-3;` `8 * 2;` `//` `multiply in JS is an asterisk 9 / 3;`

### Adding an image changer

1) Choose an image you want to feature on your example site. Ideally, the image will be the same size as the image you added previously, or as close as possible.
2) Save this image in your images folder.
3) Rename the image firefox2.png.
4) Add the JavaScript below to your main.js file.

`let myImage = document.querySelector('img');

myImage.onclick = function() {
    let mySrc = myImage.getAttribute('src');
    if(mySrc === 'images/firefox-icon.png') {
      myImage.setAttribute('src','images/firefox2.png');
    } else {
      myImage.setAttribute('src','images/firefox-icon.png');
    }
}`



> To get more information and practice how to use JavaScript go to this link here: [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)


# Website Pages
- [*About Me*](README.md)
- [*Growth Mindset*](GrowthMindset.md)
- [*Learn more about Markdown*](Learning_Markdown.md)
- [*Coders Computer*](CodersComputer.md)
- [*Revisions and Cloud*](RevisionsandCloud.md)
- [*Learning HTML structure*](LearningHTMLstructure.md)
- [*Design Website with CSS*](Design_web_pages_with_CSS.md)
- [*Building Dynamic Webpages with JavaScript*](Dynamic_web_pages_with_JavaScript.md)
- [*Programming with JavaScript*](Programming_with_JavaScript.md)
- [*Operators_and_Loops*](Operators_and_Loops.md)





