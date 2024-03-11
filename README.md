# js-es6-general

Javascript ES6 general study

# Javascript Basic

### How to add js to html

- `<script> ~~ </script>`: To do js coding inside script tag
- `<script src="fileLocation" />`: To add js file into the HTML file

### comment

- `// `: Single line comment
- `/*     */`: Multilines comments

# DOM Basic

DOM : Document Object Model

## How to get/access DOM object

### getMethods

- `document.getElementById `
- `document.getElementByClassName `
- `document.getElementByTagName `

### queryMethods

- `document.querySelector `
  - document.querySelector(".className");
  - document.querySelector("#idName");
- `document.querySelectorAll ` : document.querySelectorAll("li");

## How to manupulate DOM objects

### contents manupulate

- `textContent` : To add only 'text'
- `innerHTML` : To add text with html  
  h2.innerText = `<span style="color:red">Running</span>`

### attribute manupulate

- `setAttribute` : To add attribute to the dom
- `removeAttribute` : To remove attribute from the dom
