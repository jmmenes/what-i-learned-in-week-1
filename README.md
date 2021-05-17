
# What I Learned In Week 1 at Code Immersives

&nbsp;

## *CSS*


CSS (Cascading Style Sheets) is what makes web pages look good and presentable. Without it all websites would mostly look plain & very boring with just HTML.

CSS tells the browser how the HTML elements should be displayed. CSS is used to apply colors, determine font, text size, and page alignment.

&nbsp;

There are 3 ways to add CSS (Style) to HTML

1. Inline - Directly into an HTML Element
2. Internal - Using the style element in the head section of the HTML document
3. External - Create a stylesheet with a .css extension and link it in the HTML document, like this:


    <link rel="stylesheet" href="style.css"> 

&nbsp;

## CSS Selectors
In order to style elements, you first have to select them. 3 different ways you can select HTML elements.

1. Element
The first way to select an HTML element is by simply using the name.

*Style Sheet*

    h1 {  
    font-size: 30px;
    }  

    p {  
    color: blue;
    }

2. Class
Another way of selecting HTML elements is by using the class attribute. In HTML, we can assign different classes to our elements.

HTML

    <div class='container'>  
    <h1> This is a heading </h1>  
    </div>


*Style Sheet*

    .container {  
    margin: 20px;  
    }

3. ID
Like classes, we can also use IDs to select HTML elements and apply a style to them. The only difference between class and ID is that one ID can be assigned to only one HTML element.

HTML

    <div>  
    <p id='p1'> Lorem Ipsum blah blah... </p>  
    </div>


*Style Sheet*

    #p1 {  
    color: red;  
    font-size: 12px;  
    }


&nbsp;

## *BASH*

Bash is a command language interpreter. It is available on various operating systems and is a default command interpreter on most GNU/Linux systems. The name is an acronym for the ‘Bourne-Again SHell’.

Shell is a macro processor which allows for an interactive or non-interactive command execution.

What's a Terminal?
It's a program called a terminal emulator. This is a program that opens a window and lets you interact with the shell

Learning command line tools for managing the file system in Bash can give you more speed and control over your workflow.

https://www.hackernoon.com/top-10-bash-file-system-commands-you-cant-live-without-4cd937bd7df1

I was introduced to Bash but I wouldn't say I've learned it just yet. Still need plenty of practice which will happen as I use it more & develop a mind & muscle memory for it.


