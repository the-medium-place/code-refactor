# Code Refactor

This is the first assignment for the UW Coding Bootcamp - Due Thursday, March 5, 2020 11:59 PM. 

The Objective of this assignment was to refactor the html and css code of a website which was provided.  This source website had many pieces of redundant or missing code outlined below.

### index.html  

* **Lines 10 and 23:** Changed the ` <div class="header"> ... </div> ` tags to read ` <header> ... </header> ` 

* **Lines 71 and 76:** Changed the ` <div class="footer"> ... </div> ` tags to read ` <footer> ... </footer> `

* **Lines 33 and 40:** Remove unnecessary `id` tags from `<div class="online-reputation-management">`, and `<div class="social-media-marketing">`.

* **Lines 27, 34 and 41:** Add `alt` tags to the images inside `<div class="search-engine-optimization">`, `<div class="online-reputation-management">` and `<div class="social-media-marketing">`

* **Line 65:** Remove unnecessary `</img>` tag

* **Lines 26, 32, 33, 34, 39, 40, 41 and 46** Change `<div>` tags to `<section>` tags to delineate their primary positioning on the page

* **Lines 48 and 70** Change `<div>` tag to `<aside>` tags to delineate their secondary positioning on the page

### style.css

* Placed single quotes around `Calibri`

* Changed all `.header` and `.footer` class selectors to the `header` and `footer` html tag selectors to match changes made on `index.html`.

* Rearrange selectors for clarity: *html selectors before class selectors*.

* `.benefit-lead`, `.benefit-brand` and `.benefit-cost` selectors have identical styles. I combined them into a single block of code at **Line 113**. 

* `.benefit-lead h3`, `.benefit-brand h3` and `.benefit-cost h3` selectors have identical styles. I combined them into a single block of code at **Line 118**. 

* `.benefit-lead img`, `.benefit-brand img` and `.benefit-cost img` selectors have identical styles. I combined them into a single block of code at **Line 123**. 

* `.search-engine-optimization`, `.online-reputation-management` and `.social-media-marketing` selectors have identical styles. I combined them into a single block of code at **Line 129**. 

* `.search-engine-optimization img`, `.online-reputation-management img` and `.social-media-marketing img` selectors have identical styles. I combined them into a single block of code at **Line 139**. 

* `.search-engine-optimization h2` and `.social-media-marketing h2` selectors have identical styles. I combined them into a single block of code at **Line 143**. 

* `.search-engine-optimization`, `.online-reputation-management` and `.social-media-marketing`: added `overflow:auto;` so content does not spill out of container with resizing of the page





