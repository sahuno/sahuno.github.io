# Samuel Terkper Ahuno - Personal Website

A clean, professional personal website showcasing my research, publications, and professional experience in epidemiology and data science.

## Features

- 📱 Responsive design that works on all devices
- 🌓 Dark/light theme toggle with local storage persistence
- ⚡ Fast loading with pure HTML/CSS (no heavy frameworks)
- 🎯 Clean, minimalist design focused on content
- 📊 Organized sections for experience, education, skills, and publications

## Quick Start

1. Clone this repository
2. The main website file is `index.html`
3. Open `index.html` in a browser to preview
4. Deploy to GitHub Pages (see below)

## Deployment to GitHub Pages

### Method 1: Deploy as User Site (yourname.github.io)

1. Create a new repository named `[yourusername].github.io`
2. Push this code to the main branch
3. Your site will be available at `https://[yourusername].github.io`

### Method 2: Deploy as Project Site

1. Create a new repository with any name
2. Push this code to the main branch
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose main branch
5. Your site will be available at `https://[yourusername].github.io/[repository-name]`

### Deployment Commands

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - personal website"

# Add your GitHub repository as remote
git remote add origin https://github.com/[yourusername]/[repository-name].git

# Push to GitHub
git push -u origin main
```

## Customization

### Updating Content
- All content is in `index.html`
- Simply edit the text between HTML tags
- No build process required

### Changing Colors
Edit the CSS variables in the `:root` section:
```css
:root {
    --bg: #ffffff;        /* Background color */
    --text: #1a1a1a;      /* Main text color */
    --link: #0066cc;      /* Link color */
    /* ... */
}
```

### Adding Sections
Copy an existing section and modify:
```html
<section id="new-section">
    <h2>Section Title</h2>
    <!-- Your content here -->
</section>
```

## Structure

```
├── index.html          # Main website file
├── README.md          # This file
└── website-update-plan.md  # Detailed update instructions
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Feel free to use this template for your own personal website.

## Contact

- Email: ekwame001@gmail.com
- LinkedIn: [Samuel Ahuno](https://www.linkedin.com/in/samuel-ahuno-47857842/)
- GitHub: [ahunos](https://github.com/ahunos)

---

Built with ❤️ using HTML & CSS | Hosted on GitHub Pages