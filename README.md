# Programming Community Website

A modern, responsive community website for developers built with HTML and CSS.

## Features

- 📱 Fully responsive design
- 🎨 Modern gradient-based UI
- 🚀 Fast loading static site
- 🌐 Optimized for GitHub Pages

## GitHub Pages Deployment

This site is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup Instructions

1. **Enable GitHub Pages in Repository Settings:**
   - Go to your repository's Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Build and deployment":
     - Source: Select "GitHub Actions"
   - Save the settings

2. **Automatic Deployment:**
   - The workflow (`.github/workflows/pages.yml`) will automatically deploy the site when changes are pushed to the `main` branch
   - You can also manually trigger the workflow from the Actions tab

3. **Access Your Site:**
   - Once deployed, your site will be available at: `https://<username>.github.io/<repository-name>/`
   - For this repository: `https://codeHysteria28.github.io/ghcp-agentic/`

### Manual Deployment

To manually trigger a deployment:
1. Go to the "Actions" tab in your repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow"
4. Select the `main` branch and click "Run workflow"

## Local Development

To view the site locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/codeHysteria28/ghcp-agentic.git
   cd ghcp-agentic
   ```

2. Open `index.html` in your browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

   Or use a local web server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## Project Structure

```
.
├── .github/
│   └── workflows/
│       └── pages.yml       # GitHub Pages deployment workflow
├── index.html              # Main landing page
├── style.css              # Stylesheet
└── README.md              # This file
```

## Technologies Used

- HTML5
- CSS3
- GitHub Actions
- GitHub Pages

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

© 2025 Programming Community. All rights reserved.
