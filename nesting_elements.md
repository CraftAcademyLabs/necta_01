
## Nesting Elements 



The `<div>` tag defines a division or a section in an HTML document. This element does not have any semantic meaning, it is for pretty much any content that you want to divide from other content, often used as a container for other HTML elements to style them with CSS or to perform certain tasks with JavaScript.

Here we are going to work with `<div>` tags and practice nesting. In order to see our different divs more clearly we have a CSS style sheet prepared. To make use of this we will start by adding the link to the stylesheet in our document. 


```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="scrimba_index.css">
    <title></title>
  </head>
  </html>
```


Now we can add our first `<div>`. We will put it inside of the `<body>` element. In order to connect this specific `<div>` to specific CSS we will give it the `class="purple"`. 

 
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">  
    <link rel="stylesheet" href="scrimba_index.css">
    <title></title>
  </head>
  
  <body>
  	<div class="purple"></div>
  </body>

</html>
```


Now we will add another `<div>` next to it. 

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">  
    <link rel="stylesheet" href="scrimba_index.css">
    <title></title>
  </head>
  
  <body>
  	<div class="purple"></div>
  	<div class="orange"></div>
  </body>

</html>
```

Now we have two seperated `<div>` tags. Lets take the last one and add it inside the first one, nesting the elements. 

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="scrimba_index.css">
    <title></title>
  </head>
  
  <body>
  	<div class="purple"> 
      <div class="orange">
      </div> 
    </div>
  </body>

</html>
```

Now it's your turn to play around with this code. Have fun. 


