# AI Automation & Data Pipeline Engineer - Portfolio

A professional portfolio website showcasing expertise in AI automation, data pipelines, ETL processes, and machine learning integration.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Project Showcase**: Highlights relevant projects related to data engineering and AI automation
- **Complete Workflow**: Visual representation of the end-to-end development process
- **Skills Section**: Comprehensive display of technical competencies
- **Smooth Navigation**: Easy-to-use navigation with smooth scrolling

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (Vanilla JS)
- Font Awesome Icons

## Files Structure

```
├── index.html      # Main HTML file
├── styles.css      # CSS styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## How to Use

1. **Open the Portfolio**: Simply open `index.html` in your web browser
2. **Customize Content**: 
   - Update personal information in the HTML file
   - Modify project details to match your actual projects
   - Change contact information
   - Adjust colors in CSS variables if needed

## Customization Guide

### Update Contact Information
Edit the contact section in `index.html`:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
```

### Change Color Scheme
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... */
}
```

### Add/Modify Projects
Edit the projects section in `index.html` - duplicate a project card and modify the content.

## Deployment to Vercel

### Vercel Project Naming Requirements
- Project names must be **lowercase**
- Can include: letters, digits, `.`, `_`, `-`
- Cannot contain the sequence `---`
- Maximum 100 characters

### Deployment Steps

#### Method 1: GitHub Integration (Recommended)

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Portfolio website ready for deployment"
   git remote add origin https://github.com/Tayyriaz/Proflio.git
   git push -u origin main
   ```

2. **Deploy on Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository `Tayyriaz/Proflio`
   - Set project name (e.g., `portfolio-website` or `ai-data-engineer-portfolio`)
   - Click "Deploy"
   - Your site will be live in seconds!

#### Method 2: Vercel CLI

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Deploy:**
   ```bash
   vercel
   ```

3. **Follow the prompts:**
   - Login to Vercel
   - Set project name (follow naming rules above)
   - Deploy!

### Important Notes
- CSS and JS files use absolute paths (`/styles.css`, `/script.js`) for proper Vercel deployment
- All static assets will be automatically served
- The site will be available at `your-project-name.vercel.app`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This portfolio template is free to use and modify for personal and commercial projects.
