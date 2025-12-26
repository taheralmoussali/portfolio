# Taher Almousali - Portfolio Website

A modern, responsive portfolio website showcasing my experience as an AI & Computer Vision Engineer.

## Features

- ✨ Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Beautiful gradient hero section
- 📊 Interactive timeline for work experience
- 🚀 Smooth scrolling and animations
- 🎯 Easy to customize

## Files Structure

```
portfolio/
├── index.html          # Main HTML structure
├── style.css           # Styling and responsive design
├── script.js           # Interactive functionality
└── README.md           # This file
```

## Getting Started

### Option 1: Open Locally

Simply open `index.html` in your web browser:
- Double-click the file, or
- Right-click → Open with → Your preferred browser

### Option 2: Use a Local Server (Recommended)

For the best experience, use a local server:

**Python 3:**
```bash
python -m http.server 8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Node.js (with http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

### Option 3: Deploy Online

You can deploy this portfolio to various platforms:

- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag and drop deployment
- **Vercel**: Fast and easy deployment
- **GitLab Pages**: Similar to GitHub Pages

## Customization

### Update Personal Information

Edit `index.html` to update:

1. **Contact Information** (in the Contact section):
   - Email: `taheralmoussali@gmail.com`
   - Phone: `(+971) 502595270`
   - Location: `Dubai, UAE`

2. **Social Media Links** (update the href attributes):
   ```html
   <a href="https://your-linkedin-url" target="_blank">
   <a href="https://your-github-url" target="_blank">
   <a href="https://your-medium-url" target="_blank">
   ```

3. **Colors**: Edit CSS variables in `style.css`:
   ```css
   :root {
       --primary-color: #6366f1;
       --secondary-color: #8b5cf6;
       /* ... other colors ... */
   }
   ```

### Add/Remove Sections

All sections are clearly marked in `index.html`. Simply:
- Copy/paste section structure to add new sections
- Remove section blocks to remove sections
- Update navigation menu to match

### Update Content

- **Experience**: Modify the `.timeline-item` divs in the Experience section
- **Projects**: Update `.project-card` divs in the Projects section
- **Skills**: Modify the `.skills-list` spans in the Skills section

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS, no frameworks)
- Font Awesome (for icons)
- Google Fonts (Poppins)

## Performance

- No external dependencies (except Font Awesome and Google Fonts)
- Optimized for fast loading
- Responsive images ready
- Smooth animations with CSS

## License

This portfolio is open source and available for personal use.

## Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)

## Contact

For any questions or suggestions, feel free to reach out:
- Email: taheralmoussali@gmail.com
- Phone: (+971) 502595270
