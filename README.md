# zodiac-gallery

image gallery
This project is my second bootcamp assignment, where I built a responsive, accessible, and interactive Zodiac Mythology Gallery using HTML, CSS Grid, Flexbox, and JavaScript.

All zodiac images in the gallery were created by me using Canva AI, giving the project a unique and cohesive visual theme.

**Features Implemented**

**Responsive Layout**
Works across mobile, tablet, and desktop screens.
Uses an orientation-based media query to create a meaningful layout change in landscape mode.
CSS Grid used to build a custom structure that frames the fullscreen viewing area.

**Dynamic JavaScript Rendering**
Zodiac signs are stored in an array of objects.
JavaScript inserts each thumbnail into a specific grid location.
Clicking a thumbnail displays the full image in a fullscreen viewing area.

**Accessibility**
Each image includes descriptive alt text for screen readers.
Clean semantic structure enhances accessibility.

**Creative Design**
All artwork was generated with Canva AI.
Titles placed around the layout help organize and frame the gallery.
The fullscreen viewer offers an engaging, immersive experience.

**Technical Overview**

**HTML**
Uses semantic tags: header, main, footer.
A gallery-grid container manages layout.
A fullscreen-container displays selected images.

**CSS**
CSS Grid positions thumbnails and titles.
Flexbox centers items.
object-fit manages image behavior inside containers.
A landscape orientation media query defines the desktop layout.

**JavaScript**
Uses an array of objects containing:imageName, imageGod, thumbSrc, fullSrc, imageAlt, description.
Interacts with the DOM using querySelector and getElementById.
Event listeners handle click actions to swap images.

**Stretch Goals Planned for Future Updates**
ARIA and Accessibility Enhancements
Add aria-label to thumbnails
Add aria-describedby for fullscreen images
Add role="button" to interactive elements
Add aria-live for dynamic content updates
Keyboard Navigation

**Challenges Faced**
Image Fitting
Positioning and resizing images inside both the grid and fullscreen view required experimenting with object-fit and size constraints.
Media Query Selection: Width-based breakpoints did not work well with the custom layout.Using @media (orientation: landscape) produced the intended effect.

Grid Layout Complexity coordination
The gallery uses a creative “frame” structure rather than simple rows.
