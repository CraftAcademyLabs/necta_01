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

`<footer>` represents a group of end content for a page.

`<header>`tag represents a group of introductory content. If it is a child of <body> it defines the global header of a webpage, but if it's a child of an <article> or <section>.

`<footer>`tag

`<main>`tag is for content unique to this page. Use <main> only once per page, and put it directly inside <body>. Ideally this shouldn't be nested within other elements.
    `<article>`tag encloses a block of related content that makes sense on its own without the rest of the page (e.g. a single blog post.)
      `<h2>`tag
      `<p>`tag
      `<h3>`tag
      `<p>`tag

`<div>`tag
`<span>`tag

## The Body Part 3 - navigation and listing

`<nav>` contains the main navigation functionality for the page. Secondary links, etc., would not go in the navigation.

`<ul>` tag
`<ol>`tag
`<li>` tag
