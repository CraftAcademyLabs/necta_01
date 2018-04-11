## The Body Part 1

The `<body>` tag defines the main content of the web document or rather the section of the document that will be directly visible to your users/visitors.

This means that whatever you place inside the `<body>` will be visible to whoever is viewing the page in their browser. The content can for example be videos, images and text.

Inside the `<body>` you can start by adding a main title with an `<h1>`tag. The `<h1>` tag should be placed just below the opening `<body>`tag.


When you added a main title for your document you can go ahead and include some text. We will put it in a pragraph tag `<p>`.
  ```
  <p> This is my first Web Page .</p>
  ```
This needs of course to be within the `<body>`tags.

To make the words Web Page in the text really stand out lets make it bold using a `<strong>`tag.
  ```
  <p> This is my first <strong> Web Page </strong>. </p>
  ```


So we have a Title and some Text, let us add an Image.
We will use an `<image>`tag and use a local image.  
```
<img src="images/craft_academy.png">  
```
The next attribute we'll look at is `alt`. Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed.
```
<img src="images/craft_academy.png"
     alt="CraftAcademy's logo">  
```
This will display the description when the image cannot be rendered.



## The Body Part 2 - adding some structure

So we have added some basic content. Now it is time to give our page some structure.
We will start by adding an `<header>` to our document. 

A `<header>`tag represents a group of introductory content. If it is a child of `<body>` it defines the global header of a webpage, but if it's a child of an `<article>` or `<section>`it defines a specific header for that section.

```
<header> 
</header>
```

We will also add a`<footer>` which will contain end content for the page.
```
<footer> 
</footer>
```

`<main>`tag is for content unique to this page. Use `<main>` only once per page, and put it directly inside `<body>`. Ideally this shouldn't be nested within other elements.
    
```
<main>
</main>
```

`<article>` tag encloses a block of related content that makes sense on its own without the rest of the page for example an article or blog post. 
```
<main>

  <article>
  </article>

</main>
```

Lets add some content in this block. 

```
<main>

  <article>
    <h2> Heading </h2>
    
    <p> Some text </p>
    
    <h3> Subsection </h3>
      
    <p> Some more text </p>
  </article>

</main>
```
     


## The Body Part 3 - navigation, listing & non-semantic wrappers 

So we want our users/visitors to be able to navigate our site. We will make that possible by adding a navbar using the `<nav>` tag, which contains the main navigation functionality for the page. 

```
    <nav>

    </nav>
``` 

So we now have a navbar and we want to fill it with some links to give it some purpose. To do that we are going to use the `<ul>`tag, the `<li>` tag and the `<a>`tag. 

 The `<ul>` tag for wrapping an unordered list. Unordered lists are used to mark up lists of items for which the order of the items doesn't matter. If the order do matter you will use the `<ol>` tag instead. But for now lets go use the `<ul>` tag. 
 The `<li>` tag List item 
 The `<a>` tag anchor tag will make the piece of text it wraps around into an hyperlink.
 href: This attribute specifies as its value the web address that you want the link to point to; where the browser navigates to when the link is clicked. For example, href="https://www.craftacademy.se/"

```
    <nav>

      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>

    </nav>
``` 


Another common object you can find in a navigation bar is a search form. 
`<form>` tag 
`<input>`tag   



```
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>


       <form>
         <input type="search" name="s" placeholder="Search">
         <input type="submit" value="Go">
       </form>
    </nav>
```




`<div>` tag is a block level non-semantic element, which you should only use if you can't think of a better semantic block element to use, or don't want to add any specific meaning. For example, imagine a shopping cart widget that you could choose to pull up at any point during your time on an e-commerce site:


`<span>`tag is an inline non-semantic element, which you should only use if you can't think of a better semantic text element to wrap your content, or don't want to add any specific meaning. For example:
