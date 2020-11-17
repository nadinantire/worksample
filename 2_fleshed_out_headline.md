# Objective
this course is teaching about writing the instructions which a computer follows to enable it to store knowledge, process knowledge, and communicate knowledge with the outside world. some one who complete this leasons he/she will be able to design html page and css, get basic to javascript and ruby, leaner will be able to push task done to github. 
# Introduction

What is HTML?
 HTML is the language in which most websites are written. HTML is used to create pages and make them functional.
 HTML was first created by Tim Berners-Lee, Robert Cailliau, and others starting in 1989. It stands for Hyper Text Markup Language.
 Hypertext means that the document contains links that allow the reader to jump to other places in the document or to another document altogether. The latest version is known as HTML5.A Markup Language is a way that computers speak to each other to control how text is processed and presented. To do this HTML uses two things: tags and attributes.
 Ref:Author:Frank Moraes
     https://html.com/#ixzz6dx9OVQnt

# Creating a Simple Page
<!DOCTYPE html>
<html> 
<head> 
<title>My First Webpage</title>
<meta charset="UTF-8"> 
<meta name="description" content="This is my first website. It includes lots of information about my life."> 
</head> 
<body> 
<h1>Welcome to my webpage</h1> 
<p>Welcome to <em>my</em> brand new website.</p> <p>This site will be my <strong>new</strong> home on the web.</p> 
<a href="/page2.html">Page2</a> 
<img src="testpic.jpg" alt="This is a test image" height="42" width="42"> <p>This website will have the following benefits for my business:</p> <ul> <li>Increased traffic </li>
<li>Global Reach</li>
  <li>Promotional Opportunities</li> 
  </ul> <table> <tr> <td>Row 1 - Column 1</td> 
  <td>Row 1 - Column 2 </td> </tr> 
  <tr> <td>Row 2 - Column 1</td> <td>Row 2 - Column 2</td> 
  </tr> </table>
   </body>
    </html>

Tags are used to mark up the start of an HTML element and they are usually enclosed in angle brackets. An example of a tag is: <h1>.
<tag>
# Basic Construction of an HTML Page.
These tags should be placed underneath each other at the top of every HTML page that you create.
<!DOCTYPE html> — This tag specifies the language you will write on the page. In this case, the language is HTML 5.
<html> — This tag signals that from here on we are going to write in HTML code.
<head> — This is where all the metadata for the page goes — stuff mostly meant for search engines and other computer programs.
<body> — This is where the content of the page goes.

## How To Add Links In HTML
As you may have noticed, the internet is made up of lots of links.

Almost everything you click on while surfing the web is a link takes you to another page within the website you are visiting or to an external site.

Links are included in an attribute opened by the <a> tag. This element is the first that we’ve met which uses an attribute and so it looks different to previously mentioned tags.

The Anchor Tag
The <a> (or anchor) opening tag is written in the format:

<a href="https://blogging.com/how-to-start-a-blog/">Your Link Text Here </a>

## Adding Images

In today’s modern digital world, images are everything. The <img> tag has everything you need to display images on your site. Much like the <a> anchor element, <img> also contains an attribute.

Eg: <img src="testpic.jpg" alt="This is a test image" height="42" width="42">

## Table Markup

<table> 
<tr> 
<td>Row 1 - Column 1</td> 
<td>Row 1 - Column 2 </td> 
</tr> <tr> <td>Row 2 - Column 1</td> 
<td>Row 2 - Column 2</td> </tr> 
</table>

## Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing

<form>
form elements
</form>

## Embed

The <embed> tag defines a container for an external resource, such as a web page, a picture, a media player, or a plug-in application. Browser Support. Element. Attributes. Attribute. Global Attributes. The <embed> tag also supports the Global Attributes in HTML.

<embed type="image/jpg" src="pic_trulli.jpg" width="300" height="200">

With the use of the img tag and CSS, you can do just about anything you want.


-------------------------## CSS FOR PRESENTATION----------------------------

## Introducing Cascading Style Sheets

Cascading Style Sheets, allow you to design and ornament your web pages.
## text formatting

This text is styled with some of the text formatting properties. The heading uses the text-align, text-transform, and color properties.

body {
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}

## Colors and Backgrounds

The background-color property sets the background color of an element. The background of an element is the total size of the element, including padding and border (but not the margin).
Eg: body {background-color: coral;}

## Thinking Inside the Box

 It is achieved by overriding box-sizing with a value of padding-box. Overwriting box-sizing default value with padding-box will “invert” padding, moving it to the inner box of the element. The padding was “inverted” and now you're thinking inside the box!

## Floating and Positioning

 The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

 There are five different position values:

 1. static 
 1. relative
 1. fixed
 1. absolute
 1. sticky

 ## Grid and flexbox
  The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

## Responsive Web Design

Responsive web design is about creating web pages that look good on all devices!
A responsive web design will automatically adjust for different screen sizes and viewports.
Eg: <meta name="viewport" content="width=device-width, initial-scale=1.0">

## Transitions, Transforms, and Animation

Transforms allow us to move or change the appearance of an element on a 2D plane. We will want to use transforms with transitions in order to produce a smooth animation. They are triggered when an element changes state, such as on a hover.

## More CSS Techniques
Most designers and web developers only scratch the surface of the potent language that is CSS. In terms of programming languages, CSS has a fairly simple learning curve. That doesn't mean that CSS isn't a powerful language.

$alternate1 = array(
'bgmast' => 'ddb',
'fgmast' => '000',
'bgmenu' => 'aa7',
'fgmenu' => 'fff',
'bgcont' => 'fff',
'fgcont' => '333'
);

## Modern Web Development Tools

1. Creative Tim provides Bootstrap based design elements, which help you faster your development work. You can create web and mobile apps using this tool.
Envato HTML Templates
1. Envato has a collection of 1000+ readymade HTML5 templates that save you coding time. These templates offer power customization tools and are SEO ready. They offer optimized CSS and JS that improve Page Speed scores.

------------------------## JAVASCRIPT------------------------------


## Introduction to JavaScript

JavaScript was initially created to “make web pages alive”.The programs in this language are called scripts. They can be written right in a web page’s HTML and run automatically as the page loads.Scripts are provided and executed as plain text. They don’t need special preparation or compilation to run.In this aspect, JavaScript is very different from another language called Java.

## Using JavaScript

The HTML <script> Tag
The HTML <script> tag is used to define a client-side script (JavaScript).The <script> element either contains script statements, or it points to an external script file through the src attribute. Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content. To select an HTML element, JavaScript most often uses the document.getElementById() method.This JavaScript example writes "Hello JavaScript!" into an HTML element with id="demo":

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>

## Core

1. Asynchronous Communication
2. Dom creation and modification
3. Loops, Loops, Loops, Loops
4. Dev Tool Debugging
5. Scope
6. Functions and Function Calls
7. Conditional statements
8. Events and Event Handling
9. Reference versus Value variables and Data Types
10. Traversing the DOM – Why Javascript?

## Browser Object Model

The Browser Object Model (BOM) is the core of JavaScript on the web. The BOM provides you with objects that expose the web browser’s functionality.

## Events

HTML events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can "react" on these events.

<element event='some JavaScript'>
<!DOCTYPE html>
<html>
<body>

<button onclick="document.getElementById('demo').innerHTML=Date()">The time is?</button>

<p id="demo"></p>

</body>
</html>

## Document Object Model

The Document object has various properties that refer to other objects which allow access to and modification of document content. ... The way a document content is accessed and modified is called the Document Object Model, or DOM. The Objects are organized in a hierarchy.

What is the DOM?
The DOM is a W3C (World Wide Web Consortium) standard.
The DOM defines a standard for accessing documents: "The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

The W3C DOM standard is separated into 3 different parts:
Core DOM - standard model for all document types
XML DOM - standard model for XML documents
HTML DOM - standard model for HTML documents

The DOM represents an HTML or XML document as a hierarchy of nodes. Consider the following HTML.

<html>
    <head>
        <title>JavaScript DOM</title>
    </head>
    <body>
        <p>Hello DOM!</p>
    </body>
</html>

## Data

 There are six basic data types in JavaScript which can be divided into three main categories: primitive (or primary), composite (or reference), and special data types. String, Number, and Boolean are primitive data types. Object, Array, and Function (which are all types of objects) are composite data types.
 Eg:

 var a = 'Hi there!';  // using single quotes
 var b = "Hi there!";  // using double quotes

 var car = {
    modal: "BMW X3",
    color: "white",
    doors: 5
 }

 ------------------------------## Ruby---------------------------------

 ## Introduction
 This is a small Ruby tutorial that should take no more than 20 minutes to complete. It makes the assumption that you already have Ruby installed. (If you do not have Ruby on your computer install it before you get started.)

 Interactive Ruby
 Ruby comes with a program that will show the results of any Ruby statements you feed it. Playing with Ruby code in interactive sessions like this is a terrific way to learn the language.

 Open up IRB (which stands for Interactive Ruby).

 If you’re using macOS open up Terminal and type irb, then hit enter.
 If you’re using Linux, open up a shell and type irb and hit enter.
 If you’re using Windows, open Interactive Ruby from the Ruby section of your Start Menu.
 irb(main):001:0>
 Ok, so it’s open. Now what?

 Type this: "Hello World"

 irb(main):001:0> "Hello World"
 => "Hello World"
 Ruby Obeyed You!
 What just happened? Did we just write the world’s shortest “Hello World” program? Not exactly. The second line is just IRB’s way of telling us the result of the last expression it evaluated. If we want to print out “Hello World” we need a bit more:

 irb(main):002:0> puts "Hello World"
 Hello World
 => nil
 puts is the basic command to print something out in Ruby. But then what’s the => nil bit? That’s the result of the expression. puts always returns nil, which is Ruby’s absolutely-positively-nothing value.

 Your Free Calculator is Here
 Already, we have enough to use IRB as a basic calculator:

 irb(main):003:0> 3+2
 => 5
 Three plus two. Easy enough. What about three times two? You could type it in, it’s short enough, but you may also be able to go up and change what you just entered. Try hitting the up-arrow on your keyboard and see if it brings up the line with 3+2 on it. If it does, you can use the left arrow key to move just after the + sign and then use backspace to change it to a * sign.

 irb(main):004:0> 3*2
 => 6
 Next, let’s try three squared:

 irb(main):005:0> 3**2
 => 9
 In Ruby ** is the way you say “to the power of”. But what if you want to go the other way and find the square root of something?

 irb(main):006:0> Math.sqrt(9)
 => 3.0
 Ok, wait, what was that last one? If you guessed, “it was figuring out the square root of nine,” you’re right. But let’s take a closer look at things. First of all, what’s Math?

Modules Group Code by Topic
Math is a built-in module for mathematics. Modules serve two roles in Ruby. This shows one role: grouping similar methods together under a familiar name. Math also contains methods like sin() and tan().

Next is a dot. What does the dot do? The dot is how you identify the receiver of a message. What’s the message? In this case it’s sqrt(9), which means call the method sqrt, shorthand for “square root” with the parameter of 9.

The result of this method call is the value 3.0. You might notice it’s not just 3. That’s because most of the time the square root of a number won’t be an integer, so the method always returns a floating-point number.

What if we want to remember the result of some of this math? Assign the result to a variable.

irb(main):007:0> a = 3 ** 2
=> 9
irb(main):008:0> b = 4 ** 2
=> 16
irb(main):009:0> Math.sqrt(a+b)
=> 5.0
 As great as this is for a calculator, we’re getting away from the traditional Hello World message that beginning tutorials are supposed to focus on… so let’s  go back to that.
Ref:https://www.ruby-lang.org/en/documentation/quickstart/
date: 16 November, 2020

----------------------------## Ruby algorithms------------------------------
## Ruby algorithms
Introduction
The basic idea of a data structure is to store data in a way that meets the needs of your particular application. You might be inclined to store a particular kind of data in one giant array, but it would be rather time consuming to locate a specific value if you had a significant number and depth of items. So you need to look to other options.

You’ve already had a brief introduction to algorithms over some of the other lessons and you even got to write your own Merge Sort algorithm in the last project. You’ll find that sorting algorithms are quite common. Another major area for algorithms is in search, where milliseconds count. When you’re searching through enormous troves of data, the quality of your search algorithm is incredibly important. Traversing a data tree looking for a particular element is a related problem that’s common in data intensive applications.

Depending on the application, there are a batch of other basic data structures available to help you out. The differences between them typically have to do with trade-offs between how long it takes to first populate the structure, how long it takes to add or find elements, and how large the structure is in memory.

We’ll save the specifics of data structures for more computer-science-oriented courses, but this introduction should again expand your toolbox slightly so you can identify and solve certain problems where plain old Arrays, Hashes and Sets don’t quite cut it. New structures and strategies will be particularly relevant, for instance, when you’re trying to search through a large batch of data for a particular value or plan out a strategy several moves in advance.



---------------------- ## Git/Github ----------------------------------


## Git / Github
Resources: 
According to the latest Stack Overflow developer survey, more than 70 percent of developers use Git, making it the most-used VCS in the world. Git is commonly used for both open source and commercial software development, with significant benefits for individuals, teams and businesses.

Install git and create a GitHub account 
The first two things you'll want to do are install git and create a free GitHub account.

Follow the instructions here to install git (if it's not already installed). Note that for this tutorial we will be using git on the command line only. While there are some great git GUIs (graphical user interfaces), I think it's easier to learn git using git-specific commands first and then to try out a git GUI once you're more comfortable with the command. 

Once you've done that, create a GitHub account here.  (Accounts are free for public repositories, but there's a charge for private repositories.)

 1. Create a local git repository
 2. Add a new file to the repo
 3. Add a file to the staging environment
 4. Create a commit
 5. Create a new branch
 6. Create a new repository on GitHub
 7. Push a branch to GitHub
 8. Create a Pull Request (PR)
 9. Merge a PR
 10. Bask in your git glory

 Git command:
or create a new repository on the command line
echo "# TvetSchool" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nadinantire/TvetSchool.git
git push -u origin main
                
…or push an existing repository from the command line
git remote add origin https://github.com/nadinantire/TvetSchool.git
git branch -M main
git push -u origin main

## Summary

design responsive html page with css.
write script code to html page.
get basic to ruby.
create branches , add  new contentto existing repo and push task done to github account. 





