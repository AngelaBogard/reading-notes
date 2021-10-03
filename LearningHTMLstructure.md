# Learning HTML Structure

## HyperText Markup Language

*HTML* is a markup language that defines the structure of your content.

Which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller.

> *The opening tag*: This consists of the name of the element (in this case, p), wrapped in opening and closing *angle brackets*. This states where the element begins or starts to take effect — in this case where the paragraph begins.

> *The closing tag*: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

> *The content*: This is the content of the element, which in this case, is just text.

> *The element*: The opening tag, the closing tag, and the content together comprise the element.

 - You can put elements inside other elements too. This is called *nesting*. If we wanted to state that our cat is very grumpy, we could wrap the word "very" in a `<strong>` element, which means that the word is to be strongly emphasized

Some elements have no content and are called *empty elements*.
`<img src="images/firefox-icon.png" alt="My test image">`

![HTML Format](/HTMLexamples.png)


> `<!DOCTYPE html>` — doctype. It is a required preamble. These days, they don't do much and just basically needed to make sure your document behaves correctly.

> `<html></html>` — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element.

> `<head></head>` — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.

> `<meta charset="utf-8">` — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.

> `<title></title>` — the `<title>` element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.

> `<body></body>` — the `<body>` element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

## Headings

> `<h1>My main title</h1>`

> `<h2>My top level heading</h2>`

> `<h3>My subheading</h3>`

> `<h4>My sub-subheading</h4>`


## Paragraphs

> `<p>This is a single paragraph</p>`

## Lists

> Unordered lists are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in a `<ul>` element.
Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an `<ol>` element.
Each item inside the lists is put inside an `<li>` (list item) element.

