# YouTube_Clone_Web_SK Website: https://sk-epic-24.github.io/YouTube_Clone_Web_SK/

🎥 YouTube Clone (HTML + CSS)
This project is a static front-end clone of YouTube, built using only HTML5 and CSS3. It focuses on replicating the basic layout and design elements of the popular video platform, providing a responsive and visually clean interface.

🔧 Tech Stack
HTML5: Markup for structure

CSS3: Styling and layout

Google Fonts: For clean and modern typography (Roboto)

📁 Folder Structure

bash

Copy

Edit

/project-root

│

├── /icons          # All SVG icons like search, bell, mic, etc.

├── /images         # Logos, thumbnails, and avatar images

├── index.html      # Main HTML file

└── style.css       # Styling for the entire layout

🖼️ Features & Components
1. Sidebar Navigation (<aside>)
Contains quick-access icons like:

Home

Explore

Subscriptions

Library

SVG icons are used for a minimal look.

Stack is vertical, suitable for desktop layout.

2. Top Navigation Bar (<nav>)
Includes:

YouTube Logo

Search Bar with a search button

Microphone icon

User action icons (upload, grid, bell, avatar)

Flexbox is used for proper alignment and spacing.

3. Tags Navigation
Horizontal list of video filter categories (All, Mixes, Crypto, HTML, CSS, JavaScript)

dark and light classes help distinguish selected tags using background colors.

4. Main Video Feed (<main>)
Videos are laid out in a responsive grid.

Each video card includes:

Thumbnail

Channel avatar

Video title

Channel name

View count and time

Three-dot icon for more actions

5. Cards
Structured with:

.card-container: Defines the grid layout

.card: Individual video containers

.avatar-content: Flex layout for avatar and text

.content-status: Metadata like views and posted date

💡 Responsive Design
Utilizes auto-fit and minmax() in CSS Grid to make cards responsive.

Flexbox is used in navs and card elements for easy alignment.

🎯 Future Enhancements
This is a static front-end clone. You can improve it by:

Adding a mobile view toggle (hamburger menu).

Integrating JavaScript for dynamic features.

Connecting to a back-end to fetch live video data.

Animating hover effects for interactivity.

📜 License
This project is open-source and available under the MIT License.

🙌 Acknowledgements
Inspired by the clean UI of YouTube and created for educational and practice purposes.

Author:
SHyamsunder Kadam
