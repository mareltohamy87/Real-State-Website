🚀 New Project: MyNest – Real Estate Landing Page
Project: MyNest — Real-estate Landing Page
Role: Front-End Developer (project by me during Route Academy)
Overview:
MyNest is a clean, modern landing page for a real-estate service. It showcases the hero area (Buy / Rent CTAs), company highlights, client success stories, a “Recently Added” grid of properties, a contact/subscribe section, and a footer with social links.

🔧 Built with:

Responsive header with desktop nav and a mobile side menu (checkbox + overlay technique).

Hero section with clear CTAs and responsive image.

Info cards (Available / Sold / Rented / Happy clients) and client testimonial cards.

A flexible “Recently Added” properties grid with image cards, pricing and quick actions.

Contact and Subscribe sections with accessible form inputs and responsive buttons.

💡 Technologies & tools:

HTML5

CSS3 (Flexbox & Grid)

Custom responsive grid (grid.css) inspired by Bootstrap utilities

CSS techniques: media queries, transitions, overlay, absolute positioning for dropdowns/side menu

Assets & fonts via fonts.css

⚙️ Challenges faced & how I solved them:

Responsive layout changes (different breakpoints): tuned media queries and used a custom grid + flex utilities to ensure elements reflow cleanly from desktop to mobile.

Mobile navigation & overlay: implemented a pure-CSS sidebar using a hidden checkbox + adjacent overlay to avoid JavaScript and keep interactions lightweight.

Dropdown / submenu positioning: used position: absolute with careful z-index and box-shadow, plus hover states and spacing adjustments to prevent clipping and overlap on various viewports.

Image sizing & card alignment: ensured images used width:100% and applied consistent paddings/margins to keep card heights readable across screen sizes.

Visual consistency (spacing/typography/colors): centralized font imports and color utilities (class-based) to maintain a consistent UI and speed up styling.
<img width="1841" height="902" alt="my-nest-home" src="https://github.com/user-attachments/assets/4ae5c503-3411-4a38-addb-818250bebbfe" />


What I learned:

How to implement a CSS-only responsive navigation pattern that works well without JS.

Practical handling of layout edge-cases across breakpoints (cards, grids, and overlay interactions).

Better organization of styles with modular files (fonts.css, grid.css, style.css) and utility classes.

Short bullets to add under the Project entry (optional)

Built responsive UI with semantic HTML and modular CSS.

Implemented CSS-only mobile side menu (checkbox + overlay).

Designed reusable card components for property listings.

Focus on accessibility and performance (minimal JS, optimised layout).
