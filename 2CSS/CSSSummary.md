**Syntax**

In a .css file (no HTML tags)

selector {
   property: value;
}

 

External Style Sheets

Within the head section of the HTML file:

<head>
   <link rel="stylesheet" href="URL" />
</head>
 

Selectors
/*HTML Tags */
p, strong, h3

/* Classes */
.className

/* IDs */
#idName

 
/* Combining Selectors */
img.stinky:hover {...} /* Applied to the hovered state */
h3.stinky p {...} /* Applied to p tags inside h3 with class="stinky" */
h1, h2, h3, p {...} /* Applied to each specified element */
 

Basic Styles
@font-face {
   font-family: myFirstFont;
   src: url('Sansation_Light.ttf');
}

 
color / background-color:
red;
#f00;


background-image:
url('image.gif');
 

font-family:
verdana, helvetica, sans-serif, serif, arial, times, "times new roman", courier new, courier, monospace, cursive, fantasy;                      

font-size / line-height:
10px;          
12pt;
120%;
Small;         /* like h5 */


font-style:
normal;
italic;
 

font-variant:
normal;
 small-caps;


font-weight:
normal;
 bold;


text-align:
left;
right;
center;
justify;       

text-transform:
capitalize;
lowercase;
uppercase;