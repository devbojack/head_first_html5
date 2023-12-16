# Introducing JavaScript and the DOM: A Little Code

### Declaring a variable

JavaScript has dynamic typing. You don't have to specify a type. s

```
var winners = 1;
var name = "Bojack";
var isEligible = true;
var GPA = 4.0;
```

- // This is a js comment
- White space doesn't matter
- Once you have a variable created, you can change its value at any time, or even change it to a value that has a different type. 
```
var scoops = 5;
var scoops = true;
var scoops = undefined;
```

### Naming

```
var thisIsNotAJoke;
var _iLoveBasics;
var $importantVar;
var my4Smiles;
var cost$;
var vitamin_B_12;
```

**NOTE:**
Using the $ at the beginning of a variable name, like $myVar, is a valid naming convention in JavaScript. However, it's not a convention widely adopted in standard JavaScript programming; it's more commonly associated with certain libraries or frameworks, particularly jQuery.

**In the context of jQuery**:<br>
It's a convention used to denote variables that hold jQuery objects or elements selected from the DOM. For example:
```
var $element = $('#myElement');
```
This convention helps developers quickly identify that the variable contains a jQuery object or that it's being used in conjunction with jQuery-related operations.

### Expressions
![](/chapter2/images/expressions.jpeg)


**for loop or while loop**<br>
***for loops*** get used more for iterating over a fixed number of values (say, over the items in a shopping cart), and ***while loops*** are used more to loop until a condition is met (say, giving the user a test until he gets it right).

### Making Decisions
![](/chapter2/images/if_decisions.jpg)

## Adding JavaScript

### Place your script inline, in the &lt;head&gt; element.
The most common way to add code to your pages is to put a &lt;script&gt; element in the head of your page. When you add JavaScript in the &lt;head&gt; element, it is executed as soon as the browser parses the head (which it does first!), before it has parsed the rest of the page.

### Add your script by referencing a separate JavaScript file.
You can also link to a separate file containing JavaScript code. Put the URL of the file in the src attribute of the opening &lt;script&gt; tag and make sure you close the script element with &lt;script&gt;. If you’re linking to a file in the same directory, you can just use the name of the file.

### Add your code in the body of the document, either inline or as a link to a separate file.
You can put your code right in the body of your HTML. Again, enclose your JavaScript code in the &lt;script&gt; element (or reference a separate file in the src attribute). JavaScript in the body of your page is executed when the browser parses the body (which it does, typically, top down).

![](/chapter2/images/add_js.jpeg)
