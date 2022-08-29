<!DOCTYPE html>
<html>
<body>
<!--
    NOTES:
   # avaScript accepts both double and single quotes:
-->

<!--
mOne of many JavaScript HTML methods is getElementById().
The example below "finds" an HTML element (with id="demo"), and 
changes the element content (innerHTML) to "Hello JavaScript":
Example:
-->
<h2>What Can JavaScript Do?</h2>
<p id="demo1">JavaScript can change HTML content.</p>
<button type="button" onclick='document.getElementById("demo1").innerHTML = "Hello JavaScript!"'>Click Me!</button>
<!--
    <button type="button" onclick="document.getElementById('demo').innerHTML = 'Hello JavaScript!'">Click Me!</button>
-->


<!--
    // JavaScript Can Change HTML Attribute Values
    In this example JavaScript changes the value of the src (source) attribute of an <img> tag:
-->
<h2>What Can JavaScript Do?</h2>
<p>JavaScript can change HTML attribute values.</p>
<p>In this case JavaScript changes the value of the src (source) attribute of an image.</p>
<button onclick="document.getElementById('myImage1').src='img/pic_bulbon.jpeg'">Turn on the light</button>
<img id="myImage1" src="img/pic_bulboff.jpg" style="width:100px">
<button onclick="document.getElementById('myImage1').src='img/pic_bulboff.jpg'">Turn off the light</button>


<!--
    // JavaScript Can Change HTML Styles (CSS)
    Changing the style of an HTML element, is a variant of changing an HTML attribute:
-->
<h2>What Can JavaScript Do?</h2>
<p id="demo2">JavaScript can change the style of an HTML element.</p>
<button type="button" onclick="document.getElementById('demo2').style.fontSize='35px'">Click Me!</button>


<!--
// JavaScript Can Hide HTML Elements
    Hiding HTML elements can be done by changing the display style: 
-->
<h2>What Can JavaScript Do?</h2>
<p id="demo3">JavaScript can hide HTML elements.</p>
<button type="button" onclick="document.getElementById('demo3').style.display='none'">Click Me!</button>


<!--
// JavaScript Can Show HTML Elements
    Showing hidden HTML elements can also be done by changing the display style:
-->
<h2>What Can JavaScript Do?</h2>
<p>JavaScript can show hidden HTML elements.</p>
<p id="demo4" style="display:none">Hello JavaScript!</p>
<button type="button" onclick="document.getElementById('demo4').style.display='block'">Click Me!</button>
</body>
</html>
