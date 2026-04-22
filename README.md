# 2026WebReview

HTML Review

What does HTML stand for?
Hypertext Markup Language

What is the difference between <head> and <body>?
    <head> --> Metadata - read by the browser 
    <body> --> This content DISPLAYED in the browser

Name THREE semantic HTML elements.
<header></header>
<footer></footer>
<main></main>
<nav></nav>
<article></article>
<aside></aside>
<section></section>

What attribute does an <a> tag need to create a link?
    href --> <a href="https://www.google.com">

What is a self-closing HTML tag Give an example
Are tags that doo not have closing tags, also known as Void Elements.
<br>
<img>
<link>
<meta>

What does <!DOCTYPE html> do?
This tells the browser that the file is an HTML file.

Every HTML file has the same SKELETON (Boilerplate, template) structure:

<!DOCTYPE html>
<html>
<head>
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", initial-scale="1.0">
        - Makes the page Responsive
</head>
<body>
    <header>
        <nav>Contains any Navigation bar element</nav>
    </header>
    <h1>Largest heading most important heading. ONLY ONCE per page</h1>
    <!-- All VISIBLE elements go inside the body -->
</body>
</html>

PART 2: Core HTML Elements
Headings 1 - 6
<h1> --> There should be only 1 <h1> per page
<h2> --> section titles, subtitles
<h3> --> sub-sections
<h4>
<h5> --> Fine print (Copyright statements, etc)
<h6> --> Fine print (Copyright statements, etc)

Text elements
<p> --> paragraph  tag
<strong> --> bold/important text - semantic weight
<em> --> italic / emphasized text - semantic weight
<br> --> line break (void element)
<u> --> underline
<hr> --> Horizontal row --> visual line divider (void element)
<span> --> iline element, does not create a line break
<mark> --> highlights text 

HTML Lists

Unordered List - bulleted list
- Used for 
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

Ordered List
- Used for steps, rankings, sequences, etc.
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

Links & Images

How do I create a llink to sllboces.org?
<a href="https://sllboces.org" target="_blank">SLL BOCES</a>

How do I create a link about.html - relative path (page in the same directory)?
<a href="about.html">About</a>

Link to a file in the content folder?
<a href="page.html">Page</a>

A link to another section of the page?
<a href="#about">Jump to the About section</a>

A link to send an email?
<a href="mailto:student@sllboces.org">Email Me</a>

Images
What are the two required attributes for <img> tags?
alt - accessibility text
src - file path to the Image

<img src="images/hero.jpg" alt="Adirondack Mountains in fall">
<img src="images/logo.png" alt="SLL BOCES Logo">

What is hot-linking an image?
-linking to an image somewhere on the internet
-Placeholder images for design purposes
-Replace hotlinks before publishing the site
-Why? If the hotlinked image gets moved, it will break your design

<img src="https://google.com/2/abc/files/images/myGoogleImage.png" alt="my hotlinked image">

Part 3
What is a semantic HTML element?
semantic elements describe the meaning of the content inside of the element, not just the way it looks

Reason why we use semantic elements?
Organization (Teamwork) - allows other developers to more easily read and inderstand your code

Effects the Document Object model - How the browser reads or understands the content

Accessibility - allows screen readers to understand thee structure and meaning behind content.

SEO - Search engine optimization - how search engines rank well-structured pages - moves them higher in the search results

Semantic tags replace the use of <div> tags:
    <div class="header"> vs <header>

Layout Semantic Elements: header, nav, main, sectiom, aside, footer

Content Semantic Elements:
<figure></figure> - image with a caption
<figcaption> - caption for a figure Image
<time> - a date or time value
<address> - contact address info
<mark> - highlighted text
<details> / <summary> - expand and collapse more details
<div> - non-semantic container