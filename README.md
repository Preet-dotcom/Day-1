# Day-1: Responsive Landing Page

A simple, clean, and responsive landing page built with HTML and CSS. It includes a sticky header, hero section with a call-to-action, a small features area, and a footer with social links.

## Features
- Responsive layout (mobile to desktop)
- Sticky header with navigation
- Hero section with headline, description, and CTA button
- Lightweight: no frameworks, just HTML and CSS
- Accessible markup and keyboard-friendly mobile nav toggle

## Project Structure
```
DAY-1/
├─ index.html      # Main HTML page
├─ style.css       # Styles for layout, components, and responsive rules
└─ README.md       # Project documentation
```

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Preet-dotcom/Day-1.git
   cd Day-1
   ```
2. Open `index.html` directly in your browser, or use a local server (recommended):
   - VS Code: Install "Live Server" and click "Go Live".
   - Or use Python:
     ```bash
     python3 -m http.server 5500
     # Then open http://localhost:5500 in your browser
     ```

## Customize
- Edit text in `index.html` to match your product or service.
- Adjust colors, spacing, and breakpoints in `style.css`.
- Replace social links in the footer with your own profiles.

## Responsive Notes
- Navigation collapses to a toggle on small screens.
- Layout switches to a single column below ~900px.

## Deploy (GitHub Pages)
1. Push to `main` (already set up).
2. In GitHub repo Settings -> Pages -> Build and deployment -> Deploy from branch.
3. Select Branch `main` and folder `/ (root)`, then Save.
4. Your site will be available at the Pages URL shown in the settings.

## License
MIT — feel free to use and modify.
