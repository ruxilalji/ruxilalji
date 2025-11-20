# Ruxilalji Personal Website

A modern, responsive personal website built for GitHub Pages featuring glass morphism effects, beige/neutral color themes, photo galleries, mini blog, and useful links.

## 🌟 Features

- **Glass Morphism Design**: Modern UI with backdrop blur and semi-transparent elements
- **Beige/Neutral Color Palette**: Calming colors including #F5F5DC, #E8E8E8, #C8C8B8
- **Fully Responsive**: Mobile-first design that works on all devices
- **Photo Gallery**: Grid layout showcasing 6 curated items with hover effects
- **Mini Blog**: Three blog post cards with dates and descriptions
- **Useful Links**: Organized resources for development, design, learning, and social platforms
- **Smooth Animations**: Fade-in effects, hover transitions, and floating animations
- **No Dependencies**: Pure HTML/CSS implementation without external libraries

## 🚀 Deployment to GitHub Pages

This website is designed to be deployed as a GitHub Pages site at `ruxilalji.github.io`.

### Steps to Deploy:

1. **Ensure the repository name matches your GitHub username**:
   - Repository should be named: `ruxilalji/ruxilalji` (or `username.github.io`)

2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Under "Source", select the branch (usually `main` or `copilot/create-github-io-page`)
   - Select the root folder `/` as the source
   - Click Save

3. **Access your website**:
   - Your site will be available at: `https://ruxilalji.github.io/`
   - It may take a few minutes for changes to propagate

## 📁 File Structure

```
.
├── index.html          # Main website file with all HTML, CSS, and JavaScript
├── README.md           # This file
├── LICENSE             # License information
└── .gitignore          # Git ignore rules
```

## 🎨 Customization

To customize the website for your own use:

1. **Update the content**:
   - Edit the hero section text in `index.html`
   - Replace gallery items with your own images/content
   - Update blog posts with your own articles
   - Modify useful links to match your preferences

2. **Change colors**:
   - Edit CSS variables in the `:root` section:
     ```css
     --beige-50: #FDFBF7;
     --beige-100: #F9F6F0;
     /* ... etc */
     ```

3. **Update links**:
   - Change the GitHub link in the footer to your profile
   - Add more social media links as needed

## 🛠️ Local Development

To test the website locally:

```bash
# Using Python 3
python3 -m http.server 8080

# Or using Node.js
npx http-server -p 8080

# Then open http://localhost:8080 in your browser
```

## 📱 Browser Support

The website works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Security

All external links include `rel="noopener noreferrer"` attributes to prevent security vulnerabilities.

## 📄 License

See [LICENSE](LICENSE) file for details.

## 🤝 Contributing

This is a personal website repository. Feel free to fork it for your own use!

---

Built with ❤️ and creativity by Ruxilalji
