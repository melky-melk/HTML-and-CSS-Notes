to set the width/size of the screen
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1" />

meta viewport let sthe browser know the dimensions and scaling, knows how vig the screen is

If you are designing for a  480 pixels of width then you can use the following markup.  If the screen is more that 480px wide,  instead of zooming in the the browser will expand the viewport:

<meta name="viewport" content="width=480, initial-scale=1">

The @media rule allows different style rules for different media in the same style sheet. An example of usage:
```css
@media screen
{
   div#mainContent
 {
       font-family: verdana;
       font-size: 14px;
 }
}

 
@media screen, print
{
   div#mainContent
 {
       font-weight: bold;
 }
}
```

Alternatively, media types can be specified within the link tag

<link rel="stylesheet" media="screen" href="style320.css"/>


this is like a psudeo if statement in css. (but you should use javascript)
```css

@media media-type and (media-feature-rule) {
  /* CSS rules go here */
}

@media screen and (min-width: 480px) and (orientation: portrait)
{
   #nav li
   {
       float: right;
       margin: 0 0 0 .5em;
       border:1px solid #000000;
   }
}
```

<link rel="stylesheet" media="screen and (max-device-width: 800px)" href="style768.css"/>

Imported style sheets have the advantage of being conditionally downloaded according to the media attribute. The disadvantage is the lack of browser/device support relative to the other options. 

If you are dealing with devices that can switch orientation, placing media queries all in the one style sheet may be best.

you can make different stylesheets for every media type


In this course, we recommend you to use media queries in your style sheets.

# flexible grids	
when making chunks or blocks of objects, its best to use percentages rather than pixel measurements


is something needs to be 10px and the total size of the screen is 100px you should use 10% rather than 100%


instead of making it so that every box thing uses float, you can seperate it with colums

.container
 { 
 column-count: 2;
 } 

