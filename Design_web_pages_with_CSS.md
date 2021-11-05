# What is CSS?

> **Cascading Style Sheets** allows you to create great-looking web pages.

Using CSS you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.
CSS is a rule-based language. you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.


>  CSS can be used for very basic document text styling — for example changing the color and size of headings and links.


`h1 {
    color: red;
    font-size: 5em;
}`

- Here is the link for more color values: [ColorValues](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units#color)



The rule opens with a selector . This selects the HTML element that we are going to style. In this case we are styling level one headings `<h1>`

### How to do the **background and borders?** 
Click on the link here for more codes to use.
[Background/Boarders](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders)

## Adding CSS to our document

- The very first thing we need to do is to tell the HTML document that we have some CSS rules we want it to use. 
There are *three* different ways to apply CSS to an HTML document, but for now linking CSS from the head of your document.

- Create a file in the same folder as your HTML document and save it as styles.css. The .css extension shows that this is a CSS file.

To link styles.css to index.html add the following line somewhere inside the <head> of the HTML document:
`<link rel="stylesheet" href="styles.css">`
  
This `<link>` element tells the browser that we have a stylesheet, using the rel attribute, and the location of that stylesheet as the value of the href attribute. 
  You can test that the CSS works by adding a rule to styles.css. 
  `h1 {
  color: red;
}`
 > Save your HTML and CSS files and reload the page in a web browser. The level one heading at the top of the document should now be red.
  
 ## Three Ways to Insert CSS!
   Click on this link to see more! [How to add CSS?](https://www.w3schools.com/css/css_howto.asp)
  
  
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
  

  
  
  
  



