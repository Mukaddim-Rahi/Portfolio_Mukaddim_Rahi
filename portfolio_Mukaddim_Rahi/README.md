# Portfolio Website - Mukaddim Rahi

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- 📱 Fully responsive design
- 🎨 Clean and modern UI
- 📄 PDF resume viewer and download
- 🖼️ Publication images with modal view
- 📧 Contact form
- 🚀 Optimized for Netlify deployment
- ⚡ Fast loading and smooth animations

## Sections

- **About** - Introduction and overview
- **Experience** - Work experience timeline
- **Publications** - Academic publications with links
- **Projects** - Portfolio projects showcase
- **Achievements** - Awards and recognitions
- **Contact** - Contact information and form

## Setup Instructions

### 1. Add Your Content
- Edit `index.html` to update personal information
- Replace placeholder text with your actual content
- Update social media links and contact information

### 2. Add Your Media Files
Upload the following files to the `assets/` folder:
- `profile.jpg` - Your profile picture
- `resume.pdf` - Your resume/CV
- `publication1.jpg`, `publication2.jpg` - Publication images
- `project1.jpg`, `project2.jpg` - Project images

### 3. Customize Styling
- Edit `styles.css` to modify colors, fonts, and layout
- Update the color scheme in CSS variables if needed

## Deployment to Netlify

### Method 1: Drag and Drop
1. Zip all files in this folder
2. Go to [Netlify](https://netlify.com)
3. Drag and drop the zip file to deploy

### Method 2: Git Integration
1. Create a GitHub repository
2. Push all files to the repository
3. Connect the repository to Netlify
4. Enable auto-deployment

### Method 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy to Netlify
netlify deploy --prod --dir .
```

## File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── netlify.toml        # Netlify configuration
├── README.md           # This file
└── assets/             # Media files
    ├── profile.jpg
    ├── resume.pdf
    ├── publication1.jpg
    ├── publication2.jpg
    ├── project1.jpg
    └── project2.jpg
```

## Customization Tips

### Colors
The main colors used in the design:
- Primary: `#007bff` (Blue)
- Success: `#28a745` (Green)
- Background: `#f8f9fa` (Light Gray)
- Text: `#333` (Dark Gray)

### Fonts
- Main font: Inter (Google Fonts)
- Icons: Font Awesome 6

### Adding New Publications
1. Copy an existing publication item in `index.html`
2. Update the content with your publication details
3. Add the corresponding image to the `assets/` folder

### Adding New Projects
1. Copy an existing project card in `index.html`
2. Update the project information
3. Add the project image to the `assets/` folder

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance
- Optimized images (recommended < 500KB each)
- Minified CSS and JavaScript
- Lazy loading for images
- Smooth scrolling animations

## License
This template is free to use for personal and commercial projects.

---

**Need Help?** 
- Check the browser console for any errors
- Ensure all image files are in the correct `assets/` folder
- Verify PDF file is properly uploaded for resume functionality
