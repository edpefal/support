# Support Page - GitHub Pages

This is a modern and responsive support page designed to be deployed on GitHub Pages.

## Features

- ✅ Modern and responsive design
- ✅ Interactive FAQ section
- ✅ Functional contact form
- ✅ Smooth navigation between sections
- ✅ Animations and visual effects
- ✅ Mobile device optimized
- ✅ GitHub Pages compatible

## File Structure

```
support/
├── index.html          # Main page
├── styles.css          # CSS styles
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## How to Deploy on GitHub Pages

### Option 1: Dedicated Repository

1. Create a new repository on GitHub called `your-username.github.io`
2. Upload all files from this directory to the repository
3. Go to Settings > Pages in your repository
4. Select "Deploy from a branch" and choose "main"
5. Your page will be available at `https://your-username.github.io`

### Option 2: Subdirectory in Existing Repository

1. Create a folder called `docs` in your existing repository
2. Copy all files to the `docs` folder
3. Go to Settings > Pages in your repository
4. Select "Deploy from a branch" and choose "main" / "docs"
5. Your page will be available at `https://your-username.github.io/your-repository`

## Customization

### Change App Name

1. Edit `index.html` and change "My App" to your application name
2. Update the contact email in the contact section
3. Modify social media links in the footer

### Add More FAQ Questions

1. Edit `index.html`
2. Find the `.faq-list` section
3. Add new `.faq-item` elements following the existing structure

### Change Colors and Styles

1. Edit `styles.css`
2. Modify CSS variables at the beginning of the file
3. Main colors are defined with hexadecimal values

## JavaScript Features

- **Interactive FAQ**: Elements expand/collapse on click
- **Smooth navigation**: Smooth scroll between sections
- **Contact form**: Basic validation and submission simulation
- **Dynamic header**: Hides/shows based on scroll
- **Animations**: Elements appear with animation on scroll
- **FAQ search**: Search field to filter questions

## Technologies Used

- Semantic HTML5
- CSS3 with Flexbox and Grid
- Vanilla JavaScript (ES6+)
- Font Awesome for icons
- Google Fonts (Inter)

## Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile devices

## License

This project is under the MIT License. You can use it freely for your projects.

## Support

If you have questions about this support page, you can:

1. Check GitHub Pages documentation
2. Consult HTML/CSS/JavaScript documentation
3. Create an issue in the repository if you find any problems