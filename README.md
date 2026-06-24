# Unit 2: HTML

### 🎯 Objectives
- Understand the purpose and structure of HTML.
- Create HTML tags on a webpage.

## Table of Contents

1. [Do Now](#do-now)
2. [HTML Tags Introduction](#html-tags-introduction)
3. [Code Along](#code-along)
4. [Code Solo](#code-solo)


## Do Now

After opening the index.html file and completing the tasks, be ready to discuss the following:

1. What happened when you added text to the code? Where did it show up?
2. What was different about the text between the `<h1>`’s and the `<p>`’s?

## HTML Tags Introduction

HTML is a computer language that is used to create the structure for web pages on the internet. Like humans, computers understand many languages, and today, we'll dive into HTML (HyperText Markup Language), which is used on virtually every website you visit!

HTML is created with tags using angle brackets. The tag name goes inside the bracket. Closing tags go at the end of your content and need a slash before the tag name.

There are over 100 HTML tags that allow you to add various elements to a webpage like headers, images, links, lists, videos, and more.

Here are some HTML tags we'll practice today:

- Paragraph: `<p> </p>`
- Headings: `<h1> </h1>` (up to `<h6> </h6>`)
- Button: `<button> </button>`
- Ordered List: `<ol> </ol>`
- Unordered List: `<ul> </ul>`
- List Item: `<li> </li>`
- Break: `<br>`
- Input: `<input>`

Remember, if you want content to show up on the webpage, it MUST be nested inside the `<body>` tag.

## Code Along

Open the `code-along.html` file and complete the tasks. As I write code, make sure you are writing along with me. 

## Code Solo

Next, open the `code-solo.html` file and complete the tasks. Again, as I write code, you should also be writing along with me.

# HTML Pt 2

## Do Now

For this activity, you will be editing a website about sloths which is missing some information. Open the index.html file and complete these tasks:

- Create an `<h1>` tag which says “Sloths!”
- Create a `<p>` tag which says “Sloths are the slowest animal in the world”

## Anchor and Image Tags

Wow, you did great with those `<h1>` and `<p>` tags! Now, let's have some fun with other cool tags – `<a href…>` and `<img src…>` tags. 
<br>

### Did you say anchor?

Yes! The `<a href…>` tag is like a magic portal on a webpage. It's called an **anchor tag**, and it lets us hop around from one web page to another, or even different parts of the same page.

When you see a clickable word or picture on a webpage that takes you somewhere else when you click it, that's an anchor tag doing its thing!

But how does the anchor tag know where to take us? That's where **attributes** come in. Think of them like special instructions we give to our HTML elements. 

For an anchor tag, we use an attribute called `href` that holds the web address (URL) of where we want to go. It looks something like this: 

```html
<a href="https://www.codenation.org">Code Nation!</a>
```

In this example, "Code Nation!" is what we'll see and click on the webpage, and "https://www.codenation.org" is where we'll go when we click it.
<br>
<br>

### Picture Time with `<img>` tag

The `<img>` tag allows us to add an image to our website. But how does it know which image to show? 

Just like the anchor tag uses the `href` attribute, the `<img>` tag uses an attribute called `src` (short for source). The `src` attribute holds the address of the image we want to show.

Unlike most tags, the `<img>` tag doesn't need a closing tag. It's what we call a **self-closing tag**.

Here's what it looks like:

```html
<img src="https://www.example.com/image.jpg">
```


