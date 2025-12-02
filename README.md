# APTASK1
Here is a simple and clear path to learn and apply foundational HTML, CSS, and JavaScript concepts, along with practical examples you can try immediately.


---

✅ 1. HTML – Structure of a Webpage

Core Concepts

Tags & elements (<p>, <h1>, <img>, etc.)

Attributes (src, href, alt)

Lists (<ul>, <ol>)

Forms (<input>, <button>)

Divs and semantic tags (<header>, <section>, <footer>)


Try This Example

<!DOCTYPE html>
<html>
<head>
  <title>My First Webpage</title>
</head>
<body>
  <h1>Welcome!</h1>
  <p>This is my first HTML page.</p>

  <img src="https://picsum.photos/200" alt="Random Image">

  <a href="https://google.com">Visit Google</a>
</body>
</html>


---

✅ 2. CSS – Styling the Page

Core Concepts

Selectors (.class, #id, tag)

Colors, fonts, spacing

Flexbox & layout

Hover effects


Try This Example

<!DOCTYPE html>
<html>
<head>
<style>
  body {
    font-family: Arial;
    background-color: #f0f0f0;
  }
  h1 {
    color: #0066cc;
  }
  .btn {
    padding: 10px 15px;
    background: black;
    color: white;
    border-radius: 5px;
  }
  .btn:hover {
    background: gray;
  }
</style>
</head>
<body>
  <h1>Styled Page</h1>
  <button class="btn">Click Me</button>
</body>
</html>


---

✅ 3. JavaScript – Make the Page Interactive

Core Concepts

Variables & data types

Functions

Events (click, input)

DOM manipulation


Try This Example

<!DOCTYPE html>
<html>
<body>

<h2 id="text">Hello!</h2>
<button onclick="changeText()">Click to Change Text</button>

<script>
  function changeText() {
    document.getElementById("text").innerHTML = "You clicked the button!";
  }
</script>

</body>
</html>


---

🎯 4. Combine HTML + CSS + JS (Mini Project)

Here is a simple working project: Color Changer

<!DOCTYPE html>
<html>
<head>
<style>
  #box {
    width: 200px;
    height: 200px;
    background: lightblue;
    margin-top: 20px;
    border-radius: 10px;
  }
</style>
</head>
<body>

<h2>Color Changer</h2>

<button onclick="changeColor('red')">Red</button>
<button onclick="changeColor('green')">Green</button>
<button onclick="changeColor('blue')">Blue</button>

<div id="box"></div>

<script>
  function changeColor(color) {
    document.getElementById("box").style.background = color;
  }
</script>

</body>
</html>
