# clock: development strategy

This site was build with great team work.

## 0. Setup

> * What files do you need to create? 
- Need to create all separate files like `index.html`, `style.css`, `img` &  `data` file.
> * What are you putting in each file? 
- In `index.html` I build a skeleton of the clock and connect it with `data.js` and `style.css` files.
- In `style.css` will place the clock to the center with relaxing background image.
- In `data.js` i will define seconds, minutes and hours with `setDate` function.
  

## 1. User Story: As a user I want to have a working clock with correct time.

> * Which user story makes sense to code first?
- Create `setDate` function to activate `hours`, `minutes` and `seconds`.
> * Which files of code do you need to change?
- `style.css`  and `data.js`.
> * What are you changing in them?
- In `style.css` will define the `transition` of `rotation` and `cubic-bezier` for the clock hand.
- In `data.js` i will define seconds, minutes and hours and set it's `transition` in `style`.