🐦 Twitter (X) Clone

A fully responsive Twitter (now X) clone built with HTML5 and Tailwind CSS, replicating the look and feel of the Twitter web app interface.

This project was created as a hands-on exercise to strengthen frontend skills while learning modern utility-first styling with Tailwind. It focuses purely on the UI layer — showcasing layouts, components, and styling without backend functionality.

📸 Screenshot

Here’s how the app looks:Screenshot From 2025-09-05 01-15-42.png

✨ Features

🔹 Responsive Layout: Works across desktop and mobile screens with a grid-based, flexible design.

🔹 Twitter-like Sidebar Navigation: Includes all primary links (Home, Explore, Notifications, Messages, Lists, Bookmarks, Communities, Premium, Profile, More).

🔹 Post Creation UI: Input box with icons for media, GIFs, polls, emojis, calendar, and location.

🔹 Feed Section: Styled sample posts with user profile, content, images, and interactive icons (like, retweet, comment, analytics).

🔹 Right Panel Widgets: “What’s Happening” trending section, “Who to Follow” suggestions, and Terms/Privacy links.

🔹 Sticky Headers/Sections: Smooth scrolling with fixed top navigation and right-panel cards.

🔹 Dark Theme: Styled with Tailwind utility classes for a black/gray modern UI.

🔹 Scalable Component Structure: Built with reusable Tailwind classes that can be extended into a real application with React, Vue, or backend integration.

🛠️ Tech Stack

HTML5 – Semantic structure of the app.

Tailwind CSS – Utility-first CSS for rapid styling.

Google Fonts (Material Symbols) – For icons and UI consistency.

📂 Project Structure
├── index.html              # Main HTML structure
├── css/
│   └── output.css          # Tailwind-generated CSS
├── Screenshot From 2025-09-05 01-15-42.png   # Preview screenshot
└── README.md               # Project documentation

🚀 Getting Started

Follow these steps to run the project locally:

1️⃣ Clone the repository
git clone https://github.com/your-username/twitter-clone.git
cd twitter-clone

2️⃣ Install dependencies

Ensure you have Node.js and Tailwind CLI installed.
Initialize Tailwind if needed:

npm install -D tailwindcss
npx tailwindcss init

3️⃣ Build Tailwind CSS

Run Tailwind in watch mode to generate output.css:

npx tailwindcss -i ./input.css -o ./css/output.css --watch

4️⃣ Open in browser

Simply open index.html in your browser to view the project.

📖 Learning Outcomes

By building this project, I practiced:

Responsive UI design with Tailwind CSS

Layout building using Flexbox & Grid utilities

Managing dark UI themes with proper contrast

Creating reusable UI patterns (posts, sidebars, trending widgets)

Preparing project documentation and showcasing work on GitHub

🔮 Future Improvements

Some potential upgrades to turn this static clone into a functional app:

🔗 Convert to React + Tailwind for dynamic components.

🗄️ Add Firebase / Supabase backend for auth, posts, likes, and comments.

🌍 Implement real-time updates with WebSockets.

🎨 Add light/dark mode toggle.

📱 Progressive Web App (PWA) support.

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and open a PR with improvements.

📜 License

This project is licensed under the MIT License – free to use and modify.

👨‍💻 Author

Mohit Kr. Biswas

🌐 GitHub: Xen0pp

🐦 Twitter: @Xen0pp
