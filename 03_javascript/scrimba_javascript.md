
## JS part 1 - introduction 

JavaScript is a programming language that allows you to implement complex things on web pages. 



HTML file 

The `<script>`tag 


```
<html>
    <head>
        <script src="scrimba_javascript.js"></script>
    </head>
    
    <body>
        <div id="hello">Hello world!</div>
        <div id="craft">Coding as a Craft.</div>
    </body>
</html>
```

JS file 

```
// document object model
// the DOM

// getElementById

var node = document.querySelector('#hello');

node.innerHTML = "Hi, <b>Sophie</b>!";

```


## JS part 2 - adding a form to our web site 

HTML file 

```
<input type="text" id="myInput"></input>
<button id="myButton">Submit</button>
```


JS file
0
```
var inputValue = '';
var myButton = document.getElementById('myButton');
var myInput = document.getElementById('myInput');

myInput.onkeyup = function(event) {
    inputValue = event.target.value;
}

myButton.onclick = function(event){
    console.log('inputValue: ', inputValue);
}
```

