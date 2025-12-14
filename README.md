# Personal Portfolio Website

A clean, professional portfolio website for researchers, academics, or professionals who want to showcase their works/publications

by Geovana Franca, PhD Research at Concordia University

## Features

- 📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern Design**: Clean, professional layout with smooth animations
- 📄 **Multiple Sections**: About, Education, Publications, Experience, Projects, and CV
- 🔗 **Social Media Integration**: Easy links to email, Google Scholar, GitHub, and LinkedIn
- ⚡ **Fast Loading**: Optimized HTML, CSS, and JavaScript
- 🎯 **SEO Friendly**: Proper semantic HTML structure

## Getting Started

### 1. Customize Your Information

Edit `index.html` and replace the placeholder text with your own information:

- **Hero Section**: Your name, title, and affiliation
- **Social Links**: Update URLs to your email, Google Scholar, GitHub, and LinkedIn profiles
- **About Section**: Write your bio and research interests
- **Education**: Add your degrees and academic background
- **Publications**: List your papers, articles, and research
- **Experience**: Add your work history and positions
- **Projects**: Showcase your research or personal projects
- **CV**: Link to your CV PDF file

### 2. Add Your Assets

Place your files in the `assets` folder:

- **profile.jpg**: Your profile photo (recommended size: 300x300px)
- **CV.pdf**: Your curriculum vitae PDF file
- **publication1.jpg, publication2.jpg, etc.**: Images for your publications
- **logo1.png, logo2.png, etc.**: Organization logos for experience section

### 3. Customize Colors (Optional)

Edit the CSS variables in `styles.css` to match your preferred color scheme:

```css
:root {
    --primary-color: #2c3e50;      /* Main color */
    --secondary-color: #3498db;     /* Accent color */
    --accent-color: #e74c3c;        /* Highlight color */
    --text-color: #333;             /* Text color */
    --text-light: #666;             /* Secondary text */
}
```

### 4. View Your Website

Simply open `index.html` in your web browser to see your portfolio!

## Deployment Options - GitHub Pages (Free)

1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "main" branch as source
5. Your site will be live at `https://yourusername.github.io/repository-name`


## File Structure

```
website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
├── README.md           # This file
└── assets/             # Your images and files
    ├── profile.jpg
    ├── CV.pdf
    ├── publication1.jpg
    ├── publication2.jpg
    ├── logo1.png
    └── logo2.png
```

## Customization Tips

### Adding More Publications

Copy and paste this block in the Publications section:

```html
<div class="publication-item">
    <div class="publication-image">
        <img src="assets/publication-name.jpg" alt="Publication">
        <span class="publication-status status-published">Published</span>
    </div>
    <div class="publication-content">
        <h3>Your Publication Title</h3>
        <p class="authors">Author Names</p>
        <p class="venue">Conference/Journal Name, Year</p>
        <div class="publication-links">
            <a href="#" class="btn-link">DOI</a>
            <a href="#" class="btn-link">Code</a>
        </div>
    </div>
</div>
```

### Status Badge Options

Change the status class to show different publication states:
- `status-published` (green) - Published papers
- `status-review` (orange) - Under review
- `status-preparation` (gray) - In preparation

### Adding More Sections

You can easily add new sections by following the same pattern:

```html
<section id="new-section" class="section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers
