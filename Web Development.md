# How Does the Internet work?
The internet is just a bunch of wires that connects up different computers, but it's just on a much bigger scale, connecting up all the computers in the world

When two or more computers are connected they can talk to each other and and transfer data through the wire.

## Servers
Some of these computers have a very special job they have to be online 24/7, ready to serve you all the data and files that you are requesting when you try to access a website, and these are called **servers**. They serve you all the data and files you need to be able to access and interact with certain websites.
## Client
Any computer that a user would use to access the internet is called a **client**.

When you search of a website(e.g www.google.com) on your browser the browser sends this message to your **ISP (Internet Service Provider)**  your ISP then relays that message to a **DNS (Domain Name System)** server, a DNS server is basically a phone book, the DNS server will look up in its Database to find the exact IP address of that website that you're trying to access. 

> Every single computer that is connected to the internet has an IP address, it kind of like a postal code for your computer, so that when people need to send and receive files on the internet each computer can be located and contacted using their unique IP address.

Once the DNS server finds that IP address, it will send it back to your browser through the ISP over the internet. then you can make a direct request to that address. And what lives at that address (the google servers), and they will be able to send you back all the files and data you need to be able to view the google home page. 

nslookup.io shows you the ip address of any website

## Under Sea Cables
There are these massive undersea cables connecting all the continents on Earth 

At **submarinecablemap.com** you can see all these cables and see the ones that connect you up to the internet
The cable use fibre optic technology to send signals 



# How Do Websites Actually Work?

Once you find out the IP address of a website you can directly hit up the server computer for the website that you want to view and they'll send you all the files and Data for your browser to be able to render it on screen.

Now, the data that you receive from that server usually consist of three types of files (Code Files) **HTML**,  **CSS** and **JavaScript** 


The HTML code file is responsible for the content in your website 

> if the website was a house the HTML would be the actual bricks of the house. it's the raw materials that makes up your house. 

Similarly, the HTML file contains the content of your website, like the text content, images, buttons or links.


The CSS file determines how your website will look it is responsible for styling your website. It targets all the content in your website that you created using HTML and applies the styling to those elements.

The second type of files are the CSS files and these are responsible for styling your website like the color of the walls or the shape of your door.

The CSS file determines how your website will look
like what color will the background of the page be, or will the buttons have rounded corners?

it targets all the content in your website that you created using HTML , for example the text or the buttons and applies the styling to those elements.


JavaScript
This is the code that allows the website to actually do things, or have functionality. 

> So if you are building a house this would be like adding light bulbs that can turn on and off or putting in a cooker that can actually turn on a fire to heat your food. 

The JavaScript code turns a static website which has pretty images or text into something that a user can actually interact with 
For example, send email in Gmail or post your breakfast on Instagram. 
It allows your website to actually do things and become functional, not just something pretty to look at

The Browser is a piece of Software that specialise in dealing with these files 

## How to Get the Most Out of the Course
Watch the video First (pause around 10 minutes)
Try and Understand what's going on
Why the code is being written and understand the purpose of the code rather than trying to type along at the same pace

Once you've understood what those 10 minutes are about, 
then go to your computer and type out the code and try to replicate what happened in the 10 minutes. 



We are learning programming not how to type fast if you want to learn how to type fast go to keybr.com 
typing code out faster does not make you a better programmer


Taking notes
Cornell Note Taking System

use 
google and stackoverflow


thurrott.com


# What is HTML
## Introduction to HTML

Html Stands for **HyperText Markup Language** 

HTML Defines the content and structure of the website


HyperText refers to the pieces of text which can link to other documents in the website.
So these pieces of text are hypertext or hyperlinks, and they are the foundation of how an HTML website works 

Markup Language
is a Language tell how thing should be done
like what should be bold, what should be underlined e.t.c 

Markup is done through HTML Tags
there are many many tags in html
but you're only going to be using some of the most important ones 
eg h1 -h6, p 


# The Heading Element
## `<h1> to <h6>`


A heading Element look like this 

`<h1>Hello World</h1>`

it starts of with what's called an opening tag `<h1>`  and it ends with what's called a closing tag `</h1>`

the difference between the opening tag and the closing tag is that the closing tag has a forward slash `/` 

What goes between these two tags is the content of that particular HTML element in this case `Hello World`  

in this case we want to create a `h1` heading that contains the words, "Hello World"


## `<Tag>` vs Element

Tags refers to anything that's inside an angle bracket is a tag

`<h1>`  Opening Tag  

`</h1>` Closing Tag

### Element

The entire thing is an element. 

That includes 

the Opening Tag `<h1>`  

the content  `Hello world` and 

the Closing Tag `</h1>`

## Purpose of the Heading Element

the idea comes from book binding (Table of content)

There are six levels of Headings in HTML 

```html
<h1>Heading 1</h1>

<h2>Heading 2</h2>

<h3>Heading 3</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>
```


> There is no Heading 7

>There is no such thing as `h7` that does not exist


Once you've gone to heading six that the end
As defined by the HTML people 
An anything that is lower in importance you would start using a different type of tag

if you create a tag that starts with an `h1` and then you end with a different one like an `h6` then that's not going to work either.

if we were to run this code
we would get different heading levels and by default, they would be styled to have different sizes. the Level 1 headings are the biggest and the Level 6 headings are the smallest  


## Don't & Do

It is not good practice to have more than one`h1`, Because the `h1` is the very top-level heading. (Imagine the `h1` as the book title and the table of contents as including the other parts.) 

Don't have more than one `h1` instead if you need another level of heading, then go to the `h2` or `h3` or all of the other one up until `h6`. 

Don't skip a level 
When you are creating heading elements don't go straight from `h1` to `h3` if you have an `h3` there should also be an `h2` somewhere on that web page. 

go in order 
when you have an `h1` that you've created and then you realize you need another heading, then go to an `h2` an so on and so forth 

Don't jump between the different level headings.

These are not things that will break your code.
Your website will still look fine even if you break all these rules,
but they're just rules for convention.

you can learn more about the HTML element on 

**Mozilla Developer Network Web Docs** and they have documentation for all of the HTML elements that exist. You get more details about things that you need know and they show you some interactive examples of how it all works 

if you're going to use a new element that you haven't seen before and you don't know how it works you can take a quick look at the docs and seeing some examples about how they're used  

# The Paragraph Element
## `<p>`

`<p>This is a paragraph </p>`

it has the opening tag content and the closing tag

