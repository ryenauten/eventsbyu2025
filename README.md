# BYU Events App

A simple web application for browsing BYU campus events.

## Features

- Browse events by category (Sports, Underclassman, Senior, Club)
- View event details
- Save events to personal calendar
- Browse BYU clubs

## Project Structure

\`\`\`
byu-events-app/
├── index.html          # Homepage
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
└── pages/              # Additional HTML pages
    ├── sports.html
    ├── underclassman.html
    ├── senior.html
    ├── club.html
    ├── calendar.html
    ├── clubs.html
    └── event-detail.html
\`\`\`

## How to Use

1. Clone this repository
2. Open `index.html` in your browser

## GitHub Pages Setup

To host this site on GitHub Pages:

1. Push this repository to GitHub
2. Go to your repository settings
3. Scroll down to the GitHub Pages section
4. Select the main branch as the source
5. Your site will be published at `https://[your-username].github.io/[repository-name]/`
\`\`\`

## How to Upload to GitHub

Here are the steps to upload this project to GitHub:

1. **Create a new repository on GitHub**:
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right and select "New repository"
   - Name your repository (e.g., "byu-events-app")
   - Choose public or private visibility
   - Click "Create repository"

2. **Initialize Git locally and push your code**:
   ```bash
   # Navigate to your project folder
   cd path/to/byu-events-app

   # Initialize a new Git repository
   git init

   # Add all files to staging
   git add .

   # Commit the files
   git commit -m "Initial commit"

   # Add the remote GitHub repository
   git remote add origin https://github.com/your-username/byu-events-app.git

   # Push to GitHub
   git push -u origin main