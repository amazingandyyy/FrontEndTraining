<a name="top"></a> 

[amazingandyyy](https://amazingandyyy.github.io) > [Front End Training Course](https://github.com/amazingandyyy/FrontEndTraining) > [Materials](https://github.com/amazingandyyy/FrontEndTraining/blob/master/MATERIALS.md)
 
* [Chapter 1 Workplace setup](#setup)
* [Chapter 2 Web = HTML + CSS + JS](#web)
* [Chapter 3 Basic HTML](#html1)
* [Chapter 4 Basic CSS](#css1)
* [Chapter 5 Advance HTML](#html2)
* [Project: Build a XYZ introduction website](#uni_index)
* [Chapter 6 Bootstrap](#bootstrap)
* [Chapter 7 Basic Javascript](#js1)
* [Chapter 8 Javascript Data Structure](#js_data)
* [Chapter 9 Basic jQuery](#jquery1)
* [Project: Trigger changing color](#color_tri)
* [Chapter 10 JSON](#json)
* [Chapter 11 HTTP and AJAX](#http_req)

<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="setup"></a> Chapter 1 Workplace setup [[menu]](#top)

### 1. Browser
- Safari, Chrome, Firefox
- I use [Chrome](https://www.google.com/chrome/browser/desktop/)
    - Click with `⌘ command`, open in new tab
    - shortcut:
        - `⌘` + `T`: new tab
        - `⌘` + `N`: new windows
        - `⌘` + `W`: close tab
        - `⌘` + `R`: refresh page
        - `⌘` + `shift` + `N`: new incognito windows
    - Motivation
    - ColorPicker
    - JSON Viewer
### 2. IDE
- Sublime, Atom, Brackets
- I use [VSCode](https://code.visualstudio.com/)
### 3. Terminal
- Windows: GitHub -> Linux Terminal
- Mac: [iTerm2](https://www.iterm2.com/)
### 4. Utility
- [Lumen for Mac](https://github.com/anishathalye/lumen)
- [Spectacle for Mac](https://www.spectacleapp.com/)
### 5. GitHub
- signup GitHub
- Star and Fork [course repo](https://github.com/amazingandyyy/FrontEndTraining) 
### 6. Mac
- shortcuts:
    shortcut | function |
    --- | ---
    `⌘` + `C`| copy
    `⌘` + `V` | paste
    `⌘` + `Z` | redo
    `⌘` + `S` | save
    `⌘` + `shift` + `Z` | redo redo
    `⌘` + `space` | Spotlight Search

- System Preference
    - Mission Control > Hot Corners > Mission Control/Desktop/Sleep
- About Docker
    - Preference setting
    - Customize
<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->
## <a name="web"></a> Chapter 2 Web = HTML + CSS + JS [[menu]](#top)
- what is HTML/CSS/JS
    - comparison
        - Microsoft Word Software can read `.doc` and `.docx`
        - Microsoft PowerPoint can read `.ppt` and `.pptx`
        - Browser can read `.html` and `.css` and `.js`
    - HTML is just a file format, popular used in mordern browser
    - CSS is just a file format, popular used in mordern browser
    - JS is just a file format, popular used in mordern browser

-  HTML/CSS/JS work together
    format        | What's for                    | comparison  |
    --- | --- | ---
    HTML          | structure/content of the page | text  |
    CSS           | styles those contents         | bold  |
    Javascript    | behavior                      | alert |

<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="html1"></a> Chapter 3 Basic HTML [[menu]](#top)
### 1. What is HTML
- HTML stands for **H**yper **T**ext **M**arkup **L**anguage
- HTML describes the structure of Web pages using to show content in browser
- HTML `elements` are the building blocks of HTML pages

### 2. HTML Basic Structure
![](https://i.imgur.com/aEfWwvT.png)

### 3. Check those popular websites
- open chrome and use `⌘`+`shift`+`J` 
    - [Facebook](https://www.facebook.com/)
    ![](https://i.imgur.com/429EzCD.png)
    - [Youtube](https://www.youtube.com/)
    ![](https://i.imgur.com/HQb1GT8.png)
    - [GitHub](https://github.com/)
    ![](https://i.imgur.com/uJyL9PO.png)

### 4. What you are going to learn about HTML
> You need to learn many tags and understand what they are

> So Let's get crazy mode and learn those tags

> You will need to learn at least 20 tags

### 5. HTML elements and tags
HTML elements are wrap by a open tag and close tag, that's been said, 1 element = 2 tags and contents.
There are hundreds of `<tags>`, but you only need to rememebr the following tags

- The most common used Tags

    |tags | Description 
    --- | ---
    `<html></html>`  | html tag
    `<head></head>`  | head tag
    `<title></title>`  | title tag
    `<body></body>`  | body tag
    `<head></head>`  | head tag
    `<div></div>`  | normal block
    `<h1></h1>` ~ `<h6></h6>` | bold heading
    `<p></p>` | paragraph
    `<span></span>` | no meaning tags
    `<br />` | break a new line
    
- bonus useful Tags

    |tags | result | Description 
    --- | --- | ---
    `<b>`Amazingandyyy`</b>` | **Amazingandyyy** | bold
    `<i>`Amazingandyyy`</i>` | *Amamzingandyyy* | italic
    `<strike>`Amazingandyyy`</strike>` | ~~Amamzingandyyy~~ | strikethrough
    `<button>`Amazingandyyy`</button>` | <dl><button>click mee</button></dl> | button
    `<a href="url"></a>` | <dl><a href="https://www.instagram.com/amazingandyyy/" target="_blank">Instagram</a></dl> | links
    `<input type="text"/>` | <dl><input /></dl> | input
    `<input type="checkbox"/>` | <dl><input type="checkbox"/></dl> | checkbox
    `<input type="date"/>` | <dl><input type="date"/></dl> | checkbox

#### Chapter 3 Resources:  [[menu]](#top)
- [https://www.w3schools.com/html/html_intro.asp](https://www.w3schools.com/html/html_intro.asp)


<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="css1"></a> Chapter 4 Basic CSS [[menu]](#top)

### 1. What is CSS
- CSS stands for **C**ascading **S**tyle **S**heets
- CSS describes how HTML elements are to be displayed in browser
- CSS saves a lot of work. It can control the layout of multiple web pages all at once

### 2. CSS is human-readable
experience what CSS can do and what it works with HTML 
- add a flag to HTML element
    - class
    - id
    - inline style
- CSS can control Size
    - change text size
    - change `div` size
    - change image size
- CSS can control Color
    - change text color
    - change background-color of a `div`

### 3. CSS for styling
- Style text
    - size
    - color
    - font family
        - change font family
        - use google font
            - external css files
            - import google fonts
    - text-decoration
    - text-align

- Style `div`
    - size
    - color
    - border
        - color
        - size
        - radius
    - box-shadow

- Style behaviors
    - :hover
    - :active
    - :visited
    - cursor

### 4. CSS for position
- control div
    - margin
    - padding

    ![](https://i.imgur.com/p9or22x.png)

    - float
    - center


#### Chapter 4 Resources:  [[menu]](#top)
- [https://www.w3schools.com/html/css_intro.asp](https://www.w3schools.com/html/css_intro.asp)


<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="html2"></a> Chapter 5 Advance HTML [[menu]](#top)
### 1. More about HTML tags
- Link
    - link to a page
    - `target="_blank"`, open in new tag
    - link to `#id`
    - `mailto`, send a email
        - customize content

- Form
    - `input` tags
        - text
        - date
        - color
        - file
        - radio
        - checkbox
        - Google for more

    - `button` tags
        - style button tags
            - remove outline
            - remove border

- List
    - unorder list
        - `<ul></ul>`
    - order list
        - `<ol></ol>`
    - `<li>`

- Table
    - `<table>`
    - Google it is the best way
<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="uni_index"></a> Project:  Build a XYZ introduction website
### Hints
- design in a graphic software or powerpoint/keynote
- You may need `table` and `img` tags
- use `h1` and other tags
- push to `GitHub`
- styling button and some details

### demo
<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="bootstrap"></a> Chapter 6 Bootstrap [[menu]](#top)
### 1. What is [bootstrap](https://getbootstrap.com/)
- It is a CSS Framework
    - Framework is a big package of codes that others can use
- It is just an huge External CSS file
    - overwrite Bootstrap
    - [bootswatch](https://bootswatch.com/)
- Why bootstrap
    - icons
    - elements
        - navbar
            - read document
        - Jumbotron
    - grids
- Many more CSS Frameworks
    - Foundation
    - Semantic
    - Skeleton
    - ...

## <a name="js1"></a> Chapter 7 Basic Javascript [[menu]](#top)
- What is javascript
    - so-called JS, Vanilla JS
    - Browser can undertand JS
    - JS is a programming language
        - try some in browser:
            - console.log()
            - Date()
            - alert()
            - prompt()
        - Declare variable
        - Assign value: Assignment Operator
        - Operator
        - functions
        - input/output
- Try console log in chrome
- select and manipulate elements in DOM
    - when triggering `onClick`, run the `function`
    - samples
        - step 1: function & console.log
        ```javascript
            function log(){
                console.log("Hey! Yo")
            }
        ```
        - step 2: `.` dot notation
        ```javascript
            function double(){
                var el = document.querySelectorAll('.css-selector');
                console.log("Value is",el)
                var val = el.value;
                console.log("Value is",val)
            }
        ```
        - final step
        ```javascript
            function double(){
                var el = document.querySelectorAll('.css-selector');
                var val = el.value;
                console.log("double is ",val*2)
            }
        ```

#### Chapter 7 Resources:
- [http://youmightnotneedjquery.com/](http://youmightnotneedjquery.com/)
<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->
## <a name="js_data"></a> Chapter 8 Javascript Data Structure [[menu]](#top)
- Data type
    - string
    - number
    - boolean
    - array
    - object
- Play with object
    - Concept of DOM
    - Understand `.` dot notation

<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->
## <a name="jquery1"></a> Chapter 9 Basic jQuery [[menu]](#top)
- What is jQuery
    - jQuery is a JavaScript Library.
    - jQuery make select and manipulate elements 10x easier
    - import jQuery
- select and manipulate elements in DOM
    - From JS to jQuery
        - Selector
        ```javascript
        // javascript
        document.querySelectorAll('.css-selector');
        
        // jQeury
        $('.css-selector')
        ```
        - Get value
        ```javascript
        // javascript
        document.querySelectorAll('.css-selector').value;
        
        // jQeury
        $('.css-selector').val()
        ```
        - more on [YouMightNotNeedJquery](http://youmightnotneedjquery.com/)

- The order matters
    - About .ready()
    ```javascript
    $(document).ready(function(){
        // do something
    });
    ```
- More extroardinary effect:
    - toggle className:
    ```javascript
    $(el).fadeIn();
    ```
    - Set CSS
    ```javascript
    $(el).css('border-width', '20px');
    ```
    - Fade Element In!?
    ```javascript
    $(el).fadeIn();
    ```

#### Chapter 9 Resources:
- [http://youmightnotneedjquery.com/](http://youmightnotneedjquery.com/)
<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->

## <a name="color_tri"></a> Project: Trigger changing color
### Hints
- you need jQuery to select an element
- add a new className to the element
- make the new className has different CSS style
- build a reset button to remove the className

<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->
## <a name="json"></a> Chapter 10 JSON [[menu]](#top)
- what is JSON
    - JSON stands for **J**avaScript **O**bject **N**otation.
    - JSON is a syntax for storing and exchanging data.
    - JSON is text, written with JavaScript object notation.


<!--
########################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
-->
## <a name="http_req"></a> Chapter 11 HTTP and AJAX [[menu]](#top)
- what is HTTP
    - The Hypertext Transfer Protocol (HTTP) is designed to enable communications between clients and servers.
    - HTTP works as a request-response protocol between a client and server.
    - A web browser may be the client, and an application on a computer that hosts a web site may be the server.







![](https://i.imgur.com/PP7USjs.png)