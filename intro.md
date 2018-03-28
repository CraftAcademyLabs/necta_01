## The Anatomy of a Web Page - HTML

### Doctype
The very first thing that you typically see in an HTML file is the DOCTYPE declaration.

The <!DOCTYPE> declaration tells the browser what type of document the file is and provides an instruction to the browser about what version of HTML the page is written in. I basically ensures that the browser displays the page properly.

After the DOCTYPE, the HTML really begins. This is indicated by the <html> element or tag, as we often will refer to it.

### <html>
The <html> element is the container for all kind of information, both visible to the user in the browser as page content, and information that the user never sees, but is needed to properly display the page.

### <head>

The next thing you’ll encounter in an HTML document is the <head> section.
The stuff that goes into the head section is primarily informational. A it tells the browser certain things about the page such as the title, what characters to use, how to display information about the page for web crawlers and across various social networks, etc, etc. The <head> section. is also where you traditionally load in important external resources.

### Meta tags

Quite often, when you read through the code of an HTML document, you'll find special tags called <meta> in the <head> section.

Meta tags hold metadata about the page. Metadata takes many forms and can include keywords, authors, descriptions, etc. Here are a few notable inclusions:

### charset
The `charset` setting tells the browser which character encoding to use.

UTF stands for stands for Unicode Transformation Format. Basically in today's world there are scripts written in hundreds of other languages, formats not covered by the basic encoding used in the earlier days. Hence, UTF came into existence.

UTF-8 has character encoding capabilities and its code unit is 8 bits. Pretty technical, I know. Therefore we will not look into this any further.

IF you are looking into building websites using, for instance, Chinese or Arabic alphabets and characters, you will need in go a bit deeper into character encoding.

### Open graph

Open graph meta tags allow you to control what content shows up when a page is shared on Facebook and other social networks like Twitter and LinkedIn. There are many Open Graph meta tags that provide different information to Facebook. These tags can be added to your pages, and we'll be covering the most common ones in another section of this course.
