# Midnight - AI Home Security

This is the GitHub Pages site for Midnight, an AI-powered home security solution.

## About

Midnight provides intelligent home security using advanced AI and machine learning to protect your home 24/7. Our system learns and adapts to distinguish between real threats and everyday activity.

## Setup Instructions

### Deploy to GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select the `main` branch
   - Click "Save"

3. **Configure Custom Domain** (Optional)
   - In your domain registrar (e.g., Namecheap, GoDaddy):
     - Add an A record pointing to GitHub's IP addresses:
       - `185.199.108.153`
       - `185.199.109.153`
       - `185.199.110.153`
       - `185.199.111.153`
     - Or add a CNAME record pointing to `<your-username>.github.io`
   - In your GitHub repository:
     - Go to Settings > Pages
     - Under "Custom domain", enter `midnightsecurity.org`
     - Click "Save"
   - GitHub will automatically create a CNAME file in your repository

### Local Development

To view the site locally:

1. **Simple HTTP Server (Python)**
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

2. **Using VS Code Live Server**
   - Install the "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

## File Structure

```
midnight-splash/
├── index.html      # Main landing page
├── styles.css      # Stylesheet with brand colors
├── logo.svg        # Midnight logo
├── CNAME          # Custom domain configuration
└── README.md      # This file
```

## Brand Guidelines

### Colors
- Primary Background: `#0a0a1a` → `#1a1a2e`
- Accent Purple: `#8b5cf6`
- Accent Blue: `#3b82f6`
- Text Primary: `#e0e7ff`
- Text Secondary: `#c7d2fe`

### Typography
- Primary Font: System font stack (Arial, SF Pro, Segoe UI, etc.)
- Logo Font: Arial Black / Arial Bold

## Customization

### Update Content
Edit [index.html](index.html) to modify:
- Hero section text
- Feature descriptions
- Contact email
- Footer information

### Modify Styles
Edit [styles.css](styles.css) to change:
- Color scheme (update CSS variables in `:root`)
- Layout and spacing
- Responsive breakpoints

### Replace Logo
Replace [logo.svg](logo.svg) with your own logo, maintaining similar dimensions for best results.

## License

© 2025 Midnight. All rights reserved.
