## CSS Basic Layout - connected to basic_css.css

Grid 

Fonts 

Padding 

Alignment 

Position 

Margin 


Basic CSS `<link rel="stylesheet" href="basic_css.css">`


## CSS Elements - connected to scrimba_css.css and scrimba_css.html


We are going to add some CSS elements in order to style our web site. CSS elements are entities defined by CSS authors that contain specific values to be reused throughout a document.

We have already added some HTML and now we want to style it. Let's start with the basics. We have already prepared a stylesheet with basic CSS for you, let's have a look at it. (Go through and let them test out different fonts and font sizes.)


Now we want our web site to pop a little bit more. Let's add some colours. 

Import this to scrimba_css.css

```
html, body {
    background: #F0F8FF;
    color: #008B8B;
}

h1, p {
    color: #9932CC;
}

#navbar a {
    color: #008B8B;
}

.item {
    background: #FFB6C1;
}

button {
    background: #008B8B;
    color: 	#FFFFE0;
}

```  

This won't take effect though without being linked with the HTML page. 

Let's add `<link rel="stylesheet" href="scrimba_css.css">` to our scrimba_css.html file and our home_css.html. 

Save and refresh the page. 

Now it is your turn to play around with the colours. 

ID vs Class 

Modifying our items on our portfolio page. It would be nice to make the corners rounded. 
So we'll add a border radius the item CSS element `border-radius: 25px;`


