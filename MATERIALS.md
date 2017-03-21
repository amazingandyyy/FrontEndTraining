<a name="top"></a> 

[amazingandyyy](https://amazingandyyy.github.io) > [Front End Training Course](https://github.com/amazingandyyy/FrontEndTraining) > [Materials](https://github.com/amazingandyyy/FrontEndTraining/blob/master/MATERIALS.md)
 
* [Chapter 1 Workplace setup](#setup)
* [Chapter 2 Web = HTML + CSS + JS](#web)
* [Chapter 3 Basic HTML](#html1)
* [Chapter 4 Basic CSS](#css1)
* [Chapter 5 Advance HTML](#html2)
* [Project Build a XYZ introduction website](#uni_index)
* [Chapter 6 Bootstrap](#bootstrap)
* [Chapter 7 Basic Javascript](#js1)
* [Chapter 8 Basic jQuery](#jquery1)

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
    ![](https://i.imgur.com/rJkZAT3.png)
    - [GitHub](https://github.com/)
    ![](https://i.imgur.com/06sysPl.png)

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
- Many more CSS Framework
    - Foundation
    - Semantic
    - Skeleton
    - ...

## <a name="js1"></a> Chapter 7 Basic Javascript [[menu]](#top)
- What is javascript
    - so called JS
    - JS is a programming language
    - Browser can undertand JS
- Try console log in chrome


## <a name="jquery1"></a> Chapter 8 jQuery [[menu]](#top)
- What is jQuery



![](https://i.imgur.com/PP7USjs.png)