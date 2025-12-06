---
layout: post
title: "Hello World! My New Blog is Live"
date: 2025-12-04 22:45:00 -0500
---

First Post!
8:30-9:30
JavaScript

Sandbox warm-up:

- made a button in JavaScript that changes text on the page when you click a button

```html
<body>
  <button id="myButton">Click Me!</button>
  <p id="output">Waiting for a click...</p>
  <script>
    const button = document.getElementById("myButton");
    const output = document.getElementById("output");
    function handleClick() {
      output.textContent = "Button was clicked!";
    }
    button.addEventListener("click", handleClick);
```

This inline script creates a button variable `button` from the element with the id `myButton` and an `output` from the element with the id `output`. The function `handleClick` will replace the text content in the `output` variable with "Button was clicked" I added an `addEventListener` to the `button` variable that will run the function `handleClick` when `button` is clicked

Made a calculator in HTML/CSS that resembles the current iOS 25 calculator (black background, round buttons, different color buttons for different functions) No functionality at the moment, will add JavaScript functionality over time.

![calculator](/assets/images/calc.png)

```html
<div>
  <input
    type="text"
    value="12345"
    readonly
    style="width: 128px; text-align: right"
  />

  <table>
    <tr>
      <td><button type="button" class="topLeft">⌫</button></td>
      <td><button type="button" class="topLeft">AC</button></td>
      <td><button type="button" class="topLeft">%</button></td>
      <td><button type="button" class="func">÷</button></td>
    </tr>
    <tr>
      <td><button type="button" class="num">7</button></td>
      <td><button type="button" class="num">8</button></td>
      <td><button type="button" class="num">9</button></td>
      <td><button type="button" class="func">x</button></td>
    </tr>
    <tr>
      <td><button type="button" class="num">4</button></td>
      <td><button type="button" class="num">5</button></td>
      <td><button type="button" class="num">6</button></td>
      <td><button type="button" class="func">-</button></td>
    </tr>
    <tr>
      <td><button type="button" class="num">1</button></td>
      <td><button type="button" class="num">2</button></td>
      <td><button type="button" class="num">3</button></td>
      <td><button type="button" class="func">+</button></td>
    </tr>
    <tr>
      <td><button type="button" class="num">+/-</button></td>
      <td><button type="button" class="num">0</button></td>
      <td><button type="button" class="num">.</button></td>
      <td><button type="button" class="func">=</button></td>
    </tr>
  </table>
</div>
```

`css
body {
  background-color: black;
}
button {
  border-radius: 50%;
  width: 30px;
  color: white;
}
.func {
  background-color: orange;
}
.topLeft {
  background-color: #888888;
}
.num {
  background-color: #484848;
}
  `

Read the first chapter of The Odin Project's lesson on JavaScript
