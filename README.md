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

### Todays Notes: Building an Image Gallery

- Its a good idea to choose images that have similar themes and color shemes
