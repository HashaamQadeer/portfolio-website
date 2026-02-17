# Portfolio Website

A modern, dynamic portfolio website built with HTML, CSS, and JavaScript, ready for deployment on Netlify.

## Features

- 🎨 Modern and dynamic UI with smooth animations
- 📱 Fully responsive design
- ⚡ Fast loading and optimized performance
- 🎯 Sections for Skills, Projects, Education, and Contact
- 📥 CV download functionality
- 🔗 Social media links (GitHub, LinkedIn)
- ✨ Smooth scrolling and interactive elements
- 🌈 Beautiful gradient effects and animations

## Customization

### Personal Information

1. **Name**: Update the name in `index.html`:
   ```html
   <span class="name" id="typedName"></span>
   ```
   And in `script.js`:
   ```javascript
   nameElement.textContent = 'Your Name'; // Replace with your actual name
   ```

2. **Typing Animation**: Modify the texts in `script.js`:
   ```javascript
   const typingTexts = [
       "Full Stack Developer",
       "UI/UX Designer",
       // Add your own titles
   ];
   ```

3. **Social Links**: Update the links in `index.html`:
   ```html
   <a href="https://github.com/yourusername" target="_blank" class="social-link">
   <a href="https://linkedin.com/in/yourusername" target="_blank" class="social-link">
   ```

4. **Email**: Update the email in the contact section:
   ```html
   <p>your.email@example.com</p>
   ```

### Skills Section

Edit the skills in `index.html` under the `.skills-grid` section. Each skill card includes:
- Icon (Font Awesome)
- Skill name
- Skill level (percentage)

### Projects Section

Add your projects in `index.html` under the `.projects-grid` section. Each project card includes:
- Project image/placeholder
- Project title
- Description
- Technology tags
- Links to live demo and GitHub

### Education Section

Update your education timeline in `index.html` under the `.timeline` section. Each timeline item includes:
- Degree/Certification name
- Institution name
- Date range
- Description

### CV File

1. Create a PDF version of your CV
2. Name it `cv.pdf`
3. Place it in the root directory (same folder as `index.html`)
4. The download button will automatically work

## Color Scheme

The website uses a modern dark theme with customizable colors. To change the color scheme, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... more variables */
}
```

## Deployment on Netlify

### Method 1: Drag and Drop

1. Zip all the files (index.html, styles.css, script.js, netlify.toml, cv.pdf)
2. Go to [Netlify](https://app.netlify.com)
3. Drag and drop the zip file onto the Netlify dashboard
4. Your site will be live in seconds!

### Method 2: Git Integration

1. Push your code to GitHub
2. Connect your GitHub repository to Netlify
3. Netlify will automatically deploy your site
4. Future pushes will trigger automatic deployments

### Method 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # JavaScript functionality
├── netlify.toml        # Netlify configuration
├── cv.pdf             # Your CV (add this file)
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized CSS and JavaScript
- Lazy loading support for images
- Smooth animations with hardware acceleration
- Minimal dependencies (only Font Awesome for icons)

## License

Feel free to use this template for your own portfolio!

## Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

Built with ❤️ using modern web technologies
