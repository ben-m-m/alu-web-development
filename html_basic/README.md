HTML, basic
 By: Guillaume Salva, CTO at Holberton School
 Weight: 1
 Project will start May 11, 2026 12:00 AM, must end by May 17, 2026 11:58 PM


Resources
Read or watch:

Learn to Code HTML & CSS (until “Creating Lists” included)
Introduction to HTML
MDN
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is HTML
How to create an HTML page
What is a markup language
What is the DOM
What is an element / tag
What is an attribute
How does the browser load a webpage
Requirements
General
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
You are not allowed to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
Your code should be W3C compliant and validate with W3C-Validator
Tasks
0. Structure
mandatory
Create the most basic, simple and valid HTML file called base_index.html

The page should contain:

a DOCTYPE
a head:
with a title
a body
Tips: don’t forget to read all concept pages…

Test the webpage with the official HTML Validator. You will see that it is not happy!

First things first, fix the code in index.html so that it is valid.

You will see that the validator then becomes much happier!

Repo:

GitHub repository: alu-web-development
Directory: html_basic
File: base_index.html
Please review your task manually with the following checklist









File base_index.html exists

base_index.html has <!DOCTYPE html> as first line

base_index.html has <html> tag at the root

base_index.html has <head> tag inside <html>

base_index.html has <title> tag inside <head> (and not empty)

base_index.html has <meta charset="UTF-8"> tag inside <head>

base_index.html has <body> tag inside <html>, after the <head>

base_index.html is W3C valid


1/7 pts
1. Make a cool first webpage
mandatory
Copy your file base_index.html to index.html

Add in the body of the page:

at least 4 paragraphs;
headings (titles) of level 1, 2 and 3, which are represented by <h1>, <h2> and <h3> tags;
a clickable image of your choice (you can use the https://www.holbertonschool.com/holberton-logo.png image, or another one you find on the internet by using its full URL); and it may link to any URL online that you want.
Repo:

GitHub repository: alu-web-development
Directory: html_basic
File: index.html
Please review your task manually with the following checklist









File index.html exists

index.html has at least 4 <p> tags inside the <body>

index.html has a <h1> tag inside the <body>

index.html has a <h2> tag inside the <body>

index.html has a <h3> tag inside the <body>

index.html has a <a> tag inside the <body>

index.html has a <img> tag inside a <a> tag (which creating a clickable image)

index.html is W3C valid


0/7 pts
2. Make a cool other webpage
mandatory
Copy your file base_index.html to tweets.html

Add in the body of the page:

embed at least one tweet (Here’s the official documentation from Twitter about embedding single tweets in a webpage’s HTML code.)
contain a link to your index.html webpage, for users who may go back to your homepage
In index.html, add a link to tweets.html, for users landing on your homepage, who want to see your tweets!

Repo:

GitHub repository: alu-web-development
Directory: html_basic
File: index.html, tweets.html
Please review your task manually with the following checklist








Files index.html and tweets.html are present

tweets.html has the right structure (same as base_index.html)

tweets.html has one embedded Tweet

tweets.html contains a <a> link to index.html

index.html contains a <a> link to tweets.html

index.html is W3C valid

tweets.html is W3C valid


0/6 pts
3. Make a cool website
mandatory
However, in order to start getting consistency throughout the website, all of the HTML files (index.html and tweets.html) must now have the same structure:

The <body> tag of all of your webpages must contain exactly three direct sub-tags in that order: <header>, <main> and <footer>
The <header> tag must contain an unordered list (the <ul> and <li> tags) of links (the <a> tag) to each of your webpages. As you may have understood, this will serve as a navigation for your website.
The <footer> tag must contain one paragraph with the sentence Made by <YOUR NAME> - <a href="<ANY LINK>" target="_blank">here</a>.
The <main> tag must contain two direct sub-tags in that order: <article> and <aside>:
<article> contains the content of your webpage: texts, links, images, tweets, … This is the part of index.html and tweets.html that you have already written.
<aside> contains a single paragraph, just reading for now “placeholder to add comment thread later”.
Repo:

GitHub repository: alu-web-development
Directory: html_basic
File: index.html, tweets.html
Please review your task manually with the following checklist


















index.html and tweets.html exist

index.html has <header> tag inside <body>

tweets.html has <header> tag inside <body>

index.html has <main> tag inside <body>, after the <header>

tweets.html has <main> tag inside <body>, after the <header>

index.html has <footer> tag inside <body>, after the <main>

tweets.html has <footer> tag inside <body>, after the <main>

In index.html, the <header> contains <ul> and <li> of <a> linking to tweets.html

In tweets.html, the <header> contains <ul> and <li> of <a> linking to index.html

In index.html, the <footer> contains Made by <YOUR NAME> - <a href="<ANY LINK>" target="_blank">here</a>

In tweets.html, the <footer> contains Made by <YOUR NAME> - <a href="<ANY LINK>" target="_blank">here</a>

In index.html, the <main> contains <article> tag

In tweets.html, the <main> contains <article> tag

In index.html, the <main> contains <aside> tag, after the <article>

In tweets.html, the <main> contains <aside> tag, after the <article>

index.html is W3C valid

tweets.html is W3C valid


0/16 pts

