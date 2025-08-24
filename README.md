🌐 Responsive Webpage with CSS Grid & Flexbox

This project is a single-page, responsive website built using pure HTML and CSS. It demonstrates the combined power of CSS Grid for the main layout and Flexbox for flexible, component-level design.

✨ Features

📱 Responsive Design – Adapts seamlessly to desktop, tablet, and mobile with CSS media queries.

🟦 CSS Grid – Manages the main page structure (header, nav, main, aside, footer) using grid-template-areas for readability.

🟧 Flexbox – Used for navigation links and content cards, ensuring alignment, wrapping, and flexibility.

🚫 No Frameworks – 100% raw CSS, showcasing fundamental layout principles.

🌍 Fluid Content – Currently themed as Wanderlust Chronicles (travel blog), but adaptable for any topic.







⚙️ How It Works
🏗️ Main Layout (.grid-container)

display: grid; sets up the grid.

grid-template-areas + grid-template-columns define structure.

@media queries adjust grid areas at breakpoints (sidebar stacks under main content on smaller screens).

🧭 Navigation & Content Cards

display: flex; on .nav-links and .content-container.

flex-wrap: wrap; allows items to move onto new lines as needed.

flex: 1 1 300px; on .content-card makes each card:

grow (flex-grow: 1)

shrink (flex-shrink: 1)

prefer a base width of 300px (flex-basis).

📂 File Structure
project/
│── index.html   # Main HTML file
│── styles.css   # CSS file (if separated from HTML)

🚀 Usage

Open index.html in any modern browser.

Resize the window to see the responsive design in action.
