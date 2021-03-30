# HTML and CSS Workshop Syllabus

- [HTML and CSS Workshop Syllabus](#html-and-css-workshop-syllabus)
  - [Introduction](#introduction)
    - [Instructor](#instructor)
    - [What is HTML](#what-is-html)
    - [What is CSS](#what-is-css)
    - [Editor](#editor)
      - [VS Code](#vs-code)
      - [Online](#online)
  - [Concepts and Demos](#concepts-and-demos)
    - [HTML Basics](#html-basics)
    - [CSS Basics](#css-basics)
    - [Semantic Elements](#semantic-elements)
    - [Exercise 1](#exercise-1)
  - [Break ☕ [10 mins]](#break--10-mins)
  - [Flexbox Introduction](#flexbox-introduction)
  - [Responsive Web Design](#responsive-web-design)
    - [Exercise 2](#exercise-2)

<hr>

## Introduction

__HTML__ and __CSS__ are the building blocks of the web technology.

In this workshop, you will get glimpse of HTML and CSS basics and also get familiar with the art of using together to make website components like navigation bar, card or others

### Instructor

[Budh Ram Gurung (or BRG)](https://freelancerbrg.com) is an _IT Teacher, Educator, Mentor, Full Stack Engineer, Social Coder and a Researcher_. He has around __10 years of IT Experience__.
Following his passion, he _switched from core software development to teaching in 2019_ and has been teaching, counselling students to become a _good professional engineers_.
Click [here](https://freelancerbrg.com) to know more about him.

### What is HTML

- HTML stands for _HyperText Markup Language_.
- It is most basic building block of the Web.
- It defines the structure of the web page or content.

> "Hypertext" refers to links that connect web pages to one another, either within a single website or between websites.

> "Markup" means to mark something to change its content. Like HTML tags inform the browser to change the behavior of the content like \<b> tag will tell to make the text bold.

### What is CSS

- CSS stands for _Cascading Style Sheets_.
- Describes how the web page should be displayed (look).
- Describes how elements should be rendered on screen, on paper, in speech, or on other media.
- Simply saying, CSS adds styling to the web page.

### Editor

To create web page you need a good editor. There are many editors out there, but I prefer `VS Code`.

_NOTE:_ You can use any editor of your choice.

#### VS Code

To develop effectively, VS Code offers many extensions. Following two are recommended.
- `Emmet` (pre-installed)
- `Live Server`: To install it follow the steps below:
  -  Press shortcut keys `Ctrl + Shift + P`
  -  Type `Install Extension` then press `Enter`
  -  In search box, type `Live Server`
  -  Click on the extension by `Ritwick Dey`
  -  Click on `Install` to install extension

#### Online

[CodePen.io](http://codepen.io/) is one of the best Online Code Editor for front-end developers and best for showcasing HTML, CSS and JS code snippets. Go ahead and create account.

## Concepts and Demos

In this section we will go through some of the important concepts related to HTML and CSS along with its demos.

### HTML Basics

- Generate the boilerplate code using emmet
- Describe the page structure
- Tag, Element and Attribute
- Discuss about meta tags. [See Video.](https://brgclasses.com/courses/website-bootcamp/meta-tags)
- Working with text
  - Headings, para, pre and code
  - Div and span
  - Text formatting: `strong`, `em`, `mark` etc
- Links and Images: remove underline
- Lists and Tables
- Form and basic input elements: `input`, `checkbox`, `textarea`, `select`, `submit`

### CSS Basics

- Three types or ways to add CSS in web page:
  - Inline CSS
  - Internal CSS
  - External CSS
- Class and ID
- Basic Selectors
- Developer Tools Introduction
- Fonts in CSS
- Color, Background and Border
- Margin, padding and box model
- Inline, Block and Inline-block elements: auto margin
- Working with text
  - Font sizes: px, em, rem, %
  - [Overflow and Text Overflow](https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_text-overflow)
  - [Text indent](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_text-indent)
- CSS Positioning: `relative`, `absolute`
- Float and alignment
  - `max-width`
  - `text-align`
  - `float` and `clear`

### Semantic Elements

- `header`, `footer`, `main`, `aside`, `article`, `nav`
- HTML5 common page structure looks like below:

  <img src="/html-css/images/html5.jpg" width="500" alt="HTML5 Structure">

### Exercise 1

- Open this [CodePen Link](https://codepen.io/brgclasses/pen/yLVQBOZ)
- Start updating `HTML` or `CSS` section as per the instructions. For following
  instruction you need to set the `text-align: center` property.

  ```css
  .text-center {
    /* Center the text alignment using text-align property */
  }
  ```
- The final output of the page should look like below:

  <img src="/html-css/images/exercise1-output.jpg" width="500" alt="HTML5 Structure">

## Break ☕ [10 mins]

## Flexbox Introduction

- Aims at providing a more efficient way to layout, align and distribute space among items in a container
- Can manage elements when their size is unknown and/or dynamic (hence `flex`)
- There will be a flex container (parent) and flex items (children).
- Refer from [here](https://www.w3schools.com/css/css3_flexbox_container.asp)
- Check this [Complete guide on Flexbox by CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Responsive Web Design

- Viewport concept
  - Setting viewport
    ```css
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    ```
  - Viewport height and width
  - Refer [w3school](https://www.w3schools.com/css/css_rwd_viewport.asp) for more details

- Media queries

  - Uses the `@media` rule to include a block of CSS properties only if a certain condition is true
  - Example: Make page body background to lightblue in mobile.

    ```css
    @media (max-width: 480px) {
      body {
        background-color: lightblue;
      }
    }
    ```

### Exercise 2

- Open this [CodePen Link](https://codepen.io/coolbrg/pen/Exgbodv)
- Start updating `HTML` or `CSS` section as per the instructions.
- The final output of the page should look like below:

  <img src="/html-css/images/exercise2-output.jpg" width="500" alt="HTML5 Structure">
