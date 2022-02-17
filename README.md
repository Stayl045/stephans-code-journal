# sait-wdp-stephans-code-journal

this is my journal entry

## January 11th 2022

- Ugh, attempted three times to create a repository before finally getting it right!
- Finally have settled on a repo that works for me.
- Had to research some html basics to create an unordered list.
- Taking a break until tomorrow afternoon to complete this assignment.

## January 12th 2022

Last night I didn't feel comfortbale with completing this assignment early due to some uncertainty. However, today with Tony's excellent teaching, I am more comfortable with what I am doing.

- I was confused as I originally thought I had to write these journals in HTML as I copied the steps on Tony's cheatsheet. Now that I am doing this on MD, I am hopefully less confused.
- Next step...pushing. Hope nothing breaks!
- Ran into issues with https. **Thankfully, worked with Tony and the class to set up an SSH key. It took some work, but we finally got it and I was finally able to push the repo.**

---

## January 17-18th 2022 Code Journal 1

Goal: Push 1st README.md to GitHub without online help for Assessment #1. My ultimate goal for now is to make this process second nature in use!…here I go. SCARY!

**Steps:**

1. Create a file in my root directory.
2. Create a README.md file in that directory.
3. Add relevant information to my assessment.
4. Follow instructions laid out for this assignment.
5. Use `git init` command without any hassle.
6. Create a blank repo on “GitHub”.
7. Don’t check create initialize contents such as “README.md".
8. Click“Create” repository.

Plans failed…

I was really nervous when attempting to push my Journal to GitHub having some issues. I therefore broke down and used your help.

New plan (Taken from the help page):

1. Follow the steps provided on the website.
2. I was successfully able to push to my repo.
3. I will finish the rest tomorrow.

**January 18th**
Plan: to finished assignment #1: UX breakdown by the end of the day.

- First, I must learn some of the basics of Figma.
- I feel like I am learning the basic tools such as:
  - toying with my frames to look like cellphones.
  - creating some space between each frame so it's more pleasing to the eye.
  - utilized soft colour pallette so it's easy to read and follow.
  - tried to play with Prototype, but quickly called that quits.
- All in all, I ,ade a good outline for the assignment if I don't say so myself.
- I had some trouble adding icons such as “Search Icon”. I think I have to attribute then and components to my figma.
- I gave up and didn’t bother searching for outside icons, so I hand drew the icons (which took some time).
- Had fun figuring out figma and successfully created a wireflow without much of an issue.
  - Initially I struggled to figureout how to add images to MD to push to Git hub. However this link helped:
    - [MD Help](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- I successfully completed my plan and finished my assignment #1 of design with the help of the website to add my wireframe.

---

## January 20th **CPNT-Code-Journal #1**

No plan for today really… Just trying to absorb everything that Ash taught. A lot of different codes to memorize, page layout, and overall structuring. I think I will get there if I keep practicing the content.

**Some key notes that Ash said:**

- `CMD-shift-C`to open up Developer Tools.
- `CMD-OPT-I` to highlight in the browser to specific codes.

Another cool piece of advice that Ash gave is to, “Throw some concepts together one your down time to keep yourself fresh”. I will try to keep this in mind going forward just in case.

**Other things to keep in mind:**

- `Article`: Stand-alone. This is a good way of knowing where to place the`Article` attribute.
- Section: Larger content.
- Shortcuts to create a list: `<li> Li*3`.

**Future Goals:**

- Experiment with CSS styling more. For example, learn how to add differet images in a box and organize them that is pleasing to look at.
- memorize the layout of HTML, its codes, and how they interact with CSS.
- Play around more with CodePen on some spare time of mine.
- if i'm feeling bold. Maybe trying add some JS into my codepens.

**Proof of Work**
![WikiArticle](https://github.com/Stayl045/stephans-code-journal/blob/a0ec5ce54949528f6ebf058023d5d1770ed75cb9/Proof%20of%20Work.png)

**Links that I looked to when using CSS**
[CSSColour](https://color.adobe.com/create/color-wheel)

- I used this tool in the past and I remembred that I could've used it for this first assignment.

## **January 21st**

**Issue**

- Live Page isnt working.
  ![Screencap](https://github.com/Stayl045/stephans-code-journal/blob/13d505da8bd188cfca2d8bbdb9e80573c3920bb0/Broken%20Live.png)
  **Resolved**
  - Simply had to go into the extention and it asked me to reload the extention. This seemed to have fixed the issue.
  - Need to attibute the "lord of the rings" image.
    **Issue**
- Tried to change Live Server to FireFox, but it didn't work.

Ash gave us a quick rundown on how to push code through terminal, so I have a new plan:

**Plan:**

- Learn how create files and folders through the terminal rather then the GUI way.

  - In the terminal at the root `mkdir assets` for example to create a directoy.
  - `touch` to create a file.
  - `mv` to move a file.
  - `rm` to remove a file.
  - `../` go back one directory.
  - `./` right here.

- Ash also gave great adivce that will help me going forward. Use "open to the side" in VS to have my "code journal" on the side, so that I can add entries on the fly.

- My brother provided key shorts cuts
  - `Option + shift + down` to create a quick copy.

**January 24th 2022**

- ## GOAL
  - Create a responsive Nav Bar.
  - Has to be responsive.
  - That its pleasing to look at.
  - Create a responsive button.
- ## NOTES FROM CLASS
  - `:root {}`
    - Sets custom colours.
    - `flex-grow` selects certain items to take up more space.
    - `flex-wrap` shrink.containers to be stack down as window gets smaller.
    - `Overflow-wrap`
    - To inspect colours on a webpage on FireFox, click the little dropper to the right on DevTools.

Future **goal**: To create a drop down menu on my nav bar when making window smaller.

---

## January 25th, 2022 (CPNT-260)

**Goals**

- Make a responsive hamburger menu.
- optomixe the text FlexBox.
- Improve overall design.
- Change branch from `master` to `main`.
- Adjust header text size and font styling.
- inquire if images saved on local will show up when someone opens up my repo?
- Make my MGS page life on Pages.
- Maybe fix my body margin.
- add some more effects to the cards
  - Background shadow/glow
  - Play with more transition and hover effects.
- **IMPORTANT**: Make hover on
  cards clickable.
- Maybe add a `transform: Rotate`.
- Add `box-shadow` effect.
- Play around more with `Utility Classes` as it was a topic of discussion for most of the day.

---

## Notes from Class

- Make all your assignments **MIT License.**
- At top of CSS add:
  - body { margin: 0; }
  - img {
    width: 100%;
    height: auto;
    }
- use flex-gap between major components.
- `@media quiris` must always be at the bottom as they override.
  - Ash, said, "Queries get you to think what information is most important and which to cut". This is based on the screen size.
  - Make changes specifically on the query based on which they way you want it to look on browser or mobile.

---

### Issue #1

On GitHub, my CSS for my About Page isn't apprearing.

### **Fixed**

- on the `link`, in the `HREF` I added a `.` before linking to the css.

---

### Issue #2

Images saved on local aren't showing up on GitHub no matter what I tried.
![screencap](https://github.com/Stayl045/stephans-code-journal/blob/fbcbff008168d3a7727dde2bb1cb15cacc1e5292/github-img-display-issue.png)

### **fixed**

After hours of scouring the internet, I finally found a solution to this issue on https://github.com/mkdocs/mkdocs/issues/1757. I found that I was using `absolute paths` when I should have been using `relative paths`. For example: `../` instead of `/`. This has fixed this issue. HURRAY!
![screencap](https://github.com/Stayl045/stephans-code-journal/blob/d8d172b6d6a3b7bb2eb0b61d5cc6e57e068bc1f6/solved%20issue.png)

---

## January 26th

**GOAL FOR TODAY**

- Learn how to create Hamburger Menu in my services/products assignment for desktop screens.

## Notes

- Images
  - `div class.img-wrapper *3` + `tab` will auto complete what needs to be filled out.

---

## January 27th

## **Goal**

- To create my page layout and design for **Assignment #2: Products and Services**.
- Also, to create a 404 error page due on the **28th**.

## Plan

- Think of a design theme
- Main color scheme
- How I want the play with the layout?
- What tools in CSS will I utilize and learn?
- Explore some CSS Grid
  designs to use for assignment #2
  1. Choose a design
  2. Convert some Images
  3. Choose a color scheme (maybe add a template)
- Add a toggle drop down menu as some flare.
- Add a GitHub Repo.
- Create a `utilities.css` folder. Maybe even a `fonts.css` folders in the assets folder. This oganizes the contents easier.
  - call <link href=""> for the `utilities`, `fonts`, `reset` and other folders before the `main.css`
  -

## Class Notes for the Day

- learn to use some essential Hot Keys

### GRID NOTES

- Use Display: Grid;
- How: Set Grid Columns
  - Optomize using repeat
  - Set up `auto` flow riles and `min-max` rules
  - Use `justify-items`, `align-items` and `place-items`
    use fraction `fr` unit
    use `gap`
- **Trick with grid**: Header rule to expand all the columns and its space.
  - Tell grid to start at a certain column use: `grid-column-start` on third column for example
- `grid-column: 1 / -1` (short hand syntax): This starts in the first column to the
- Maybe start `main` with `display: flex` + `justify-content: center` to play with both flex and grid.

## Some Useful attributes:

- `auto-fill`: Fits as many remaining columns
- `auto-fit`: Fits the currently available columns
- `tab` hold to select more that one item thats needs adjustment.

---

## January 28th Notes

### Goals

I would like to have my layout completed on assignment #2 by the end of that

- In addition to that, finish the "error 404 page#

### Plan

- Play around with `grid` a bit more. I feel like im not grasping how it fully works yet.
  - For the assingnment, ill play with creating box layouts and work with its attributes.

## Todays Class Notes

- Creating a `label` layout:
  - **Example:**"
    - <form action="" method="get">
      <legend>Info</legend>
        input type="text"> Username="user"
        id="user"></label>
        input type="text" name="User">
      </form>"
    - Can pair all `labels` in a `fieldset`
  - Words of Wisdom from Ash - "Come up with a set of Goals"
    - Collaborate with parnters in a cohesive manor. Each have a task to do. Ex: One person researaches color schemes while the other types out the boiler plate template.
    - Look up documentation.
    - Choose a color scheme

## January 29th Notes

Today....I **FINALLY** have a basic understanding of how `CSS-Grid` works!! Previously, I was fumbling like chicken with his head cut off randomly inputing commads :(.

- Today, this changed after watching [Kevin Powell's](https://www.youtube.com/watch?v=rg7Fvvl3taU) guide to `CSS-Grid` video.
  - About halfway through the video, I determined that I was under-utilizing FireFox Dev Tools and not reading the grid correctly.
    - I learned that I needed to turn on my `Grid Display Setting` Checkboxes. After doing this, I learned how to navigate the lines and change my CSS accordingly.
    - As a results, I successfully played around with Grid boxes to the point where I am feeling comforable making a half-way decent layouts. HAZAHHH!!!

## Jan 31st Journal Entry Notes

### Plan for Building my Gallery

1. Its a good idea to choose images that have similar themes and color shemes
2. create folder/file directories
3. Create a seperate CSS folder/file for all the fonts that I want to use can link to
4. Create a reset.css for `*` CSS.
5. Create a wire-frame using Figma for my layout by organizing images occording to their widht and height

- "This workflow helps reduce errors.

### Todays Notes: Building an Image Gallery

- Use `figure` as a parent to the `img` with `figcaption` in between.
- can mix flexbox within the `grid` on the `figure` selector and choose a `flex-direction`
- Add comments in between each image to quickly know where to navigate to
- Remember to think about overflow.
- Remember to set "img {
  width: 100%;
  height: auto;
  }"
- Use `grid-portrait` class to tall images and `grid-wide` for long images
- figcaption text can be on top of image by using `grid-column: 1 /1` + `grid-row: 1`

## CPNT 260: February 1st Journal Entry #5

### Building a Hero Section

### Notes

set images that spread two columns to `1 / -1` rather than `span 2;` as this causes it to only stay at two columns no matter the screen size.

---

## February 2nd Notes

### **Goal for the Day**

I was finally able to create a gallery that is responsive when the sizes are smaller. However, the layout has all the same heights and widths.

- Therefore, today I will attempt to have more of a random sized layout.
  - To accomplish this, I will research `implicit` and `explicit` grid and attempt to change things accordingly.
- I will also try to figure out `custom variables/utility classes/root styles` better as it seems essential.
- Use `formspree` or `formstark` to attach API for my homepage assignment.
  - Sign up and create an account.
  - Navigate to HTML and copy the top text of the form
    - <.form action="the link I copied"
    - change <.method="post".>
- Add animations to my title to make it fun and engaging

## Notes for the Day

- Ashe "White space is your friend"

- Jessica Gust, "Alignment is very important!"
- Write `done` when you are done omptomizing other peoples code. Helps the person track through the changes faster.

- Jessica Gust, "I find you can also take a piece of paper and put it against your screen so you can do line by line".
- Download "BitWarden" as my password manager
- Add more `comments` to my projects as it can be pretty handy

- Form:
  - Use `block` to have the following text on a different line.
- CSS is inherintly cascading

## Transition & Animation Notes

### **Transitions**

- Slide content: ".slide-box {
  transform: translateX(100px)
  }"
  - can move depending on how many px you set
- #### **Slide Transition:**
- Can use `transition` in its various forms to make some cool effects
- ".slide-box: active {
  transition: transform
  2s ease;
  }"
  - moves at that pace; can also use `ms` for quicker response
- #### **Spinning Transition:**
  - Make items spin
  - "#spin-ball {
    transition: transform 3s ease;
    }"
  - "#spin-ball:hover {
    transform: rotate(100turn);
    }"
- #### **Skew a Shape:**
  - Shapes skews in a specified direction
  - "#skew-rect {
    trasition: transform 3s;
    transform: skew(-50deg);
    }"
  - "#skew-rect:hover {
    transform: skew(20deg);
    }"
  - Can transform scale:
    - tranform: scale(0.2)
- #### **Cubic-Bezier** KNOW THIS

  -[cubic-bezier](https://cubic-bezier.com/#.17,.67,.83,.67)

### **Animation/Key Frames**

#### **Changing Color**

- "@keyframes color-shift {
  from {
  transform: translateX(0%);
  }

  to {
  transform: translateX(100%);
  }
  }
  /_ Then apply the keyframe like this _/
  .class-name {
  animation: identifier 5s infinite;
  }"
  }

".text-color {
animation-name: color-shift;
animation-duration: 4s;
animiation-iteration-count: infinite;
}"

- #### **Translate #3D**
- Transform: 3d()
- can be attached to key "frames.
  from {
  transform: translaate 3d()
  to {
  transform: translate 3d()
  }
  }"
  or shorthand

  - "animation: 3s ease-in-out infinite bounce;

- #### **Floating Ball**

  - floating-ball {
    animation: dot;
    animation-duration: 2s;

  }

## Review of 260 Notes

- think about syntax
- class override values
- in flexbox
  - avoid using margin and padding to position items as it can break on mobile screens
- Avoid spam coding (THINK THINGS THROUGH)

## February 3rd Journal Notes

### Goal for Today

I would like to get a head start on assignment 4 by deciding what kind of Home Page I want to developr.

#### **Plan**

1. Think of a home page theme
2. Plan what that page will look like
3. Create a repo
4. Pull utility colors and other attributes
5. Find images on "UnSplash"
6. Ogranize my folders
7. Start designing

### JavaScript Basics

- we are doing js es5 and es6
- **REALLY understand `functions` if anything else!! KNOW**
- We use `CONST` more often then `let`
- all the JavaScript must be in the `head`.
  - this is a modern convention
- if you get an `error` `invalid unit` on console. check if its `const`

## February 4th Notes

- In JS, in htmlthe `Defer`in the `script` tag is critical as without it, the page may break! Itll run after the DOM loads rather then before.
  - Always add `defer` to save myself future headaches in JS.
  - "<.script src="js/tip.js" defer></script.>" REMEMBER THIS!!

---

## CPNT-262 Journal #1 Notes Febraury 7th

### Goal for the Day

My main two milestones for the day would be to get a head start on the `plugin` assignment and to get a more of a comprehensive understanding of `functions` within JavaScript.

### Class Notes for the Day

#### Functions

- Functions are slef containted code that take inputs and outputs (return value)
  - Want to use a single piece of code that we can use multiple times
- Functions are in `()` parenthisies.

- ## Differnce between declaring and invoking a function.
- Function expression

  - const greet = function (){
    }
  - ## Invoking
  - Fat Arrow

    - "const greet = () => {

    }"...This is prefered way to declare functions.

#### Arguments and Parameters

- To add parameters, add in between the `()`.
- Template Literals
  - A cleaner way of injecting variables into string
    - Use backtik string $
    - the name has to be in the of argument into the functions between the parathesies
- "`Prompt` (My birthday is)" to add arguments in a different way

#### Dealing with **`Coercion`**

- when JS will auto convernt one data type to another. This may lead to unexpected results

### Plugin Achievement Assignment

#### Plan

1. Locate a JS library
2. Create a repo for this assignment

## February 8th

## Notes for the Day

- One of the most use of functions is used for invoking triggered functions
- Used for lots of cliking events
- Use `element.innerText` for achievement #2
- To change specific `string` words.
  - string.toCharAt(0).toUpperCase() - to change to uppercase
- to turn string into an object
- Dont have to name the same thing
  - `Object("string")`
- toFixed() - can move number to nearest decimal place

### **Steps To Take for Syntax and Logic Errrors**

1. To console log your variables

- Its because we are dealing with `coercion` prompt may turn number into string
- No squigly line means its not a syntax error
- console log relevant variables to confirm what you expect

### Events

- These allow us to interact with the DOM
- ![DOM-tree](https://github.com/Stayl045/stephans-code-journal/blob/1db07199ba323290d98c178ef8a0574f8807b5ad/dom-tree.png)
  - Basicly a tree:
    1. top: HTML
    2. Underneath: Head and body
    - below that is all the content. Ex. h1, p, form,
    3. Css and event listener attach to the content
  - This creates the tree in memory
  - to add js to selector
    - document.querySelector("button");
  - We are going to be interacting with DOM a lot by pressing `.`

#### document.querySelector()

- goal: execute prompts when button is pressed
- 1. Wrap prompts inside an `clickHander() function`
  - create a function with event that you are usling
    - ex. const clickHandler = () => {} in `js`
    - in HTML

2. Instead of manually invoking function, attach it to a button as an event listener

- const button = document.querySelector('button') console.log(button)

3. create a button variable
4. add `clickHandler()` to a button with a `click` event

#### eventTarget.addEvent Listener()

#### Button

Attaching triggers to any DOM element which triggers the function

---

## February 11th Journal Notes

- Dont do more then 1 comparison operator at the same time
  - Instead use `&&` operator to validate if seperate variables aer true

### Utility Functions

- REALLY IMPORTANT!! What is an expressions and how expressions move through an application
- Using an Utility as an expression
- They are small and narrow
- Download Library: `LoDash`

### Value Validation

- Syntax error
  - Error of wrinting in js
  - easiest to debug
  - has squiglys
    -RUN time errors
  - code is technically correct
  - example: file/library/module not found
- Logic Error
  - Code is broken
- Often get these errors when their is unexpected data type
- Not defined
- When something is out of scope (usually returns undefined)

#### **Testing for Undefined**

- if (typeof myVar !== 'undefined' {})

- example:
  - const name = "stephan"
  - typeof name : This should output string

#### Testing for specife data types

- Google this
- Array
  - (Array.isArray(myVar))

#### Advenced Assignment operstion

- **Logical or (||)**
  - Returns on the right-hand side whn left-hand value oprand is a fasly value
- **Nullish Coalescing or (??)**
  - Returns right-hand oprand when lef-hand oprand is null, undefinfed, and not other falsy values.
- **Optional Chaining Operator (?.)**

### Scope

- Where a variable is available in your code

## February 14th Notes: Arrays and Strings

### Arrays

- Array start at '0' rather than '1'
- **Array Literal**

  - A comma seperated list of values surrounded by []. ex. ['cats', 'dogs', 'fish']

- **Array Index**
  - The location of an item in an array. This is always a sequential number starting at 0.
- **Array Item#**
  - Individual value
  - Any Javascript days type (i.e. value) that an array index points to.
- Value Data Types
  - can be nay data type
    - Although its possible you'll normally see one specefic data type
- **Length**
  - How many items are in a particular array
  - Last item would be (-1)
- Finding and Removing Items
  - find the index of an item
    let pos = animals.indexOf('bear');
  - **Remove and Item by Index** Position
    - let removeItem = animals.splice(pos, 1);
- Search Arrays
  - This includes ()
- Convert an Array to a String
  - (elements. going)

### Strings and String Methods

- The String Object
  - JS can convert strings in a string object, which in includes:
    - An Array of each character in the string
    - An string.Length property representing the number of characters in the string
    - A number of string methods that provide useful searching and manipulation function. These methods will often accept or return the index of a characeter or substring.
- **Common sting Operations**
  - the the 'lentgth' of a string
- Testing for a substring
  - thie includes() method
-

## February 15th Notes

### For Loop

- The `for looops` is ubiquoes in the programming world. Almost every programming langauge has one and many employers will use a for loop challange in their hiring proces
- Terminology
  - Iteration
    - Some procerdure that is repeated multiple times
  - itereator
    - A counter variable that keeps track of which program is in
  - Iterable
    - An object which can be looped over or iterated over with the help of a for loop/.
- The for LOOP SYNTAX
  - "FOR ([INITIALIZER]); [condition]; [increment]){
    // Code goes herer
    }"
  - example: to print 1 to 100 for a loop.
    - "for (let i =; i <=; i++) {
      console.log(i);
      }"
  - The for Loop Process
    1. The initializer expression executes and creates one or more loop counters. The syntax allws an expression of any degree of complexity
    2. The conition expression is evaluated
    3. the block executes
    4. the increment expressions excuted
    5. Control returns to step 2
  - KEy Takeways
    - Name Iterator (i): its the convention
- be careful when defining your condition. Its easy to be 'one-off' when choosing a comparison such as < and <=.

## February 16th Notes

### Ayscynscronous Code

-Good way of understading Asyncronous code

- Go to McDonalds, they are going got take your order. Make order and wait for food. This is a asynhronous environemnt

- Blocking
- when browser executes extensive chunk of code

- Promises
  - New style of sync code that youll see used in web APIs

### Retreieving Data with Fetch

- Terminology
  - Callback
    - Anytime you pass a argument to another functions as a value to be invoked later
  - Promise
    - Instead of callbacks. Can only have two outcomes: **Success or Failure**
- async/await
  - New in ES7: provides
- Traditional Promises
  - fetch (), .then and .catch means its a promise
- Async/awaiy
  - syntax for using promises.
  - const fetchData = async function() {
    const response = awaiy fetch ()
    const data = away
    }
- Async function

  - 1. We need a function

    - const fetchData = async function () {

    }

- 'pausing' your code with AWAIT
  - used to 'pause' your code when incoking a function that returns a promise.
  -
- Key Takeways
  - The execution script will finish beore code can execute
  - Promises act as a 'reminder' for your code prociess as repsonse once it arrives
  -
- Think to remember
  - ways only works insude a function defined with async keyword
  - Away must be added in front of any unfction
  - any data retursn from a promise is only available inside a async function
  - use try...catch blocks to handle rejected promises

## February 17th Code Journal Notes

### Exceptions

- An error object created by JS when there a runtime error. It contains a description of error and where its occured
- throw exception
  - Act of generating an exception

### Try-catch-finally

- A stetment that handles exceptions
- Try
  - A clause that runs code that can generate exceptions
- Catch
  - A clause that catches exceptsions that are thrown
- Finally
  - A clause that always gets executed
- Throw
  - A statment that manually generates exceptions

### Exceptions Promises

- Promises can either succeed or fail
- Rejected promises with throw

### Considerations with fetch()

- it only rejects a promise if there is a network error
- an exceptions is not thrown when excounteres a 404 error not found or similer error
  - Fetch returns a Response.Ok property that is true if status is between 200 - 304
