#Responsive Webpage with CSS Grid & Flexbox
This project is a single-page, responsive website built using pure HTML and CSS. It showcases the combined power of CSS Grid for a robust main layout and Flexbox for flexible, component-level design.

#Features
Responsive Design: The layout adapts seamlessly to different screen sizes, including desktop, tablet, and mobile, using CSS media queries.

CSS Grid: The main page structure (header, nav, main, aside, footer) is managed by CSS Grid, using grid-template-areas for a clear, readable layout.

Flexbox: Flexbox is used for laying out the navigation links and the content cards in the main section. It ensures these elements align and wrap dynamically based on the available space.

No Frameworks: The entire layout and styling are built with raw CSS, demonstrating a fundamental understanding of core layout properties.

Fluid Content: The content is focused on a "Wanderlust Chronicles" travel theme, but the layout is easily adaptable for any topic.

#How It Works
Main Layout (.grid-container):

display: grid; creates the main grid layout.

grid-template-areas and grid-template-columns define the structure for different screen sizes.

Media queries (@media (max-width: ...) ) are used to redefine the grid-template-areas at specific breakpoints, causing the sidebar to stack below the main content on smaller screens.

#Navigation & Content Cards:

display: flex; is applied to .nav-links and .content-container.

flex-wrap: wrap; allows the items to flow onto new lines as needed, which is crucial for the responsive card layout.

The flex: 1 1 300px; shorthand property on .content-card tells each card to be flexible (flex-grow: 1), shrinkable (flex-shrink: 1), and have a preferred base width of 300px (flex-basis: 300px).

#File Structure
The project is contained within a single HTML file with embedded CSS. For a more organized project, the CSS would be separated into a style.css file linked to the index.html document.

#Usage
To view the webpage, simply open the index.html file in any modern web browser. You can then resize the browser window to see the responsive layout in action.
