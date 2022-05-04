# Fundemental terms

## HTML CSS and JavaScript
HTML is hyptertext markup language
- Skeleton/Structure
- define the building blocks of the layout
- image, heading text, text, icons.
- adds the building blocls

CSS is cascading stylesheet
- pretty walls, windows and tiles
- aesthetics mainly and visual effects
- makes text bold, makes images round, adds padding, changes colour of the icons
- can make animations

Javascript
- Functionality lets you actually do things

HTML is a markup language
CSS is a styling language
JAVASCRIPT is a programming language

you cannot use HTML and CSS to tell computers what to do, you can define webpages and style them, thats what javascript does

## FRAMEWORKS

React is not a framework it is a library. it is a tool for repetitive tasks

##

URL: Uniform resource locator
HTTP: Hypertext transfer protocol. it tells the server what it is looking for and where it should get it from. server recieved the message and sends it back to the client, its called an HTTP request. then the client sends a response

the browser reads the HTML code then constructs a DOM or Document Object Model. Model that represent the objects or element in the model.

as the browser is reading it, it looks at the resources needed to load it, for each resource it will send seperate URL requests to the server. Once it has everything it will render the website 


## markup tag guidelines

HTML files contain a set of tags e.g. <head></head>, <title></title>, <em></em>
Tags are case insensitive, but the convention is to write them in lowercase
All HTML tags are enclosed in angled brackets: ‘<’ and ‘>’
Tag elements often come in pairs. That is, you have a beginning tag and an ending tag e.g. <html></html>. Beginning tags mark the start of a tag element and closing tags mark the end of a tag element i.e. a paragraph starts here (<p>) and ends here (</p>)
Some tags do not need to be closed as browses are smart; it is obvious to the browser that once a new tag starts, the unclosed tag must have ended. After all, certain tags cannot be nested inside other tags. E.g. <p>, <html> and <body>
About the Tags

DOCTYPE declares the type of document you are writing. If this tag is missing, the browser will try to guess the type. Including the DOCTYPE is good practice for backward compatibility with older browsers. DOCTYPE html indicates the document is type HTML5

<html> tells the browser this is the start of an HTML document and </html> tells the browser this is the end of the HTML document

<head> represents an area for heading information e.g. title and meta information (data about data). Heading information is not displayed in the browser window except the title.

<title> contains the title of your document. The title is displayed in the browser's caption:
HTMLa5tags.png

<body> contains text that will be displayed in the browser

<h1>, <h2>, <h3> represent headings. <h1> is the largest heading and <h6> is the smallest heading

<ol> defines an ordered (numbered) list. Inside the <ol> tag, you need to mark the individual list item element by using the <li> tag (list items)

<ul> is similar to <ol> except it defines an unordered list. This means individual <li> tags will define bulleted list items

<p> is a paragraph tag with an automatic line break afterwards

<em> defines text to be emphasised (the browser default displays this tag with an italic effect)

<strong> mark-up important text (the browser default displays this tag with a bold effect)

Notice we can also have nesting of tags to define an emphasised and important text. This is common in HTML: <strong><em> ...</strong></em>


to go down a folder you do "../image.png"

to navigate to another folder "foldername/image.png"

to go to the same folder "image.png"