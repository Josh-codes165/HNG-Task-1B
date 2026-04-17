 Joshua — Developer Profile Card

A clean, responsive, and fully testable Profile Card component built with pure HTML, CSS, and JavaScript. Designed to showcase a developer's identity, skills, stats, and social presence — all in a single elegant card.

✨ Live Preview

A warm-toned, modern profile card with a live timestamp, animated status badge, social links, and responsive layout — built without any frameworks.

📁 Project Structure
profile-card/
├── index.html      # Markup & semantic structure
├── style.css       # All visual styling & responsive rules
├── script.js       # Live timestamp logic
└── profile.jpg     # Avatar image

🚀 Features
Live Timestamp — Footer displays a real-time Unix timestamp, updated every second via setInterval
Open to Work Badge — Animated blinking dot signals availability
Stats Section — Projects, months of learning, and stacks at a glance
Hobbies & Dislikes Panels — Two-column layout revealing personality
Social Links — Direct buttons to Twitter/X, GitHub, and LinkedIn
Skill Tags — React, Web3, UI Design, JavaScript, FUTO
Fully Responsive — Gracefully adapts to screens as narrow as 320px
Test-Ready — Every key element carries a data-testid attribute for automated testing

🧪 Test IDs Reference
All interactive and content elements are wired with data-testid attributes for easy querying in test suites (Jest, Playwright, Cypress, etc.):
Element

data-testid
Profile card root
test-profile-card
User avatar
test-user-avatar
User name
test-user-name
Bio paragraph
test-user-bio
Hobbies section
test-user-hobbies
Dislikes section
test-user-dislikes
Social links nav
test-user-social-links
Twitter/X link
test-user-social-twitter
GitHub link
test-user-social-github
LinkedIn link
test-user-social-linkedin
Live time display
test-user-time

🛠️ Getting Started
No build tools. No dependencies. Just open and go.

1. Clone the repo
git clone https://github.com/Josh-codes165/profile-card.git
cd profile-card

2. Add your avatar
Place your profile image in the root directory and name it profile.jpg, or update the src in index.html:
<img src="/your-image.jpg" alt="Your Name profile avatar" />

3. Open in browser
# Simply open index.html in any browser
open index.html

 For local font loading, serve with a simple local server:
npx serve .
# or
python -m http.server 8000

 Design Tokens
The card uses a consistent warm earth-tone palette:

Role
Color
Background
#f5e6dc
Card surface
#fffaf7
Primary text
#2c1a0e
Accent / handles
#c9956a
Muted text
#a07060
Border
#e8d5c8

Typography is powered by Inter (Google Fonts) at weights 400, 500, 600, and 700.
📱 Responsive Behaviour
Breakpoint
Layout change
> 420px
Full layout — hero, two-col panels, inline socials
≤ 420px

Hero wraps, panels stack to 1 column, socials go vertical

🔧 Customisation
To make this card your own, update the following in index.html:
Name — data-testid="test-user-name"
Handle — .handle span
Location — text inside .location
Bio — data-testid="test-user-bio"
Tags — .tags section
Stats — .stat-num values
Hobbies / Dislikes — list items inside each .panel
Social URLs — href on each .social-btn

👤 Author
Joshua Okoronkwo
Frontend Developer · Web3 Enthusiast · 


Built with 💛 and zero frameworks — just HTML, CSS & JavaScript

