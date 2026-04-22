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
