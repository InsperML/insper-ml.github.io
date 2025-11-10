# Insper Machine Learning Group Website

Official website for the Insper Machine Learning Group research team.

🌐 **Live Site**: [https://insperml.github.io/insper-ml.github.io/](https://insperml.github.io/insper-ml.github.io/)

## About

This website showcases the research, people, and publications of the Insper Machine Learning Group. We are dedicated to advancing machine learning and artificial intelligence through innovative research and collaboration.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional interface with smooth animations
- **Research Areas**: Highlighting our work in deep learning, computer vision, NLP, and more
- **Team Profiles**: Showcasing our faculty, PhD students, and Master's students
- **Publications**: Displaying our latest research contributions
- **Contact Form**: Easy way for interested parties to reach out

## Structure

``` text
insper-ml.github.io/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript for interactivity
├── assets/             # Static assets
│   ├── images/         # Image files
│   │   └── team/       # Team member photos
│   └── README.md       # Assets documentation
└── README.md           # This file
```

## Customization

### Adding Team Members

1. Open `index.html`
2. Find the appropriate section (Faculty, PhD Students, or Master's Students)
3. Copy an existing `person-card` div and modify:

```html
<div class="person-card">
    <div class="person-avatar">
        <div class="avatar-placeholder">👤</div>
        <!-- Or use an image: <img src="assets/images/team/name.jpg" alt="Name"> -->
    </div>
    <h4>Full Name</h4>
    <p class="person-title">Position</p>
    <p class="person-research">Research Interests</p>
    <div class="person-links">
        <a href="#" class="person-link">Website</a>
        <a href="#" class="person-link">Scholar</a>
    </div>
</div>
```

### Adding Publications

1. Open `index.html`
2. Find the `publications-list` section
3. Add a new publication:

```html
<div class="publication-item">
    <h4 class="pub-title">Your Paper Title</h4>
    <p class="pub-authors">Author 1, Author 2, Author 3</p>
    <p class="pub-venue">Conference/Journal Name YEAR</p>
    <div class="pub-links">
        <a href="#" class="pub-link">Paper</a>
        <a href="#" class="pub-link">Code</a>
        <a href="#" class="pub-link">BibTeX</a>
    </div>
</div>
```

### Updating Research Areas

Edit the `research-grid` section in `index.html` to add or modify research focus areas.

### Styling Customization

Modify CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary brand color */
    --accent-color: #3b82f6;     /* Accent color */
    /* ... other variables */
}
```

## Contact Form Setup

The contact form currently displays an alert on submission. To make it functional:

1. **Use a Form Service**:
   - [Formspree](https://formspree.io/)
   - [Netlify Forms](https://www.netlify.com/products/forms/)
   - [EmailJS](https://www.emailjs.com/)

2. **Backend Integration**: Set up your own backend API to handle form submissions

3. Update the form handling in `script.js` accordingly

## Deployment

This site is designed for GitHub Pages:

1. Push changes to the `main` branch
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Site will be available at `https://insperml.github.io/insper-ml.github.io/`

## Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Vanilla JS for interactivity
- **Google Fonts**: Inter font family

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

To contribute to this website:

1. Create a new branch
2. Make your changes
3. Test locally
4. Submit a pull request

## License

© 2025 Insper Machine Learning Group. All rights reserved.

## Contact

For questions or updates, contact: <ml-group@insper.edu.br>
