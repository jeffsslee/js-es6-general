# js-es6-general

Javascript ES6 general study

# Javascript Basic

### How to add js to html

- <span style="color:brown;background:#e9e9e9;font-weight:bold">`<script> ~~ </script>`</span>: To do js coding inside script tag
- <span style="color:brown;background:#e9e9e9;font-weight:bold">`<script src="fileLocation" />`</span>: To add js file into the HTML file

### comment

- <span style="color:brown;background:#e9e9e9;font-weight:bold">`// `</span>: Single line comment
- <span style="color:brown;background:#e9e9e9;font-weight:bold">`/*     */`</span>: Multilines comments

# DOM Basic

DOM : Document Object Model

## How to get/access DOM object

### getMethods

- <span style="color:brown;background:#e9e9e9;font-weight:bold">`document.getElementById `</span>
- <span style="color:brown;background:#e9e9e9;font-weight:bold">`document.getElementByClassName `</span>
- <span style="color:brown;background:#e9e9e9;font-weight:bold">`document.getElementByTagName `</span>

### queryMethods

- <span style="color:brown;background:#e9e9e9;font-weight:bold">`document.querySelector `</span>  
  document.querySelector(".className");  
  document.querySelector("#idName");
- <span style="color:brown;background:#e9e9e9;font-weight:bold">`document.querySelectorAll `</span> : document.querySelectorAll("li");

## How to manupulate DOM objects

### contents manupulate

- <span style="color:brown;background:#e9e9e9;font-weight:bold">`textContent`</span> : To add only 'text'
- <span style="color:brown;background:#e9e9e9;font-weight:bold">`innerHTML`</span> : To add text with html  
  h2.innerText = `<span style="color:red">Running</span>`
