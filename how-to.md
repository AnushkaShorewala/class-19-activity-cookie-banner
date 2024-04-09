# Class-19-Activity-Cookie-Banner

## Follow these steps to implement the cookie banner

1. Review the HTML and CSS for the cookie banner.
   
   HTML:  note the ID's and classes used
   CSS:  note the .banner classes created

2.  Add jquery .js file at the bottom of all the HTML pages - this is already in your scripts sub-directory:
   
     `<script src="scripts/jquery-3.7.1.js"></script>`

3.  Create a cookie-banner.js file in the scripts sub-directory

4.  Add cookie-banner.js file at the bottom of all the HTML pages - after the jquery.js:
   
     `<script src="scripts/cookie-banner.js"></script>`

5. Code the interactivity for the cookie banner using these snippets:

Listen/Respond to Events on an Element - 

    '$("TODO: CSS Selector").click(function() {
    
    /* TODO: JavaScript+jQuery code to respond to "click" event */
    
    });`

Add/Remove CSS Class - 

    `$("TODO: Selector").addClass("TODO: class name");`

    `$("TODO: Selector").removeClass("TODO: class name");`

6.  Make the cookie banner sticky at the top of the page:

`position: sticky;
top: 0;
z-index: 10;`