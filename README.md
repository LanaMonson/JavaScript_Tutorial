# JavaScript_Tutorial
from w3schools

A JavaScript function is a block of JavaScript code, that can be executed when "called" for.
JavaScript Functions and Events: a function can be called when an event occurs, like when the user clicks a button.

JavaScript Display Possibilities
JavaScript can "display" data in different ways:
-	Writing into an HTML element, using innerHTML.
-	Writing into the HTML output using document.write().
-	Writing into an alert box, using window.alert().
-	Writing into the browser console, using console.log().


Using innerHTML
To access an HTML element, JavaScript can use the document.getElementById(id) method.
The id attribute defines the HTML element. The innerHTML property defines the HTML content:
Ex:
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My First Paragraph</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 5 + 6;
</script>

</body>
</html>


