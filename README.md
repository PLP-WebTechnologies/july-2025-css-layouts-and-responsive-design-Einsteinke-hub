#🌐 Responsive Webpage with CSS Grid & Flexbox






#A single-page, responsive website built with pure HTML & CSS, showcasing the combined power of CSS Grid for layout and Flexbox for components.

#✨ Features

📱 Responsive Design – Works perfectly on desktop, tablet, and mobile.

🟦 CSS Grid – Defines main page structure (header, nav, main, aside, footer).

🟧 Flexbox – Aligns navigation links and responsive content cards.

🚫 No Frameworks – 100% vanilla HTML + CSS.

🌍 Fluid Content – Themed as Wanderlust Chronicles but easily adaptable.

⚙️ How It Works
🏗️ Layout with CSS Grid (.grid-container)

display: grid; creates the main grid.

grid-template-areas defines readable layout zones.

@media queries adjust layout for different screen sizes (sidebar stacks below main on mobile).

🧭 Navigation & Cards with Flexbox

display: flex; on .nav-links and .content-container.

flex-wrap: wrap; ensures cards move onto new lines responsively.

flex: 1 1 300px; on .content-card ensures cards scale smoothly.

📂 File Structure
project/
│── index.html   # Main HTML file
│── styles.css   # External stylesheet (if not embedded)
│── assets/      # Images, icons, etc.

🚀 Usage

Clone or download the repository.

git clone https://github.com/your-username/responsive-webpage.git
cd responsive-webpage


Open index.html in any modern browser.

Resize the browser window to test responsiveness.

📸 Screenshots
Desktop View	Mobile View

	
🔗 Live Demo

👉 View Demo on GitHub Pages

🛠️ Technologies Used

HTML5 – semantic structure

CSS3 – Grid, Flexbox, Media Queries

📜 License

This project is licensed under the MIT License – feel free to use and modify.
