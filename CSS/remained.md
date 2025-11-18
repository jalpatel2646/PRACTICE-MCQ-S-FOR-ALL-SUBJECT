# CSS MCQs

This document contains multiple-choice questions (MCQs) on various CSS topics for practice.

---

## 1. Tables

1. Which CSS property sets the spacing between cells in a table?
   A. border-spacing
   B. border-collapse
   C. table-layout
   D. cell-spacing
   **Answer:** A. border-spacing

2. Which value of `border-collapse` merges table cell borders into a single border?
   A. separate
   B. collapse
   C. merge
   D. join
   **Answer:** B. collapse

3. Which property controls the width of table columns?
   A. column-width
   B. table-width
   C. width
   D. table-layout
   **Answer:** D. table-layout

4. Which property changes the background color of table rows on hover?
   A. tr:hover { background-color: #ccc; }
   B. table:hover { background-color: #ccc; }
   C. td:hover { background-color: #ccc; }
   D. row:hover { background-color: #ccc; }
   **Answer:** A. tr:hover { background-color: #ccc; }

5. Which value of `table-layout` lets the browser automatically calculate column widths?
   A. fixed
   B. auto
   C. flexible
   D. default
   **Answer:** B. auto

6. How do you remove spacing between table borders?
   A. border-spacing: 0;
   B. border-collapse: collapse;
   C. cell-padding: 0;
   D. Both A and B
   **Answer:** D. Both A and B

7. What is the default display property of `<table>`?
   A. block
   B. inline
   C. table
   D. flex
   **Answer:** C. table

8. Which selector targets the first row of a table?
   A. table:first-row
   B. tr:first-child
   C. table>tr:first-child
   D. tr:first-row
   **Answer:** B. tr:first-child

9. How can you make all table headers bold?
   A. th { font-weight: bold; }
   B. table-header { font-weight: bold; }
   C. header { font-weight: bold; }
   D. tr th { font-style: bold; }
   **Answer:** A. th { font-weight: bold; }

10. Which property sets the height of table cells?
    A. cell-height
    B. line-height
    C. height
    D. table-height
    **Answer:** C. height

---

## 2. Display

1. Which of the following is the default `display` value of a `<div>` element?
   A. inline
   B. block
   C. inline-block
   D. flex
   **Answer:** B. block

2. What does `display: inline-block;` do?
   A. Makes element block-level only
   B. Makes element inline-level only
   C. Makes element inline-level but allows width and height
   D. Hides the element
   **Answer:** C. Makes element inline-level but allows width and height

3. Which display property makes an element behave like a table?
   A. display: table
   B. display: block
   C. display: flex
   D. display: grid
   **Answer:** A. display: table

4. Which display value is used to hide an element but keep it in the document flow?
   A. display: none
   B. visibility: hidden
   C. display: hidden
   D. opacity: 0
   **Answer:** B. visibility: hidden

5. Which value of `display` creates a flex container?
   A. block
   B. flex
   C. grid
   D. inline
   **Answer:** B. flex

6. What is the effect of `display: none;`?
   A. Hides the element and removes it from layout flow
   B. Hides the element but keeps layout space
   C. Makes element invisible but clickable
   D. Makes element transparent
   **Answer:** A. Hides the element and removes it from layout flow

7. Which display property is used for a CSS Grid container?
   A. display: grid
   B. display: flex
   C. display: block
   D. display: inline-grid
   **Answer:** A. display: grid

8. Which display value allows an element to behave like an inline element but accept block properties?
   A. inline
   B. block
   C. inline-block
   D. flex
   **Answer:** C. inline-block

9. Which display value is default for `<span>`?
   A. block
   B. inline
   C. inline-block
   D. none
   **Answer:** B. inline

10. To make a `<p>` element behave like an inline element, which property would you use?
    A. display: inline
    B. display: block
    C. display: inline-block
    D. display: flex
    **Answer:** A. display: inline

---

## 3. Max-Width

1. What does the CSS property `max-width` do?
   A. Sets the minimum width of an element
   B. Sets the maximum width an element can grow to
   C. Sets a fixed width of an element
   D. Sets the width based on content only
   **Answer:** B. Sets the maximum width an element can grow to

2. Which of the following is a valid `max-width` value?
   A. 500px
   B. 80%
   C. none
   D. All of the above
   **Answer:** D. All of the above

3. What happens if an element's content exceeds its `max-width`?
   A. It overflows the element
   B. It automatically wraps or shrinks depending on CSS rules
   C. It resizes the element ignoring `max-width`
   D. Both A and B
   **Answer:** D. Both A and B

4. What is the default value of `max-width`?
   A. 0
   B. auto
   C. none
   D. 100%
   **Answer:** C. none

5. Which property works together with `max-width` to make an element responsive?
   A. min-width
   B. width
   C. overflow
   D. Both A and B
   **Answer:** D. Both A and B

6. Which unit can be used with `max-width`?
   A. px
   B. %
   C. em
   D. All of the above
   **Answer:** D. All of the above

7. If `width: 800px; max-width: 600px;` is applied, what will be the actual width?
   A. 800px
   B. 600px
   C. 400px
   D. Auto
   **Answer:** B. 600px

8. Which of the following is true about `max-width: 100%;`?
   A. Element will always stay smaller than parent
   B. Element will never grow beyond its parent width
   C. Element can shrink but not exceed parent width
   D. All of the above
   **Answer:** D. All of the above

9. How does `max-width` affect images in responsive design?
   A. Prevents images from growing too large
   B. Automatically scales images down to fit container
   C. Both A and B
   D. Has no effect
   **Answer:** C. Both A and B

10. Can `max-width` have negative values?
    A. Yes
    B. No
    **Answer:** B. No

---

## 4. Positions

1. Which CSS property is used to set an element’s position?
   A. display
   B. position
   C. float
   D. top
   **Answer:** B. position

2. What is the default value of the `position` property?
   A. relative
   B. absolute
   C. static
   D. fixed
   **Answer:** C. static

3. Which `position` value makes an element stay relative to the viewport, even when scrolling?
   A. relative
   B. absolute
   C. fixed
   D. sticky
   **Answer:** C. fixed

4. Which property is required to position an element when `position: absolute;` is used?
   A. top, right, bottom, left
   B. float
   C. display
   D. margin
   **Answer:** A. top, right, bottom, left

5. What does `position: relative;` do?
   A. Moves the element relative to its normal position
   B. Fixes element to viewport
   C. Removes element from document flow
   D. Behaves like static
   **Answer:** A. Moves the element relative to its normal position

6. Which position type allows an element to stick to a position within its parent container while scrolling?
   A. fixed
   B. relative
   C. sticky
   D. absolute
   **Answer:** C. sticky

7. If an element has `position: absolute;` but no parent has positioning, it is positioned relative to:
   A. nearest positioned ancestor
   B. document body
   C. viewport
   D. sibling element
   **Answer:** B. document body

8. Which combination will make an element overlap other content?
   A. position: static; z-index: 10
   B. position: relative; z-index: 1
   C. position: absolute; z-index: 10
   D. position: relative; float: right
   **Answer:** C. position: absolute; z-index: 10

9. What happens to space in the document flow when `position: absolute;` is applied?
   A. Space is reserved as usual
   B. Element is removed from document flow
   C. Document shrinks automatically
   D. Space is doubled
   **Answer:** B. Element is removed from document flow

10. Which position allows smooth layering when combined with `z-index`?
    A. static
    B. relative
    C. absolute
    D. All of the above
    **Answer:** D. All of the above

---

## 5. Z-Index

1. What does the CSS `z-index` property control?
   A. The font size of an element
   B. The stacking order of elements
   C. The color intensity
   D. The border thickness
   **Answer:** B. The stacking order of elements

2. Which `position` values allow `z-index` to work?
   A. static only
   B. relative, absolute, fixed, sticky
   C. inline-block only
   D. All elements by default
   **Answer:** B. relative, absolute, fixed, sticky

3. Higher `z-index` values appear:
   A. Behind elements with lower z-index
   B. In front of elements with lower z-index
   C. At the same level as other elements
   D. Hidden
   **Answer:** B. In front of elements with lower z-index

4. What is the default `z-index` of elements with `position: relative` or `absolute`?
   A. 0
   B. 1
   C. auto
   D. -1
   **Answer:** C. auto

5. Can `z-index` take negative values?
   A. Yes
   B. No
   **Answer:** A. Yes

6. If two elements have the same `z-index`, which one appears on top?
   A. The first in the HTML
   B. The last in the HTML
   C. Randomly
   D. Depends on browser
   **Answer:** B. The last in the HTML

7. Does `z-index` work on elements with `position: static`?
   A. Yes
   B. No
   **Answer:** B. No

8. Which of these is a valid `z-index` value?
   A. 100
   B. -5
   C. auto
   D. All of the above
   **Answer:** D. All of the above

9. How can you make a modal appear above all other elements?
   A. Give it `z-index: 9999` and `position: relative` or `absolute/fixed`
   B. Only change `opacity`
   C. Set `display: block`
   D. Increase font-size
   **Answer:** A. Give it `z-index: 9999` and `position: relative` or `absolute/fixed`

10. Which property is often used together with `z-index` for layering effects?
    A. opacity
    B. position
    C. transform
    D. All of the above
    **Answer:** D. All of the above

---

## 6. Overflow

1. What does the CSS `overflow` property control?
   A. Content wrapping inside an element
   B. How content behaves when it exceeds an element's box
   C. Padding inside the element
   D. Border size
   **Answer:** B. How content behaves when it exceeds an element's box

2. Which of the following is a valid value for `overflow`?
   A. visible
   B. hidden
   C. scroll
   D. auto
   E. All of the above
   **Answer:** E. All of the above

3. Which `overflow` value allows scrolling when content exceeds the box size?
   A. visible
   B. hidden
   C. scroll
   D. clip
   **Answer:** C. scroll

4. What happens if `overflow: hidden;` is applied?
   A. Content is clipped and hidden
   B. Scrollbars appear
   C. Content overflows visibly
   D. Nothing
   **Answer:** A. Content is clipped and hidden

5. Which property can control horizontal and vertical overflow separately?
   A. overflow-x and overflow-y
   B. overflow-horizontal and overflow-vertical
   C. scroll-x and scroll-y
   D. max-overflow
   **Answer:** A. overflow-x and overflow-y

6. What is the default `overflow` value for most elements?
   A. hidden
   B. visible
   C. auto
   D. scroll
   **Answer:** B. visible

7. Which value prevents content overflow but doesn't add scrollbars?
   A. scroll
   B. hidden
   C. visible
   D. auto
   **Answer:** B. hidden

8. Which `overflow` value automatically shows scrollbars only when necessary?
   A. hidden
   B. scroll
   C. auto
   D. visible
   **Answer:** C. auto

9. Can `overflow` be applied to inline elements?
   A. Yes
   B. No
   **Answer:** B. No

10. Which of the following is true about `overflow: clip;`?
    A. Clips content but doesn't provide scrollbars
    B. Same as hidden
    C. Visible overflow with no clipping
    D. Adds scrollbars
    **Answer:** A. Clips content but doesn't provide scrollbars


# CSS MCQs - Floats

This document contains multiple-choice questions (MCQs) on the CSS topic **Floats**.

---

## Floats

1. What does the CSS `float` property do?
   A. Positions an element to the left or right of its container
   B. Hides the element
   C. Changes the display type
   D. Aligns text only
   **Answer:** A. Positions an element to the left or right of its container

2. Which values can `float` take?
   A. left
   B. right
   C. none
   D. inline
   **Answer:** A. left, B. right, C. none

3. What happens to inline content around a floated element?
   A. It ignores the floated element
   B. It wraps around the floated element
   C. It disappears
   D. It moves below the floated element
   **Answer:** B. It wraps around the floated element

4. How do you clear floats to prevent parent collapse?
   A. clear: left/right/both
   B. overflow: hidden
   C. Both A and B
   D. float: none
   **Answer:** C. Both A and B

5. Which of the following is true about floated elements?
   A. They are removed from normal document flow
   B. Parent containers may collapse
   C. Inline content wraps around them
   D. All of the above
   **Answer:** D. All of the above

6. What is the default value of `float`?
   A. left
   B. right
   C. none
   D. inherit
   **Answer:** C. none

7. Which property stops text from wrapping around a floated element?
   A. clear
   B. overflow
   C. display
   D. float
   **Answer:** A. clear

8. How can you force a parent container to expand to contain floated children?
   A. Use a clearfix with `::after` pseudo-element
   B. Set `overflow: auto` or `hidden` on the parent
   C. Both A and B
   D. Float the parent as well
   **Answer:** C. Both A and B

9. Can multiple elements float in the same direction?
   A. Yes
   B. No
   **Answer:** A. Yes

10. What happens if `float: left;` is applied to two block elements consecutively?
    A. They stack vertically
    B. They sit side by side
    C. One disappears
    D. Only the first floats
    **Answer:** B. They sit side by side

# CSS MCQs - Combinators

This document contains multiple-choice questions (MCQs) on the CSS topic **Combinators**.

---

## Combinators

1. Which combinator selects elements that are direct children of a specified element?
   A. Descendant selector
   B. Child selector (`>`)
   C. Adjacent sibling (`+`)
   D. General sibling (`~`)
   **Answer:** B. Child selector (`>`)

2. Which combinator selects elements that are anywhere inside a specified element?
   A. Descendant selector (space)
   B. Child selector (`>`)
   C. Adjacent sibling (`+`)
   D. General sibling (`~`)
   **Answer:** A. Descendant selector (space)

3. Which combinator selects the immediate next sibling element?
   A. Descendant selector
   B. Child selector
   C. Adjacent sibling (`+`)
   D. General sibling (`~`)
   **Answer:** C. Adjacent sibling (`+`)

4. Which combinator selects all siblings after a specified element?
   A. Descendant selector
   B. Child selector
   C. Adjacent sibling (`+`)
   D. General sibling (`~`)
   **Answer:** D. General sibling (`~`)

5. Which combinator is used in `div > p`?
   A. Descendant
   B. Child
   C. Adjacent
   D. General sibling
   **Answer:** B. Child

6. Which combinator is used in `div p`?
   A. Descendant
   B. Child
   C. Adjacent
   D. General sibling
   **Answer:** A. Descendant

7. Which combinator would select the second `p` immediately following a `h1`?
   A. h1 p
   B. h1 > p
   C. h1 + p
   D. h1 ~ p
   **Answer:** C. h1 + p

8. Which combinator would select all `p` elements after a `h1` sibling?
   A. h1 p
   B. h1 > p
   C. h1 + p
   D. h1 ~ p
   **Answer:** D. h1 ~ p

9. Which combinator requires no symbol but a space?
   A. Descendant
   B. Child
   C. Adjacent sibling
   D. General sibling
   **Answer:** A. Descendant

10. Which combinator would select `p` elements inside `div` but not directly under it?
    A. div > p
    B. div p
    C. div + p
    D. div ~ p
    **Answer:** B. div p



Pseudo-Classes

What is a CSS pseudo-class?
A. A class that selects an element based on its state or position
B. A normal CSS class
C. A JavaScript function
D. An ID selector
Answer: A. A class that selects an element based on its state or position

Which pseudo-class selects the first child of a parent?
A. :last-child
B. :first-child
C. :nth-child(1)
D. :only-child
Answer: B. :first-child

Which pseudo-class applies style when a user hovers over an element?
A. :active
B. :focus
C. :hover
D. :visited
Answer: C. :hover

Which pseudo-class targets links that have been clicked?
A. :link
B. :hover
C. :visited
D. :active
Answer: C. :visited

Which pseudo-class applies style to a focused form element?
A. :focus
B. :hover
C. :active
D. :checked
Answer: A. :focus

Which pseudo-class targets elements that are the only child of their parent?
A. :first-child
B. :last-child
C. :only-child
D. :nth-child(1)
Answer: C. :only-child

Which pseudo-class applies when an element is being clicked?
A. :hover
B. :focus
C. :active
D. :checked
Answer: C. :active

Which pseudo-class is used to style every even child of a parent?
A. :nth-child(even)
B. :nth-child(odd)
C. :first-child
D. :last-child
Answer: A. :nth-child(even)

Which pseudo-class selects checked input elements like checkboxes or radio buttons?
A. :checked
B. :selected
C. :active
D. :focus
Answer: A. :checked

Which pseudo-class selects elements that are empty (no child elements)?
A. :empty
B. :blank
C. :null
D. :void
Answer: A. :empty


Pseudo-Elements

What is a CSS pseudo-element?
A. A selector that styles part of an element
B. A normal CSS class
C. A JavaScript function
D. An ID selector
Answer: A. A selector that styles part of an element

Which pseudo-element inserts content before an element's content?
A. ::after
B. ::before
C. :first-child
D. :last-child
Answer: B. ::before

Which pseudo-element inserts content after an element's content?
A. ::after
B. ::before
C. :first-child
D. :last-child
Answer: A. ::after

Which pseudo-element targets the first line of a block of text?
A. ::first-letter
B. ::first-line
C. ::before
D. ::after
Answer: B. ::first-line

Which pseudo-element targets the first letter of a block of text?
A. ::first-letter
B. ::first-line
C. ::before
D. ::after
Answer: A. ::first-letter

Which pseudo-element allows you to style the placeholder text in an input field?
A. ::placeholder
B. ::before
C. ::after
D. ::first-letter
Answer: A. ::placeholder

Which pseudo-element allows content to be styled in a specific part of an element?
A. ::before and ::after
B. ::first-letter and ::first-line
C. Both A and B
D. None of the above
Answer: C. Both A and B

Can pseudo-elements be used with classes and IDs?
A. Yes
B. No
Answer: A. Yes

Which pseudo-element is used to style a selection made by the user?
A. ::selection
B. ::highlight
C. ::selected
D. ::active
Answer: A. ::selection



Navbars

Which CSS property is commonly used to create a horizontal navbar?
A. display: block
B. display: flex
C. float: left
D. position: absolute
Answer: B. display: flex

How can you remove bullets from a list used in a navbar?
A. list-style-type: none;
B. display: none;
C. text-decoration: none;
D. float: none;
Answer: A. list-style-type: none;

Which property is used to space navbar items evenly?
A. justify-content
B. align-items
C. float
D. margin
Answer: A. justify-content

How can you make navbar items change color on hover?
A. a:hover { color: red; }
B. li:hover { color: red; }
C. div:hover { color: red; }
D. ul:hover { color: red; }
Answer: A. a:hover { color: red; }

Which property fixes the navbar at the top of the page while scrolling?
A. position: static
B. position: relative
C. position: fixed
D. float: top
Answer: C. position: fixed

Which property changes the background color of a navbar?
A. color
B. background-color
C. border-color
D. text-color
Answer: B. background-color

How do you horizontally align items in a flex-based navbar?
A. align-items: center;
B. justify-content: space-between;
C. text-align: center;
D. Both A and B
Answer: D. Both A and B

Which element is typically used to create a navbar?
A.
B.
C.
D.
Answer: B.

How can you make a responsive navbar collapse on smaller screens?
A. Using media queries
B. Using float
C. Using inline styles
D. Using z-index
Answer: A. Using media queries

Which pseudo-class is often used for active navbar links?
A. :hover
B. :focus
C. :active
D. :visited
Answer: C. :active

Which of these is the correct syntax for pseudo-elements?
A. :before
B. ::before
C. ::after
D. All of the above
Answer: D. All of the above


# CSS MCQs - Dropdowns

This document contains multiple-choice questions (MCQs) on the CSS topic **Dropdowns**.

---

## Dropdowns

1. Which property is commonly used to hide a dropdown menu by default?
   A. display: none
   B. visibility: hidden
   C. opacity: 0
   D. All of the above
   **Answer:** D. All of the above

2. Which pseudo-class shows a dropdown when hovering over a parent element?
   A. :focus
   B. :hover
   C. :active
   D. :checked
   **Answer:** B. :hover

3. Which CSS property is used to position the dropdown menu relative to the parent?
   A. position: relative
   B. position: absolute
   C. float
   D. display: block
   **Answer:** B. position: absolute

4. How can you prevent the dropdown menu from being cut off by overflow?
   A. overflow: visible;
   B. overflow: hidden;
   C. overflow: scroll;
   D. overflow: auto;
   **Answer:** A. overflow: visible;

5. Which property controls the spacing of items inside the dropdown?
   A. padding
   B. margin
   C. line-height
   D. All of the above
   **Answer:** D. All of the above

6. How can you make a dropdown menu appear smoothly?
   A. transition
   B. animation
   C. Both A and B
   D. overflow
   **Answer:** C. Both A and B

7. Which property ensures the dropdown menu stays above other elements?
   A. z-index
   B. float
   C. display
   D. position
   **Answer:** A. z-index

8. Which HTML element usually triggers a dropdown?
   A. <div>
   B. <button> or <a>
   C. <span>
   D. <ul>
   **Answer:** B. <button> or <a>

9. How can you create a responsive dropdown menu for mobile devices?
   A. Media queries
   B. Flexbox or Grid layout
   C. Both A and B
   D. float
   **Answer:** C. Both A and B

10. Which pseudo-class can show a dropdown menu when a button is focused via keyboard navigation?
    A. :hover
    B. :focus
    C. :active
    D. :checked
    **Answer:** B. :focus

