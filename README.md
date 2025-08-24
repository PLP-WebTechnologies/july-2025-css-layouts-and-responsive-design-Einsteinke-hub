🌐 Responsive Webpage with CSS Grid & Flexbox






A single-page, responsive website built with pure HTML & CSS, showcasing the combined power of CSS Grid for layout and Flexbox for components.

📑 Table of Contents

✨ Features

⚙️ How It Works

📂 File Structure

🚀 Usage

📸 Screenshots

🔗 Live Demo

🛠️ Technologies Used

📜 License

✨ Features

📱 Responsive Design – Adapts seamlessly to desktop, tablet, and mobile screens.

🟦 CSS Grid – Structures the main layout (header, nav, main, aside, footer).

🟧 Flexbox – Aligns navigation links and content cards dynamically.

🚫 No Frameworks – 100% vanilla HTML + CSS, no libraries used.

🌍 Fluid Content – Currently themed as Wanderlust Chronicles but easily customizable.

⚙️ How It Works
🏗️ Main Layout with CSS Grid (.grid-container)

display: grid; creates the grid layout.

grid-template-areas + grid-template-columns define the structure.

@media queries adjust grid layout at breakpoints (📱 sidebar stacks below main content on smaller screens).

🧭 Navigation & Content Cards with Flexbox

display: flex; on .nav-links and .content-container.

flex-wrap: wrap; allows items to flow onto new lines responsively.

flex: 1 1 300px; on .content-card means:

1 → Can grow (flex-grow: 1)

1 → Can shrink (flex-shrink: 1)

300px → Preferred base width (flex-basis).

💡 Tip: Resize your browser window to see the responsive behavior in action.

📂 File Structure
project/
│── index.html    # Main HTML file
│── styles.css    # External stylesheet (if not embedded in HTML)
│── assets/       # Images, icons, etc.

🚀 Usage

Clone or download the repository:

git clone https://github.com/your-username/responsive-webpage.git
cd responsive-webpage


Open index.html in any modern browser.

Resize the window to test responsiveness.

📸 Screenshots
Desktop View	Mobile View

	
🔗 Live Demo

👉 View Demo on GitHub Pages

🛠️ Technologies Used

HTML5 – Semantic structure

CSS3 – Grid, Flexbox, Media Queries

📜 License

This project is licensed under the MIT License – feel free to use, modify, and share.
