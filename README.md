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

---

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

  - Fetch returns a Response.Ok property that is true if status is between 200 - 299. Others is false

  ***

## February 18th CPNT 201 Journal Notes

### Node (CMD/Server) npm Package Manner

- **Dependancy Management**
- Keeping track of software versions is hard work. npm makes this easier
- **Development and Deployment**
  - Along with git, npm is odten used to manage code on live servers
- **Project Collaboration**
  - Aling with get, npm is used to make sure team members are developing with the same software versions

### Terminology

- **Dependaccy**
  - Software that your aoo neeeds to function properly. Each dependancy will also often also have their own dependicies
- **Package Managment Sysyems**
  - Software that automates the installation and updating of software dependencies
- **Semantic Versioing**
  - A three number version system (major.minor.patch => 2.3.1) for software
- **Node**
  - A framework for running JS from the command line or on a server
- node will not run browser-specefic codel like document.queryselector

### Typical Usage

- 1.  Initialize
- npm init
- 2. install package
  - npm install <`package-name`>

## CPNT 201 - February 22nd Code Journal Notes

### Tailwind

#### NPM Steps

1. in the ternimal, type `npm init`
2. In the ternimal again type: `npm install -D tailwindcss`
3. add to a `tailwind.css` file or whatever name you choose:
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
4. Use `npx tailwindcss init --full` in the ternimal instead of what it says on the tailwind website
5. in the terminal: `npx tailwindcss -i assets/css/tailwind.css -o assets/css/main.css --watch`
6. In the `package.json` file within the `scripts` add `"build": "npx tailwindcss -i assets/css/tailwind.css -o assets/css/main.css --watch",`
7. Add `"*.html"` to the `tailwind.config.json`
8. In the terminal, `npm run build`
9. In the ternimal, `npm run dev` (only run on developer with the installed framework. Ex nuxt)
10. This should allow me to use `root` styles in my `index.html`

#### Installing Nuxt After

1. npm init nuxt-app <project-name>
2. add modules
3. to add: ex. npm install -D @nuxt/image
4. Add `'@nuxt/image'` to the `modules` in the `nuxt.config` folder (makesure to comment the url above where found it)

## February 24th Notes

### Debugging NPM

- Use `npm audit` to check if there is vulnerabilities
  - research or Google the right version on how to fix some of the vulnerabilities

## February 24th Code Journa Notes

- Its like WordPress when is manages contents
- A headless CMS is any type of back-end content management system where the content repository “body” is separated or decoupled from the presentation layer “head.” Content that is housed in a headless CMS is delivered via APIs for seamless display across different devices.

### Headless CMS

- Developer driven. You organize content on a website and send it anywhere
  - Optomize different work flows
  - Example:
    - Wordpress and Drupai

#### Why Headless?

- More flexible, secure and developer friendly
- JAMstack allows content editors a devs to be able to use tools that work best with their workflow
- Headless CMS allws devlopnment of content to muitiple frontends this more challanging then

### JAMStack

-Jamstack is an architecture designed to make the web faster, more secure, and easier to scale. It builds on many of the tools and workflows which developers love, and which bring maximum productivity.

- Javascript: Language
- API: Content Delivery
- Markup: Content

## March 4th 200 Code Journal Notes

### REst API's

- **CRUD**
  - Anything that you can do with an object
    - R= Create
    - R= Retrieve/read
    - U= Update
    - D= Delete
- Http Methods
  - Get
  - Post
  - Put
  - Delete

### Accessing Data

- **HTTP Request**
  - A request for a resource from the browser to a server
- **HTTP Response**
  - A response from a server the a browser containing either a resource or the result of a operation

#### Http Terminiology

- Resource
  - A target request, such as html. json data, and
- Methods
  -A CRUD operation performed on a resrouce
  - POST (create)
  - GET (read)
  - PUT (update)
  - DELETE (delete)
- Example
  1. Browser makes a GET request for a url
  2. Server recieves a request and finds the resource such as a file, image, or data
  3. the server sends the resource bak as a response
  4. The browser recieves the response and might:
  - Display a page/image
  - load JSON data with JS

### REST API's

REspresentation state transfer

Difference between authentication and authorzition

- Authentication (tokens)
  - Processes of veryifying a use
    - In the body typically
- Authorization (acess tokens, keys)
  - prcoess of what an application has access to

## March 7th Code Journal

## Fixing Security Vulnerabilities from installing modules or nuxt

(re-watch 50 minutes in March 7th)

1. npm audit
2. in thepackage.json create a `"resolutions" {

}`array 3. in scripts create a`"preinstall": "npx npm-force-resolutions`

### Netflify Deployment

-

#### Storyblok with vs code

1.  First `npm install @storyblok/nuxt` on the terminal
2.  '@storyblock/nuxt/module'
3.  Make sure `@nuxt/composition-api` is installed
4.  add to `build modules` under `nuxt.config.js` file add
    buildModules: [
    '@nuxtjs/composition-api/module',
    [
    '@storyblok/nuxt/module',
    {
    accessToken: process.env.STORYBLOK_API_KEY,
    bridge: true,
    apiOptions: {},
    useApiClient: true,
    }
    ],
    'nuxt-webpack-optimisations'
    ],
    ],
5.  On the settings of your `space` changed the url to `http://localhost:3000`

6.  Use `npm run dev` to text if its working on storyblok

#### Then:

1. Copy api key from `preview` storyblok api into `.env` that I created
   2 STORYBLOK_API_KEY=(KEY GOES HERE)
2. in `config` change relative path to `/` on storyblok

#### After that: Deploying on Netlify

1. Choose the repo you wants rather then using a template
2. `npm run generate` in the terminal on VSCode

#### Get storyblock public api on netlify

1. in `environmental variables` folder on netlify in the settings and click `edit variables`
2. in `key` add STORYBLOK_API_KEY
3. Add the public key from Storyblok
4. Use `npm run generate` rather then `npm run dev`. This is because `dev` is a development server.

---

## March 8th Notes

### Stroyblok Nuxt Achievement

#### Creating 3 Components on Storyblok

##### Steps on Storyblok Components

1. create a new space (can't use demo content) from scratch

- Name it whatever you want

2. Look at a website and look at what I might need (nav, hero, card, footer for example)

- Take time to plan out a project
  - **UI Components**
    - Navigation (one)
    - Home Page (hero(once))
    - Page header (same design, different content)
    - Page header Post information
    - Post ext content
    - post image collage
    - Post image
    - Code Block
    - Post section titles
    - Links (custom styles)
    - Post Tag List

3. Go into components

- Delete default components

4. In components click new and write a `navigation` component(make nestable)

- Change display name

5. In schema

- Create `nav_items` schema (block
- nava (site wite naviagtion in description)
- Add blocks with a maximum of 5

5. In `nav_items` component

- Create text
- config name change display name

6. Click new and write `site_header`
7. Create a group called Site UI (do this first)
8. Create another group called `blog posts
9. In `site_header` gve it a name

- In schema create a site_logo
- Create a `nav_bar`
  - Both can be blocks to insert content

10. In new create `logo_link`

- create a schema within called `logo` with `asset` for images
  - Add a description of what you are going to to
- create another schema within named `text`with text with another description
  - Also change the display name
- Create another schema named `link` with the type of link

11. `site_header` can take its components wishlist
12. after added info to vue

- in setting of space change url to localhost:3000
- in config in real path add `/` there

#### Creating 3 components vue (VSCode)

##### Steps on Vue for Components

1. set up tailwind
2. Donwload `npm i`
3. go into VSVode and go into components
4. Remmeber to use `<nuxt-link="to">` to link to another vue
5. And add a file name `TheHeader.vue` in the components folder
6. Create another file name `TheNavBar.vue` in the components folder
<!-- 5. Create another file name `TheNavBarItem.vue` -->
7. create another file named `TheLogo.vue`
8. in the `TheHeader.vue`

- Add template tag
- Add div tag
- in the div add <TheLog / >

8. In `TheLogo.vue` add another templage tag - Add image tag - Use span tag within the template - In there text `w/logo`
   = <nuxt-link to="/"></nuxt-link>
   - In the `TheNavBar.vue` add another template

- within add nav tag
  - within that add ul tag
    - Add Li and with nuxtLink tag and add `to="articles"`
- in the scripts tag at `setup` (<script setup>)

10. IN THE PAGES FOLFER IN THE INDEX.VUE ADD `TheHeader /`
11. create anotehr folder called `layout`

- in the create a file named `default.vue`

  - Add a template tag in teh div add <TheHeader>
    and a h1 for home page
  - add <nuxt /> in there

---

- **Components go inside the components folder**
- PascaleCase (this is a vue thing) inside the components folder
  - ts so custom components stand out clearly
- Anything you look like go into the template tag
  - Only one root component can be in template tag
- **In script tag (Oranize logic)**
  - import of components
    Logic goes into script tag
-

## March 9th Code Journal Notes

### Using Figma

- place image in frame, lock image in frame reduce opacity se you easily see what im drawing. Locking is key so you dont click it by accident
- move you anchor 1/3 the way when tracing an image

## March 10th Notes

### In line SVGs (Scalable Vector Graphics)

- <img src="no-bugs.svg"> or background-img: url(no-bugs.svg)
  img {
  display: block;
  width: 50vmin
  }

- Adantages o
  - No need to worry about SVG code; the browser will treat it like a raster image
    Image wil be sharp
- Inline Svg

  -

- Advantages of inline svgs
  - Can be styles and animated with CSS

### Tips and Tricks

- Width and Height

  - WHen in doubt, removie the width and height to make more responsive

- XMLNS Attribute
  - Is not needed for inline SVGs but is required for SVGs referenced as images
  - When in doubt, inculde this attribute in case
- Version 1.1 should alwaus be removed

### Exporting SVGs

- Every vector application is different
- For inline SVgs, you generally want to flatten Pathfinder effects before export
- If you want \

### To export from figma

- select whole frame
- flatten to whole image
- export as an SVG
- Present in an html document

## March 14th Code Journal

### Figma Notes

- To prototype, copy the page and make varations to it. That links to the homepage
- Group items on sidebar to clean up and navigate lie the website layout
- Use "place image" for figma to get more of a clean design
- Layout grids
  - On right panel that says "layoutgrid" to access this, select the frame.
  - 12 column grid is good for desktop grid
  - select columns rather then the default grid
  - gutters
    - gutters
      - Thickness of the grid columns
    - Want some white space around the edges
      - 36 is good

### Prototype on figma

- click on what you want to prototype drag to other page,click navigagte to ...and animation

## March 15th Server-side JavaScript (Node) Code Journal

### JS Review

- Array
  - const heroes = ['Ironman', 'Black Widow', 'Star Lord']
    - heroes
    - heroes[2]
    - heroes[3]
  - **for loop**
    - for(let = 0; i < heroes.length; i++) {
      console.log(heroes[i])
      }
- Fat arrow
  - heroes.forEach(hero) => console.log(hero))
  - function listHerores(arr) {
    console.log(arr.forEach(x) => console.log(x))
    }
  - Jess said "You can think of the array of objects like a house, you need your api key to get into the house, you need the door 'key' inside the key: value pair to access the value"

### Node Global Objects

- A number of default objects and properties come with the Node environment.

#### Terminology

- \_\_filename : The absolute file name of the current module.

- \_\_dirname : The directory of the current module.

- process Global Object : A global object provides various information sets about the runtime of a program.

- process.argv : An array containing the command-line arguments passed when the Node.js process was launched.

- this : The infamous this keyword returns an empty object by default.

- global : The Node global object replaces the window object in browsers.

---

## March 16th Code Journal Notes

### JS Review

- for (let i= 0; i < 5; i++>){
  console.log('\*')
  }

- Example from [w3schools](https://www.w3schools.com/js/js_loop_for.asp)

  - From the example above, you can read:
  - Statement 1 sets a variable before the loop starts (let i = 0).

  - Statement 2 defines the condition for the loop to run (i must be less than 5).

  - Statement 3 increases a value (i++) each time the code block in the loop has been executed.

#### Nesting For Loops

- **Example:**
  - for (let i = 0; 1 < 4; i++) {
    for (let j = 0; j < 4; j++) {
    stry += '\*';
    }
    console.log(i)
    }

#### How to import files from the outside

- We use `argv`
  - Example:
    - const { argv } = required('process');
      const args = process.argv.slice(2);

#### Plan to re-fresh my JS skills

- I am findings as we are doing the more JS lessons that I am forgetting a lot of the fundamental components of js
  - As a result, I think I am going to re-take the JS course from CodeAcademy
    1. I start with the basics
    2. Then focus on `if/else statements`
    3. The `forloops`
    4. lasty, I will attempt to a refresh on `async`

### Intro to Vue.js (Fontend Framework)

- can use `options api` or `composition api`

- Known as the `progressive framework`

- Look into the built in `directives` on [vuejs](https://vue.js.org/)

- **Rehydrate**
  - helps provide a dynamic experience on the client side
- Get familiar with the terms SSR, SPA and SSG

- A lot easier to use as we dont really have to use `queryselector` for example.

- Vue Example from `vuejs.org`
  - in `<script>` tag
    - const myShit = {
      name: 'Stephan',
      lastName: 'Taylor',
      age: '32'
  - Then in `<template>` tag
    - <p>
      My name is {{ myShit.name }} I am {{  myShit.age }} years old. I am a very old disgusting man.
      </p>

#### v-text

- can be used the same way as `innerText/html`
  - `Moustache Syntax` seems like the better way to go

#### v-bind

- most useful
- Render attributes with `v-bind`
- Spifiically for binding attributes and props into your html

  - Useful for `img` tags

- Can be used as shorthand

#### v-for

- [vuejs](https://www.geeksforgeeks.org/v-for-directive-in-vue-js/?ref=gcse)

  - "v-for directive is a Vue.js directive used to loop over a data usually an array or object. First, we will create a div element with id as app and let’s apply the v-for directive to an element with data. Now we will create this data by initializing a Vue instance with the data attribute containing the value."

- Make sure to give a `v-for` a `:key="item.id"` to remove errors

#### v-slot

- another thing I need to play around with

---

## March 17th Code Journal Notes

### Refresh of JS Nested Looping

- Again, today I really need to watch some videos and tutorials on js for loops/nested as I am still struggling with in

  - In my previous journal entry, I was supposed to do it on the 16th, but my new laptop setup was problamatic.

- `for (let i = 0; i < 4; i+ +) { for (let j = 0; j < 4; j++) { str += '*'; } str += '\n' }`for example.
- Make an empty string

- For each Array Method
  - Loop through things that doesn't return a value
  - const arr = [
    'one', 'two',
    'three',
    ]
    arr.foreach((item) => console.log(item));

### Importing JS files and Modules

#### Importing

- `const taskList = required('./tasklist');` from the file named `taskList.js`
  - `const tasks = taskList.tasks`
- move into the file and the exports in particular

#### Exporting

- import { tasks } from './taskList.mjs'

- export const tasks = [
  // array here
  ]

### Vue Cli Installation Process

1. Install using `nnpm install -g @vue/cli`
2. Can use vue --help
3. to run project ui use `vue ui`
4. to run use `npm run serve`

- Make sure i'm in the right folder

5. In the project ui, click tasks, click run task, then click open app
6. This will allow me to see changes that I made in the local
7. src in world files and public is for assets and extra stuff

### Vue Installation Problem

- I had issues installing `vue` giving me fatal errors evertime. Ash and Jess told me to get to the root globally and use `sudo npm i -g vue/cli`
  - This fixed this issue
