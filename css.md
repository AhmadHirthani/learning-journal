## CSS
### What is CSS?
CSS is a shortcut for Cascading Style Sheets. CSS is responsible for the apperance for each element in HTML page. Thanks to CSS we can change the font color, font size, element color or background color for any element in HTML page

### How to use CSS?
We have 3 ways that we can use to use CSS. The first one is by adding the style as attribute inside the element tag, the seond one is by initlizing style element in the head of HTML document, the third one is by creating a new file with the extention .css.

### How to spicify the targeted element?
We have many ways to target the elements and we will explain these ways by examples:

#### Example1
h2{
    color:red;
}
This example will change the color of all h2 elements in the document.

#### Example2
article h2{
    color:red;
}
This example will change the color of h2 elements inside the article only.

#### Example3
h2,h3{
    color:red;
}
This example will change the color of all h2 and h3 elements in the document.
