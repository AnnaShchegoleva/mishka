#Personal project «Mishka»

Online store of cute things for home handmade.

“Mishka”. Adaptive Website. The project was implemented HTML&CSS, Adaptive Website Coding and Automation. Less, Gulp, JS, Figma, Webstorm.

*Description*
Grid: defined in the layout.
Grid adaptability: mobile, tablet and desktop versions (“fixed” or “rubber”). 
Graphics adaptability: retinization, vector images.
Methodology used: BEM.
Preprocessor used: Less or Sass.
Used automation tool: Gulp.
Crossbrowser compatibility: Chrome, Firefox, Safari.
Typography: partially defined in the layout (others are up to the developer).
Font used: Open Sans.

The project has 3 pages (main page, form page, catalog page).
Layouts have modal windows.
Layouts are made up gradually: first the mobile version, then from the mobile version to the tablet version, and then to the desktop one.


Block Behavior Requirements

Between versions (mobile, tablet, desktop), the grid can be either fluid or fixed.
With a fixed grid, the content area is centered and cannot be narrower than the layout width. Backgrounds that rest against the edges of the layout should extend to the entire page.
The logo on the inner pages is a link to the main page.
Wavy line graphics must be limited to the width of the content area.
The main menu in the mobile version appears under the site header.
The mobile menu can be implemented in two ways:
   implementation without JS;
   implementation using JS.
When implemented without using JS, the main menu in the mobile version should always be open, and the icon with a cross should be hidden. 
When implemented using JS, the block with the main menu in the mobile version should open when you click on the “hamburger” icon. When the menu is open, the hamburger icon changes to a cross. Clicking on the cross icon closes the menu.
All hover and click states of elements are specified in the style guide.
The Academy logo and the HTML Academy link in the footer lead to the landing page https://up.htmlacademy.ru/.

Index
Mobile version (Index > Mobile):
The logo consists only of the name of the store "Mishka".
In the blocks "Interior items" and "Children's toys", the link should not be the text, but the entire block. When pressed, the transition to the corresponding sections of the catalog should be carried out (section pages do not need to be implemented).
The button for ordering the product of the week should cause a modal window to appear.
Block "Reviews": scrolling through the reviews is not necessary. Sufficient implementation would be a typed 1 review and review toggle buttons.
The button in the "Reviews" block should lead to the page for adding a review (the page for adding a review does not need to be implemented).
Map block: the required implementation is an interactive map (Google or Yandex maps), the width adjusts to the width of the viewport (but not narrower than the content width of the layout), a marker is placed on the map (it can be either custom or default), the center of the map corresponds to the center of the block in layout.
The "Write to us" button should lead to a page with a feedback form (the page with a feedback form does not need to be implemented).

Tablet version (Index > Tablet):
Blocks change size and position according to the layout.
New elements are being added to the logo. 
The main menu is always open regardless of its state on the mobile version.

Desktop version (Index > Desktop):
Blocks change size and position according to the layout.
New elements are added to the logo.


Form
The form page should not have a modal window.

Mobile version (Form > Mobile):
Custom form elements must be implemented.
The phone and mail input fields must have the appropriate types for convenient filling from the phone.
If you try to submit a form that has the phone or mail fields filled with data in the wrong format, you receive an error message built into the browser.

Tablet version (Form > Tablet):
Blocks change size and position according to the layout.

Desktop version (Form > Desktop):
Blocks change size and position according to the layout.

Catalog page

Mobile version (Catalog > Mobile):
The image and name of the product are links to the page with a detailed description of the product (the page with a detailed description of the product does not need to be implemented). 
The cart icon should cause a modal window to appear.
In the "Production process" video player block, you need to implement a container for the player with a video recording (you do not need to add a video player script to the page, just add an image from the layout).

Tablet version (Catalog > Tablet):
Blocks change size and position according to the layout.

Desktop version (Catalog > Desktop):
Blocks change size and position according to the layout.



___________________________
Layout
https://www.figma.com/file/S1Uu6NqtWVQT64XqcXdlB5/HTML-2-%2F-Mishka?node-id=1159%3A685
